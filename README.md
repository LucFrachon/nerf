# Neural Radiance Fields from Scratch

This is a notebook that I developed when exploring the topic of NeRFs for a Medium blog post (to be published).
I wrote it after reading the NeRF paper (Mildenhall, B., Srinivasan, P.P., Tancik, M., Barron, J.T., Ramamoorthi, R. and Ng, R., 2021. "NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis". Communications of the ACM, 65(1), pp.99–106.) and will use some of the plots in the post.

It is not the most optimal way to implement it (in fact the original implementation uses accumulated gradients over chuncks to save memory), but it works with the Tiny NeRF dataset.

It's still a very cool concept!
