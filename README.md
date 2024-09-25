## About
Calculates the maximum flow in a flow network using the Edmonds-Karp algorithm and generates an animation depicting the process.
[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff)](#)
[![](https://img.shields.io/badge/University%20of%20Alabama-9E1B32.svg?logo=data:image/svg%2bxml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iVVRGLTgiIHN0YW5kYWxvbmU9Im5vIj8+PCFET0NUWVBFIHN2ZyBQVUJMSUMgIi0vL1czQy8vRFREIFNWRyAxLjEvL0VOIiAiaHR0cDovL3d3dy53My5vcmcvR3JhcGhpY3MvU1ZHLzEuMS9EVEQvc3ZnMTEuZHRkIj48c3ZnIHdpZHRoPSIxMDAlIiBoZWlnaHQ9IjEwMCUiIHZpZXdCb3g9IjAgMCAyNTAgMjQxIiB2ZXJzaW9uPSIxLjEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHhtbDpzcGFjZT0icHJlc2VydmUiIHhtbG5zOnNlcmlmPSJodHRwOi8vd3d3LnNlcmlmLmNvbS8iIHN0eWxlPSJmaWxsLXJ1bGU6ZXZlbm9kZDtjbGlwLXJ1bGU6ZXZlbm9kZDtzdHJva2UtbGluZWpvaW46cm91bmQ7c3Ryb2tlLW1pdGVybGltaXQ6MjsiPjxnPjxwYXRoIGQ9Ik0xODIuMDc0LDEyMS40NzZsLTMwLjk5NywzLjc3NmMxNS40NDUsLTI0LjcwOCAyMy44OTQsLTQ3LjU1NiA0OC43OTUsLTcyLjYxMWMtNi44NjUsMjEuODg3IC0xMi40NTcsNDYuNzE3IC0xNy43OTgsNjguODM1bTYwLjk2Miw4NC42ODJjLTIxLjEwNSwxMC44OTcgLTM2Ljk2Nyw4LjYxMyAtMzguNjU0LC00LjU0MmMtMS45MDIsLTE0LjcxNSAtMC44NTQsLTM1LjQxNyAtMC4xNTksLTQzLjMxMmMwLjI1OCwtMi44OTEgMS4xMzQsLTEyLjIzIDEuNjksLTE1LjA1YzcuMjA5LC0xLjUwMyAxNi44MzksLTUuMDI0IDE2LjgzOSw3LjUwNGMzLjY0MiwtMS44NTYgMTAuMzIyLC03LjMzNSAxMS40NjgsLTEzLjE1MmM2LjM1OCwtMzAuMDY1IC0yNS4xNTEsLTIyLjE4IC0yNS4xNTEsLTIyLjE4YzcuNjg1LC0zNS41MTYgMTUuOTQ4LC03My4zNCAzMy41NDMsLTEwNC41NTJsLTE3LjUzOSwtOC40MDRjLTExLjg3MSw5LjA4NyAtMjMuODI4LDE4LjI4NiAtMzMuODAyLDE5Ljc3NGMtOS4xMDUsMi4xOTcgLTY0Ljc3Myw2LjU2NyAtNjAuODU5LC0xOC45MTdjLTYuMjE5LDAuNDk4IC05LjcxNiw3LjgxNSAtOS42NzksMTQuMTI5YzIuMDA5LDI3LjUgMzcuNzUsMjIuMDQ4IDU5LjUxMiwyNC43NGMtMjIuNDYsMjguMTE5IC00Mi4xOTcsNTcuMjM4IC02MC4wMzIsODcuMzljLTE0LjEzNiwyLjcwNCAtMTUuOTk3LC0xNC44MzEgLTEzLjU5MiwtMTkuNjU3YzAsLTAgLTkuMzI2LDIuNjE4IC0xMi45NDMsMTIuODI5Yy00LjM2NiwxMC43MzEgMC41NzgsMjguODgyIDE1Ljc5MiwyOS44OTdjLTE1LjA2LDI2LjQ5NCAtMzMuMTE5LDY5LjkwNSAtNzAuMDcxLDYxLjIzYy0xMi4zNjUsLTIuNTUgLTI2LjgwMiwtMjMuNDg2IC0xOS4zMjgsLTM1LjkzOGM0LjU4NCwtNi4zNzYgLTIuMjEzLC0xMC44NDcgLTEwLjAxMiwtMS4zOTJjLTE5LjE3NCwyMS4xNiAtMC42NzYsNjMuNDIxIDM5LjQ5NSw2MC44OGM0My4xOTIsMC45MzcgNzIuMzM2LC01Mi43NDMgODguMDYyLC04NC42MzZsNDAuOTU1LC02LjQzOGwtMi41OTEsMzMuNDE4Yy01LjE2NSw4My4xMDYgNTQuNjUxLDUxLjAyOCA1NC42NTEsNTEuMDI4YzguMzE1LC0zLjc3NCAxNy4wMjQsLTEyLjg3MiAxNi44MDksLTIzLjQ3NGMtMC40NDksLTMuNTcxIC0yLjQyNCwtMi4xODUgLTQuNDA3LC0xLjE3NCIgc3R5bGU9ImZpbGw6I2ZmZjtmaWxsLXJ1bGU6bm9uemVybzsiLz48L2c+PC9zdmc+)](#)


## Usage

```
python edmonds_karp.py [capacity matrix]
```
Capacity matrix files contain an adjacency matrix with weights representing the edge's flow capacity

### Generating graphs
Graphs can be generated using the included graph generator script:
```
python generate_graph.py [number of nodes] [name of file]
```
Created graphs are placed in the test subfolder. Example usage of the graph generator script to generate a graph with 12 nodes:
```
python generate_graph.py 12 Size12
```

### Dependencies
```
pip install matplotlib numpy networkx
```
In order to save a .mp4 of the animation, [ffmpeg](https://ffmpeg.org/download.html) is required as well. Without ffmpeg, the animation will still display, but will not be saved.

## Authors
- [@cole-sullivan](https://github.com/cole-sullivan)
- [@mdreis](https://github.com/mdreis)
- [@jcwilliams37](https://github.com/jcwilliams37)
- [@brian419](https://github.com/brian419)
- [@kdbryant2](https://github.com/kdbryant2)

## References
- NetworkX documentation: https://networkx.org/documentation/latest/reference/index.html
- Animating NetworkX: https://stackoverflow.com/questions/43646550/how-to-use-an-update-function-to-animate-a-networkx-graph-in-matplotlib-2-0-0
- Drawing multiple edges between 2 nodes with NetworkX: https://stackoverflow.com/questions/22785849/drawing-multiple-edges-between-two-nodes-with-networkx
- Matplotlib.animation documentation: https://matplotlib.org/stable/api/animation_api.html
- Edmonds-Karp Pseudocode: https://cp-algorithms.com/graph/edmonds_karp.html#:~:text=Edmonds%2DKarp%20algorithm%20is%20just,independently%20of%20the%20maximal%20flow.
