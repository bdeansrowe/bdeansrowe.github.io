### bdeansrowe.github.io

Simple demonstration of an algorithm to find all of the inner-faces from a dataset that:

1. A set of vertices connected by edges in the plane
2. The edges do not intersect except at their endpoints
3. Together, they form a collection of closed polygons
4. The edges form a connected component

The data must be in a JSON file formatted like this:

```json
{										
"vertices": [[0, 0], [2, 0], [2, 2], [0, 2]],		
"edges": [[0, 1], [1, 2], [0, 2], [0, 3], [2, 3]]
}
```

After data has been loaded, it will display on the page and you may press the __Find and Display Interior Faces__ button.

The interior faces will be displayed in the __Results__ section both textually and graphically.
