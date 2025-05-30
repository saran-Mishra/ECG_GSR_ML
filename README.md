# ECG_GSR_ML

Individuals who have social anxiety may face many obstacles in their everyday life and interactions.
Social anxiety is defined as the fear of being judged and scrutinized by others that is beyond the
normal expectation in a specific social situation. It is important we know what kinds of features can
predict the changes in an anxiety episode.
First we need to detect the physical and physiological patterns of a subject. Then we must determine
what measured fluctuations and tendencies are of interest. Using a machine learning algorithms, we
will differentiate between different episodes of social anxiety. A suitable algorithm is required to
improve the accuracy. 

With six study participants (4 undergraduate students and 2 graduate students), we used the Shimmer
ECG and GSR sensors to collect physiological and physical data with their context (solo video
watching, dyad normal talk with/without evaluation), with 4 periods (baseline, anticipatory, experience
and post-events) and then extract data streams related to accelerometer signals, gyroscope signals and
skin conductance signals.
By using a sliding window algorithm, we extracted the most important features as input data, with
34 features from all these signals. Also the Social Interaction Anxiety Scale (SIAS) scores were
collected by the HOBBY pilot surveys.

Models explored: Linear Regression (LR), Support Vector Machine, LEast Absolute Shrinkage and Seleection Operator (LASSO),
Multi-Layered Perceptron (MLP), K-Nearest Neighbor Regression, Gaussian Naive-Bayes (NB) and Random Forest.
