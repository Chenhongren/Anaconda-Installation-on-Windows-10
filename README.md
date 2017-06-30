# Anaconda-Installation-on-Windows-10
 *Anaconda Python*

# Download
- __Anaconda__:

    https://www.scivision.co/install-opencv-python-windows/
    
- __OpenCV__:

    - __Step1__: Download .whl file from the URL below.
    
         http://www.lfd.uci.edu/~gohlke/pythonlibs/#opencv

        *【NOTE】contrib includes OpenCV-extra packages.*
        *For example, assuming you have Python 3.6, you might download opencv_python-3.2.0+contrib-cp36-none-win_amd64.whl*
        
    - __Step2__: Input Cmmand below to Anaconda Prompt
 
            > pip install opencv_python-3*win_amd64.whl


【NOTE】TEST Anaconda Python 3.6 and OpenCV 3.2.0

*referance : http://docs.opencv.org/3.0-beta/doc/py_tutorials/py_gui/py_image_display/py_image_display.html*

        #Import Package including Numpy and OpenCV
        import numpy as np
        import cv2
        # Load an color image in grayscale
        img = cv2.imread('messi5.jpg',0)
        #Show Image
        cv2.imshow('image',img)
        cv2.waitKey(0)
        cv2.destroyAllWindows()

# Extra-installation 

   - __1__: "GIT" command

        *referance : http://oranwind.org/git-zai-windows-xia-an-zhuang-git-ban-ben-kong-zhi/*

   - __2__: Python Package - __NUMPY__
   
            > pip install numpy
        
   - __3__: Python Package - __SCIPY__

            > pip install scipy
        
   - __4__: Python Package - __THEANO__

            > pip install theano
        
   - __5__: Python Package - __Keras__

            > pip install keras
        
   - __6__: Python Package - __TENSORFLOW__
    
            > pip install tensorflow

# Keras Usage

   - __Step1__: Git keras project from GITHUB
            
            > git clone https://github.com/fchollet/keras.git
            
   - __Step2__: change floder direction to keras/examlpe
            
            > cd 【keras_project_dircetion】/keras/example
            
   - __Step3__: Run 
            
            > python mnist_mlp.py
            
