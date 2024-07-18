# Finding-heart-rate-and-ECG-waveforms-from-a-12-lead-ECG.

## 시작하기

이 지침을 따르면 로컬 컴퓨터에서 프로젝트를 실행할 수 있습니다.

### Prerequisites (전제 조건)
```
pip install numpy
pip install os
pip install neurokit2
```

### 설치

프로젝트를 실행하려면 다음 단계를 따르십시오.

1. 리포지토리를 복제합니다.

```
git clone https://github.com/kiyuyeon/Mimic_icu.git
```

2. 프로젝트 디렉토리로 이동합니다.

```
cd Mimic_icu
```

3. 필요한 패키지를 설치합니다.

```
pip install -r requirements.txt
```

4. Jupyter Notebook 또는 스크립트를 실행합니다.

```
python model.py
```

### 사용법

본 모델은 Python 3.12 버전을 사용하였습니다. - 필요한 라이브러리의 버전은 requirements.txt 파일에 작성되어 있으며, Docker를 실행할 때 해당 라이브러리가 설치되도록 작성되어 있습니다. 

실행 방법
먼저 Docker Desktop을 설치합니다. - 터미널 또는 명령 프롬프트를 열고 다음 명령을 사용하여 Docker 이미지를 빌드합니다
docker build -t your-image-name . - Docker 이미지 빌드가 완료되면 다음 명령을 사용하여 컨테이너를 실행합니다: - docker run your-image-name

## 기여

이 문서는  ICU 환자의 예후를 배설량 데이터를 중심으로 예측합니다. 


## 감사의 말

감사합니다.

