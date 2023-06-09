# Handwritten Character Recognition

Recognition of handwritten characters is crucial for enhancing human-computer interaction. 
Due to the vagueness and unevenness of each person's writing styles and strokes, the task could be difficult. 
Additionally, the potential for a poor source image quality makes the work more difficult.

<h2> Objective </h2>
To interpret the scanned or uploaded images of handwritten texts.

<h2> Abstract </h2>
We have proposed a CNN architecture that uses keras as an interface for tensorflow library. 
The model has been validated for english as well as devanagari scripts. 
Dataset put-to-use for english is ‘EMNIST_ByClass’ [1] and for devanagari is ‘devanagari handwritten character dataset - DHCD’ [2]. 
The model achieved 87.20% accuracy for EMNIST_ByClass and 98.19% accuracy for DHCD dataset.

<h2> Dataset </h2>
<h4> 1. Hindi Devnagari </h4>
Train Dataset: https://drive.google.com/file/d/1egHJ3E6ivL5355OVJypYmAGvYATQyYHL/view?usp=sharing <br>
Test Dataset: https://drive.google.com/file/d/1N7R-S5B9RMdUYa0sWiIgRMScrcy9lb_B/view?usp=sharing <br>

<h4> 2. EMNIST Byclass </h4>
Train Dataset: https://drive.google.com/file/d/1kGfJJPWAi6L7sJgFjBiV-qoTkPPDv5-J/view?usp=sharing <br>
Test Dataset: https://drive.google.com/file/d/1AlnTmYPT_13pkAR7H8gfliMJkbw9gShk/view?usp=sharing <br>

<h2> References </h2>
[1] G. Cohen, S. Afshar, J. Tapson and A. van Schaik, "EMNIST: Extending MNIST to handwritten letters," 2017 International Joint Conference on Neural Networks (IJCNN), 2017, pp. 2921-2926, doi: 10.1109/IJCNN.2017.7966217. <br>
[2] Acharya, Shailesh et al. “Deep learning based large scale handwritten Devanagari character recognition.” 2015 9th International Conference on Software, Knowledge, Information Management and Applications (SKIMA) (2015): 1-6.
