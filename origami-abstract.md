---
layout: post
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

| 10 nonagrams (rectified truncated icosahedron)|
|--|
|![atI](imgs\ten_nonagrams.png) |
|<https://levskaya.github.io/polyhedronisme/?recipe=atI>|
| 90-degree units folded out of 4.25”x2.125” paper, 90 units total |

The following three compounds are a bit different than the rest on this page; they're based off of Meenakshi Mukerji's planar star guides, which are degree-4 graphs that don't necessarily have a nice polyhedral representation in 3D. But due to their degree-4-ness and symmetric nature, their structure works just as well for origami compounds.

| 7 hexagrams (weaving based on TUVWXYZ Star) | 8 heptagrams (weaving based on STUVWXYZ Star) | 9 octagrams (weaving based on RSTUVWXYZ Star)|
|--|--|--|
| ![7](imgs\seven_hexagrams.png) | ![8](imgs\eight_heptagrams_1.png) | ![9](imgs\nine_octagrams_1.png) |
| 120-degree units folded out of 5.5”x2.667” paper, 42 units total | ~103-degree units folded out of 4.5”x2.125” paper, 56 units total | ~103-degree units folded out of 4.5”x2.125” paper, 72 units total |


### Expanded Degree-3 Polyhedra

The Archimedean rhombicosidodecahedron and rhombicuboctahedron below certainly also count as well-known degree-4 polyhedra. However, they are included in this section because they fit the generalization of expansions of degree-3 polyhedra. From math, we know that the expansion of any polyhedron is degree-4, which is something we'll come back to. But expansions of degree-3 polyhedra in particular have a clear face-to-star correspondence since each face turns into a cupola when expanded. As a result, there is a shared theory behind the weaving of the following shapes.

| 12 pentagrams (rhombicosidodecahedron) | 6 quadgrams (rhombicuboctahedron) |
|--|--|
| ![eD](imgs\rhombicosidodecahedron.png) | ![eC](imgs\six_quadgrams_1.png) |
| 120-degree units folded out of 5.5”x2.25” paper, 60 units total | ~132-degree units folded out of 5.5”x2.25” paper, 24 units total |

| 12 pentagrams + 4 hexagrams (expanded truncated triakis tetrahedron) |
|--|--|
| ![et6k3T](imgs\truncated_triakis_tetrahedron_1.png) |
| <https://levskaya.github.io/polyhedronisme/?recipe=K9eK9t6k3T> |
| 1:2 rectangles, 120 degrees |

| expanded truncated icosahedron | expanded goldberg polyhedron |
|--|--|
| ![etI](imgs\expanded_truncated_icosahedron_1.png) | ![ewD](imgs\expanded_goldberg_polyhedron.png) |
| <https://levskaya.github.io/polyhedronisme/?recipe=etI> | <https://levskaya.github.io/polyhedronisme/?recipe=eK99wD> |
| 1:2.22, 120 degrees | 11/6”x4.25”, 120 degrees |

| expanded great rhombicuboctahedron | expanded great rhombicosidodecahedron |
|--|--|
| ![egeC](imgs\expanded_great_rhombicuboctahedron.jpeg) | ![egeD](imgs\expanded_great_rhombicosidodecahedron.jpg) |
| <https://levskaya.github.io/polyhedronisme/?recipe=A9etaC> | <https://levskaya.github.io/polyhedronisme/?recipe=A9etaD> |
| all 1:2 rectangles, quadgrams at angle listed above, hexagrams at 120 degrees, octagrams at weird slightly >90 angle | 11/6”x4.25” rectangles, quadgrams at angle listed above, hexagrams at 120 degrees, decagrams at 90 degrees |


### More-expanded Polyhedra

What happens when you expand a polyhedron that's already degree-4? The result is that each cycle "doubles", i.e. becomes two parallel cycles, each with double the length as before. In origami terms, each n-gram will turn into two (2n)-grams. For example, the icosidodecahedron is Six Intersecting Pentagrams; but the expanded icosidodecahedron below is comprised of 12 decagrams. I came up with many of the compounds in this section by just doing the expansion operation on the polyhedra from above.

| expanded icosidodecahedron | expanded cuboctahedron |
|--|--|
| ![eaD](imgs\expanded_icosidodecahedron.png) | ![eaO](imgs\expanded_rhombicuboctahedron.jpeg) |
| <https://levskaya.github.io/polyhedronisme/?recipe=K999eaD> | <https://levskaya.github.io/polyhedronisme/?recipe=K999eaO> |
| (12 decagrams) doubled icosidodecahedron 1:2 4.25’’ rectangles; angle 90 degrees  |doubled cuboctahedron 4.25’’x11/6’’ rectangles, angle 120 degrees |

| expanded rectified truncated icosahedron |
|--|
| ![eatI](imgs\expanded_rectified_truncated_icosahedron.jpeg) |
| tk |

| expanded rhombicosidodecahedron | expanded rhombicuboctahedron |
|--|--|
| ![eeD](imgs\doubled_rhombicosidodecahedron_1.png) | ![eeC](imgs\expanded_rhombicuboctahedron.jpg) |
| <https://levskaya.github.io/polyhedronisme/?recipe=K999eeD> | <https://levskaya.github.io/polyhedronisme/?recipe=K999eeC> |
| (24 decagrams) 4.25”x2.125” and 5.5”x2.125”, 90 degree angle  | (12 octagrams) doubled rhombicuboctahedron 4.25”x2.125” and 1.2x longer, 90 degree angle |

The Archimedean degree-3 truncated tetrahedron, truncated octahedron, and truncated cube have yet to be mentioned, because I felt their expanded versions were too small to be made into a non-trivial compound. But an additional expansion does the job:

| expanded expanded truncated tetrahedron| expanded expanded truncated octahedron | expanded expanded truncated cube |
|--|--|--|
| ![eetT](imgs\2expanded_truncated_tetrahedron.jpeg) | ![eetO](imgs\2expanded_truncated_octahedron.jpg) | ![eetC](imgs\2expanded_truncated_cube.jpg) |
| <https://levskaya.github.io/polyhedronisme/?recipe=K9eetT> | <https://levskaya.github.io/polyhedronisme/?recipe=K999eetO> | <https://levskaya.github.io/polyhedronisme/?recipe=K99eetC> |
| hexgrams: 4.25’’x2.125’’ and 5.5’’x2.125’; dodecagrams: 4.25’’x2.125’’ and 1.1x longer | (eetO) (12 octagrams + 16 dodecagrams) 4.25’’x2.125’’ and 1.2x longer, 90 degree angle; for both octagrams and dodecagrams | (eetC) hexagrams: 4.25’’x2.125’’ and 5.5’’x2.125’ at 120 degrees; hexadecagrams: 4.25’’x2.125’’ and 1.15x longer at min angle for 1:2 rect |

This "doubling" expansion process can be applied multiple times, though size and resources posed a physical limitation on which shapes this could be applied to. In the compounds below, I applied it twice, creating "quadruple" parallel loops which are quite visually identifiable.

| expanded expanded cuboctahedron |
|--|
| ![eeaC](imgs\quadrupled_cuboctahedron_1.png) |
| <https://levskaya.github.io/polyhedronisme/?recipe=K99eeaO> |
| (16 dodecagrams) quadrupled cuboctahedron, 4.25”x2.125” and 1.08x longer, 90 degree angle |

|expanded expanded rhombicuboctahedron |
|--|
| ![eeeC](imgs\quadrupled_rhombicuboctahedron_1.png)|
| <https://levskaya.github.io/polyhedronisme/?recipe=K99eeeC> |
| 24 hexadecagrams, 4 sizes of rectanges with width 2.125”; lengths are 4.25”, 4.87”, 5.28”, 5.5”; angle slightly less than 90 degrees (limit of 1:2 unit) |

From now on, this process is nicknamed as "doubling", "quadrupling", etc.


### "Twisty" Polyhedra

After much experimentation and operation spamming in polyhedronisme, I found another generalization: applying the truncation then rectification operation on a degree-4 shape results in twisted doubled version of each closed loop. In origami terms, this means each n-gram is turned into two "parallel" (1.5n)-grams that repeatedly twist and intersect eachother, almost like a DNA double helix. This result is also pretty visually identifiable.

This "twisty" process can also be combined with "doubling", as can be seen several times in this section. They are not commutative, however (see expanded rectified truncated octahedron versus rectified truncated expanded octahedron).

| rectified truncated octahedron | expanded rectified truncated octahedron | rectified truncated expanded octahedron|
|--|--|--|
| ![rtO](imgs\twisty_octahedron.jpeg) | ![ertO](imgs\expanded_twisty_octahedron.jpeg) | ![rteO](imgs\twisty_expanded_cuboctahedron.jpeg) |
| <https://levskaya.github.io/polyhedronisme/?recipe=K999atO> | <https://levskaya.github.io/polyhedronisme/?recipe=K999eatO> | <https://levskaya.github.io/polyhedronisme/?recipe=K999ateO> |
| (6 hexagrams), “twisty octahedron” 4.25’’x11/6’’ rectangles, angle 120 degrees | (eatO) (12 dodecagrams) doubled “twisty octahedron” 4.25’’x11/6’’ rectangles, angle 90 degrees | tk |

| rectified great rhombicuboctahedron | expanded rectified great rhombicuboctahedron |
|--|--|
| ![rtaO](imgs\twisty_cuboctahedron.jpeg) | ![ertaO](imgs\expanded_twisty_cuboctahedron.jpeg) |
| <https://levskaya.github.io/polyhedronisme/?recipe=K999abO> | <https://levskaya.github.io/polyhedronisme/?recipe=A9eabO> |
| (8 nonagrams) “twisty cuboctahedron” 11/6”x4.25” rectangles, angle between 120 and 90 degrees, midpoint between those two edges | (16 octadecagrams) doubled “twisty cuboctahedron” 11/6”x4.25” rectangles, 90 degrees |

| rectified great rhombicosidodecahedron |
|--|
| [photo temporarily unavailable] |
| <https://levskaya.github.io/polyhedronisme/?recipe=K999abD> |
| (12 pentadecagrams) “twisty icosidodecahedron” 11/6”x4.25” rectangles, 90 degrees |

| rectified truncated rhombicuboctahedron | rectified truncated rhombicosidodecahedron |
|--|--|
| ![rteC](imgs\twisty_rhombicuboctahedron.jpeg) | ![rteD](imgs\twisty_rhombicosidodecahedron.jpg) |
| <https://levskaya.github.io/polyhedronisme/?recipe=K9A9ateC> | <https://levskaya.github.io/polyhedronisme/?recipe=K9A9ateD> |
| (12 dodecagrams) “twisty rhombicuboctahedron” 11/6”x4.25” rectangles, 90 degrees | (24 pentadecagrams) 11/6”x4.25” rectangles, 90 degrees |


### "Floral" Polyhedra

The last (and perhaps weirdest) generalization covered here is the result of snubbing and expansion. Visually, we can see that the resulting origami compounds have elaborate self-intersecting faces (they look a bit like flower petals). There is a rough correspondence between the faces of the original shape and the cycles in the expanded snubbed version. The exact specifications (cycle length and turning number) of these self-intersecting cycles are predictable, though much less clearly.

| expanded snub cube | expanded snub dodecahedron |
|--|--|
| ![esC](imgs\floral_cube.jpeg) | [photo temporarily unavailable] |
| <https://levskaya.github.io/polyhedronisme/?recipe=A9esC> | <https://levskaya.github.io/polyhedronisme/?recipe=K99esD> |
| (6 loops) “floral cube” 11/6”x4.25” rectangles, 20-grams with turning number 3 at 120 degrees | (12 loops) “floral dodecahedron” 11/6”x4.25” rectangles, 25-grams with turning number 3 at 90 degrees |

| expanded snub truncated tetrahedron | expanded snub truncated octahedron | expanded snub truncated cube |
|--|--|--|
| ![estT](imgs\floral_truncated_tetrahedron.jpeg) | ![estO](imgs\floral_truncated_octahedron.jpg) | ![estC](imgs\floral_truncated_cube.jpeg) |
| <https://levskaya.github.io/polyhedronisme/?recipe=A9estT> | <https://levskaya.github.io/polyhedronisme/?recipe=A9estO> | <https://levskaya.github.io/polyhedronisme/?recipe=A9estC> |
| “floral truncated tetrahedron” 6 colored by edges of tetrahedron; each color gets 2 pentagrams at 11/6”x4.25”, 2 long decagrams with 2*(3 11/6”x4.25” and 2 3:1 @90 degrees) | “floral truncated octahedron” {4/3}: 20-grams with turning number 3 at 120 degrees (11/6”x4.25”) {6/3}: do long decagrams with 2*(4 11/6”x4.25” and 1 3:1 @90 degrees) | “floral truncated cube” {3/3}: 3 pentagrams (11/6”x4.25”) {8/3}: 40-grams 8*(4 11/6”x4.25” and 1 3:1 @90 degrees), used some glue |

| expanded snub cuboctahedron | expanded snub rhombicuboctahedron |
|--|--|
| ![esaO](imgs\floral_cuboctahedron.jpg) | ![eseC](imgs\floral_rhombicuboctahedron.jpeg) |
| <https://levskaya.github.io/polyhedronisme/?recipe=A9esaC> | <https://levskaya.github.io/polyhedronisme/?recipe=A99eseC> |
| “floral cuboctahedron” (8 loops) {3/4}: 11/6”x4.25” rectangles, 30-grams with turning number 4, angle midpoint btwn 120 and 90 degrees | “floral rhombicuboctahedron” {3/4}: 11/6”x4.25” rectangles, 30-grams with turning number 4, angle midpoint btwn 120 and 90 degrees {4/4} 11/6”x4.25” rectangles, 4 10-grams, 2/3rds from 120 degrees to 90 degrees |

Generally, all of the polyhedra above have turned out pretty spherical, but this isn't necessarily the case in this section. The expanded snub truncated tetrahedron is visibly tetrahedral and the expanded snub truncated octahedron is visibly octahedral. Both the expanded snub truncated cube and expanded snub rhombicuboctahedron are cube-like.