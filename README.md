# YOLOv3-tiny Android APP
- 성능 개선 전 yolov3-tiny
<img src="https://github.com/CAUCV/YOLOv3-Android/blob/main/result_image/yolov3-tiny.jpg?raw=true" width="600px">

## 개발 환경
- Windows 10
- Android Studio
- opencv-3.4.5-android-sdk

### yolov3 & yolov3-tiny weight download:
- debug의 assets 폴더 안에 넣어야 한다.
- https://pjreddie.com/media/files/yolov3-tiny.weights
- https://pjreddie.com/media/files/yolov3.weights

## 성능 개선을 위해 봐야할 것
- yolov3-tiny.cfg 에서 batch size, classification 등 수정
- yolov3 는 layer가 3개, yolov3-tiny 는 layer가 2개 (cfg 파일의 [yolo])

## 참고 문서
- https://github.com/ivangrov/Android-Deep-Learning-with-OpenCV
- https://docs.opencv.org/3.4/d0/d6c/tutorial_dnn_android.html (getPath 참고)
- https://m.blog.naver.com/bdg9412/221795234705
