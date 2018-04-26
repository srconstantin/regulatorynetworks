# regulatorynetworks

Big Graph creates a regulatory network model from published papers, where we mark "A upregulates/activates/produces B" with a "+1" and "A inhibits/blocks/destroys B" with a "-1".

Little Graph creates a smaller network including only the Hallmarks of Aging.

Big Graph SVD computes the singular value decomposition of this matrix, and projects it onto the unit vectors for each of the Hallmarks of Aging, so that we isolate which molecules contribute the most (in the long-run of regulatory network dynamics) to each hallmark of aging.

Graph Roots computes root nodes of Big Graph and ranks them by number of descendants.

Spectral Clustering divides Big Graph into spectral clusters.

Boolean Networks creates a Boolean network out of Little Graph.
