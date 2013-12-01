These are solutions to the exercises up at the [Stanford OpenClassroom Deep Learning class](http://openclassroom.stanford.edu/MainFolder/CoursePage.php?course=DeepLearning) and [Andrew Ng's UFLDL Tutorial](http://ufldl.stanford.edu/wiki/index.php/UFLDL_Tutorial). When I was solving these, I looked around for copies of the solutions so I could compare notes because debugging learning algorithms is often tedious in a way that isn't educational, but almost everything I found was incomplete or obviously wrong. I don't promise that these don't have bugs, but they at least give outputs within the range of the expected outputs for the assignments.

Apologies for the mess. I'll clean this up when I have some spare time. Pull requests welcome, of course.

I've attempted to make this Octave compatible, so that you can run this with free software. I've done this through the self-taught learning exercise, and it seems to work, but the results are slightly different. One side effect of this is that I'm using [fminlbfgs instead of minFunc](http://ufldl.stanford.edu/wiki/index.php/Fminlbfgs_Details)

Here's the order of the exercises:
#### [Stanford OpenClassroom Deep Learning class](http://openclassroom.stanford.edu/MainFolder/CoursePage.php?course=DeepLearning)
1. `linear.m`
2. `multiple.m`
3. `logistic.m`

#### [Unsupervised Feature Learning and Deep Learning Tutorial](http://ufldl.stanford.edu/wiki/index.php/UFLDL_Tutorial)
1. Sparse Autoencoder: `sparseae_exercise/train.m`
2. Vectorized Implementation: sparseae_exercise/train.m (`1` is already vectorized)

3.1. PCA in 2d: `pca_2d/pca_2d.m`
3.2. PCA: `pca_gen/pca_gen.m`
4. Softmax Regression: `softmax_exercise/softmaxExercise.m`
5. Self-Taught Learning: `stl_exercise/stlExercise.m`
6. Building Deep Networks for Classification: `stackedae_exercise/stackedAEExercise.m`

