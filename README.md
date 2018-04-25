# regulatorynetworks

Big Graph creates a regulatory network model from published papers, where we mark "A upregulates/activates/produces B" with a "+1" and "A inhibits/blocks/destroys B" with a "-1".

Big Graph SVD computes the singular value decomposition of this matrix, and projects it onto the unit vectors for each of the Hallmarks of Aging, so that we isolate which molecules contribute the most (in the long-run of regulatory network dynamics) to each hallmark of aging.

