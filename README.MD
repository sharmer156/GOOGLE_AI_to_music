# 用机器学习搞艺术，谷歌 Megenta 项目集锦 #（附 Github） 
原创 2018-04-21 雷锋字幕组 AI研习社 AI研习社 

雷锋网 AI 研习社按：本文为雷锋字幕组编译的技术博客，原文 Make Music and Art Using Machine Learning，作者 magenta。
翻译 | 汪星宇  王飞  魏洪贵    整理 |  凡江
##   概述 ##
Magenta 项目的一个主要目标是证明机器学习可以用来提高所有人的创造性潜能。
页面上的演示和应用均来自谷歌人（内部或是外部），他们打造有趣的玩具、富有创意的应用、研究笔记和专业工具，这将对许多人有所帮助。
  分类
•	Web 应用
https://magenta.tensorflow.org/demos#web-apps
•	Colab 笔记本
https://magenta.tensorflow.org/demos#colab-notebooks
•	本机应用
https://magenta.tensorflow.org/demos#native-apps
•	社区贡献
https://magenta.tensorflow.org/demos#community-contrib
  Web 应用
本部分包括基于浏览器的应用程序管理，许多是通过TensorFlow.js，对WebGL-accelerated的推理实现的。

![](https://i.imgur.com/mB6za5q.gif)



## 1. Beat Blender ##
•	demo
https://g.co/beatblender
•	blog
https://magenta.tensorflow.org/music-vae
•	code
https://github.com/googlecreativelab/beat-blender
Torin Blankensmith ( Github: torinmb，Twitter: tBlankensmith )
Kyle Phillips ( Github: hapticdata , Twitter: hapticdata )
 
这是谷歌Creative Lab基于MusicVAE用MusicVAE.js API实现的一个交互demo。你可以使用它来生成鼓点的二维调色板，并通过latent空间绘制路径以创建不断变化的节拍。四个角可以手动编辑，替换为预设，或从latent空间采样以重新生成调色板。

![](https://mmbiz.qpic.cn/mmbiz_gif/bicdMLzImlibRTF49VZ09raObibNgTTcAnBfTKViazhRWzsN5twpgJdotwp4ibdtG5hZgOVPb9iarUP6bYibUKqdwIxpg/640?wx_fmt=gif&tp=webp&wxfrom=5&wx_lazy=1)
## 2. Latent Loops ##
•	demo 
https://goo.gl/magenta/latent-loops
•	blog
https://magenta.tensorflow.org/music-vae
Catherine McCurry ( Github:  currycurry )
Zach Schwartz ( Github:  zischwartz )
Harold Cooper ( Github:  hrldcpr )
 
这是谷歌的Pie Shop基于MusicVAE用MusicVAE.js API实现的一个交互demo。Latent Loops可以让你在一个由不同音阶组成的方阵里挑选曲子并生成循环的曲子，再用这些生成一个更长的曲子。搞音乐的人可以用这个界面创建一个完整的曲子并轻松地将它挪到他们自己的数字音乐工作站中。


![](https://mmbiz.qpic.cn/mmbiz_gif/bicdMLzImlibRTF49VZ09raObibNgTTcAnBBBj1icJCa9Bh2SRs0hhu6AvqzfDiaAtIV3neAakiaYFI0gVOlcu37noibA/640?wx_fmt=gif&tp=webp&wxfrom=5&wx_lazy=1)
##  3. Melody Mixer ##
•	demo 
https://g.co/melodymixer
•	blog 
https://magenta.tensorflow.org/music-vae
•	code
https://github.com/googlecreativelab/melody-mixer
Torin Blankensmith ( Github:  torinmb , Twitter: tBlankensmith )
Kyle Phillips ( Github:  hapticdata , Twitter: hapticdata )
 
这个demo是由谷歌Creative Lab基于MusicVAE用MusicVAE.js API创建的。它能让你轻松生成两小段曲子之间的过渡音乐。
![](https://mmbiz.qpic.cn/mmbiz_gif/bicdMLzImlibRTF49VZ09raObibNgTTcAnBgF4A5iaRuYib1S3SCbcuSiaTzbUrqOrRCSTlRsuo2BKTX4MUm8JeL3ZeQ/640?wx_fmt=gif&tp=webp&wxfrom=5&wx_lazy=1)
## 4. PerformanceRNN ##
•	demo
https://goo.gl/magenta/performancernn-demo
•	blog 
https://magenta.tensorflow.org/performance-rnn-browser
•	code
https://goo.gl/magenta/performancernn-demo-code
Curtis Hawthorne ( Github: cghawthorne )
Nikhil Thorat ( Github: nsthorat , Twitter: nsthorat )
 
PerformanceRNN可以在浏览器里实时演奏钢琴，他是用TensorFlow.js开发的。
## 
![](https://mmbiz.qpic.cn/mmbiz_gif/bicdMLzImlibRTF49VZ09raObibNgTTcAnBBJIUoM8IY3vxiamUYgWBQicuosuaCbVjFeJLqO2btibVHnX26at5HIqcA/640?wx_fmt=gif&tp=webp&wxfrom=5&wx_lazy=1)
5. SketchRNN ##
•	demo
https://magenta.tensorflow.org/assets/sketch_rnn_demo/index.html
•	blog
https://magenta.tensorflow.org/sketch-rnn-demo
•	code
https://github.com/tensorflow/magenta-demos/blob/master/sketch-rnn-js
David Ha ( Github: hardmaru , Twitter:   hardmaru )
Jonas Jongejan ( Github:  HalfdanJ , Twitter: HalfdanJ )
Ian Johnson ( Github: enjalot , Twitter: enjalot )
 
这个demo可以让你和SketchRNN一起画画。

## 6. NSynth Sound Maker ##
•	demo
https://g.co/soundmaker
•	blog
https://magenta.tensorflow.org/nsynth-instrument
•	code
https://github.com/googlecreativelab/aiexperiments-sound-maker
Yotam Mann ( Github: tambien , Twitter: yotammann )
 
一个基于NSynth的交互AI的尝试，NSynth是与谷歌Creative Lab合作完成， 你可以选择两种乐器将他们合成一个新的音乐。

## 7. A.I. Duet ##
•	demo
https://g.co/aiduet
•	blog
https://magenta.tensorflow.org/2017/02/16/ai-duet
•	code
https://github.com/googlecreativelab/aiexperiments-ai-duet
Yotam Mann ( Github:  tambien , Twitter:  yotammann )
 
一个基于NSynth 的交互AI的例子，MelodyRNN是与谷歌Creative Lab合作完成的，它让你通过机器学习来作曲。通过很多MIDI的例子来训练一个神经网络让它学习音乐概念，创建一个关于音符和时序图。你演奏一些音符，看看它如何反应的吧。
  Colab 笔记本
Colaboratory是谷歌的一个用于普及机器学习教育和研究的研究项目。环境是Jupyter笔记本，完全运行在云端，不需要本地进行设置。
我们为Colab笔记本提供了一些模型，这些模型可以让你在托管的谷歌云实例上与它们进行免费交互。
## 8. E-Z NSynth ##
•	demo
https://g.co/magenta/nsynth-colab
Jesse Engel ( Github:  jesseengel , Twitter:  jesseengel )
 
这个Colab笔记本能够免费帮助你上传你自己的声音文件，然后使用NSynth模型对这些声音文件进行重建修改。
## 9. MusicVAE ##
•	demo
https://g.co/magenta/musicvae-colab
Adam Roberts ( Github: adarob , Twitter: ada_rob )
 
MusicVAE学习乐谱的潜在空间。 此Colab笔记本提供的功能可供您从先前的分配中随机抽样，并在几个预先训练的MusicVAE模型的现有序列之间进行插值。你还可以将结果与MusicVAE论文中描述的基准模型进行比较，这篇论文的题目是：用于学习音乐长期结构的分层潜在矢量模型。
## 10. Onsets and Frames ##
•	demo
https://colab.research.google.com/notebook#fileId=/v2/external/notebooks/magenta/onsets_frames_transcription/onsets_frames_transcription.ipynb
Curtis Hawthorne ( Github:  cghawthorne )
Onsets and Frames是一个自动钢琴音乐转录模型。 这款Colab笔记本演示了在用户提供的录音上模型的运行。
 
##  11Latent Constraints ##
•	demo
https://colab.research.google.com/notebooks/latent_constraints/latentconstraints.ipynb
Jesse Engel ( Github:  jesseengel , Twitter:  jesseengel )
有关潜在约束的运行实验代码：无条件生成模型的条件生成。

  本机应用
本机应用程序在本地机器上运行，通常需要您安装其他软件，但有时更适合专业人士使用。
## 12. NSynth MaxForLive Device ##
•	blog
https://magenta.tensorflow.org/nsynth-instrument
•	code
https://github.com/tensorflow/magenta-demos/tree/master/nsynth
Jesse Engel ( Gituhub:  jesseengel , Twitter:  jesseengel )
 
MaxForLive设备集成到Max MSP和Ableton Live中。 它可以让你通过直观的网格界面探索NSynth声音的空间。
## 13. A.I. Jam (NIPS 2016 Demo) ##
•	blog
https://magenta.tensorflow.org/2016/12/16/nips-demo
•	code
https://github.com/tensorflow/magenta-demos/tree/master/ai-jam-js
Adam Roberts ( Gituhub: adarob , Twitter:  ada_rob )
Jesse Engel ( Gituhub:  jesseengel , Twitter:  jesseengel )
互动式“A.I. Jam使用AI Duet的前端构建的“Jam Session”，结合Magenta MIDI界面，在浏览器中重现屡获殊荣的Magenta 2016 NIPS演示体验。
  社区贡献
社区贡献都是在没有谷歌参与的情况下创建的，使用的是Magenta模型和库。 如果你有一个你认为属于这里的演示，请通过我们的讨论组分享。
## 14. Latent Cycles ##
•	demo
https://codepen.io/teropa/full/rdoPbG/
•	blog
https://codepen.io/teropa/details/rdoPbG/
•	code
https://codepen.io/teropa/pen/rdoPbG
Tero Parviainen ( Gituhub: teropa , Twitter:  teropa )
 
使用ImprovRNN的Magenta MusicVAE模型种子生成旋律循环的潜在空间，然后相互演奏循环，探索潜在的谐波可能性。                                     
由TensorFlow.js和Magenta.js提供支持。
## 15. Neural Drum Machine ##
•	demo
https://codepen.io/teropa/full/RMGxOQ/
•	blog
https://codepen.io/teropa/details/RMGxOQ/
•	code
https://codepen.io/teropa/pen/RMGxOQ
Tero Parviainen ( Gituhub: teropa , Twitter: teropa )
 
由TensorFlow.js和Magenta的DrumsRNN和MusicVAE提供动力的实验电子鼓乐器。 要使用它，请在左侧定义种子模式，并使用“生成”按钮。 DrumsRNN梦想着延续你的种子模式。 “密度”滑块使用MusicVAE添加或删除图案中的点击。
## 16. Neural Arpeggiator ##
•	demo
https://codepen.io/teropa/full/ddqEwj/
•	blog
https://codepen.io/teropa/details/ddqEwj/
•	code
https://codepen.io/teropa/pen/ddqEwj
Tero Parviainen ( Gituhub: teropa , Twitter:  teropa )
 
保持一个音符或和弦，让深度神经网络在其周围播放琶音模式。
由TensorFlow.js和Magenta的ImprovRNN提供支持。
## 17. Neural Melody Autocompletion ##
•	demo
https://codepen.io/teropa/full/gvwwZL/
•	blog
https://codepen.io/teropa/details/gvwwZL/
•	code
https://codepen.io/teropa/pen/gvwwZL
Tero Parviainen ( Gituhub:  teropa ,Twitter:  teropa )
 
播放并保持旋律或和弦，让深层神经网络为您完成。
由TensorFlow.js和Magenta的ImprovRNN提供支持。
## 18. Deep Roll ##
•	demo
https://codepen.io/teropa/full/zpbLOj/
•	blog
https://codepen.io/teropa/details/zpbLOj/
•	code
https://codepen.io/teropa/pen/zpbLOj
Tero Parviainen ( Gituhub: teropa , Twitter:  teropa )
 
一个深度的神经网络，在你的浏览器中做出旋律。 
由TensorFlow.js和Magenta的ImprovRNN提供支持。
这些旋律是由ImprovRNN生成的，和弦产生条件是通过使用马尔可夫链生成的。
## 19. mSynth ##
•	demo
https://itunes.apple.com/us/app/msynth/id1269514201
•	blog
https://magenta.tensorflow.org/blog/2017/09/12/outside-hacks
•	code
https://github.com/lamtharnhantrakul/mSynth
Hanoi Hantrakul ( Gituhub: lamtharnhantrakul)

mSynth是一款在2017年Outside Hacks中获得第一名的应用程序，Outside Hacks是旧金山Outside Lands音乐节上举办的官方24小时音乐编程马拉松。该团队开发了一个艺术家观众交互式体验，节日观众可以通过倾斜手机实时共同控制Magenta的NSynth。
博客原址 https://magenta.tensorflow.org/demos
