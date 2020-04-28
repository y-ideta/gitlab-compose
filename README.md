# このリポジトリについて
gitlabをオンプレ環境で動かすための最小構成です。

気が向いたらまたdocker-compose.override.ymlとか書いてアップデートすると思います。

## 確認環境
- macOS 10.15.1 Beta
- docker on mac 2.2.0.5

## 動かし方
dockerが入っている環境で  

`git clone https://github.com/y-ideta/gitlab-compse`

`docker-compose up -d`

立ち上がるのに結構時間がかかるので  
`docker-compose logs -f`

とかで進捗を確認しながら、立ち上がったらブラウザから

http://localhost:8888

に接続することでGitLabのページが表示される様になると思います
