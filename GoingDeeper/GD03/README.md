# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 오수연
- 리뷰어 : 최세영


# PRT(Peer Review Template)
- [O]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
        - ![image](https://github.com/user-attachments/assets/83a188e7-2127-4cc1-aadf-b32131b2cc33)
        - ![image](https://github.com/user-attachments/assets/6f6970b5-1e37-4dde-a271-68ec5923ddfd)
        - ![image](https://github.com/user-attachments/assets/8a8ea262-3213-4119-9449-2a1a3148c711)
        - 루브릭에 맞는 답을 잘 찾아주셨습니다
    
- [O]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - ![image](https://github.com/user-attachments/assets/396d0ce7-31b9-4f88-bbf2-3dfcf691c3aa)
        - ![image](https://github.com/user-attachments/assets/a0c2628b-0392-436f-bdbb-5856fedc2525)
     
        - 주석 각주 등을 잘 작성해주셨고, IoU를 구하는 함수를 설정할 때 해당 부분에 대한 설명이 자세히 작성되어있습니다.


        
- [O]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - ![image](https://github.com/user-attachments/assets/e7c0679d-cbd8-4b91-ad86-b57bcb81e423)
        - ![image](https://github.com/user-attachments/assets/feaf67d6-0e29-4aef-80d6-01832cdb0670)
        - IoU와 Bounding box 및 CAM, Grad-CAM overlay 시작화를 한 번에 실행할 수 있는 함수화가 아주 잘 되어있었습니다.
        - 또한 아래와 같이 추가 학습을 통해 모델의 발전을 시켜보려는 시도가 있었습니다.
        - ![image](https://github.com/user-attachments/assets/5cd6985d-e7aa-4a6e-8313-9a5723558680)

        
- [O]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - ![image](https://github.com/user-attachments/assets/4a729308-6212-49d1-8aae-d9f6edc00643)
        - 회고가 잘 작성되었고, CAM과 Grad-CAM의 차이에 대해 잘 조사해보셨습니다.
        - ![image](https://github.com/user-attachments/assets/50291044-2f4b-46c8-88f7-a2fedbc5543e)


        
- [O]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - ![image](https://github.com/user-attachments/assets/6e493424-880e-43ab-8d3a-5292c1c4aace)
        - ![image](https://github.com/user-attachments/assets/7414754e-7586-428c-8df7-a1eacfb8efe1)
        - 위의 예시코드와 같이 전체적으로 함수화를 잘 해두셔서 중복된 코드의 사용을 최소화 하였습니다.




# 회고(참고 링크 및 코드 개선)
```
IoU와 Bounding box, CAM vs Grad-CAM overlay image 를 한 번에 도출할 수 있는 함수화가 정말 인상 깊었습니다.
다음에 저도 이렇게 한 번에 해결할 수 있는 함수화를 도전해보고자 합니다!
```
