# TracknetV3-tennis
TrackNet V3 fine tuned on a tennis dataset
Task 1- Technical summary of the paper

Task2 - Model Tracknet is finetuned on a dataset of labeled tennis match images. The script for fine tuning is attached and the weights of tracknet obtained from fine tuning are also attached.
The weights include the confusion matrix in the parameter dictionary.
Confusion Matrix is calculated by validation on a dataset of tennis balls using only Tracknet.

'TP': 933.0, 'TN': 0.0, 'FP1': 5.0, 'FP2': 0.0, 'FN': 46.0, 'accuracy': 0.948170731707317, 'precision': 0.9946695095948828, 'recall': 0.9530132788559755, 'f1': 0.9733959311424101, 'miss_rate': 0.04698672114402452}

Task3 - Inference.py and app.py are attached. On running app.py, a video input can be given to the model by uploading the video to swagger docs,
The output json consisting of predictions can be viewed and downloaded from swagger docs.
Inference.py also outputs a csv to the local machine.

The original repository can be cloned and these files can be attached with them to run.
