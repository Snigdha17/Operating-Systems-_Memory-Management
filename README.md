# Operating-Systems - Memory-Management

## Implemented the Memory Management system of OSP2 simulation software using the LRU page replacement algorithm, dirty-bit optimization and a proactive page cleaning daemoned.
###The daemon should kick in every 20,000 clock ticks and swap out the 6 least recently used pages.


### The following statistics were calculated and resported for the implementation and compared with the default scheduling strategy which uses  a very simplistic algorithm for page replacement: it scans the entire frame table and chooses the first replaceable frame
* The number of pages swapped in and out
* CPU utilization
* Service time per thread (avg turnaround time)
* Normalized service time per thread (avg normalized turnaround time)

*University policy prohibits me from sharing the code online. However, the report (outlining the statistics) is linked and code is available on request.*
