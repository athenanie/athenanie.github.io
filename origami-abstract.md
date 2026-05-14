---
title: Designing Spiky Origami Polyhedra
---

All photos and additional can be viewed on [Flickr](https://flic.kr/s/aHBqjCP2Nq).

### Abstract

Origami polyhedral compounds are composed of interlocking wireframes, which are polyhedra or polygons constructed only out of their edges. This project focuses on compounds woven from polygonal frames, constructed with each edge bent slightly for easier weaving. As a result, each frame takes on a spiky, star-like shape.

A well-known example of this type of model is Six Intersecting Pentagrams. It's made out of six interwoven 5-pointed stars, and the polyhedral shape underlying the compound is an icosidodecahedron. From a mathematical perspective, I noticed there are many other polyhedra that could inspire compounds constructed using a similar method, yet no one had made them before. This project investigates and pushes the limits on the criteria for a polyhedron to be designed and constructed in this manner. Drawing on established knowledge of polyhedra, I independently designed, folded, and categorized thirty-five origami compounds, and generalized my design insights to graph theory.

All polyhedra were constructed from simple edge units, with varying angles and paper ratios. Each n-gram (n-pointed star) frame is constructed out of n edge units. Then the star frames are woven together in a basket-weave-like pattern, following closed loops along the edges of the chosen polyhedron. Each model is colored symmetrically, never letting the same color touch itself aside from self-intersection. Design work involved creating polyhedron mockups in polyhédronisme, taking measurements, and angle/ratio calculations. Materials include 24lb Astrobrights color paper and *no glue*. These were designed and folded by me between December 2024 and August 2025, though the vast majority of folding took place during Summer 2025 (May-Aug 2025).

Generally, I found that polyhedra with degree 4 (four edges at each vertex) can be woven into these compounds, though this project only explores highly symmetrical polyhedra. There are specific polyhedral operations that can create degree-4 polyhedra with predictable visual effects: expansion of degree-3 shapes, further expansion of degree-4 shapes (“double”, “quadruple”, etc), truncation + rectification of degree-4 shapes (“twisty”), and snub + expansion (“floral”). This work expands on both simple and complex origami compound designs and finds patterns that can be used by artists, designers, and engineers to create interesting 3-dimensional forms.


### Originally Degree-4 Polyhedra

In figuring out why Six Intersecting Pentagrams and the icosidodecahedron "worked", I noticed that degree-4 polyhedra naturally have a basket-weaving-like pattern. By following edges around the shape, always jumping to the opposite edge at each vertex, we form closed cycles that partition the entire set of edges. Each cycle (of length 2n) can be represented by an n-pointed star (n-gram), which in fact has 2n edges. Each vertex is where two stars/cycles intersect, and by following an in-and-out weaving pattern, we are able to create a stable origami compound.

| ten nonagrams (rectified truncated icosahedron)|
|--|
|![atI](imgs\ten_nonagrams.png) |
|<https://levskaya.github.io/polyhedronisme/?recipe=atI>|
| 90-degree units folded out of 4.25”x2.125” paper, 90 units total |

The following three compounds are a bit different than the rest on this page; they're based off of Meenakshi Mukerji's planar star guides, which are degree-4 graphs that don't necessarily have a nice polyhedral representation in 3D. But due to their degree-4-ness and symmetric nature, their structure works just as well for origami compounds.

| 7 hexagrams (TUVWXYZ Star) | 8 heptagrams (STUVWXYZ Star) | 9 octagrams (RSTUVWXYZ Star)|
|--|--|--|
| ![7](imgs\seven_hexagrams.png) | ![8](imgs\eight_heptagrams_1.png) | ![9](imgs\nine_octagrams_1.png) |
| 120-degree units folded out of 5.5”x2.667” paper, 42 units total | ~103-degree units folded out of 4.5”x2.125” paper, 56 units total | ~103-degree units folded out of 4.5”x2.125” paper, 72 units total |


### Expanded Degree-3 Polyhedra

The Archimedean rhombicosidodecahedron and rhombicuboctahedron below certainly count as well-known degree-4 polyhedra. However, they're included in this section because they fit the generalization of expansions of degree-3 polyhedra. From math, we know that the expansion of any polyhedron is degree-4, which is something we'll come back to. But expansions of degree-3 polyhedra in particular have a clear face-to-star correspondence since each face turns into a cupola when expanded. As a result, there is a shared theory behind the weaving of the following shapes.

| 12 pentagrams (rhombicosidodecahedron) | 6 quadgrams (rhombicuboctahedron) |
|--|--|
| ![](imgs\rhombicosidodecahedron.png) | ![](imgs\six_quadgrams_1.png) |
| 120-degree units folded out of 5.5”x2.25” paper, 60 units total | ~132-degree units folded out of 5.5”x2.25” paper, 24 units total |

| 12 pentagrams + 4 hexagrams (expanded truncated triakis tetrahedron) |
|--|--|
| ![et6k3T](imgs\truncated_triakis_tetrahedron_1.png) |
| <https://levskaya.github.io/polyhedronisme/?recipe=K9eK9t6k3T> |
| 120-degree units folded out of 5.5”x2.25” paper, 84 units total |

| expanded truncated icosahedron | expanded goldberg polyhedron |
|--|--|
| ![etI](imgs\expanded_truncated_icosahedron_1.png) | ![ewD](imgs\expanded_goldberg_polyhedron.png) |
| <https://levskaya.github.io/polyhedronisme/?recipe=etI> | <https://levskaya.github.io/polyhedronisme/?recipe=eK99wD> |
| 120-degree units folded out of 4.25”x1.92” paper, 90 units total | 120-degree units folded out of 4.25"x1.833" paper, 420 units total |

| expanded great rhombicosidodecahedron | expanded great rhombicuboctahedron |
|--|--|
| ![egeD](imgs\expanded_great_rhombicosidodecahedron.jpg) | ![egeC](imgs\expanded_great_rhombicuboctahedron.jpeg) |
| <https://levskaya.github.io/polyhedronisme/?recipe=A9etaD> | <https://levskaya.github.io/polyhedronisme/?recipe=A9etaC> |
| 4.25"x1.833" paper, ~132-degree for quadgrams, 120-degree for pentagrams, 90-degree for decagrams, 360 units total | 4.25"x2.125" paper, ~132-degree for quadgrams, 120-degree for hexagrams, ~103-degree for octagrams, 144 units total|


### More-expanded Polyhedra

What happens when you expand a polyhedron that's already degree-4? Each existing cycle "doubles", i.e. becomes two parallel cycles, each with double the length as before. In origami terms, each n-gram will turn into two (2n)-grams. For example, the icosidodecahedron is Six Intersecting Pentagrams; but the expanded icosidodecahedron below is comprised of 12 decagrams. I came up with many of the compounds in this section by just doing the expansion operation on the polyhedra from above.

| doubled icosidodecahedron (12 decagrams) | doubled cuboctahedron (8 hexagrams) |
|--|--|
| ![eaD](imgs\expanded_icosidodecahedron.png) | ![eaO](imgs\expanded_rhombicuboctahedron.jpeg) |
| <https://levskaya.github.io/polyhedronisme/?recipe=K99eaD> | <https://levskaya.github.io/polyhedronisme/?recipe=K99eaO> |
| expanded icosidodecahedron; 90-degree units folded out of 4.25"x1.125" paper, 120 units total |expanded cuboctahedron; 120-degree units folded out of 4.25"x1.833" paper, 48 units total |

| doubled ten planes (20 octadecagrams) |
|--|
| ![eatI](imgs\expanded_rectified_truncated_icosahedron.jpeg) |
| <https://levskaya.github.io/polyhedronisme/?recipe=A9eatI> |
| expanded rectified truncated icosahedron; <83-degree units folded out of 4.25”x2’’ rectangles, 360 units total |

| doubled rhombicosidodecahedron (24 decagrams) | doubled rhombicuboctahedron (12 octagrams) |
|--|--|
| ![eeD](imgs\doubled_rhombicosidodecahedron_1.png) | ![eeC](imgs\expanded_rhombicuboctahedron.jpg) |
| <https://levskaya.github.io/polyhedronisme/?recipe=K99eeD> | <https://levskaya.github.io/polyhedronisme/?recipe=K99eeC> |
| expanded rhombicosidodecahedron; 90-degree units folded out of 4.25”x2.125” and 5.5”x2.125” paper, 240 units total  | expanded rhombicuboctahedron; 90-degree units folded out of 4.25”x2.125” and 5.1”x2.125” paper, 96 units total |

The Archimedean degree-3 truncated tetrahedron, truncated octahedron, and truncated cube have yet to be mentioned, because I felt their expanded versions were too small to be made into a non-trivial compound. But an additional expansion does the job:

| doubled expanded truncated tetrahedron | doubled expanded truncated octahedron | doubled expanded truncated cube |
|--|--|--|
| ![eetT](imgs\2expanded_truncated_tetrahedron.jpeg) | ![eetO](imgs\2expanded_truncated_octahedron.jpg) | ![eetC](imgs\2expanded_truncated_cube.jpg) |
| <https://levskaya.github.io/polyhedronisme/?recipe=K9eetT> | <https://levskaya.github.io/polyhedronisme/?recipe=K999eetO> | <https://levskaya.github.io/polyhedronisme/?recipe=K99eetC> |
| expanded expanded truncated tetrahedron; 120-degree hexagrams, 4.25"x2.125" and 5.5"x2.125" paper; 90-degree dodecagrams, 4.25"x2.125" and 5.1"x2.125" paper; 144 units total | expanded expanded truncated octahedron; 90-degree octagrams and dodecagrams out of 4.25"x2.125" and 5.1"x2.125" paper; 288 units total | expanded expanded truncated cube; 120-degree hexagrams, 4.25"x2.125" and 5.5"x2.125" paper; ~83 degree hexadecagrams, 4.25"x2.125" and 1.15x longer rectangles; 288 units total |

This "doubling" expansion process can be applied multiple times, though size and resources posed a physical limitation on which shapes this could be applied to. In the compounds below, I applied it twice, creating "quadruple" parallel loops which are quite visually identifiable.

| quadrupled cuboctahedron (16 dodecagrams) |
|--|
| ![eeaC](imgs\quadrupled_cuboctahedron_1.png) |
| <https://levskaya.github.io/polyhedronisme/?recipe=K99eeaO> |
| expanded expanded cuboctahedron; 90-degree units folded out of 4.25”x2.125” and 1.08x longer rectangles, 192 units total |

|expanded expanded rhombicuboctahedron |
|--|
| ![eeeC](imgs\quadrupled_rhombicuboctahedron_1.png)|
| <https://levskaya.github.io/polyhedronisme/?recipe=K99eeeC> |
| ~83-degree units folded out of 4 sizes of rectanges of width 2.125”; lengths are 4.25”, 4.87”, 5.28”, 5.5", 384 units total |

From now on, this process is nicknamed as "doubling", "quadrupling", etc.


### "Twisty" Polyhedra

After much experimentation and operation spam in polyhedronisme, I found another generalization: applying the truncation then rectification operation on a degree-4 shape results in twisted doubled version of each closed loop. In origami terms, this means each n-gram is turned into two "parallel" (1.5n)-grams that repeatedly twist and intersect eachother, almost like a DNA double helix. This result is also pretty visually identifiable.

This "twisty" process can also be combined with "doubling", as can be seen several times in this section. They are not commutative, however (see "doubled twisty octahedron" versus "twisty doubled octahedron" below).

| twisty octahedron (6 hexagrams) | doubled twisty octahedron (12 dodecagrams) |
|--|--|
| ![rtO](imgs\twisty_octahedron.jpeg) | ![ertO](imgs\expanded_twisty_octahedron.jpeg) |
| <https://levskaya.github.io/polyhedronisme/?recipe=K999atO> | <https://levskaya.github.io/polyhedronisme/?recipe=K999eatO> |
| rectified truncated octahedron; 120-degree units folded out of 4.25"x1.833" paper, 36 units total | expanded rectified truncated octahedron; 90-degree units folded out of 4.25"x1.833" paper, 144 units total |

| twisty cuboctahedron (8 nonagrams) | doubled twisty cuboctahedron (16 octadecagrams) | twisty doubled cuboctahedron (16 octadecagrams)|
|--|--|--|
| ![rtaO](imgs\twisty_cuboctahedron.jpeg) | ![ertaO](imgs\expanded_twisty_cuboctahedron.jpeg) | ![rteO](imgs\twisty_expanded_cuboctahedron.jpeg) |
| <https://levskaya.github.io/polyhedronisme/?recipe=K999abO> | <https://levskaya.github.io/polyhedronisme/?recipe=A9eabO> | <https://levskaya.github.io/polyhedronisme/?recipe=K9ateaO> |
|  rectified truncated cuboctahedron, AKA rectified great cuboctahedron; ~104-degree units folded out of 4.25”x1.833" paper, 72 units total | expanded rectified truncated cuboctahedron; 90-degree units folded out of 4.25”x1.833" paper, 288 units total | rectified truncated expanded cuboctahedron; 90-degree units folded out of 4.25"x1.833" paper, 288 units total |

| twisty icosidodecahedron (12 pentadecagrams) |
|--|
| [photo temporarily unavailable] |
| <https://levskaya.github.io/polyhedronisme/?recipe=K999abD> |
| rectified truncated icosidodecahedron, AKA rectified great rhombicosidodecahedron; 90-degree units folded out of 4.25”x1.833" paper, 180 units total |

| twisty rhombicuboctahedron (12 dodecagrams) | twisty rhombicosidodecahedron (24 pentadecagrams) |
|--|--|
| ![rteC](imgs\twisty_rhombicuboctahedron.jpeg) | ![rteD](imgs\twisty_rhombicosidodecahedron.jpg) |
| <https://levskaya.github.io/polyhedronisme/?recipe=K9A9ateC> | <https://levskaya.github.io/polyhedronisme/?recipe=K9A9ateD> |
| rectified truncated rhombicuboctahedron; 90-degree units folded out of 4.25”x1.833" paper, 144 units total | rectified truncated rhombicosidodecahedron; 90-degree units folded out of 4.25”x1.833" paper, 360 units total |


### "Floral" Polyhedra

The last (and perhaps weirdest) generalization covered here is the result of snubbing and expansion. Visually, we can see that the resulting origami compounds have elaborate self-intersecting faces (they look a bit like flower petals). There is a rough correspondence between the faces of the original shape and the cycles in the expanded snubbed version. The exact specifications (cycle length and turning number) of these self-intersecting cycles are predictable, though much less clearly.

From now on, the notation {n/k} is used to denote self-intersecting loops/cycles that have n "petals" with turning number k. Note that if gcd(n,k)>1, they will decompose into simpler shapes.

| floral cube (6 loops) | floral dodecahedron (12 loops) |
|--|--|
| ![esC](imgs\floral_cube.jpeg) | [photo temporarily unavailable] |
| <https://levskaya.github.io/polyhedronisme/?recipe=A9esC> | <https://levskaya.github.io/polyhedronisme/?recipe=K99esD> |
| expanded snub cube, comprised of six 20-grams with turning number 3; 120-degree units folded out of 4.25”x1.833" paper, 120 units total | expanded snub dodecahedron, comprised of twelve 25-grams with turning number 3; 90-degree units folded out of 4.25”x1.833" paper, 300 units total |

| floral truncated tetrahedron | floral truncated octahedron | floral truncated cube |
|--|--|--|
| ![estT](imgs\floral_truncated_tetrahedron.jpeg) | ![estO](imgs\floral_truncated_octahedron.jpg) | ![estC](imgs\floral_truncated_cube.jpeg) |
| <https://levskaya.github.io/polyhedronisme/?recipe=A9estT> | <https://levskaya.github.io/polyhedronisme/?recipe=A9estO> | <https://levskaya.github.io/polyhedronisme/?recipe=A9estC> |
| expanded snub truncated tetrahedron; 6-colored by edges of overall tetrahedron shape: each color gets 2 pentagrams at 120-degrees with 4.25”x1.833" paper, 2 long-decagrams at 90-degrees with 2*(3 4.25”x1.833" and 2 5.5"x1.833") paper, 180 units total | expanded snub truncated octahedron; {4/3} at 120-degrees with 4.25”x1.833" paper, {6/3} are comprised of long decagrams with 2*(4 4.25”x1.833" and 1 5.5"x1.833") paper, 360 units total | expanded snub truncated cube; {3/3} are comprised of pentagrams at 120-degrees with 4.25”x1.833" paper, {8/3} are 40-grams at 90-degrees with 8*(4 11/6”x4.25” and 5.5"x1.833" paper), 360 units total |

| floral cuboctahedron (8 loops) | floral rhombicuboctahedron |
|--|--|
| ![esaO](imgs\floral_cuboctahedron.jpg) | ![eseC](imgs\floral_rhombicuboctahedron.jpeg) |
| <https://levskaya.github.io/polyhedronisme/?recipe=A9esaC> | <https://levskaya.github.io/polyhedronisme/?recipe=A99eseC> |
| expanded snub cuboctahedron, comprised of eight 30-grams with turning number 4; 90-degree units folded out of 4.25”x1.833" paper, 240 units total | expanded snub rhombicuboctahedron; {3/4} are 30-grams at ~104-degrees with 4.25”x1.833" paper, {4/4} are comprised of decagrams at >90-degrees with 4.25”x1.833" paper, 480 edges |

Generally, all of the polyhedra above have turned out pretty spherical, but this isn't necessarily the case in this section. The expanded snub truncated tetrahedron is visibly tetrahedral and the expanded snub truncated octahedron is visibly octahedral. Both the expanded snub truncated cube and expanded snub rhombicuboctahedron are cube-like.