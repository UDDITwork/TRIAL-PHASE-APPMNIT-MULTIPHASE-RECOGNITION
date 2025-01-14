# TRIAL-PHASE-APPMNIT-MULTIPHASE-RECOGNITION
'''
python 3.13 ka version is not compatible with deepface,opencv-python,flask,tesnroflow,tf-keras---kuki utils naam ki directory ya file is not present in 3.13 , therefore to use the requirements.txt of this directory , use python 3.11 ok ?
'''
C:\Users\Mahakaal\Desktop\attend_school\backend>pip show keras tensorflow deepface opencv-python mtcnn
Name: keras
Version: 2.12.0
Summary: Deep learning for humans.
Home-page: https://keras.io/
Author: Keras team
Author-email: keras-users@googlegroups.com
License: Apache 2.0
Location: C:\Users\Mahakaal\AppData\Local\Programs\Python\Python311\Lib\site-packages
Requires:
Required-by: deepface, mtcnn, tensorflow-intel
---
Name: tensorflow
Version: 2.12.0
Summary: TensorFlow is an open source machine learning framework for everyone.
Home-page: https://www.tensorflow.org/
Author: Google Inc.
Author-email: packages@tensorflow.org
License: Apache 2.0
Location: C:\Users\Mahakaal\AppData\Local\Programs\Python\Python311\Lib\site-packages
Requires: tensorflow-intel
Required-by: deepface, retina-face
---
Name: deepface
Version: 0.0.79
Summary: A Lightweight Face Recognition and Facial Attribute Analysis Framework (Age, Gender, Emotion, Race) for Python
Home-page: https://github.com/serengil/deepface
Author: Sefik Ilkin Serengil
Author-email: serengil@gmail.com
License: UNKNOWN
Location: C:\Users\Mahakaal\AppData\Local\Programs\Python\Python311\Lib\site-packages
Requires: fire, Flask, gdown, gunicorn, keras, mtcnn, numpy, opencv-python, pandas, Pillow, retina-face, tensorflow, tqdm
Required-by:
---
Name: opencv-python
Version: 4.8.0.76
Summary: Wrapper package for OpenCV python bindings.
Home-page: https://github.com/opencv/opencv-python
Author:
Author-email:
License: Apache 2.0
Location: C:\Users\Mahakaal\AppData\Local\Programs\Python\Python311\Lib\site-packages
Requires: numpy
Required-by: deepface, mtcnn, retina-face
---
Name: mtcnn
Version: 0.1.1
Summary: Multi-task Cascaded Convolutional Neural Networks for Face Detection, based on TensorFlow
Home-page: http://github.com/ipazc/mtcnn
Author: Iván de Paz Centeno
Author-email: ipazc@unileon.es
License: MIT
Location: C:\Users\Mahakaal\AppData\Local\Programs\Python\Python311\Lib\site-packages
Requires: keras, opencv-python
Required-by: deepface
