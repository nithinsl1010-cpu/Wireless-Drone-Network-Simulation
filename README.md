Wireless Drone Network Simulation Using Python

1. Project Description

- Simulates wireless communication between drones using Python.
- Models drone movement, packet transmission, packet loss, and route discovery.
- Evaluates network performance using Packet Delivery Ratio (PDR).

2. Objectives

- Simulate drone communication and movement.
- Establish wireless connections based on transmission range.
- Implement BFS-based, AODV-style route discovery.
- Calculate packet delivery performance.

3. Technologies Used

- Python
- Matplotlib
- Math, Random, Time, Collections

4. Simulation Parameters

- Area: 500 × 500 meters
- Nodes: 5
- Transmission Range: 150 meters
- Packet Size: 512 bytes
- Simulation Time: 6 seconds
- Movement Speed: 10 units/second

5. Network Nodes

- DRONE-1: Source node
- DRONE-2, DRONE-3, DRONE-4: Forwarding nodes
- CONTROL-STATION: Destination node

6. Routing Mechanism

- Uses BFS for route discovery.
- Finds a path from DRONE-1 to the CONTROL-STATION.
- Uses available wireless connections to forward packets.

7. Performance Metric

- Measures packets sent, received, and lost.
- Calculates Packet Delivery Ratio (PDR).

PDR = (Packets Received / Packets Sent) × 100

8. Execution

- Install Python and Matplotlib.
- Run "pip install matplotlib".
- Execute "python wireless_drone_simulation.py".

9. Expected Output

- Drone positions and wireless connections.
- Dynamic network visualization.
- Packet statistics and final PDR.

10. Conclusion

- Demonstrates drone communication, mobility, routing, and packet delivery.
- Helps understand wireless network performance using Python.# Wireless-Drone-Network-Simulation
