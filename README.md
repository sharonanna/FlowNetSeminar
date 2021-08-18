# FlowNetSeminar
A seminar report based on the paper 'FlowNet: Learning Optical Flow with Convolutional Networks'.

Convolutional neural networks (CNNs) are widely used in computer vision applications due to their successes in the field. 
Recent works, including this paper, have applied CNNs to predict optical flow. This supervised learning task is carried out by using two architectures: a generic one where the network learns to process the data by itself and one that includes a correlation layer to map corresponding feature vectors. They are trained using a generated synthetic Flying Chairs dataset since available ground-truth datasets are not large enough. These architectures show a competitive accuracy of 5 to 10 fps when compared with other well-performing methods and also sufficiently generalize to existing datasets such as Sintel and KITTI.
