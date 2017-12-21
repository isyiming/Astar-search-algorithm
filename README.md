# Astar-search-algorithm
search the shortest road in an image by A* algorithm

If we have a map in the form of image or 2D-array and we want to search the shortese road,
one of the based way is A*, although we need a precondition is that we have abstract our map to many nodes.
but if we view every pixel as a nodes , A* still could be used straightly.

This code will read a image:"maps.png". in this image,  zero gray value represent this pixel is a barrier.
Our result will be save as a image "informap.png". I have drawn the road in it.
