Forked from[scgcn](https://github.com/QSong-github/scGCN). Just for fun:)

Fix bugs:
1. Those classes with small number of cells cause train_test_split (data.py) error.
2. Unseen types in target labels cause onehot transformation (utils.py) error.
3. Construction of adjacency matrix is very slow when n_cell > 50000 (utils.py).
