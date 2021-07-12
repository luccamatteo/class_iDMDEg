[![](https://img.shields.io/badge/arXiv-2106.15196%20-red.svg)](https://arxiv.org/abs/2106.15196)

# Modification of CLASS (v2.9) for interacting DM-DE

This modified version of the [CLASS](https://github.com/lesgourg/class_public) code allows the computation of background quantities and perturbation equations for the multi-interacting dark energy scenario discussed in [Lucca 2021](https://arxiv.org/abs/2106.15196) (arXiv:2106.15196). This code can be used freely provided you cite the specific release paper ([Lucca 2021](https://arxiv.org/abs/2106.15196)) and the original CLASS release paper ([Blas et al. 2011](https://arxiv.org/abs/1104.2933)).

The code has been edited by M. Lucca (mlucca AT ulb.ac.be). We refer to the main CLASS code [wiki](https://github.com/lesgourg/class_public/wiki/Installation) for installations instructions. The main modifications with respect to the original version are in input.c, background.c and .h, thermodynamics.c, and perturbations.c (always enclosed in the comments "BEGIN/END MODIFICATION ML"). An input file test_iDMDEg.ini has been created with the basic quantities needed in order to run the modified code.




