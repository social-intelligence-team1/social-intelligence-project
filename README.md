# 소셜 인텔리전스 프로젝트
## 세종특별자치시 불법주정차 현황 및 대응 정책 마련

## 활용 데이터
- [세종특별자치시_주차장정보.csv](https://www2.sejong.go.kr/bigdata/metaDataDetailView.do)
- [세종특별자치시_불법주정차 단속현황_20250731.csv](https://www.data.go.kr/data/15135364/fileData.do)

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

