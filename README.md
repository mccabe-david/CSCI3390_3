# Large Scale Data Processing: Project 3
## David McCabe  

1. **(4 points)** Implement the `verifyMIS` function.  

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
a.  
Total runtime = 2703s.  
Total Iterations = 14.  
Remaining Vertices after each iteration = {7505596, 55316, 5779, 1233, 349, 159, 76, 40, 22, 16, 14, 6, 2, 0}  
![prt1](https://user-images.githubusercontent.com/43038510/115490726-a5de4480-a22c-11eb-8072-f2d3c1650aa9.PNG)  
![prt2](https://user-images.githubusercontent.com/43038510/115490763-bee6f580-a22c-11eb-9775-67277ad8cb1a.PNG)

b.  
**4x2 cores**  

**2x2 cores** 
