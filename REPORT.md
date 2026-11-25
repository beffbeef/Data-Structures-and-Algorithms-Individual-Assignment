# REPORT.md - Individual Assignment

Keep this concise and specific to your implementation.

## 1. Initial analysis

- How are locations and connections represented in the baseline?

Locations by ints and "ids".
Connections by ints and fromLocationId.

- Which operations appear frequent?

Operations that appear the most is Linear search in FindLocationByID and FindOutgoingConnections.

- Which operation(s) do you predict may scale poorly? 

I think it will scale poorly because its a linear search, which tend to scale poorly when the data is bigger since it scales with O(n).

- What will you investigate first?
How to improve the speed of the Linear search to make it more efficient to use.




BaseLine-----
Test summary: total: 6; failed: 0; succeeded: 3; skipped: 3; duration: 2,0s
Build succeeded in 2,8s
PS C:\Users\casper.bengtsson2\Documents\GitHub\Data Structures and Algorithms, Individual Assignment> dotnet run --project Standalone/src/FrontierDispatch.App -- --baseline
Baseline world-query workload
Locations: 2500
Connections: 9800
Iterations: 5000
Elapsed: 443 ms
Checksum: 6267100
Absolute time varies by machine. Keep this result for before/after comparison.

## 2. Data representation

Describe important changes/retained choices, operations affected, and time/memory trade-offs.

## 3. Algorithms and adaptation

Explain your route finder at a useful high level and how the travel-budget query adapts the same ideas.

## 4. Complexity

| Operation | Your representation/algorithm | Complexity | Short explanation |
| --- | --- | --- | --- |
| Find location by ID | | | |
| Get outgoing connections | | | |
| Priority queue enqueue | | | |
| Priority queue dequeue-min | | | |
| Route finding | | | |

## 5. Correctness and testing

Important tests/edge cases and what they demonstrate.

## 6. Performance investigation

Record reproducible before/after measurements for loading/preparation, repeated runtime work, and relevant allocation behavior. Explain what changed and why.

## 7. Development reflection

Describe one bug, wrong assumption, failed approach, or surprising result and how you investigated it.

## 8. Tools and AI assistance

Briefly describe relevant assistance, if any.

## 9. VG extension

Only if attempting VG: heuristic, traversal constraints, correctness, and Dijkstra/A* comparison.
