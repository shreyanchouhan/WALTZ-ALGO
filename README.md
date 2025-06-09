# WALTZ-ALGO
Edge Detection
Uses OpenCV to detect edges from a line drawing (e.g., cube-like structures).

Edge Representation
Each detected edge is given an ID and stores its coordinates and label possibilities.

Junction Constraints
Based on the type of junction (L, T, Y, Arrow), it constrains possible labels using the Waltz consistency rules.

Waltz Interpreter
Iteratively applies constraints until the label possibilities are reduced to only valid combinations.

Graphical Output
Matplotlib is used to:

Draw each edge with directional arrows.

Annotate with edge IDs and allowed labels (C, V, O).
