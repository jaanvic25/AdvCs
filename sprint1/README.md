<h1>Fourier Transforms and Applications</h1>
<h2>Team Members</h2>
<p>Jaanvi</p>
<h2>Summary</h2>
<p>I would like to study the topic of fourier transforms (breaking down an image or audio file into simpler components) allowing us to put blurring or smoothing filters, or compress images/audio files. I would like to understand the underlying math and how this topic is necessary for audio and image files and with this knowledge make a basic project such as a program that lets you input an audio file and what factor to compress it by, then shows you how much memory it will take, and how much of its original sound it would retain. Another project idea would be to let the user input an image and have the program break it down into its components then re-draw it with the vectors, depending on how much precision the user wants. Or I could try to apply a blurring or smoothing filter or something like that instead. These would be more tools to show the topic to others or for my understanding rather than for actual use.</p>
<h2>Resources, Are there outside databases or APIs that you think might be helpful?</h2>
<p>Python Libraries: numpy, scipy, matlab, matplotlib, pillow

https://www.youtube.com/watch?v=r6sGWTCMz2k&list=PLIbBLQw7h0JcjDEQU5n8nppgkBWY3vguB&index=5 - this is where I got the idea for the vector drawing
</p>

<h2>Tasks</h2>
<ul>
<li>Research the basic of fourier</li>
<li>Review cos and sin </li>
<li>Complex numbers</li>
<li>Frequency</li>
<li>Read article? About fourier transform</li>
<li>Time domain vs frequency domain</li>
<li>Learn about DFT and FFT</li>
<li>Try to understand mathematically</li>
<li>Learn about O(N) and why FFT reduces complexity significantly</li>
<li>understand/ write pseudo code for algos</li>
<li>Convolutions </li>
<li>Write a program to graph sin and cos waves</li>
<li>Then implement or write discrete fourier transform? </li>
<li>Compare to FFT</li>
<li>Image</li>
<li>Read image with pillow</li>
<li>Visualize it with matplotlib or a library</li>
<li>Try to experiment with filtering or compression <li>using and not using fourier</li>
<li>Look at complexity/time either way 
</li>
</ul>

<h1>SLAM Algorithm Project</h1>
<h2>Team Members</h2>
<p>Jaanvi</p>
<h2>Summary</h2>
<p>I would like to continue something I was working on 2 years ago that mapped out the room surrounding a mini car/ robot using sensors. It would be able to go in a circular room and then recreate that map of a circle to the user.</p>
<h2>Resources, Are there outside databases or APIs that you think might be helpful?</h2>
<p>Python
Libraries: numpy, scipy, matlab, matplotlib
I would need to use a lidar or some distance sensor and have a mini car of some sort – I could use a chassis from robotics for this. I would also need the electronics to run the mini car.

https://www.sciencedirect.com/science/article/abs/pii/S0921889009001900 – article that inspired 
</p>

<h2>Tasks</h2>
<ul>
<li>Look at different localization and mapping algorithms / methods</li>
<li>Look into clustering and different types of it – distance based, convolutional, etc</li>
<li>Either work on old implementation of it that I made and revisit the paper I based it off of or start new and try to write something for clustering (if I want to use that)
</li>
<li>If not clustering look into other ways of constructing the map around the car</li>
<li>Then look into how to create the lines from clusters</li>
<li>Different mathematical ways, Accuracy tradeoff</li>
<li>While doing that also build? Or find a chassis and set up to use</li>
<li>Test out the lidar or distance sensor </li>
<li>Run test programs to make sure its working as intended
</li>
<li>Test out clustering algorithm with lidar
</li>
<li>Debug
 </li>
<li>Test out the line extraction ones
</li>
<li>If workingish then plot a simple graph to be able to finetune and make the algorithms more accurate or efficient or change completely if graphs show they are not working </li>
<li>Find a way to visualize the map that the car is creating
</li>
</ul>
<h1>Identity Recognition System</h1>

<h3>Team Members:</h3>
Erim Keresteci, Jaanvi Chirimar (maybe)

<h3>Summary:</h3>
The aim of this project is to create software that can detect peoples’ voices and faces using machine learning. 
The audience for this project would be the people working on it, however the later stages of this project (possibly in another sprint) would be for other people who would test the program (malware). The motivation behind this project is to learn how to use machine learning with video and audio data and extract specific information from that data (i.e. a name). The long term goal with this project, stretching into other sprints, would be to create a malware that can collect data about a subject. 

<h3>Resources:</h3>
This project would use Python as the primary programming language. Libraries that would be useful include keras, TensorFlow, Pandas, NumPy, OpenCV, and an audio-processing library. There could very well be more libraries used, however for now this is what I can foresee. I can’t write a lot on the resources matter because this kind of project is very new to me, so I’m not sure what else I might need.  

Helpful articles:
https://www.datacamp.com/tutorial/face-detection-python-opencv
https://realpython.com/face-recognition-with-python/
https://www.geeksforgeeks.org/python-speech-recognition-module/
https://www.simplilearn.com/tutorials/python-tutorial/speech-recognition-in-python

There are no products I would like to purchase as of now. 

<h3>Tasks:</h3>
Research how facial recognition works
Work with OpenCV to create a video feed that receives input from webcam
Create a machine learning model that can detect a face on the video feed
Continue step 4
Continue step 4
Continue step 4
Modify the machine learning model to be able to detect facial expressions and features (i.e. smiling/frowning, eye color, etc)
Continue step 10
Continue step 10
Continue step 10
Continue step 10
Continue step 10
Modify the machine learning model to be able to detect and classify different faces as different people.
Continue step 13
Continue step 13
Continue step 13
Modify step 13 so that it can save these “profiles” to a datastore 
Continue step 17
Continue step 17
Continue step 17
Modify step 17 so that it can label faces it has detected in the past with the corresponding profiles upon re-detection
Continue step 21
Continue step 21
Research how speech recognition works
Work with an audio-processing library to be able to get a live audio feed from computer - possibly extracting it from the video feed even
Continue step 25
Continue step 25
Test to see if audio feed works
Create machine learning model to detect a specific persons voice
Continue step 29
Modify step 29 to be able to detect multiple voices at once and save them to profiles
Continue step 31
Continue step 31
Continue step 31
Modify step 21 so that the facial recognition model can detect when a person is speaking through mouth movements
Continue step 35
Combine step 31 and 35 so that voices and faces are matched to the same profiles
Continue step 37
Continue step 37
Test + bug fixes 

<h3>Additional Notes:</h3>
The follow-up project to this is a little unethical due to its potential uses so I am limiting myself to just the functionality portion and not doing anything malware related for now. 

