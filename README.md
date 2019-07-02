# Human Factors Psychology Lab
### 2019 Summer Workshop

### 1. 환경 준비

1. 깃헙(github)

--깃헙이 처음인 사람--

1.a.1 깃헙 계정을 만드세요
https://github.com

1.a.2. 윈도우 운영 체제 사용자는 git bash도 다운로드 받으세요. 맥은 따로 설치할 필요 없습니다. 
https://gitforwindows.org/

--깃헙을 사용할 줄 아는 사람--

1.b.1 git clone & pull

Terminal 또는 git bash에서

  git clone https://github.com/yoonlee78/lab_workshop.git

이미 clone을 했다면 업데이트를 위해 git pull을 한다.

  git pull

2. Anaconda 환경 설정

--- Anaconda가 처음인 사람---

2.a.1. Anaconda 3 설치하세요

https://www.anaconda.com/distribution/

다운로드 조건: Python 3 버전, Anaconda 3 다운로드하세요. For Windows, For Mac 배포 버전이 다르니 자신의 운영체제(Windows, Mac, Linux)에 맞는 설치 프로그램을 선택하세요. 

3. Jupyter Notebook (JN) 설치 (선택)

처음 오시는 분들은 위 1번만 충족되어도 실습 따라하는 데는 문제 없습니다. 기타 데이터 분석을 하고 싶은 사람은 아래 사항도 준비해오시기 바랍니다. 

### 2. [심화] python library 구동 확인

위 1번 사항이 이미 충족된 사람은, 주피터 노트북에서 다음 패키지 로딩에 문제가 없으면 됩니다.

2.1. 파이썬 분석 및 시각화: Numpy, pandas, matplotlib, seaborn, wordcloud

2.2. 텍스트 분석: nltk, KoNLPy, gensim, pyLDAvis, sklearn

2.3. 추가로 다음 코퍼스, tagger와 데이터를 다운로드 받는다. (강의 자료 내에 포함되어있습니다).

nltk.download('wordnet')
nltk.download('brown')
nltk.download('gutenberg')
nltk.download('maxent_treebank_pos_tagger')
국민청원데이터(다운로드 링크: https://s3.ap-northeast-2.amazonaws.com/data10902/petition/petition.csv 출처: https://github.com/akngs/petitions에서 전체 데이터인 petetion.csv 다운로드)

