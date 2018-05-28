## Project Abstract
The vast majority of indoor navigation algorithms either rely on manual scene augmentation and labelling or exploit multi-sensor fusion techniques in achieving simultaneous localisation and mapping (SLAM), leading to high computational costs, hardware complexities and robustness deficiencies. This paper proposes an efficient and robust indoor navigation framework for robots which relies solely on visual input from a single RGB camera. Firstly, we put forward an end-to-end trainable siamese deep convolutional neural network (DCNN) which decomposes navigation into orientation and localisation in one branch, while achieving semantic scene mapping in another. In mitigating the computational costs associated with DCNNs, the proposed model design shares a significant amount of convolutional operations between the two branches, streamlining the model and optimising for efficiency in terms of memory and inference latency. Secondly, in addressing the insufficiency of datasets for indoor navigation, a transfer learning regime is explored in demonstrating how such siamese DCNNs can be efficiently pretrained for high convergence rates without extensive manual dataset labelling. The resulting siamese framework efficiently combines semantic scene understanding with orientation estimation towards predicting collision-free and optimal navigation paths. Experimental results demonstrate that the proposed framework is accurate, efficient and outperforms existing "navigation-by-classification" variants.

## Model
Coming soon.

## Dataset
The full dataset and accompnaying labels will be made available [here](https://drive.google.com/open?id=70BU) soon.The dataset is conventionally labelled for classficaiton and semantic segmenation tasks.

## Code Implementation
The source codes related to the project will be uploaded [here](https://github.com/yyeboah/AutoNav) soon. Implementation is achieved using the Keras high level API with TensorFlow as a backend. A list of required dependences will be maintained on this page.

### Sponsors
Coming soon.

### Citation
Coming soon.
