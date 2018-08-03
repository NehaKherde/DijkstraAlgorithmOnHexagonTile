# DijkstraAlgorithmOnHexagonTile
Minimal-Cost Path through a Hexagonally-Tiled Map:

Define a Rectangular 233-Hexagon Map to be a Rectangular 233-Hexagon Array in which
each hexagon is assigned either a positive integer value ( referred to as that hexagon's cost ),
or the value –1.

The text file describing the Rectangular 233-Hexagon Map then consists of 233 lines of text,
each line of which consists of a hexagon position number from the diagram above, followed
by a space, followed by the cost of that hexagon in the Rectangular 233-Hexagon Map that
the text file is to represent.

A path through a Rectangular 233-Hexagon Map is a sequence of hexagon position numbers (see
Figure 3) such that the first position number in the sequence is 226 (the lower left-hand corner of
the Rectangular 233-Hexagon Map), the last position number in the sequence is 8 (the upper right-
hand corner of the Rectangular 233-Hexagon Map), consecutive position numbers in the sequence
correspond to adjacent positions in the Rectangular 233-Hexagon Array, and no hexagon on the
path has value –1.

The cost of a path is defined to be the sum of the costs of the hexagons on the path.
A minimal-cost path through a given Rectangular 233-Hexagon Map is a path such that
no other path through that Rectangular 233-Hexagon Map has lower cost. Note that a
Rectangular 233-Hexagon Map may have more than one minimal-cost path.

Design an algorithm to find a minimal-cost path through a given Rectangular 233-Hexagon Map.
Implement your algorithm as a Windows-compatible computer program which, given as input
the text file representation of a Rectangular 233-Hexagon Map, produces as output a text file
containing (one per line) the sequence of hexagon position numbers comprising a minimal-cost
path through that Rectangular 233-Hexagon Map followed by a line containing the (positive
integer) cost of that path preceded by the string "MINIMAL-COST PATH COSTS: ".
