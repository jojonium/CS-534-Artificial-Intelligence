% Artificial Intelligence Notes
% Joseph Petitti
% January 27, 2020

# A*

Evaluation function $f(n) = g(n) + h(n)$

  - $g(n) =$ cost from start to node $n$
  - $f(n) =$ heuristic cost from node $n$ to goal

Heuristic is optimistic

  - Straight-line distance underestimates real costs
  - When you actually explore a path, the cost *usually* goes up (at least, it
	will never go down)
  - May have to backtrack and consider paths you thought would be less good

## Sliding Puzzle

  - Cost of each move: 1
  - Admissible heuristics: Manhattan distance from each tile to its goal, or
	number of tiles in the wrong place (both functions work)
  - Because the first heuristic always gives higher numbers than the second
	while still being admissible, we say it "dominates," and is therefore more
	useful
  - The domainating heuristic leads to a smaller branching factor, which means
	we explore fewer paths.

