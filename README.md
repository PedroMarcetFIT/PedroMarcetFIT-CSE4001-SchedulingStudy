# PedroMarcetFIT-CSE4001-SchedulingStudy

## Design

### First Come First Serve (FCFS)
FCFS is a simple scheduling algorythm that simply
(as its name suggests) allows threads to run in
the order they are set to ready. This algorytm
is fair on arrival time and will perform for
systems where that is important, but will tend to
underperform with systems where there are threads
of varying lengths or when threads requiring
interactivity are present.

### Multi-Level Feedback Queue (MLFQ)
MLFQ is a slightly more advanced scheduling
algorythm. It splits threads into different
queues with varying priority. This allows for
systems where some treads might be more important
to run than others, such as if a thread is
interactive.


## Implementation

### Switching Scheduling Algorythms
![Screenshot](booleans.png)

### FCFS
FCFS was fortunately easy to implement as most of
the existing code was working in a FCFS manner.
