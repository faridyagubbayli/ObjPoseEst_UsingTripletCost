# ObjPoseEst_UsingTripletCost
Object Pose Estimation using CNN and Triplet Cost in Tensorflow | TUM Tracking &amp; Detection Course | Project 3

Project aims to recognize object pose from given images. It was implemented using TensorFlow and uses triplet cost (Anchor-Puller-Pusher) in order to measure performance while training. You can find result in the following files:
 
* Accuracy history -> History of model accuracy on validation data during training phase 
* Loss history -> History of loss on train and validation data during training phase 
* Confusion_Matrix -> Confusion matrix of the final model

After 1500 iterations model reaches 95% accuracy. Here, final model was trained by 3K iterations and reached 97.4% accuracy on test data. ADAM optimizer was used for optimization.

Dataset is a subset of LineMOD dataset.

