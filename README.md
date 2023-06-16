# :dog: Personalized AI PET :cat:


## Our goal 💡
Enhanced Emotion Recognition

More Natural Interaction

Expanded Personalization
## Using model in project 
Model Selction Critieria 
Inference Speed :small_red_triangle: & Accuracy :small_red_triangle:
### Enhanced Emotion Recognition
<Real-time CNN for Emotion Classification>
git link : https://github.com/petercunha/Emotion
  
![image](https://github.com/gachon-graduation-project/AI_pet/assets/105128163/f2b3afc9-28d0-48da-a92c-d7a850d9089f)

![image](https://github.com/gachon-graduation-project/AI_pet/assets/105128163/11f57a6a-9a33-4be5-8690-99a52ca36d13)

## More Natural Interaction 
![image](https://github.com/gachon-graduation-project/AI_pet/assets/105128163/b6ffbf01-fdc8-4dfc-82e8-225c6db5d38f)

The two-way interaction will be structured to receive an input through image recognition through openCV and provide an output value for the input. The formalized Pet patterns the reactions, builds a database, and responds based on it.

## Personalized Reaction 
![image](https://github.com/gachon-graduation-project/AI_pet/assets/105128163/668f268d-edbc-4de1-99ce-a55b1e753573)

For personalization, we use reinforcement learning to calculate the weight that fits the owner and proceed with personalization. Create a database by patterning and change the response and pattern to suit the user. This is called unity ML agent. (unity ML agent is a tool for reinforcement learning.)
 Reinforcement learning is customized to the user. Through transfer learning, the weight of the pre-trained model is gradually changed in the real world to personalize it, which greatly reduces the actual learning time, so you can expect fast responses and fast reward algorithm updates.

#### Reward Recognition for reinforcement Learning
GitHub -[ nicknochnack/RealTimeObjectDetection](https://github.com/nicknochnack/RealTimeObjectDetection)

Hand gestures will be recognized independently of facial expression recognition to process the reward algorithm for reinforcement learning.

## Overall Structure 
![image](https://github.com/gachon-graduation-project/AI_pet/assets/105128163/06cddc38-53c4-4e04-8fcc-240ebf91fba0)

The overall structure is that it receives data from the device, goes through two recognition models and one reinforcement model, and then commands the device to take an action.

![image](https://github.com/gachon-graduation-project/AI_pet/assets/105128163/aec47eac-fc1d-4534-a508-8157e2d2efea)

The server receives emotions from facial expression recognition and rewards from hand gesture recognition from the device, providing a total of seven emotions and two rewards, + and -. The server receives behavioral backers from Unity, which it converts into Raspberry electrical signals and sends to the device.
The reinforcement learning model uses the rewards to update the weights and the emotions to give the behavioral backers. During this process, the reward is also given by the owner, so it goes from facial expression -> behavior -> hand gesture reward -> update.

![image](https://github.com/gachon-graduation-project/AI_pet/assets/105128163/3f84ac93-4a99-4db8-8ed8-0d236a33aa33)

Rather than starting a model with a cold start, we're going to use a model that we've pre-trained.
So we pre-train and build an initial model. Then we build the underlying model and deploy it.

## Member :runner:
|학번|이름|
|------|---|
|202033312|Kim Yeji|
|202135744|Kim Uijin|
|202135771|Park Jonghyun|
|202135826|Jang Heejin|
|202139848|Kang Minjae|
