# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 홍예린
- 리뷰어 : 김민호


# PRT(Peer Review Template)
- [X]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - ![image](https://github.com/user-attachments/assets/f215551c-9ee3-4d80-a77c-37603442e875)
        - SimpleBaseline에 대한 구현과 30에포크나 되는 학습까지 모두 진행하셨다
        - 정성적인 평가 역시 진행하여, 코드리뷰 때도 언급해주셨다.

    
- [X]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - ![image](https://github.com/user-attachments/assets/ac944124-9d8e-44c5-837c-dad07dfeddf1)
        - 주석을 통해 코드블럭의 기능을 잘 이해할 수 있었다.

        
- [X]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - ![image](https://github.com/user-attachments/assets/40055530-9b56-45bb-bedb-5767b4034c27)
        - 에러가 난 부분에서 float로 캐스팅 하여 해결하셨다.

        
- [X]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - ![image](https://github.com/user-attachments/assets/63fcd940-265b-40d3-a20b-86705c64542a)
        - 회고 역시 잘 작성해 주셨다. 다들 비슷한 고민을 한 프로젝트인 것 같다는 생각을 하게 됐다.

        
- [X]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - ![image](https://github.com/user-attachments/assets/d00fd212-b237-4280-913a-45f70da47b21)
        - 전체적인 코드를 다 재사용할 수 있도록 함수화 하여 프로젝트를 진행하셨다. 


# 회고(참고 링크 및 코드 개선)
```
30에포크나 되는 학습을 해도 loss가 거의 줄 지 않아서 생각하는 것 이상으로 어려운 Task라는 생각을 하게 되었다.
논문을 참고해서 어떤 데이터셋으로 몇 에포크를 논문에서는 학습했는지 언급해 주셔서 이 모델의 학습에 대한 이해도가 올라갔다.
```
