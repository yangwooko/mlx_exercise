이 레포지토리를 받은 후 그 폴더에 mlx 예제도 받은 후 노트북을 열어서 실행하셔야 합니다. 

```bash
$ git clone https://github.com/ml-explore/mlx-examples.git
```

노트북에서 사용할 Jupyter Server 는 python 3.11 로 구동하는 것으로 가정하였습니다. pipenv + MS VS Code 를 사용하는 경우에는 이런식으로 설정하시면 됩니다.

```bash
$ pipenv --python=3.11
$ pipenv shell
$ code .
```

VS Code가 실행되면 노트북 파일을 열고 셀을 실행하면 Jupyter Server를 지정하라고 나오는데 이때 방금 만든 Python 환경을 지정해주시면 됩니다.