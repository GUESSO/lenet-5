# Lenet-5
This is  lenet-5 network implemented without any Machine Learning framework by myself according to the thesis http://219.238.82.130/cache/5/03/yann.lecun.com/b1a1c4acb57f1b447bfe36e103910875/lecun-01a.pdf, however I made some changes including: 
1. Use activation function ReLU instead of tanh; 
2. Every kernel in C3 layer in the paper is designed separately to convolute different feature maps, which is in order to get rid of symmetry of the layer and to save computational capacity due to the speed of computers in 1998;
3. A convolutional layer is conventionally set with a bias parameter, but according to some paper and blog, bias doesn't matter with the final result, so I remove the parameter bias.
