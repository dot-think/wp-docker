# wp-docker

WordPress開発のDocker環境です。

## 前提

- Dockerがインストールされていること
-- https://docs.docker.com/install/

## インストール方法

### Git Clone

``` git clone https://github.com/onocom/wp-docker.git ```

### Docker立ち上げ

#### クローンしたディレクトリに移動

``` cd wp-docker ```

#### Docker起動

``` docker-compose up -d ```

#### Docker停止

``` docker-compose down ```

## 使い方

### WordPressインストール

http://localhost:8000/

初回起動時には、WordPressのインストール画面が立ち上がるはずです。

### phpMyAdmin

http://localhost:8080/

### MailHog

ローカル環境でメール受信・送信を確認する画面が立ち上がります。

http://localhost:8025/


## ディレクトリ構成

Dockerが起動すると、以下のディレクトリが生成されます。
htmlがApacheのドキュメントルートになります。

``` /www/html/ ``` 

※ www配下のディレクトリは、gitignoreされています。

