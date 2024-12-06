# Gender-and-Age-Detection

<h2>Objective</h2>

<p>Develop a gender and age detection system capable of estimating the gender and age range of a person based on their facial image, either from a photo or a webcam feed.</p>

<p>This Python-based project leverages deep learning techniques to estimate gender and age from a single facial image. The models, pre-trained by Tal Hassner and Gil Levi, have been utilized to perform these predictions. The gender prediction outputs one of two categories: Male or Female. For age, the system predicts one of the following predefined ranges:

(0 – 2)
(4 – 6)
(8 – 12)
(15 – 20)
(25 – 32)
(38 – 43)
(48 – 53)
(60 – 100)
The classification approach was chosen over regression due to the inherent challenges in pinpointing an exact age from a single image. Factors such as makeup, lighting, obstructions, and facial expressions can significantly impact accuracy. By framing it as a classification problem, the model can effectively assign the image to the most probable age range.



</p>
<h2>Additional Python Libraries Required :</h2>
<ul>
  <li>OpenCV</li>
          
     pip install opencv-python
  
</ul>
<ul>
 <li>argparse</li>
  
     pip install argparse
</ul>
<h2>Contents :</h2>
<ul>
  <li>opencv_face_detector.pbtxt</li>
  <li>opencv_face_detector_uint8.pb</li>
  <li>age_deploy.prototxt</li>
  <li>age_net.caffemodel</li>
  <li>gender_deploy.prototxt</li>
  <li>gender_net.caffemodel</li>
  <li>a few pictures to try the project on</li>
  <li>detect.py</li>
 </ul>

 <h2>Usage :</h2>
 <ul>
  <li>Download my Repository</li>
  <li>Open your Command Prompt or Terminal and change directory to the folder where all the files are present.</li>
  <li><b>Detecting Gender and Age of face in Image</b> Use Command :</li>
  
      python detect.py --image <image_name>
</ul>
