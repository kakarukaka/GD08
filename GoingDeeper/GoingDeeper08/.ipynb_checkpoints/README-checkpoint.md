# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 구재현
- 리뷰어 : 오학균


# PRT(Peer Review Template)
- [ ]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - ![이미지](peer_review_image/1-1.jpg)
    - ![이미지](peer_review_image/1-2.jpg)
    - 모델 학습한 시각화도 보이며, 각 keypoint과 예측간의 거리계산으로 표로 정리를 잘 해두심(일종의 metric으로 보임)
    
- [ ]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - ![이미지](peer_review_image/2-1.jpg)
    - Hourglass 모델과 비교하기 위한, SimpleBaseline을 구축
    - 다른 분들과 다르게 pre-trained을 사용하지 않고, 직접 층을 쌓음
        
- [ ]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - ![이미지](peer_review_image/3-1.jpg)
    - 1에서 말한 것처럼, 각 keypoint에 대한 metric으로 거리를 보여줌
    - 다만 학습하면서 거리가 가까워지는 keypoint도 있지만, 이상하게 학습하면서 멀어지는 keypoint도 존재해서 의아함
        
- [ ]  **4. 회고를 잘 작성했나요?**
    - ![이미지](peer_review_image/4-1.jpg)
    - ![이미지](peer_review_image/4-2.jpg)
    - 마지막 단락에 내용을 잘 정리해둠.
    - 다만 시간부족으로 keypoint를 추론하고 시각화한 이미지가 없어서 아쉬웠음
        
- [ ]  **5. 코드가 간결하고 효율적인가요?**
    - ![이미지](peer_review_image/5-1.jpg)
    - 함수화로 잘 정리 해둠


# 회고(참고 링크 및 코드 개선)
```
metric 개념으로, 각 keypoint들마다 어떻게 학습하는 동안 변화하는지 잘 보여준게 인상깊었음
```
