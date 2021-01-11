# BassBoost
Chord Estimation with Inversions in Beatles Songs

Elena Georgieva (etg259@nyu.edu), Michal Goldstein (mng320@nyu.edu), and Juan Sierra(jds833@nyu.edu)

A final project for MPATE-GE 2623 Music Information Retrieval at New York University. 

Abstract:
Previous approaches for automatic chord recognition focus on major and minor thirds, overlooking other significant features of the chords including chord inversions. A chord is inverted when a note other than the root appears in the bass, and inverted chords can alter a chord's perceptual function in a song. In this paper, we added bass information to major/minor chord estimates generated by an existing machine-learning-based method. We accomplished this by estimating the bass track using the CREPE pitch tracker and adding the resulting bass line to the chord information. In order to evaluate our method, we sampled 10 songs from the Beatles dataset and compared the estimated chord labels including bass information to the reference annotation.

<img src="https://ccrma.stanford.edu/~egeorgie/images/paulbass.jpg" width="320" height="214" />
