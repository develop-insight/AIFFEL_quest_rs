# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 박수연
- 리뷰어 : 조성호


# PRT(Peer Review Template)
- [ ]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - Word2Vec 임베딩을 활용하기 전엔 더 높은 성능이 나왔지만, 활용한 결과에선 약간 성능이 떨어진 상태로 제출되었다.
![image](https://github.com/user-attachments/assets/e2e90ad9-a354-4ecc-8496-8006d71ea9f7)

![image](https://github.com/user-attachments/assets/bb8e48cb-a413-4987-b5a8-2623a8fe777f)

    
- [ ]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        
- [ ]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - tokenizer가 무엇인지 확인하고, load_data() 함수를 직접 구현할 때 에러가 난 부분의 기록을 남겼다.
![image](https://github.com/user-attachments/assets/661dca1d-a76c-45bc-bb05-3b236aac6772)


![image](https://github.com/user-attachments/assets/f88065cd-fcd1-450c-a4c1-7fc9090ee231)

        
- [ ]  **4. 회고를 잘 작성했나요?**
    - 전체적인 내용을 정리한 회고가 작성되어 있다.
![image](https://github.com/user-attachments/assets/15803d08-301d-4769-88ea-4ba0a9b68d8e)

        
- [ ]  **5. 코드가 간결하고 효율적인가요?**
    - 토큰화, 불용어 처리 함수를 만들어 코드를 간결하게 만들었다.
![image](https://github.com/user-attachments/assets/00860410-5dc1-4aa4-ad34-f8a389f04a6e)



# 회고(참고 링크 및 코드 개선)
```
제가 실험한 방식과 다른 부분이 많아 배울 것이 많았습니다.
모델 체크포인트로 가장 성능이 높은 모델을 저장하는 것이 인상깊었습니다.
제가 실험해보지 않은 1D convolution의 성능을 확인할 수 있는 것도 좋았습니다.
마지막 Word2Vec 부분에서는 모델의 넓이를 너무 좁게 만들어 모델의 성능 향상이 없었던 것이 아쉬웠습니다.
```
