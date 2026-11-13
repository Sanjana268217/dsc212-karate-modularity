# Finding Hidden Groups in the Karate Club Network (DSC212)

**Name:** Sanjana Krishna S
**Roll number:** IMS25185

A Jupyter notebook that finds communities in Zachary's Karate Club network using recursive spectral modularity partitioning (Newman, 2006). It draws the graph after every split and tracks how four node measures (degree, betweenness, closeness, clustering) change.

## Files
- `karate_modularity.ipynb`: the notebook (code, results, plots and discussion)

## What the notebook covers
- **Task 1:** Recursive spectral modularity partitioning
- **Task 2:** Graph visualizations across each split
- **Task 3:** Node metrics after each split
- **Task 4:** Evolution of each metric across iterations
- **Task 5:** Discussion

## How to run
```bash
pip install numpy networkx matplotlib jupyter
jupyter lab karate_modularity.ipynb
```
Then choose Kernel -> Restart & Run All. (In VS Code, open the notebook and click Run All.)

## Note on AI use
As allowed by the instructor, I used an AI assistant (Claude) to help write the code and first draft of this notebook. I have gone through it and understand the concepts behind it.

## References
- M. E. J. Newman (2006). *Modularity and community structure in networks.* PNAS 103(23):8577-8582.
- W. W. Zachary (1977). *An information flow model for conflict and fission in small groups.* J. Anthropological Research 33(4):452-473.
