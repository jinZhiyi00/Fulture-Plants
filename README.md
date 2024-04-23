# Plant Symphony
AR-Plant Symphony 
万物有灵，人类与植物共生共存互相影响。长久以来我们身边，似乎都是人类对植物进行美学的选择与规训，设想当人类去中心化后，植物是否有反征服的欲望，在驱动自身器官功能迭代进化的同时，蔓延突破局限对人类进行美学改造？彼时你是否幻想可与植物进行交流？未来的无机植物生长自过去的媒介，让我们通过ar与它们进行对谈，与它们奏响共同的乐章。该项目让参与者以一种新时代人类的视角进行体验，在具备趣味性的同时思考人与自然之间的关系。

Everything has a spirit, and human beings and plants coexist and affect each other. For a long time, it seems that all human beings have chosen and disciplined the aesthetics of plants. Imagine that when human beings are decentralized, do plants have the desire to counter-conquest? While driving the iterative evolution of their own organ functions, they will spread and break through the limitations to carry out the aesthetic transformation of human beings? Did you fantasize about communicating with plants at that time? Future inorganic plants grow from the media of the past. Let's talk to them through ar and play a common movement with them. This project allows participants to experience from the perspective of a new era of human beings and think about the relationship between man and nature while having fun.


















主要功能
AR体验：1.通过后置摄像头可以在手机屏幕上选择植物，点击并摆放所选择的植物。你可以打造属于自己的植物花园。选择点击植物，将会出现独属于这一个植物的声音。你可以戴上耳机，穿梭于你所种植的未来植物之间，在手机屏幕上触碰它们，倾听它们不同的种类和空间方位的声音所奏响的乐章。2.通过前置摄像头，佩戴虚拟面饰，模拟想象中不同种类植物对人类的美学改造。

AR experience: 1. Through the rear camera, you can select the plants on the mobile phone screen, click and place the selected plants. You can build your own plant garden. Select and click on the plant, and the sound of this plant will appear. You can put on headphones, shuttle between the future plants you plant, touch them on the mobile phone screen, and listen to the movements played by their different types and spatial directions. 2. Through the front camera and wearing a virtual face, it simulates the aesthetic transformation of different kinds of plants in the imagination of human beings.

<img width="583" alt="1713877900639" src="https://github.com/jinZhiyi00/Fulture-Plants/assets/163079470/d106c93c-7882-4ae3-a251-781ec9ae43ce">
















技术线
建模与贴图：Blender   游戏引擎：Unity(URP管线）像塑  增强现实框架：ARKit
Modeling and mapping: Blender Game Engine: Unity (URP Pipeline) Image Plastic Augmented Reality Framework: ARKit














功能亮点
快速平面检测 场景环境映射 面部识别 音频播放
Fast plane detection, scene environment mapping, facial recognition

















它是如何工作的
添加ARKit 插件 ，设置 AR Session 和 Target，实现平面识别
给平面创建 Prefab，添加 Collider
跟踪手势识别，实现单击，拖动，双击，长按
给模型创建材质，调整 Scale，添加 Collider，创建 Prefab
![微信图片_20240423213203](https://github.com/jinZhiyi00/Fulture-Plants/assets/163079470/93f4648a-1d7b-42b1-b504-c2ee237dfa0f)
创建空物体，添加Button，添加 AudioSource，编写代码，
![357b8048a7f2561dd182fa82a0e2116](https://github.com/jinZhiyi00/Fulture-Plants/assets/163079470/262e973e-fd4d-46c7-a17f-c236bfe7a6de)


新建脚本ButtonListrner
![d9f7f75b1fc3098198e4175e7cd4c15](https://github.com/jinZhiyi00/Fulture-Plants/assets/163079470/d0d2b201-7932-4a7b-8112-a0e6ac055abc)

将脚本挂在Button上
![6d930284069a7082a8e5e6b1318d18b](https://github.com/jinZhiyi00/Fulture-Plants/assets/163079470/36afb494-7a4f-4a08-a056-53161302d349)


根据交互切换 AudioClip 作为音源

Add ARKit plug-in, set AR Session and Target, and achieve plane recognition
Create Prefab for the plane and add Collider
Track gesture recognition to achieve click, drag, double-click, long press
Create materials for the model, adjust Scale, add Collider, and create Prefab
Create empty objects, add AudioSource, write code, and switch AudioClip as the sound source according to the interaction.















UI
添加下滑栏，设置单个项目对应的模型
添加 Reset，一键清空场景
Add a slide bar and set the model corresponding to a single project.
Add Reset and clear the scene with one click.

















交互设置
识别平面，在下滑栏中选择需要放置的物体
单击平面，模型出现在被点击位置
拖动模型实现移动，长按模型固定模型位置，再长按模型可解除固定
双击模型播放声音
点击 Reset 清空当前场景
Identify the plane and select the object to be placed in the slide bar.
Click the plane, and the model appears in the clicked position.
Drag the model to move, long press the model to fix the position of the model, and then long press the model to remove the fixation.
Double-click the model to play the sound
Click Reset to clear the current scene.




识别人脸，选择特效。张嘴触发特效，挥手关闭特效
Recognize faces and select special effects. Open your mouth to trigger the effect, wave your hand to turn it off.
















使用示例




<img width="989" alt="1713879305393" src="https://github.com/jinZhiyi00/Fulture-Plants/assets/163079470/9095ef71-6699-46af-a5d2-beafe535f2de">

![Uploading 1713879305393.png…]()

















出发点
我想构想的是人类去中心化后植物的未来形态。
这种形态可以是对人类审美中植物美学的反叛，可能人类偏爱饱满的花朵，它偏偏长了小花朵和大叶子。也可以是为了抵抗污染和破坏的形态进化。
另一方面想做一个衍生的小项目，在前置摄像头想通过ar做出或许符合未来植物审美的人的样貌。思考未来植物反过来可能会对于人类的美学改造。
这样，表现自然与人出现的荒诞失衡的关系。

What I want to imagine is the future form of plants after human decentralization.

This form can be a rebellion against plant aesthetics in human aesthetics. Maybe human beings prefer full flowers, which grow small flowers and large leaves. It can also be used to resist the evolution of pollution and destruction.

On the other hand, if there is time, this is a derivative small project. The front camera wants to make the appearance of a person who may be in line with the aesthetics of plants in the future through ar. I will think about the future that plants may in turn transform the aesthetics of human beings, so as to show the absurd imbalance between nature and human beings.

![a2e2c7ef02384111ea6c6797662f8a8](https://github.com/jinZhiyi00/Fulture-Plants/assets/163079470/a6dc4c92-4ab8-4bd0-8536-44e0303bdf6e)
















项目未来发展
1植物建模的多元化趣味化，希望发展成一个未来植物库，为搭建植物沙盘带来更多选择。同时丰富同一种植物的不同形态，使其有着如同现实植物般的生长过程。
2拓展曲库，增加植物的音效类型用来丰富植物乐器的种类
3植物动画设计，点击植物触发它的动画，为项目更加趣味性与可玩性
4丰富UI设计，使得界面更加个性化
5 AR虚拟面饰增加动画与手势互动效果

1 The diversification and interest of plant modeling hopes to develop into a future plant library, bringing more choices for building plant sand tables. At the same time, it enriches the different forms of the same plant, so that it has a growth process like a real plant.

2 Expand the music library and increase the sound effects of plants to enrich the variety of plant musical instruments.

3 Plant animation design, click on the plant to trigger its animation, making the project more interesting and playable

4 Rich UI design makes the interface more personalized

5 AR virtual face decoration adds animation and gesture interaction effect















 
