# Assembly Reorganization Explorer (prototype)

Interactive prototype built for the New Jersey Health Foundation Research Grant
application *Cell-Assembly Rigidity in Prodromal Alzheimer's Disease: A Circuit
Biomarker of Cognitive Inflexibility* (Guimu Guo, PI, Computer Science, and
Elizabeth A. West, Co-PI, Neuroscience, Rowan University).

Planned live page: https://guimuguo.github.io/assembly-reorg-demo/

**All data on the page are simulated.** Networks for one wild-type animal and two
AD-model phenotypes (rigidity, fragmentation) are generated deterministically in
the page's JavaScript across 10 conditioning sessions and a post-devaluation test.
The assembly enumeration (dense subgroups of 3 to 5 units, maximal, overlap-pruned)
and the four per-animal metrics are computed live from those simulated networks.
The 34-rat cohort, the regression fits and the ROC curves are simulated as well.
No recordings have been analyzed.

Panels: guided tour; animal / task-epoch / session controls with playback; co-firing
network with certified assemblies and hover details; per-animal metrics (formation,
cue-outcome binding, reorganization index, fragmentation) with a per-session
sparkline and assembly list; Aim 2 cohort scatter (network measure vs. single-neuron
measure, table view) and genotype ROC curves; pipeline, significance and team sections.
Light and dark themes.

Not yet built (planned): a surrogate-certification panel (observed vs. 1,000 jittered
networks) and a GraphMine definition-selection panel.

Single self-contained `index.html` (D3 v7 from cdnjs, no build step). Serve the folder
with any static server; `og.png` (1200x630 preview image) still to be added.
