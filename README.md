# 소셜 인텔리전스 프로젝트
## 공영 주차장과 불법 주정차의 상관관계 분석 및 대안 마련

## TODO
### 데이터 분석
- [ ] illegal_pariking.csv 분석
- [x] parking_lot.csv 분석     


## 데이터
- [parking_lot.csv(주차장 현황)](https://www2.sejong.go.kr/bigdata/metaDataDetailView.do)
- [illegal_parking.csv(불법주정차 현황)](https://www.data.go.kr/data/15135364/fileData.do)

## 환경 설정
### MacOS
```bash
# Create Venv
python<version> -m venv venv

# Acitvate Venv
source venv/bin/activate

# Installation Libraries
pip install -r requirements.txt

# Deactivate Venv
deactivate
```

### Conda
```bash
# Create Venv
conda env create -f environment.yml
```

