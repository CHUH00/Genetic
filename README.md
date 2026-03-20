<div align="center">

# 🧬 유전 알고리즘 (Genetic Algorithms): 진화적 최적화
### 🌱 생물학적 진화 원리를 결합한 파이썬 탐색 알고리즘

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)

</div>

## 📌 프로젝트 소개
이 저장소는 파이썬을 기반으로 한 **유전 알고리즘 (Genetic Algorithm, GA)** 의 핵심 구현 코드(`genetic.ipynb`)를 담고 있습니다. 

유전 알고리즘은 찰스 다윈의 진화론적 자연선택의 개념, 즉 "환경에 적응한 개체만이 살아남아 다음 세대로 형질을 전달한다"는 메커니즘에서 착안된 탐색 휴리스틱 기법입니다. 본 프로젝트는 이러한 생물학적 연산 과정을 컴퓨터 알고리즘 모델로 구현하여, 복잡한 비선형 환경에서의 다목적 최적화 문제 해결 과정을 시뮬레이션 합니다.

## ✨ 주요 기능
- **초기화 (Initialization)**: 문제 공간 내에서 무작위로 구성된 유전자 정보를 가진 초기 염색체 군집(Population)을 생성합니다.
- **적합도 평가 (Fitness Evaluation)**: 목적 함수를 통해 각 개체가 최적의 해에 얼마나 부합하는지 그 적합성(성능)을 백분율로 계산합니다.
- **선택 (Selection)**: 우수한 유전자를 물려줄 확률을 기반으로 다음 세대의 부모가 될 우수 객체를 뽑아냅니다. (룰렛 휠 및 토너먼트 선택 기법 등)
- **교차 및 돌연변이 (Crossover & Mutation)**: 생물학적 번식과 유전자 변이를 모델링하여 새로운 자식 염색체를 생성함으로써 지역 최적해(Local Optima)에 빠지는 것을 방지합니다.
- **수렴 과정 파악**: 만족할 만한 최적해 도출 또는 성능 수렴이 이뤄질 때까지 알고리즘이 스스로 세대를 교체하며 점점 나은 해답을 찾아갑니다.

## 🛠️ 기술 스택
* **언어**: `Python 3.x`
* **주요 라이브러리**: `NumPy`
* **개발 환경**: `Jupyter Notebook`

## 🚀 실행 방법

### 요구 환경
```bash
pip install numpy jupyter
```

### 노트북 실행
1. 레포지토리를 클론합니다.
   ```bash
   git clone https://github.com/CHUH00/Genetic.git
   cd Genetic
   ```
2. 주피터 노트북을 실행합니다.
   ```bash
   jupyter notebook
   ```
3. `genetic.ipynb` 파일을 열어 진화형 알고리즘을 모의 시뮬레이션해 보세요!

---
*본 프로젝트는 인공지능, 딥러닝 및 진화 알고리즘 분야에 대한 끊임없는 탐구의 일환으로 [우진(Woojin Choi)](https://github.com/CHUH00)에 의해 개발되었습니다.*
