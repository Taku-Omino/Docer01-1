FROM mysql:5.7



# パスワード設定

ENV MYSQL_ROOT_PASSWORD=password



# 文字コード設定

COPY ./my.cnf /etc/mysql/conf.d/my.cnf



# 初期化用スクリプトをコピー

COPY ./init.sql /docker-entrypoint-initdb.d/