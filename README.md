# BFS-using-PySpark-and-Map-Reduce

### implementation

In this mini-project, I implemented BFS using PySpard and 
the MapReduce technique. This code will do one parallel step of BFS.
At the end of each round, we'll have the correct distance for each
node within the k steps of the start node, plus its adjacency list.
At the end of the round, we'll have the correct distance for each
node within k+1 steps of the start node, plus their adjacency lists.
So this will need to run as many times as the graph's diameter.
The initial state will give 0 distance for the start node and
MAX_INT for all others. 
Further explanations on implementation are provided in the code.

### Dataset
###### Marvel-Graph.txt:
This dataset consists of the superheroes' ids wherein the first
id represents the superhero id, and the rest of the line represents the
superheroes with whom it is friends.

###### Marvel-Names.txt:
This dataset consists of the names of the superheroes with their IDs.
