# Data for replication

Here is the data needed for replicating the experiments. 

## Problem instance source

10 topologies and 180 instances from [SNDlib](http://sndlib.zib.de)

10 topologies and 180 instances from [Internet Topology Zoo](http://www.topology-zoo.org) 

9 topologies and 162 instances randomly generated

## Problem instance format

NumberOfNodes NumberOfEdges NumberOfDemands

[For each edge:]

Origin Destination Capacity PrimaryCost SecondaryCost Delay

...

[For each demand:]

Origin Destination Bandwidth DelayDifferenceThreshold

...
