Hand count verification

Middle pattern

Three live cells were arranged vertically
#
#
#

Program output

111
212
323
212
111

Hand calculation:

# Top live cell has 1 live neighbor
# Middle live cell has 2 live neighbors
# Bottom live cell has 1 live neighbor
# Cells directly to the left and right of the middle cell have 3 neighbors
# Cells directly to the left and right of the top and bottom cells have 2 neighbors
# Corner cells around the pattern have 1 neighbor

Result:

The hand calculated values matched the ouput from "print_neighbor_count()"

Corner pattern

Three live cells arranged vertically on the left edge

#
#
#

Hand calculation:

12
23
23
12
00

The top left live cell has 1 live neighbor
the middle live cell has 2 live neighbors
The bottom live cell has 1 live neighbor
Cells immediately to the right of the pattern have counts of 2-3

Result?

The hadn calculated counts agree with the expected neighbor counts for a pattern on the edge of the grid
