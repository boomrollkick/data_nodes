This Project ingests a series of linked nodes
using vue js in a json format

Vue then converts the json to an index object
and renders a list of the individual nodes

When a node is selected we then navigate the tree structure
to determine which other nodes will be linked and which nodees belong in the first phase
and the second phase. 
Other nodes are grouped in a third category.

Thes nodes and links are then sent to d3 and rendered in force simulation


