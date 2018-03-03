# quick-find
solution to the 'Union find' problem using a 'eager algorithm' called Quick Find. Just clone the repo and dash open it with your fav IDE. 
Alternatively, just run javac QuickFind.java


Indexes of the array are the nodes and the values of the array are the connections. When the value of one index equals that of another node’s value, then the two nodes are connected.

Quick Find approach has a very fast method to check connectivity. To check the connectivity, you just need to access the array twice. However, union is extremely slow. Since whenever you do union, you have to go through all the array, you will end up with O(N) runtime.
