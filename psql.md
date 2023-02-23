* UbuntuにPostgresqlインストール
    * https://www.digitalocean.com/community/tutorials/how-to-install-postgresql-on-ubuntu-20-04-quickstart-ja

* サーバ起動方法
    * ``` service postgresql start ```
    * https://qiita.com/domodomodomo/items/12fe7555513de6b078db

### データベース
* データベース作成
    * ``` CREATE DATABASE name ```
    * https://www.javadrive.jp/postgresql/database/index2.html

* データベース一覧取得
    * ``` \l ```
    * https://www.javadrive.jp/postgresql/database/index1.html#section1

* データベースに接続
    * ``` \c mydb ```
    * https://www.javadrive.jp/postgresql/database/index4.html#section1


### スキーマ
* スキーマとは？ 
    * 
* スキーマを作成
    * ``` CREATE SCHEMA schema_name ```
    * https://www.javadrive.jp/postgresql/schema/index2.html#section1
* スキーマ切り替え
    * https://qiita.com/bibio/items/dc37e9dabb7b78bcf71f


### テーブル
* テーブル削除
    * DROP TABLE
    * https://www.javadrive.jp/postgresql/table/index2.html#section1

* テーブル作成
    * CREATE TABLE table_name ();
    * https://www.javadrive.jp/postgresql/table/index1.html

* csvインポート
    * ``` \COPY ＜table name＞ FROM 'location + file_name' DELIMITER ',' CSV HEADER; ```
    * https://www.ashisuto.co.jp/db_blog/article/how-import-and-export-data-using-csv-files-postgresql.html

* テーブル一覧表示
    * ``` \dt ```
    * https://www.javadrive.jp/postgresql/table/index9.html#section2