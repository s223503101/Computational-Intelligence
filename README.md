# Computational-Intelligence
Assignment 1
SIT215 T1 2025 Assignment 1 – Wheelchair-Accessible Navigation System

📌 Project Overview
This project presents an accessibility-aware navigation system tailored for wheelchair users. It uses A* and Dijkstra algorithms with environmental metadata (slope, surface, ramps) to find optimal and safe routes. It includes both a CLI-based analysis and a Tkinter-based GUI for interactive use.

All 5 tasks (including the optional bonus GUI) have been implemented and explained.

📁 Files Included
- SIT215_Assignment1_Tasks1_2_3_4_5_Final_Explained.ipynb: The main code and solution walkthrough.
- README.txt: Instructions on how to run and interpret the project.
- SIT215_Assignment_1_Report_Submission_s223503101.pdf: Formal assignment report (submit separately).
- bonus_task_demo.mp4: (Optional) GUI demonstration video.

🚀 How to Run

1. REQUIREMENTS
Install Python 3.8+ and the following libraries:

pip install numpy matplotlib networkx geopy

Note: Tkinter is used for the GUI (Task 5) and is pre-installed with most Python distributions. If it is not, use your system package manager.

2. RUNNING THE NOTEBOOK
You can use:
- JupyterLab (via Anaconda): Fully supports all functionalities including GUI.
- Google Colab: All tasks except GUI will run. Skip GUI section as Tkinter is not supported on Colab.

To start:
jupyter notebook SIT215_Assignment1_Tasks1_2_3_4_5_Final_Explained.ipynb

📌 Notebook Sections:
- Task 1: Creates the environment (graph of nodes with real coordinates).
- Task 2: Basic A* implementation with Haversine heuristic.
- Task 3: Enhances environment with slope/surface/ramp and updates heuristic accordingly.
- Task 4: Compares A* with Dijkstra.
- Task 5 (Bonus): GUI to input start/goal nodes and visualize results.

🧠 Features
- Uses real-world coordinates.
- Haversine and enhanced heuristics with accessibility-based penalties.
- Graph rendering with matplotlib.
- GUI (Tkinter) that supports path input and visualization.
- Results table for comparing cost and time of A*, Enhanced A*, and Dijkstra.

🎮 GUI Instructions (Tkinter)
Only available when run on JupyterLab/desktop Python:
1. Go to the GUI cell in the notebook or convert GUI logic to a standalone .py.
2. Input start and end node names.
3. Select heuristic (basic or enhanced).
4. Click "Calculate Path" to visualize.

📝 Notes
- No external file (CSV) loading needed. All graph data is embedded in the code.
- GUI is optional but implemented fully and demonstrated in video.
- Be sure to cite any packages used as per the assignment guidelines.

