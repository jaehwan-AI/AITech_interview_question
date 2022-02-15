# Table of Contents
* [딥러닝 발달 이전에 사물을 Detect할 때 자주 사용하던 방법에 대해 설명해 주세요.](#1)
* Faster R-CNN에 대해 설명해 주세요. 그리고 장점과 단점에 대해서도 설명해 주세요.
* YOLO에 대해 설명해 주세요. 그리고 장점과 단점에 대해서도 설명해 주세요.
* dlib에 대해 설명해 주세요.
* 알고 있는 Object Detection 알고리즘에 대해 설명해 주세요. 그리고 그 알고리즘의 장점과 단점에 대해 설명하고 알고 있는 더 좋은 알고리즘이 있는지 설명해 주세요.
* [Detection의 평가 지표로 많이 사용되는 mAP에 대해 설명해 주세요.](#6)
* Average Pooling과 Max Pooling에 대해 설명해 주세요. 그리고 차이점에 대해서도 설명하고 알고 있는 다른 Pooling 방법에 대해서도 설명해 주세요.
* 네트워크는 깊을수록 좋은 것인지 설명해 주세요. 깊을수록 좋다면 무조건 깊은 모델은 좋은 것인지 설명해 주세요.
* Residual Network에 대해 설명해 주세요. 그리고 왜 학습이 잘 되는지도 설명하고 Ensemble과 관련이 있는지도 설명해 주세요.
* CAM(Class Activation Map)에 대해 설명해 주세요.
* Localization에 대해 설명해 주세요.
* Semantic Segmentation에 대해 설명해 주세요. 그리고 알고 있는 관련 모델에 대해서도 설명해 주세요.
* Visual Q&A(VQA)에 대해 설명해 주세요.
* Image Captioning에 대해 설명해 주세요.
* Fully Connected Layer의 기능에 대해 설명해 주세요.
* Neural Style은 어떻게 진행되는지 설명해 주세요.
* CNN에 대해서 설명해 주세요.
  * CNN이 MLP보다 좋은 이유에 대해서 설명해 주세요.
  * CNN의 파라미터 개수는 어떻게 계산할 수 있는지 설명해 주세요.
  * 주어진 CNN과 똑같은 MLP를 만들 수 있는지 설명해 주세요.
  * 시퀀스 데이터(Sequence data)에 CNN을 적용하는 것이 가능한지 설명해 주세요.
* 자율주행 자동차의 원리에 대해 설명해 주세요.
* OpenCV 라이브러리만을 사용해서 이미지 뷰어(crop, gray, zoom 등의 기능 포함)는 어떻게 만들 수 있는지 설명해 주세요.

---

## #1
#### 딥러닝 발달 이전에 사물을 Detect할 때 자주 사용하던 방법에 대해 설명해 주세요.

---

## #6
#### Detection의 평가 지표로 많이 사용되는 mAP에 대해 설명해 주세요.

각 클래스에 대한 AP의 평균을 나타냅니다.
AP는 Precision-Recall 그래프의 면적을 의미하는데 Recall에 대한 Precision을 그래프화 한 것입니다.
Precision은 모델이 True라고 예측한 것 중 정답도 True인 것의 비율이고, Recall은 실제 정답이 True인 것 중에서 모델이 True라고 예측한 것의 비율입니다.
```
Precision = TP / (TP + FP)
Recall = TP / (TP + FN)

TP = True Positive, TN = True Negative, FP = False Positive, FN = False Negative
```


---

