# David Silver RL Course : Lecture 3 내용 관련 주요 알고리즘

## __Lec3__ : *__Planning Dynamic Programming__*
  * Value iteration for (Env. 5x5 grid world)
  * Policy iteration for (Env. 5x5 grid world)

### 개발환경
  * OS: windows 10
  * Setup develop environments using Anaconda(`python 3.5`) or `pip`

### 또 다른 버전의 파이썬 인터프리터 기반의 아나콘다 가상환경 만들기
```bash
conda create -n py35 python=3.5 anaconda
```

### py35 환경 활성화 한뒤 개발환경 패키지 설치하기
```bash
activate py35
```

### 설치 패키지
  * python `3.5.5`
  * tensorflow `1.0.0`
  * keras `2.0.3`
  * gym `0.9.4`                     
  * gym-maze `0.4`                  
  
### 주요 패키지 버전
```bash
pip install tensorflow==1.0.0
pip install msgpack
pip install keras==2.0.3
python -m pip install --upgrade pip
pip install gym==0.9.4
cd C:\Users\YOUR_PATH}\rl_env_collection 
git clone https://github.com/tuzzer/gym-maze.git 또는 git clone https://github.com/MattChanTK/gym-maze.git
cd C:\Users\{YOUR_PATH}\rl_env_collection\gym-maze
python setup.py install
```
