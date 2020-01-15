# 워드클라우드 제작용 konlpy-noun-extractor

> 워드클라우드 제작 사이트 : http://wordcloud.kr/
>
> 텍스트에 konlpy로 정제한 데이터 결과를 넣으면 워드 클라우드 완성도가 높아집니다.

## install (for MacOS)

1. terminal.app을 실행하여 저장소를 복제하는 아래의 스크립트 입력합니다.

```bash
git clone https://github.com/Jeongah-Shin/konlpy-noun-extractor.git
```

2. 저장소 복제 후, 해당 디렉토리로 이동합니다.

```bash
cd konlpy-noun-extractor
```

3 . jupyter notebook 실행

```bash
jupyter notebook
```

(jupyter notebook이 없을 경우, 아래 스크립트 실행 후 3번으로 회귀)

```bash
# python3 기준
pip3 install --upgrade pip
pip3 install jupyter
```

4 . data.txt 에 정제가 필요한 응답 내용을 담고 `extractor.py` 를 실행합니다.

