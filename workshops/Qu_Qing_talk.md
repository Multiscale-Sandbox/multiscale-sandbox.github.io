# Learning Low-complexity Models from the Data – Geometry, Optimization, and Applications 

## Qing Qu (NYU)

## Abstract: 

Today we are collecting a massive amount of data in forms of images and videos, that
we want to learn from the data themselves to extract useful information and to make predictions.
The data are high-dimensional, but often possess certain low-dimensional structures (e.g.,
sparsity). However, learning these low-complexity models often results in highly nonconvex
optimization problems, where in the past our understandings of solving them were very limited.
In the worst case, optimizing a nonconvex problem is NP-hard.
 
In this talk, we present global nonconvex optimization theory and guaranteed algorithms for
efficient learning of low-complexity models from high-dimensional data. For several important
problems in imaging science (i.e., sparse blind deconvolution) and representation learning (i.e.,
convolutional/overcomplete dictionary learning), we show that the underlying symmetry and
low-complexity structures avoid the worst-case scenarios, leading to benign global geometric
properties of the nonconvex optimization landscapes. In particular, for sparse blind
deconvolution that aims to jointly learn the underlying physical model and sparse signals from
convolutions, the geometric intuitions lead to efficient nonconvex algorithms, with linear
convergence to target solutions. Moreover, we extended our geometric analysis to convolutional
dictionary learning based on its similarity with overcomplete dictionary learning, providing the
first global algorithmic guarantees for both problems. Finally, we demonstrate our methods on
several important applications in scientific discovery.

## Speaker Bio: 

Qing Qu is a Moore-Sloan data science fellow at the Center for Data Science, New
York University, and he will be joining EECS at the University of Michigan as an assistant
professor starting from Spring 2021. He received his Ph.D. from Columbia University in
Electrical Engineering in Oct. 2018. He received his B.Eng. from Tsinghua University in Jul.
2011, and an M.Sc.from the Johns Hopkins University in Dec. 2012, both in Electrical and
Computer Engineering. He interned at U.S. Army Research Laboratory in 2012 and Microsoft
Research in 2016, respectively. His research interest lies at the intersection of the foundation of
data science, machine learning, numerical optimization, and signal/image processing. His
research focuses on developing computational methods for learning low-complexity
models/structures from high dimensional data, leveraging tools from machine learning,
numerical optimization, and high dimensional probability/geometry. He is also interested in
applying these data-driven methods to various engineering problems in imaging sciences,
scientific discovery, and healthcare. He is the recipient of Best Student Paper Award at
SPARS’15 (with Ju Sun and John Wright), and the recipient of Microsoft Ph.D. Fellowship
2016-2018 in machine learning.
