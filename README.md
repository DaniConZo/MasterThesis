# MasterThesis
Galaxy classification with ML algortihms. I tried to classify galaxies into three different types (red green blue) from their photometry, using supervised and unsupervised ML algorithms. I also determined the redshift of each galaxy from their photometry with a Neural Network in Pytorch and the kNN algorithm. The repository contains all the raw jupyter notebooks I used along the project. It also contains the data file.

'ANF40pau...' contains: coordinates Ra-Dec, narrow and wide energy fluxes with errors, spectroscopic redshift, photo redshift, and a galaxy type variable for over 12000 galaxies in total.

All Jupyter notebooks named 'TFM...' The name is self explanatory.

Estadística descriptiva: contains some code to check the nature of our galaxies sample. Histograms with different galaxy types, redshift distribution, somo color-color plots, Principal components analysis...

Supervised algorithms: I tried kNN, a simple decision tree and a linear fit

Unsupervised algorithms, where I tried DBSCAN, Agglomerative clustering...

k-means: different tries with this non supervised algorithm. Different inputs, redshift windows...

redshift: redshift estimation with kNN algorithm (all galaxies at the same time or estimating redshift for a particular type only), and some previous plots.