# Definição

[Wikipedia](https://en.wikipedia.org/wiki/Travelling_salesman_problem):
The **travelling salesman problem** (**TSP**) asks the following question: "Given a list of cities and the distances between each pair of cities, what is the shortest possible route that visits each city exactly once and returns to the origin city?" It is an [NP-hard](https://en.wikipedia.org/wiki/NP-hardness "NP-hardness") problem in [combinatorial optimization](https://en.wikipedia.org/wiki/Combinatorial_optimization "Combinatorial optimization"), important in [theoretical computer science](https://en.wikipedia.org/wiki/Theoretical_computer_science) and [operations research](https://en.wikipedia.org/wiki/Operations_research "Operations research"). ^07d1c6

![[GLPK solution of a travelling salesman problem.png]] ^d0da04

# Relevância

The problem was first formulated in 1930 and is one of the most intensively studied problems in optimization. It is used as a [benchmark](https://en.wikipedia.org/wiki/Benchmark_(computing) "Benchmark (computing)") for many optimization methods. Even though the problem is computationally difficult, many [heuristics](https://en.wikipedia.org/wiki/Heuristic "Heuristic") and [exact algorithms](https://en.wikipedia.org/wiki/Exact_algorithm "Exact algorithm") are known, so that some instances with tens of thousands of cities can be solved completely and even problems with millions of cities can be approximated within a small fraction of 1%.[[1]](https://en.wikipedia.org/wiki/Travelling_salesman_problem#cite_note-1)

# TSP Euclidiano - ETSP

[Wikipedia](https://en.wikipedia.org/wiki/Travelling_salesman_problem)

For points in the [Euclidean plane](https://en.wikipedia.org/wiki/Euclidean_plane "Euclidean plane"), the optimal solution to the travelling salesman problem forms a [simple polygon](https://en.wikipedia.org/wiki/Simple_polygon "Simple polygon") through all of the points, a [polygonalization](https://en.wikipedia.org/wiki/Polygonalization "Polygonalization") of the points.[[37]](https://en.wikipedia.org/wiki/Travelling_salesman_problem#cite_note-37) Any non-optimal solution with crossings can be made into a shorter solution without crossings by local optimizations. The [Euclidean distance](https://en.wikipedia.org/wiki/Euclidean_distance "Euclidean distance") obeys the triangle inequality, so the Euclidean TSP forms a special case of metric TSP. However, even when the input points have integer coordinates, their distances generally take the form of [square roots](https://en.wikipedia.org/wiki/Square_root "Square root"), and the length of a tour is a [sum of radicals](https://en.wikipedia.org/wiki/Sum_of_radicals "Sum of radicals"), making it difficult to perform the [symbolic computation](https://en.wikipedia.org/wiki/Symbolic_computation "Symbolic computation") needed to perform exact comparisons of the lengths of different tours.

## Polygonization

[Wikipedia](https://en.wikipedia.org/wiki/Polygonalization)

In [computational geometry](https://en.wikipedia.org/wiki/Computational_geometry "Computational geometry"), a **polygonalization** of a finite set of points in the [Euclidean plane](https://en.wikipedia.org/wiki/Euclidean_plane "Euclidean plane") is a [simple polygon](https://en.wikipedia.org/wiki/Simple_polygon "Simple polygon") with the given points as its vertices.[[1]](https://en.wikipedia.org/wiki/Polygonalization#cite_note-reflexivity-1) A polygonalization may also be called a **polygonization**,[[2]](https://en.wikipedia.org/wiki/Polygonalization#cite_note-dfor-2) **simple polygonalization**,[[3]](https://en.wikipedia.org/wiki/Polygonalization#cite_note-fekete-3) **Hamiltonian polygon**,[[4]](https://en.wikipedia.org/wiki/Polygonalization#cite_note-grunbaum-4) **non-crossing Hamiltonian cycle**,[[5]](https://en.wikipedia.org/wiki/Polygonalization#cite_note-long-5) or **crossing-free straight-edge spanning cycle**.[[6]](https://en.wikipedia.org/wiki/Polygonalization#cite_note-ssw-6)