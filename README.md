# Ticket to Ride Europe Adjacency Matrix
An [adjacency matrix](http://faculty.ucr.edu/~hanneman/nettext/C5_%20Matrices.html) representing connections (edges/links/ties) between cities (nodes/vertices) in the board game Ticket to Ride Europe. In this matrix, I assume 4-5 players and naïvely calculate tie strength as 1 (tie exists), 2 (parallel tracks), or blank (no tie). In the future I hope to calculate tie strength using a method that accounts for the number of cards required to form a given tie on the board.

Both adjacency matrix formats have been tested - .csv in Gephi and .mat in Cytoscape using aMatReader.

Credit to Daniel B Scott whose ["Ticket to Ride's Adjacency Matrix"](https://danbscott.ghost.io/ticket-to-rides-adjacency-matrix/) from 2015 served as inspiration for my implementation of the European spinoff. 