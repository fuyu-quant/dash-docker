# dash-docker
<img src="image/Dash.png" width="400">
Dash docker

## Contents
* [Basic docker operations](#basic-docker-operations)
* [Dash](#dash)
* [Reference](#reference)



## [Basic docker operation](https://github.com/fuyu-quant/dockerfile-for-data-scientists)

## Dash

### Dashの起動
* コンテナ起動時に起動
初期設定ではコンテナ起動時に立ち上がるようになっている
```bash
# コンテナ内部から起動
ENTRYPOINT ["python", "src/app.py"]
```

* コマンドで起動
```bash
docker-compose exec dash bash -c "python src/app.py"
```
When you want to exit, press [control + c]
* Link  
    * http://127.0.0.1:8050/


## Reference
* https://qiita.com/NobuYoshi/items/9078d0689fef748486ac
