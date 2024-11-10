# quasicrystal
Mathematical Investigation into quasicrystals

Project members: Alan

References:
https://github.com/fogleman/Tiling


Others:
https://arxiv.org/abs/1811.03792v1

https://epubs.siam.org/doi/10.1137/0215074
https://www.amazon.science/publications/quantum-optimization-of-maximum-independent-set-using-rydberg-atom-arrays

Findings:
2d structure:
2 types of tesselations, regular and semi regular. Regular tesselations are made of a single repeating unit while semi-regular tesselations are made of 2 or more repeating units.
Regular tesselations can only be made of polygons with internal angles that are integer dividers of 360 degrees. Mathematically, 360 ≅ 0 (mod (n-2)*180/n) 
Only three unit shapes possible for regular tesselation, triangles, squares and hexagons.
polygons with 5 fold symmetry cannot regularly tesselate as internal angles of such polygon is 108 degrees, not an integer diviser of 360.

Sources: https://www.mathsisfun.com/geometry/tessellation.html

Higher dimensional structure:
Angle between two vectors θ in higher dimensions is defined by the dot product: a · b = |a| × |b| × cos(θ)
internal angles of units in crystal must add to 360 degrees when resolved in all dimensions
For a regular structure with the repetition of a single unit crystal must observe translational symmetry, where repeating units are translated in n dimensions to form the entire crystal.
A regular polygon in the nth dimesion must have faces that are regular polygons of the (n-1)th dimesion, as well as equal angles between verticies.

Sources:https://earthscience.stackexchange.com/questions/1015/why-are-there-no-crystals-with-5-fold-symmetry  
https://geo.libretexts.org/Bookshelves/Geology/Mineralogy_(Perkins_et_al.)/11%3A_Crystallography/11.02%3A_Translational_Symmetry

Quasicrystals:
Quasicrystals have an orderly structure but lack translational symmetry dissimilar to regular crystals
Crystal structure has long-range order with predictable arrangements of units across the entire crystalline structure but repetition of units is not periodic
Diffraction analysis of quasicrystals reveal that individual units have 4 dimensional complexity (???)
Crystals with regular tiling of higher dimensions can be projected onto a lower dimension to form quasicrystalline patterns (???)



Update 10/11/24:
Steradian: solid angle, in the form of a circular cone section of a sphere. Steradian Ω=A/r^2 where A is the area of spherical section at bottom the cone, simplified to Ω=2(pi)h/r
Steradian=1/4(pi) of complete sphere
If solid angles of units add up to 4(pi) steradians, unit can tesselate in 3d
code:
python turtle graphics (WIP)
Libraries for plotting: numpy, mathplotlib, installed via PIP
Golden ratio within penrose structure: Ratio of sizes of polygons such as sizes of adjascent rings is usually determined by the golden ratio
Quasicrystals as vector sum of waves in a plane: http://mainisusuallyafunction.blogspot.com/2011/10/quasicrystals-as-sums-of-waves-in-plane.html








Sources:
https://en.wikipedia.org/wiki/Quasicrystal
https://en.wikipedia.org/wiki/Aperiodic_crystal
https://www.sciencedirect.com/topics/materials-science/quasicrystal
https://modern-physics.org/quasicrystals/
