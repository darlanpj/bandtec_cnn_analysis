# bandtec_cnn_analysis
Some analyzes of CNN (Convolutional Neural Networks) using PlaidML, Keras and Tensorflow. Final project for completion of postgraduate course.

Within the list of available networks it is possible to execute the Plaidbench with the command below

`$plaidbench keras [network]`


List of available networks
*choose from densenet121, densenet169, densenet201, inception_resnet_v2, inception_v3, mobilenet, nasnet_large, nasnet_mobile, resnet50, vgg16, vgg19, xception, imdb_lstm)

Example output:

 Running 1024 examples with inception_v3, batch size 16
 Example finished, elapsed: 24.196819067001343 (compile), 344.5688681602478 (execution), 0.336493035312742 (execution per example)
Correctness: untested. Could not find golden data to compare against.

Running passing batch size as parameter:

`$plaidbench --batch-size 16 keras xception`
