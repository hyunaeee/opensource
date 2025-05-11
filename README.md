

# 🧪 오픈소스 프로젝트 실습 모음

이 리포지토리는 다양한 오픈소스 프로젝트를 실습하고 실험한 결과를 모아둔 개인 학습 저장소입니다. 주로 자연어 처리(NLP), 검색 기반 생성(RAG), 하이퍼파라미터 튜닝, 모델 배포 등의 주제를 다루며, Jupyter Notebook을 활용하여 실험을 진행하였습니다.

## 📁 주요 파일 구성

* **RAG\_with\_Ko\_PlatYi\_6B.ipynb**: KoPlatYi 6B 모델을 활용한 검색 기반 생성(RAG) 실험 노트북입니다.
* **eda\_test.ipynb**: 데이터셋에 대한 탐색적 데이터 분석(EDA)을 수행한 노트북입니다.
* **hyperparam\_test.ipynb**: 모델의 하이퍼파라미터 튜닝을 실험한 노트북입니다.
* **model\_product.ipynb**: 모델을 제품화하거나 배포하기 위한 실험을 진행한 노트북입니다.

## 🛠️ 사용된 기술 스택

* Python
* Jupyter Notebook
* PyTorch
* Transformers (Hugging Face)
* scikit-learn
* pandas
* NumPy

## 🚀 실행 방법

1. 리포지토리 클론:

   ```bash
   git clone https://github.com/hyunaeee/opensource.git
   cd opensource
   ```
2. 필요한 패키지 설치:([GitHub][2])

   ```bash
   pip install -r requirements.txt
   ```

   *`requirements.txt` 파일이 없는 경우, 각 노트북 상단의 패키지 설치 안내를 참고하세요.*
3. Jupyter Notebook 실행:

   ```bash
   jupyter notebook
   ```

   원하는 노트북 파일을 열어 실행합니다.

## 📄 참고 자료

* KoPlatYi 6B 모델: [Hugging Face 모델 페이지](https://huggingface.co/KoPlatYi/6B)
* Transformers 라이브러리: [https://huggingface.co/transformers/](https://huggingface.co/transformers/)
* scikit-learn: [https://scikit-learn.org/](https://scikit-learn.org/)

## 📌 기타

이 리포지토리는 개인 학습을 위한 용도로 작성되었으며, 실험 결과와 코드 구현에 대한 피드백은 언제든지 환영합니다.

