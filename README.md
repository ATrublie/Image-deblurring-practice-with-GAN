# Image-deblurring-practice-with-GAN
Practice project


Fixed issue with AttributeError: module 'tensorflow' has no attribute 'placeholder' 

```bash 
import tensorflow.compat.v1 as tf
tf.disable_v2_behavior()
