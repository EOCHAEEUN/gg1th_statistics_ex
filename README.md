# gg1th_statistics_ex
통계기본실습 

# git 레포 만들기 
- 레포 틀론하기

```
git clone git_url(SSH) statistics_ex 
```

# 가상환경 구성하기 
- 디렉토리 이동 
```
cd statistics_ex
```
- uv 가상환경 만들기
```
uv init --bare
```


# 주피터 노트북 사용환경 구성하기 
- ipykernel 설치
```
uv add ipykernel
```
- 가상환경 .venv를 eda_env이름으로 등록하기 
```
uv run python -m ipykernel install --user --name .venv --display-name "eda_env"
Installed kernelspec .venv in /home/ai_fish/.local/share/jupyter/kernels/.venv
```

# 설치 라이브러리
```
uv add numpy
```
