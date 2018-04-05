# py-dnn-facedetect

主要來源：https://www.pyimagesearch.com/2018/02/26/face-detection-with-opencv-and-deep-learning/

內文有提到，原本 OpenCV 所提供的 dnn 方法中沒有 model, 所以作者自己建立了一個 model

詳細建立及訓練方法可以參考這個：https://github.com/opencv/opencv/tree/master/samples/dnn/face_detector

# usage

cv2.dnn 需要兩個參數
prototxt => prototxt.txt

model => res10_300x300_ssd_iter_140000.caffemodel
