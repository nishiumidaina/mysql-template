# mysql-template  
Dockerで使用するMySQLのテンプレート。  
## URL・設定(docker-compose.yamlに記載)  
phpMyAdmin：[http://localhost:8080](http://localhost:8080)    
サーバ名：mysqldb  
ユーザー名：root  
パスワード：root  
ホスト：host.docker.internal:3306  
デフォルトのデータベース：testdb  
## 環境構築
1.リポジトリのclone
```
git clone https://github.com/nishiumidaina/mysql-template.git
```
2.作業ディレクトリに入る
```
cd mysql-template
```
3.コンテナを起動
```
docker-compose up -d --build
```
