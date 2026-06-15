Emergency Response Dispatch System (ERDS)
A console-based C++ application that simulates a centralized Emergency Response Dispatch System. All data structures are implemented manually from scratch without STL.

Features

Incident prioritization using Min-Heap
Vehicle lookup and status control using Hash Table with chaining
City map and proximity search using Weighted Graph and BFS
Historical incident logging using AVL Tree
Vehicle maintenance scheduling using Queue
Dispatcher command history using Stack
Save and load system state using file I/O


Data Structures

IncidentMinHeap — Min-Heap to prioritize incidents by urgency 
VehicleHashTable — Hash Table with Linked List chaining for O(1) vehicle lookup
CityMapGraph — Adjacency List Graph to model city roads and intersections
HistoricalAVL — AVL Tree to store and search resolved incident records
TaskQueue — FIFO Linked List Queue for vehicle maintenance scheduling
CommandStack — LIFO Linked List Stack for dispatcher action history


How to Compile and Run
g++ -o erds main.cpp IncidentMinHeap.cpp VehicleHashTable.cpp CityMapGraph.cpp HistoricalAVL.cpp TaskQueue.cpp CommandStack.cpp
./erds
