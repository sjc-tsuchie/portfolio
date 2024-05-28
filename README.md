# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

# version

|name|version|
|:---|:---|
|Ruby| 3.3.0|
|Ruby on Rails| 7.1.3.2|

# 環境構築手順

1. DockerDesktopをインストールする
	- https://www.docker.com/products/docker-desktop/

1. git cloneする

	`git clone git@github.com:sjc-tsuchie/portfolio.git`
  

1. dockerイメージを作成する

	`docker compose build --no-cache`

1. dockerコンテナを起動する

 	`docker compose up`

1. http://localhost:3000/ にアクセスできることを確認する
