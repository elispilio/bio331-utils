# bio331-utils
Utility functions for Reed College Bio331: Computational Systems Biology.

## QuickStart

These utility functions are used in Bio331, starting with Lab1.  They are wrapper scripts to post graphs to [GraphSpace@Reed](http://ec2-52-41-252-78.us-west-2.compute.amazonaws.com/), a web server for interactive graph sharing and collaboration.

- `json_utils.py` contains functions to write an annotated graph to a text file in [JSON](http://www.json.org/) format readable by GraphSpace.
- `graphspace_utils.py` contains [curl commands](https://curl.haxx.se/docs/manpage.html) to post the JSON file to GraphSpace.

Auto-generated documentation is available on the [Bio331 website](http://www.reed.edu/biology/courses/bio331/) under [Support Code](http://www.reed.edu/biology/courses/bio331/supportcode/index).

## GraphSpace

GraphSpace was originally developed at Virginia Tech.  It is available at (www.graphspace.org) and the source code is available on the [GitHub Page](https://github.com/Murali-group/GraphSpace).

example.py is filled with a variety of functions I think will be useful. In addition to some functions, there is a class called graph, which can act as a container for graph objects, and compute degree. This object also holds the node and edge attributes. The functions outside of this class are a breadth first search, a value to hex editor, a file input function. 
Eli Spiliotopoulos
