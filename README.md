# IslandProblemsSuite
IslandProblemsSuite is a C++ project that integrates multiple classic LeetCode island problems into a single, easy-to-use program.    
Using Depth-First Search (DFS), it can:  Count the number of islands (LeetCode 200).    
Find the maximum area of an island (LeetCode 695)  Calculate the maximum perimeter of an island (LeetCode 463).    

---

## Repository Architecture:

```
IslandProblemsSuite/
│
├── README.md ─────────────── Project overview
│
├── Core Logic
│   └── leetcode.cpp ───────── Combined DFS logic
│
├── Problem Solutions
│   ├── only200.cpp ────────── LeetCode 200 (Number of Islands)
│   ├── solve695via200.cpp ─── LeetCode 695 (Max Area, via 200)
│   └── perimeter.md ───────── Notes for LeetCode 463 (Perimeter)
│
└── Visualizations
    ├── leetcode200.html ───── Visual demo for problem 200
    └── visual2.html ───────── Visual demo (perimeter/area)
```
