# 소프트웨어 마에스트로
> 9기 연수생 황다솔 2018.6 ~ 2018.11 
    
    
    
## 나만의 암호화폐 알고리즘 트레이딩 플랫폼  
    
![head](https://user-images.githubusercontent.com/32833990/51304012-65eeec80-1a7a-11e9-9a56-b71274fd7d2d.jpg)  
![why](https://user-images.githubusercontent.com/32833990/51304147-aea6a580-1a7a-11e9-8f46-7b87d89892db.jpg)   
<img width="1000" alt="summary" src="https://user-images.githubusercontent.com/32833990/51304328-2f65a180-1a7b-11e9-9815-2fe06b386d5e.png">  
  
  
  
------------------------------  
    
    
### 강화학습 투자 알고리즘
  
> 강화학습은 어떤 환경 안에서 정의된 에이전트가 현재의 상태를 인식하여 선택 가능한 행동들 중 보상을 최대화 하는 행동을 선택하여 학습하는 방법입니다   
    
    
 크립스탈의 강화학습 투자 알고리즘은 암호화폐 차트 안에서 투자자인 에이전트가  
 현재 차트의 상태와 현재 투자자의 상태를 인식하여 매수, 매도, 관망 중에 수익을 최대화하는 행동을 선택하여 학습합니다
    
    
    
- 전체적인 강화학습 투자 알고리즘의 흐름  
<img width="1000" alt="rf-ing" src="https://user-images.githubusercontent.com/32833990/51304186-c847ed00-1a7a-11e9-9daa-6b29a8d625d1.png">  
    
    
- 강화학습 구간에 관한 아이디어
<img width="1000" alt="rf" src="https://user-images.githubusercontent.com/32833990/51303962-3f30b600-1a7a-11e9-9728-605617fa3106.png">  
  
- 투자하려는 현재 시장 상황과 비슷한 과거 구간을 학습한다면, 강화학습이 더 적절한 투자 판단을 할 것이라고 생각했습니다
- 사용자가 직접 학습 구간을 설정할 수 있도록 하여 사용자의 주관이 들어간 투자가 가능하도록 하였습니다
  - 현재의 투자 흐름이 하락장이라면 과거 하락장 구간을 선택하여 그 부분을 학습할 수 있도록
  - 학습 구간을 직접 드래그하거나 시작, 종료 날짜를 입력할 수 있도록 구성
  
  
***   
  
  
[References]  
- <https://github.com/quantylab/rltrader>  
- <https://wikidocs.net/book/1436>  
