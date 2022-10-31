# notes

## notes for boys:
- the mcpi_fast_query algo that returns blocks returns them using the block ids for picraft which r different than mcpi, grass blocks are 2 in picraft (returns by the function) but 2 is grass in mcpi for example

## notes for video:

**Terraforming**
- Terraforming algorithm needs access to the height of blocks, the mc.getHeight function is very slow, so instead the heights of all blocks were stored in a heightMap on generation of the grid in order to speed up operation
- made use of the mcpi_fast_query script found on github to greatly speed up requests to the mc server for getHeight and getBlock

**Pathfinding**

**House construction**
