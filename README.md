# Large Scale Data Processing: Project 3
## David McCabe  

1. **(4 points)** Implement the `verifyMIS` function.  
2.
|        Graph file       |           MIS file           | Is an MIS? |
| ----------------------- | ---------------------------- | ---------- |
| small_edges.csv         | small_edges_MIS.csv          | Yes        |
| small_edges.csv         | small_edges_non_MIS.csv      | No         |
| line_100_edges.csv      | line_100_MIS_test_1.csv      | Yes        |
| line_100_edges.csv      | line_100_MIS_test_2.csv      | No         |
| twitter_10000_edges.csv | twitter_10000_MIS_test_1.csv | No         |
| twitter_10000_edges.csv | twitter_10000_MIS_test_2.csv | Yes        |

2. **(3 points)** Implement the `LubyMIS` function.   

|        Graph file       |     Iterations     |    Runtime     |
| ----------------------- | ------------------ | -------------- |
| small_edges.csv         |          2         |       6s       |
| line_100_edges.csv      |          4         |       8s       |
| twitter_100_edges.csv   |          2         |       6s       |  
| twitter_1000_edges.csv  |          3         |       8s       |
| twitter_10000_edges.csv |          4         |       11s      |

3. **(3 points)**  
a. Run `LubyMIS` on `twitter_original_edges.csv` in GCP with 3x4 cores. Report the number of iterations, running time, and remaining active vertices (i.e. vertices whose status has yet to be determined) at the end of **each iteration**. You may need to include additional print statements in `LubyMIS` in order to acquire this information. Finally, verify your outputs with `verifyMIS`.  
b. Run `LubyMIS` on `twitter_original_edges.csv` with 4x2 cores and then 2x2 cores. Compare the running times between the 3 jobs with varying core specifications that you submitted in **3a** and **3b**.
