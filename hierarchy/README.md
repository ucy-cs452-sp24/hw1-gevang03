# Homework Assignment 1

## Methodology
The measurements where performed on a cluster of two physical machines
(c220g5) in the same rack, using the utilities and commands referred in
the assignment description.

## Comments
The measurements verify that it may make sense to use rack DRAM instead
of local disk, since the bandwidth is higher and the latency lower. The
metrics measured, do not differ significantly between local and rack disk,
due to the network between nodes on the same rack. However, the capacity
would scale in a more general topology.
