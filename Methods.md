Methods:

The cell classification pipeline for human blastoids involved several steps. Two main objects, the blastoid and the center of the inner cell mass (defined by nuclei with more neighbors), were segmented as references for locating all cell types. Two distance maps were generated: one representing the distance of each pixel to the blastoid border, and another representing the distance to the most inner nuclei border. Using these distance maps, the outer cell layer was defined as cells at the blastoid border, and the inner cell mass was defined as nuclei not classified as outer cells. Polar cells were identified as outer cells in contact with inner cells, with an additional filter for complex-shaped blastoids to include outer cells touching the first detected polar cells. Mural cells were defined as outer cells not classified as polar cells, and transitional cells were mural cells in contact with polar cells. First transitional cells were mural cells touching polar cells, while second transitional cells were mural cells touching the first transitional cells. This methodology allowed for precise classification and analysis of cell types within human blastoids, enhancing the understanding of their spatial organization and interactions.

Histogram equalization was applied to all image channels except for the nuclei channel to enhance contrast.