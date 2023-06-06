
# Drag and Drop 

This project shows implementation of drag and drop on a set of lists using functional component.


# Step 1: Create a list and make its elements draggable

# Step 2: locate the item to be dragged
We'll use the useRef hook to hold the item we're dragging located, then we'll use onDragStart to drag it and paste it to all the items in this list

# Step 3: Track items being dragged

In this step, we need to find which element our dragged element is floating on. With UseRef we can achieve this, changing links when the element hovers over another element. The onDragEnter event listener will also do this.

# Step 4: Rearrange the list

One of the last steps is to rearrange the list when you manage to place the element you dragged on top of another element or in another place.
