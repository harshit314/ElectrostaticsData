# ElectrostaticsData
Data generated using BIM used in the paper 'Electrostatic interactions between anisotropic particles'.

The folders are named based on the aspect ratio of the spheroids, i.e. kappa1 -> sphere-sphere case, kappa4 -> prolate-sphere case and kappaD25 -> oblate-sphere case.
The folders contain text files for the values of the potential matrix computed using BIM in the following format:
$d$,  $\psi$,  $cos(\psi)$,  $\phi_{11}$,  $\phi_{12}$,  $\phi_{22}$

$d$ is the centre to centre distance between the two bodies, non-dimensionalized by the longer side length of the spheroid. Thus, for kappa1 and kappa4, this distance is relative to the side length $a$, while for kappaD25, this distance is relative to side length $a/\kappa$.

$\psi$ is the angle between separation vector and the symmetry axis of the spheroid.

$\phi_{ij}$ is the ij-th element of the potential matrix. Since potential matrix is symmetric, $\phi_{12} = \phi_{21}$.

CInvLub files have data for $d \ll 1$ when the bodies are nearly touching.



