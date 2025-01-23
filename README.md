# 미국 자전거 공유 데이터 분석

## 프로젝트 개요  
이 프로젝트는 NanoDegree 프로그램 중 세 번째 소주제 프로젝트입니다.
**시카고, 뉴욕, 워싱턴 세 도시의 자전거 공유 데이터를 분석**합니다.  
`bikeshare.py`를 실행하여 데이터를 탐구하고 통계 분석을 수행합니다.

## 프로젝트 상세 정보  

- **프로젝트 제목**: 미국 자전거 공유 데이터 분석  
- **최종 업데이트 일자**: 2025-01-23 
- **사용 데이터**:  
  - Chicago.csv  
  - New York City.csv  
  - Washington.csv  
- **주요 파일**:  
  - `bikeshare.py` (Python 스크립트 파일)

---

## 기술적 접근 방식  

- **프로그래밍 언어**: Python  
- **주요 라이브러리**: Pandas  
- **주요 기능**:  
  - 시간 데이터 필터링 및 분석 (Pandas `.dt` 사용)  
  - 사용자 유형별 대여 패턴 분석  

---

## 데이터 파일 관리  

### CSV 파일  
- 프로젝트에서 사용하는 대용량 CSV 파일은 **Git 버전 관리에서 제외**됩니다.  
- `.gitignore`에 추가된 파일:  
  ```plaintext
  Chicago.csv  
  New York City.csv  
  Washington.csv  
  ```

---

## 프로젝트 사용 방법  

1. **프로그램 실행**  
   터미널에서 다음 명령어로 프로그램을 실행하세요:  
   ```bash
   python bikeshare.py
   ```

2. **분석 옵션 선택**  
   프로그램 실행 후 다음과 같은 분석 옵션을 선택할 수 있습니다:  
   - 특정 시간대별 대여량 확인  
   - 특정 도시 필터링  
   - 사용자 유형별 대여 패턴 분석  

3. **결과 확인**  
   분석 결과는 터미널에 출력됩니다.  

---