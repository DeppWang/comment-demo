## 安装

安装虚拟环境

```
python3 -m venv venv
. venv/bin/activate
```

安装依赖

```
pip install -r requirements.txt
```

## 运行


```
$ export FLASK_APP=comments
$ flask init-db
$ flask run
```

## 测试

安装 `Comments`:

```
$ pip install -e .
```

执行测试

```
pytest
```

