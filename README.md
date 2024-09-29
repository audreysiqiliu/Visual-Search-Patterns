# Visualizing Search Strategies via Mouse Trajectories

See Jupyter Notebook on Google Colab [here](https://colab.research.google.com/drive/16Yq-kTzFO0Qfbt8GljHT8cL6NSm9FkjY?usp=sharing)

Data collected from online Ts and Ls task. See task demo at github repo: [Simple Visual Search Task](https://github.com/audreysiqiliu/Simple-Visual-Search-Task/blob/main/README.md).

Question: How do we identify subjects who use similar visual search strategies using their mouse trajectory information during a search task? Would subjects perform better when paired with similar or dissimilar other participants or AI models?

## Contents: Mouse Tracking Visualizations

### Feature Space

PCA analysis with main mouse trajectory features (shape and length).

**By Trials - K Means Clustering**
Visualizations of each subject's position in this 2D feature space on each trial. Subjects clustered into three groups of similar strategies based on distance in this feature space using K Means. Colors indicate cluster identity.

**By Trials - Performance Quads**
Same as above but colors instead indicate performance quadrants by speed and accuracy (slow, accurate; fast, accurate; slow, inaccurate; fast, inaccurate). Helps visualize strategies that lead to optimal overall performance.

**By Subject**
Visualization of how all trials completed by each subject fall in 2D feature space. Marker shapes indicate target presence, color indicates set size (difficulty). Shows how subject strategies change based on task demands.

### Similarity
Similarity matrices for subjects based on distance in trial-by-trial feature space; colors indicate number of trials where subjects shared the same K-Means cluster membership. Also includes dendrograms to visualize 'families' of strategies.
