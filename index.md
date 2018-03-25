## Project Index Page

> ## **Sorry** 
> Sorry about the redirection. The failure of the Mix server has made all my projects on my website disappear. So for you guys can keep track of what I've done, I made this temporary content sheet on GitHub page. Hope you don't miss anything if you're interested in my stuff.

<br />

------

<br />
> ## Simple Prototype of Platform Game with SDL2 | C++

<br />

![popeye-platformer](/images/platformer.png)

<br />
Currently it's just a prototype about how to make a prototype of 2D platform game using SDL in C++. Tile maps are created via self-made tile editor developed with Qt library. And a sprite previewer is implemented for the game character design. All the works can be found on my Github. The design of the component systems are pretty satisying:) I believe it can be re-used for further platformer developemnt.

Further improvement on UI and art design is definitely needed. If you have any idea, do contact me.
- [Github Link](https://github.com/Wycode-fish/Popeye-Platform-Game-SDL2) 
- [Youtube Link](https://www.youtube.com/watch?v=-vvl9IDg0vU)


<br />

------

<br />


> ## Web Multi-Player Othello Game | Phoenix/ReactJS

<br />

![othello](/images/othello.png)

<br />
A web application based on Phoenix and ReactJS. Multiple game rooms is allowed via Elixir Agent implementation on server side. Audience are allowed for each game room without interfering game players.
ReactJS-based front end transmit data via channel broadcast. 
Solo play mode is enabled by implementation of MiniMax algorithm as Game AI.
- [Github Link](https://github.com/Wycode-fish/Multi-Player-Othello-Game) 
- [Game URL](http://othello.luqi.eason.space/)



<br />

------

<br />



> ## Web Task Tracker with Time-Block Management | Phoenix/Elixir

<br />

![task-tracker](/images/task-tracker.png)

<br />
A web application based on Phoenix and PostgreSQL database, where USERs and TASKs resources are both managed. Interaction with PostgreSQL is achieved by implementation of Ecto. Users are able to record and edit each time period they've spent on the current projects.
Front end is supported by Bootstrap and the data transfer between front end component and server is done by AJAX.
- [Github Link](https://github.com/Wycode-fish/WEBDEV-TASK-TRACKER-2) 
- [URL](http://tasks2.eason.space/)


<br />

------

<br />



> ## Sprite Previewer | p5.js

<br />

![sprite-previewer](/images/sprite-previewer.png)

<br />
I have been interested in p5.js for quite a long time. So I decided to give it a shot after I realized we need a sprite editor for our platform game development. I gotta say it almost feels like cheating when I use p5.js finished my graphic design task with a snap while others were still struggling in tons of code.:) It's so powerful.

Basically this is just a previewer which allows you select out the frames you wanted from a large sprite and see the effect of the animation or download them. FPS control, background color change and frame size adjustment are implemented for better preview effect. 
Besides p5.js, I also used JQuery and bootstrap.
- [Github Link](https://github.com/Wycode-fish/Sprite-Previewer) 
- [URL](http://sprite.eason.space/)



<br />

------

<br />


> ## Rammission | Unity 3D

<br />

![rammission](/images/rammission.png)

<br />
It is probably the reason why i decide to take on a career of game development. This global game jam changes my view about game development and really motivate me to becaome a better programmer. Working along side with guys like Billy, Luke and Anna is both enjoyable and stressing. 

I still think we got the best game on my site for this GGJ.:)
- [Github Link](https://github.com/heyx3/Rammission) 
- [GGJ URL](https://globalgamejam.org/2018/games/rammission) 
- [Youtube Trailer](https://www.youtube.com/watch?v=eNMZHBhoarg&feature=youtu.be)



<br />

------

<br />



> ## Real-time Object Recognition on Android | OpenCV/Android

<br />

![real-time-recognition-app](/images/android2.png)

<br />
I was assigned to this task which basically asked me to implement a multiple-object recognition system on mobile end. Since I was not familiar with CNN back then, after I looked up some genral applications, I decide to use OpenCV as the framework(it comes along with OpenCV4Android library, I didn't know about Tensorflow back then. Oops!). It turned out to be a painful process for the classifier training which I'll elaborate later. 

Basically, the final application is able to perform 10-class object recognition with an acceptable average precision(hit rate) at 0.86. The false alarm rate is 0.05.

I also implemented JNI in order to improve the performance rate of the Android app which enables me to directly invoke C library in Android.
- [Github Link](https://github.com/Wycode-fish/Real-time-Object-Recognition-on-Android)


<br />

------

<br />



> ## OpenCV Classifier Training | OpenCV/C++

<br />

![OpenCV-classifier-training](/images/opencv.png)

<br />
As I mentioned above, the training process of OpenCV classifier was crucifying. Originally, OpenCV provided its training method focused on haar features extraction, which was what I used initially. Well, all I can say is that the training speed of this haar training method with adaboost algorithm is  extremely frustrating. Later on, I adopted cascade training instead, which is a relatively new method released by OpenCV to replace the original haar training. Indeed, it was faster. But the problem is that it doesn't come along with a proper performance evaluation method as opencv_haartraining does with opencv_performance. So users have to write their own testing script. And still, to improve the precision of the classifiers, some scripts for pre-processing needs to be written.

You can find my performance evaluation script (python) and pre-processing script and tools (shell) in my repository.
- [Github Link](https://github.com/Wycode-fish/OpenCV-Classifier-Training)



<br />

------

<br />


> ## Face++ Web App | Servlet

<br />

![face++](/images/face++.png)

<br />
This is a servlet project which performs facial features extraction via data communication with Face++ server, which renders cutting-edge facial recognition service in China. Basically, I was using socket communication with the Web API key provided by Tsinghua University official, to utilize the feature point landmarking functionality from Face++. The result returned in JSON form will then be parsed for further use and display.

- [Github Link](https://github.com/Wycode-fish/Face-WebApp)



<br />

------

<br />

