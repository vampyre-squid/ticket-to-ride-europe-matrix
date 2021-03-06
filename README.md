# Ticket to Ride: Europe's Adjacency Matrix
An [adjacency matrix](http://faculty.ucr.edu/~hanneman/nettext/C5_%20Matrices.html) representing connections (edges/links/ties) between cities (nodes/vertices) in the board game _Ticket to Ride: Europe_. For this matrix, I assume 4-5 players and naïvely calculate tie strength as 1 (tie exists), 2 (parallel tracks), or blank (no tie). In the future, I hope to calculate tie strength using a method that is closer to the ground truth of play by accounting for the number of cards required to form a given tie on the board.

Both adjacency matrix formats have been tested - .csv in [Gephi](https://gephi.org/) and .mat in [Cytoscape](https://cytoscape.org/) using [aMatReader](http://apps.cytoscape.org/apps/amatreader).

Credit to Daniel B Scott whose ["Ticket to Ride's Adjacency Matrix"](https://danbscott.ghost.io/ticket-to-rides-adjacency-matrix/) from 2015 served as inspiration for my implementation of the European spinoff. 
