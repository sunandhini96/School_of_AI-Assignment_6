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


Second Network:


Total params: 151,504
Trainable params: 151,504
Non-trainable params: 0


EPOCH: 0
100%|██████████| 2500/2500 [00:26<00:00, 95.74it/s] 

Train set: Average loss: 0.0729, Accuracy: 23660/50000 (47.32%)


Test set: Average loss: 0.0603, Accuracy: 5662/10000 (56.62%)

EPOCH: 1
100%|██████████| 2500/2500 [00:26<00:00, 96.13it/s] 

Train set: Average loss: 0.0651, Accuracy: 26736/50000 (53.47%)


Test set: Average loss: 0.0530, Accuracy: 6207/10000 (62.07%)

EPOCH: 2
100%|██████████| 2500/2500 [00:25<00:00, 97.09it/s]

Train set: Average loss: 0.0599, Accuracy: 28653/50000 (57.31%)


Test set: Average loss: 0.0486, Accuracy: 6559/10000 (65.59%)

EPOCH: 3
100%|██████████| 2500/2500 [00:26<00:00, 96.08it/s] 

Train set: Average loss: 0.0560, Accuracy: 30162/50000 (60.32%)


Test set: Average loss: 0.0457, Accuracy: 6791/10000 (67.91%)

EPOCH: 4
100%|██████████| 2500/2500 [00:25<00:00, 96.27it/s]

Train set: Average loss: 0.0530, Accuracy: 31265/50000 (62.53%)


Test set: Average loss: 0.0422, Accuracy: 7062/10000 (70.62%)

EPOCH: 5
100%|██████████| 2500/2500 [00:26<00:00, 95.87it/s]

Train set: Average loss: 0.0505, Accuracy: 32211/50000 (64.42%)


Test set: Average loss: 0.0403, Accuracy: 7200/10000 (72.00%)

EPOCH: 6
100%|██████████| 2500/2500 [00:25<00:00, 96.25it/s]

Train set: Average loss: 0.0459, Accuracy: 33929/50000 (67.86%)


Test set: Average loss: 0.0367, Accuracy: 7444/10000 (74.44%)

EPOCH: 7
100%|██████████| 2500/2500 [00:25<00:00, 96.95it/s]

Train set: Average loss: 0.0450, Accuracy: 34328/50000 (68.66%)


Test set: Average loss: 0.0365, Accuracy: 7447/10000 (74.47%)

EPOCH: 8
100%|██████████| 2500/2500 [00:25<00:00, 96.93it/s]

Train set: Average loss: 0.0445, Accuracy: 34496/50000 (68.99%)


Test set: Average loss: 0.0370, Accuracy: 7386/10000 (73.86%)

EPOCH: 9
100%|██████████| 2500/2500 [00:25<00:00, 98.63it/s] 

Train set: Average loss: 0.0440, Accuracy: 34602/50000 (69.20%)


Test set: Average loss: 0.0361, Accuracy: 7448/10000 (74.48%)

EPOCH: 10
100%|██████████| 2500/2500 [00:25<00:00, 98.31it/s] 

Train set: Average loss: 0.0438, Accuracy: 34684/50000 (69.37%)


Test set: Average loss: 0.0354, Accuracy: 7535/10000 (75.35%)

EPOCH: 11
100%|██████████| 2500/2500 [00:25<00:00, 97.57it/s]

Train set: Average loss: 0.0433, Accuracy: 34820/50000 (69.64%)


Test set: Average loss: 0.0357, Accuracy: 7515/10000 (75.15%)

EPOCH: 12
100%|██████████| 2500/2500 [00:25<00:00, 98.59it/s] 

Train set: Average loss: 0.0426, Accuracy: 35089/50000 (70.18%)


Test set: Average loss: 0.0355, Accuracy: 7524/10000 (75.24%)

EPOCH: 13
100%|██████████| 2500/2500 [00:25<00:00, 97.78it/s] 

Train set: Average loss: 0.0427, Accuracy: 34977/50000 (69.95%)


Test set: Average loss: 0.0352, Accuracy: 7551/10000 (75.51%)

EPOCH: 14
100%|██████████| 2500/2500 [00:25<00:00, 96.52it/s]

Train set: Average loss: 0.0425, Accuracy: 35219/50000 (70.44%)


Test set: Average loss: 0.0356, Accuracy: 7532/10000 (75.32%)

EPOCH: 15
100%|██████████| 2500/2500 [00:25<00:00, 98.74it/s] 

Train set: Average loss: 0.0428, Accuracy: 35026/50000 (70.05%)


Test set: Average loss: 0.0354, Accuracy: 7524/10000 (75.24%)

EPOCH: 16
100%|██████████| 2500/2500 [00:25<00:00, 97.34it/s] 

Train set: Average loss: 0.0426, Accuracy: 35053/50000 (70.11%)


Test set: Average loss: 0.0349, Accuracy: 7546/10000 (75.46%)

EPOCH: 17
100%|██████████| 2500/2500 [00:25<00:00, 96.93it/s]

Train set: Average loss: 0.0426, Accuracy: 35107/50000 (70.21%)


Test set: Average loss: 0.0358, Accuracy: 7489/10000 (74.89%)

EPOCH: 18
100%|██████████| 2500/2500 [00:25<00:00, 97.60it/s] 

Train set: Average loss: 0.0427, Accuracy: 35090/50000 (70.18%)


Test set: Average loss: 0.0353, Accuracy: 7543/10000 (75.43%)

EPOCH: 19
100%|██████████| 2500/2500 [00:25<00:00, 98.67it/s] 

Train set: Average loss: 0.0424, Accuracy: 35090/50000 (70.18%)


Test set: Average loss: 0.0358, Accuracy: 7495/10000 (74.95%)

EPOCH: 20
100%|██████████| 2500/2500 [00:25<00:00, 97.86it/s] 

Train set: Average loss: 0.0424, Accuracy: 35145/50000 (70.29%)


Test set: Average loss: 0.0351, Accuracy: 7544/10000 (75.44%)

EPOCH: 21
100%|██████████| 2500/2500 [00:25<00:00, 99.56it/s]

Train set: Average loss: 0.0425, Accuracy: 35257/50000 (70.51%)


Test set: Average loss: 0.0355, Accuracy: 7513/10000 (75.13%)

EPOCH: 22
100%|██████████| 2500/2500 [00:25<00:00, 97.94it/s] 

Train set: Average loss: 0.0427, Accuracy: 35078/50000 (70.16%)


Test set: Average loss: 0.0347, Accuracy: 7568/10000 (75.68%)

EPOCH: 23
100%|██████████| 2500/2500 [00:25<00:00, 98.21it/s] 

Train set: Average loss: 0.0424, Accuracy: 35186/50000 (70.37%)


Test set: Average loss: 0.0347, Accuracy: 7576/10000 (75.76%)

EPOCH: 24
100%|██████████| 2500/2500 [00:25<00:00, 98.82it/s]

Train set: Average loss: 0.0422, Accuracy: 35232/50000 (70.46%)


Test set: Average loss: 0.0355, Accuracy: 7515/10000 (75.15%)

EPOCH: 25
100%|██████████| 2500/2500 [00:25<00:00, 98.37it/s] 

Train set: Average loss: 0.0423, Accuracy: 35251/50000 (70.50%)


Test set: Average loss: 0.0354, Accuracy: 7519/10000 (75.19%)

EPOCH: 26
100%|██████████| 2500/2500 [00:25<00:00, 97.62it/s] 

Train set: Average loss: 0.0426, Accuracy: 35142/50000 (70.28%)


Test set: Average loss: 0.0350, Accuracy: 7562/10000 (75.62%)

EPOCH: 27
100%|██████████| 2500/2500 [00:25<00:00, 98.92it/s] 

Train set: Average loss: 0.0425, Accuracy: 35111/50000 (70.22%)


Test set: Average loss: 0.0350, Accuracy: 7541/10000 (75.41%)

EPOCH: 28
100%|██████████| 2500/2500 [00:25<00:00, 98.37it/s] 

Train set: Average loss: 0.0424, Accuracy: 35196/50000 (70.39%)


Test set: Average loss: 0.0348, Accuracy: 7557/10000 (75.57%)

EPOCH: 29
100%|██████████| 2500/2500 [00:25<00:00, 98.40it/s] 

Train set: Average loss: 0.0423, Accuracy: 35157/50000 (70.31%)


Test set: Average loss: 0.0351, Accuracy: 7542/10000 (75.42%)

EPOCH: 30
100%|██████████| 2500/2500 [00:25<00:00, 98.27it/s] 

Train set: Average loss: 0.0424, Accuracy: 35237/50000 (70.47%)


Test set: Average loss: 0.0351, Accuracy: 7522/10000 (75.22%)

EPOCH: 31
100%|██████████| 2500/2500 [00:25<00:00, 98.28it/s]

Train set: Average loss: 0.0425, Accuracy: 35219/50000 (70.44%)


Test set: Average loss: 0.0358, Accuracy: 7487/10000 (74.87%)

EPOCH: 32
100%|██████████| 2500/2500 [00:25<00:00, 97.51it/s] 

Train set: Average loss: 0.0425, Accuracy: 35159/50000 (70.32%)


Test set: Average loss: 0.0354, Accuracy: 7529/10000 (75.29%)

EPOCH: 33
100%|██████████| 2500/2500 [00:25<00:00, 97.93it/s] 

Train set: Average loss: 0.0424, Accuracy: 35201/50000 (70.40%)


Test set: Average loss: 0.0354, Accuracy: 7524/10000 (75.24%)

EPOCH: 34
100%|██████████| 2500/2500 [00:25<00:00, 98.32it/s]

Train set: Average loss: 0.0424, Accuracy: 35233/50000 (70.47%)


Test set: Average loss: 0.0357, Accuracy: 7495/10000 (74.95%)

EPOCH: 35
100%|██████████| 2500/2500 [00:25<00:00, 97.27it/s] 

Train set: Average loss: 0.0423, Accuracy: 35230/50000 (70.46%)


Test set: Average loss: 0.0353, Accuracy: 7551/10000 (75.51%)

EPOCH: 36
100%|██████████| 2500/2500 [00:25<00:00, 98.67it/s]

Train set: Average loss: 0.0423, Accuracy: 35139/50000 (70.28%)


Test set: Average loss: 0.0350, Accuracy: 7548/10000 (75.48%)

EPOCH: 37
100%|██████████| 2500/2500 [00:25<00:00, 97.03it/s]

Train set: Average loss: 0.0426, Accuracy: 35069/50000 (70.14%)


Test set: Average loss: 0.0353, Accuracy: 7525/10000 (75.25%)

EPOCH: 38
100%|██████████| 2500/2500 [00:25<00:00, 99.07it/s]

Train set: Average loss: 0.0425, Accuracy: 35148/50000 (70.30%)


Test set: Average loss: 0.0352, Accuracy: 7526/10000 (75.26%)

EPOCH: 39
100%|██████████| 2500/2500 [00:25<00:00, 98.82it/s]

Train set: Average loss: 0.0420, Accuracy: 35251/50000 (70.50%)


Test set: Average loss: 0.0353, Accuracy: 7513/10000 (75.13%)

EPOCH: 40
100%|██████████| 2500/2500 [00:25<00:00, 99.03it/s] 

Train set: Average loss: 0.0425, Accuracy: 35074/50000 (70.15%)


Test set: Average loss: 0.0355, Accuracy: 7514/10000 (75.14%)

EPOCH: 41
100%|██████████| 2500/2500 [00:25<00:00, 98.31it/s]

Train set: Average loss: 0.0425, Accuracy: 35084/50000 (70.17%)


Test set: Average loss: 0.0356, Accuracy: 7532/10000 (75.32%)

EPOCH: 42
100%|██████████| 2500/2500 [00:24<00:00, 100.16it/s]

Train set: Average loss: 0.0426, Accuracy: 35143/50000 (70.29%)


Test set: Average loss: 0.0350, Accuracy: 7531/10000 (75.31%)

EPOCH: 43
100%|██████████| 2500/2500 [00:25<00:00, 97.37it/s] 

Train set: Average loss: 0.0423, Accuracy: 35242/50000 (70.48%)


Test set: Average loss: 0.0356, Accuracy: 7503/10000 (75.03%)

EPOCH: 44
100%|██████████| 2500/2500 [00:26<00:00, 96.08it/s]

Train set: Average loss: 0.0424, Accuracy: 35307/50000 (70.61%)


Test set: Average loss: 0.0355, Accuracy: 7527/10000 (75.27%)

EPOCH: 45
100%|██████████| 2500/2500 [00:25<00:00, 96.18it/s] 

Train set: Average loss: 0.0424, Accuracy: 35245/50000 (70.49%)


Test set: Average loss: 0.0361, Accuracy: 7480/10000 (74.80%)

EPOCH: 46
100%|██████████| 2500/2500 [00:25<00:00, 99.08it/s] 

Train set: Average loss: 0.0423, Accuracy: 35161/50000 (70.32%)


Test set: Average loss: 0.0354, Accuracy: 7532/10000 (75.32%)

EPOCH: 47
100%|██████████| 2500/2500 [00:25<00:00, 97.72it/s]

Train set: Average loss: 0.0423, Accuracy: 35265/50000 (70.53%)


Test set: Average loss: 0.0351, Accuracy: 7525/10000 (75.25%)

EPOCH: 48
100%|██████████| 2500/2500 [00:25<00:00, 98.14it/s] 

Train set: Average loss: 0.0424, Accuracy: 35195/50000 (70.39%)


Test set: Average loss: 0.0354, Accuracy: 7516/10000 (75.16%)

EPOCH: 49
100%|██████████| 2500/2500 [00:25<00:00, 98.32it/s] 

Train set: Average loss: 0.0422, Accuracy: 35260/50000 (70.52%)


Test set: Average loss: 0.0348, Accuracy: 7559/10000 (75.59%)

EPOCH: 50
100%|██████████| 2500/2500 [00:25<00:00, 98.91it/s] 

Train set: Average loss: 0.0425, Accuracy: 35038/50000 (70.08%)


Test set: Average loss: 0.0349, Accuracy: 7559/10000 (75.59%)

EPOCH: 51
100%|██████████| 2500/2500 [00:25<00:00, 97.36it/s]

Train set: Average loss: 0.0424, Accuracy: 35177/50000 (70.35%)


Test set: Average loss: 0.0350, Accuracy: 7555/10000 (75.55%)

EPOCH: 52
100%|██████████| 2500/2500 [00:25<00:00, 98.27it/s] 

Train set: Average loss: 0.0424, Accuracy: 35094/50000 (70.19%)


Test set: Average loss: 0.0348, Accuracy: 7569/10000 (75.69%)

EPOCH: 53
100%|██████████| 2500/2500 [00:25<00:00, 99.07it/s] 

Train set: Average loss: 0.0421, Accuracy: 35349/50000 (70.70%)


Test set: Average loss: 0.0358, Accuracy: 7505/10000 (75.05%)

EPOCH: 54
100%|██████████| 2500/2500 [00:25<00:00, 96.21it/s]

Train set: Average loss: 0.0424, Accuracy: 35159/50000 (70.32%)


Test set: Average loss: 0.0351, Accuracy: 7536/10000 (75.36%)

EPOCH: 55
100%|██████████| 2500/2500 [00:25<00:00, 99.42it/s]

Train set: Average loss: 0.0422, Accuracy: 35289/50000 (70.58%)


Test set: Average loss: 0.0352, Accuracy: 7531/10000 (75.31%)

EPOCH: 56
100%|██████████| 2500/2500 [00:25<00:00, 98.48it/s] 

Train set: Average loss: 0.0423, Accuracy: 35169/50000 (70.34%)


Test set: Average loss: 0.0352, Accuracy: 7536/10000 (75.36%)

EPOCH: 57
100%|██████████| 2500/2500 [00:25<00:00, 98.04it/s] 

Train set: Average loss: 0.0423, Accuracy: 35258/50000 (70.52%)


Test set: Average loss: 0.0352, Accuracy: 7517/10000 (75.17%)

EPOCH: 58
100%|██████████| 2500/2500 [00:26<00:00, 95.61it/s] 

Train set: Average loss: 0.0424, Accuracy: 35167/50000 (70.33%)


Test set: Average loss: 0.0349, Accuracy: 7555/10000 (75.55%)

EPOCH: 59
100%|██████████| 2500/2500 [00:26<00:00, 95.98it/s] 

Train set: Average loss: 0.0426, Accuracy: 35022/50000 (70.04%)


Test set: Average loss: 0.0348, Accuracy: 7559/10000 (75.59%)


![image](https://user-images.githubusercontent.com/63030539/219003857-d8f426c3-4e69-44ff-8ce7-4a46aec218e5.png)



