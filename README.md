# gg1th_statistics_ex
통계 기본 실습

## git repository 만들기
```
git clone <git_url> statistics_ex
```

## 가상환경 구성하기
```
cd statistics_ex
uv init --bare
```

## 주피터 노트북 사용환경 구성하기

- ipykernel 설치 
```
uv add ipykernel 
```

- 가상환경 .venv를 eda_env 이름으로 등록하기
```
uv run python -m ipykernel install --user --name .venv --display-name "eda_env"
```

## 라이브러리 설치하기
```
import numpy as np
from scipy import stats
import pandas as pd
```

