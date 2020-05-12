# Computer-Vision-Tutorial-basic-projects-
Image processing some basic projects and hands on experience of computer-vision basics. 
Detailed description in comments and keep in mind to not change directories of files and images.

### 1.face-detecor(rectangle-around-face)(caffemodel)
  A basic face-detecor using caffemodel                                                                                           
   To run on any image type in terminal:  python3 face-detection.py --image "imagename".jpg --prototxt deploy.prototxt.txt \
	--model res10_300x300_ssd_iter_140000.caffemodel                                                                                
  eg:-python3 face-detection.py --image heet.jpg --prototxt deploy.prototxt.txt \
	--model res10_300x300_ssd_iter_140000.caffemodel                                                                                   
                                                                                                                                     
  To run through web-cam tyoe in terminal:python3 face-detection-webcam.py --prototxt deploy.prototxt.txt \
	--model res10_300x300_ssd_iter_140000.caffemodel                                                                                 
