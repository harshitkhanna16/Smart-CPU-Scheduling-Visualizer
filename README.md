# Smart CPU Scheduling Visualizer

This is a simple web-based project to visualize and understand different CPU scheduling algorithms. It helps in understanding how various scheduling techniques work using a real-time Gantt chart and performance metrics. The project also provides a smart suggestion feature that recommends the best algorithm based on the average waiting time.

---

## Features

- Visualizes multiple CPU scheduling algorithms:
  - FCFS (First Come First Serve)
  - SJF (Shortest Job First)
  - SRTF (Shortest Remaining Time First)
  - Round Robin
  - Priority Scheduling
- Real-time Gantt Chart visualization
- Smart Suggestion for best algorithm
- Average Waiting Time and Turnaround Time calculation
- Simple dark themed user interface
- Easy input system for process details

---

## About the Project

This project was developed as part of the Operating System subject to understand CPU scheduling algorithms practically.  
Users can enter process details such as arrival time, burst time, and priority, then select an algorithm to visualize how the scheduling is performed.  
The system displays results in tabular form and provides average waiting and turnaround times for performance comparison.

---

## Tech Stack

- HTML5  
- CSS3  
- JavaScript (ES6)
  
---

## Algorithms

Algorithm	Description
FCFS - Executes processes in the order they arrive
SJF - Executes the process with the shortest burst time first
SRTF - Preemptive version of SJF
Round Robin - Each process gets equal CPU time (uses time quantum)
Priority - Executes process with the highest priority first

---

## Smart Suggestion

The smart suggestion feature automatically analyzes the entered processes and suggests the most efficient algorithm by comparing average waiting times.

---

## Developed By

Harshit Khanna
B.Tech CSE (AI & ML)
Graphic Era University
