# Playwiright_modal
미리캔버스 페이지에서 네이버 로그인까지 자동화테스트 후 allure을 통해 리포트

**파이썬 버전 3.8이상 필요**

#가상환경 세팅 (독립적 테스트 환경을 만들기 위함)

**가상환경 명은 자유**

1. 가상환경 생성
python -m venv venv(가상환경 명)
2. 가상환경 활성화
venv\Scripts\activate


**활성화 후 가상환경 내에 설치**

1. playwright 설치
pip install playwright

2. Chromium, Firefox, WebKit 브라우저 설치
playwright install

3. pytest 설치
pip install pytest

4. 파이썬용 allure 설치
pip install allure-pytest
