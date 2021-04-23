# license-plate-yolov5
## ALPR-Yolov5 (Automatic license Plate detection and recognition) 
### dependencies

NVIDIA GPUs
NVIDIA graphic driver
CUDA toolkit
cuDNN library
OpenCV 
Cython
matplotlib>=3.2.2
numpy>=1.18.5
opencv-python>=4.1.2
pillow
PyYAML>=5.3
scipy>=1.4.1
tensorboard>=2.2
torch>=1.6.0
torchvision>=0.7.0
tqdm>=4.41.0

This is the Automatic license plate detection and recognition system using Yolov5. Both plate detection and character detection and recognition using Yolov5. I used EnglishLP dataset for experiment but you can try with any other dataset also
We need 2 pt files in this project.1 file detect number plate, 1 file detect characters.You can train the model yourself on google colab.
link : https://colab.research.google.com/drive/1gDZ2xcTOgR39tGGs-EZ6i3RTs16wmzZQ
After you have your model, you can replace the model number plate recognition to `final_weight / (detection_weight) .pt`, and recognize characters in`recognition_model/final_weight/(character recognition weight).pt`
In my code, I have added 2 .pt files to the right location, the accuracy of the data in the 2 files is relative, you can try.

Final: run the file `combinetest.py`
![P1010002](https://user-images.githubusercontent.com/66860881/115814289-f2897180-a41e-11eb-9161-e136a84c46be.png)
