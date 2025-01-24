# Finding-heart-rate-and-ECG-waveforms-from-a-12-lead-ECG

## 시작하기

이 지침을 따르면 로컬 컴퓨터에서 프로젝트를 실행할 수 있습니다.

### Prerequisites (전제 조건)

이 프로젝트는 PTB-XL 데이터를 사용하여 작성하였습니다.
https://www.kaggle.com/datasets/bjoernjostein/ptbxl-electrocardiography-database
해당 파일은 MATLAB 형식이지만, 병원에서 사용하는 데이터가 npy로 저장되어 있어 npy로 변환 후 사용하였습니다.


### **구현된 주요 기능**
1. **데이터 로드 기능**:
   - `load_npy_data` 함수로 디렉토리 내 `.npy` 파일을 읽어와 배열로 변환.
   
2. **ECG 신호 분석**:
   - `find_pqrst_and_calculate_hr` 함수에서 NeuroKit2를 사용하여 PQRST 피크 탐지 및 심박수 계산.
   - 결측값(NaN)을 처리하여 배열로 변환.

3. **리드별 데이터 분석**:
   - `analyze_lead`와 `analyze_all_leads` 함수로 특정 샘플의 리드 데이터를 개별적으로 분석 가능.

4. **결과 출력**:
   - 각 리드별로 피크 데이터와 심박수를 출력.

---


이 추가 기능을 통해 코드의 효율성과 사용자 편의성을 크게 향상할 수 있습니다.

감사합니다.

