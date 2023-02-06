# School_of_AI-Assignment_6
Image Classification:
CIFAR-10 dataset contains of 60,000 32×32 colour images, each containing one of ten object classes, with 6000 images per class. It consists of 50,000 32×32 color training images labelled across ten categories and 10,000 test images.


Output of summary:
Total params: 185,936
Trainable params: 185,936

----------------------------------------------------------------
Input size (MB): 0.01
Forward/backward pass size (MB): 3.45
Params size (MB): 0.71
Estimated Total Size (MB): 4.17

Here we used Atrous convolution and depthwise seperable convolution.
Atrous convolution helps in increasing the field of view. Same number of parameters used.
Depthwise seperable convolution helps in depthwise followed by point wise convolution. It reduces the number of parameters.

Trained the model for 15 epochs achieved testing accuracy around 70 %. 

Output logs as follows:

EPOCH: 0
Loss=2.5588433742523193 Batch_id=12499 Accuracy=35.47: 100%|██████████| 12500/12500 [03:05<00:00, 67.52it/s]

Test set: Average loss: 0.3594, Accuracy: 4921/10000 (49.21%)

EPOCH: 1
Loss=2.391526222229004 Batch_id=12499 Accuracy=44.72: 100%|██████████| 12500/12500 [03:01<00:00, 69.01it/s]

Test set: Average loss: 0.3278, Accuracy: 5391/10000 (53.91%)

EPOCH: 2
Loss=1.1631410121917725 Batch_id=12499 Accuracy=48.99: 100%|██████████| 12500/12500 [02:58<00:00, 69.98it/s]

Test set: Average loss: 0.3001, Accuracy: 5849/10000 (58.49%)

EPOCH: 3
Loss=1.6102139949798584 Batch_id=12499 Accuracy=52.01: 100%|██████████| 12500/12500 [02:58<00:00, 69.90it/s]

Test set: Average loss: 0.2842, Accuracy: 5954/10000 (59.54%)

EPOCH: 4
Loss=2.137784957885742 Batch_id=12499 Accuracy=54.89: 100%|██████████| 12500/12500 [02:59<00:00, 69.60it/s]

Test set: Average loss: 0.2759, Accuracy: 6189/10000 (61.89%)

EPOCH: 5
Loss=1.0353155136108398 Batch_id=12499 Accuracy=56.19: 100%|██████████| 12500/12500 [02:59<00:00, 69.81it/s]

Test set: Average loss: 0.2631, Accuracy: 6331/10000 (63.31%)

EPOCH: 6
Loss=2.2583305835723877 Batch_id=12499 Accuracy=60.55: 100%|██████████| 12500/12500 [02:58<00:00, 70.01it/s]

Test set: Average loss: 0.2383, Accuracy: 6662/10000 (66.62%)

EPOCH: 7
Loss=0.49761176109313965 Batch_id=12499 Accuracy=61.72: 100%|██████████| 12500/12500 [02:59<00:00, 69.49it/s]

Test set: Average loss: 0.2369, Accuracy: 6716/10000 (67.16%)

EPOCH: 8
Loss=2.487778663635254 Batch_id=12499 Accuracy=61.99: 100%|██████████| 12500/12500 [02:59<00:00, 69.54it/s]

Test set: Average loss: 0.2343, Accuracy: 6723/10000 (67.23%)

EPOCH: 9
Loss=0.8206443190574646 Batch_id=12499 Accuracy=62.15: 100%|██████████| 12500/12500 [03:05<00:00, 67.49it/s]

Test set: Average loss: 0.2295, Accuracy: 6800/10000 (68.00%)

EPOCH: 10
Loss=0.715792715549469 Batch_id=12499 Accuracy=62.65: 100%|██████████| 12500/12500 [03:02<00:00, 68.59it/s]

Test set: Average loss: 0.2314, Accuracy: 6802/10000 (68.02%)

EPOCH: 11
Loss=1.0757040977478027 Batch_id=12499 Accuracy=63.19: 100%|██████████| 12500/12500 [02:59<00:00, 69.75it/s]

Test set: Average loss: 0.2291, Accuracy: 6860/10000 (68.60%)

EPOCH: 12
Loss=0.744814395904541 Batch_id=12499 Accuracy=63.97: 100%|██████████| 12500/12500 [02:59<00:00, 69.55it/s]

Test set: Average loss: 0.2269, Accuracy: 6860/10000 (68.60%)

EPOCH: 13
Loss=0.35308030247688293 Batch_id=12499 Accuracy=63.91: 100%|██████████| 12500/12500 [02:58<00:00, 69.84it/s]

Test set: Average loss: 0.2287, Accuracy: 6852/10000 (68.52%)

EPOCH: 14
Loss=0.6351791620254517 Batch_id=12499 Accuracy=64.09: 100%|██████████| 12500/12500 [02:59<00:00, 69.46it/s]

Test set: Average loss: 0.2261, Accuracy: 6920/10000 (69.20%)
