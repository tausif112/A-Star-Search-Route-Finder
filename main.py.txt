import heapq

# Path costs
graph = {
    "Home": [("Khamarbari", 0.40), ("Medelion", 0.34), ("Masjid", 0.30)],
    "Khamarbari": [("Farmgate", 0.70)],
    "Farmgate": [("UAP", 0.70)],
    "Medelion": [("Panthapath", 0.45)],
    "Panthapath": [("UAP", 0.45)],
    "Masjid": [("IBA Hostel", 0.20)],
    "IBA Hostel": [("UAP", 0.22)]
}

# Heuristic values
heuristic = {
    "Home": 1.0,
    "Khamarbari": 0.40,
    "Farmgate": 0.59,
    "Medelion": 0.29,
    "Panthapath": 0.43,
    "Masjid": 0.26,
    "IBA Hostel": 0.21,
    "UAP": 0
}

def a_star(start, goal):
    # Priority queue: (f(n), g(n), current_node, path)
    open_list = [(heuristic[start], 0, start, [start])]
    closed_set = set()

    while open_list:
        f, g, node, path = heapq.heappop(open_list)

        if node == goal:
            return path, g

        if node in closed_set:
            continue
        closed_set.add(node)

        for neighbor, cost in graph.get(node, []):
            if neighbor not in closed_set:
                g_new = g + cost
                f_new = g_new + heuristic[neighbor]
                heapq.heappush(open_list, (f_new, g_new, neighbor, path + [neighbor]))

    return None, float("inf")


# Run A* from Home to UAP
path, cost = a_star("Home", "UAP")

print("Optimal Path:")
print(" -> ".join(path))
print("Total Path Cost:", cost)
