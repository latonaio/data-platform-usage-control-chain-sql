# data-platform-usage-control-chain-sql 
data-platform-usage-control-chain-sql は、データ連携基盤において、用途制御チェーンデータを維持管理するSQLテーブルを作成するためのレポジトリです。  

## 前提条件  
data-platform-usage-control-chain-sql は、データ連携にあたり、API を利用し、本レポジトリ の sql 設定ファイルの内容は、下記 URL の API 仕様を前提としています。  
https://api.XXXXXXXX.com/api/OP_API_XXXXXXX_XXX/overview 

## sqlの設定ファイル  
data-platform-usage-control-chain-sql には、sqlの設定ファイルとして、以下のファイルが含まれます。 

* data-platform-usage-control-chain-sql-usage-control-chain-data.sql （データ連携基盤 用途制御チェーン - 用途制御チェーンデータ）

## MySQLのセットアップ / Kubernetesの設定 / SQLテーブルの作成方法  
MySQLのセットアップ / Kubernetesの設定 / 具体的なSQLテーブルの作成方法、については、[mysql-kube](https://github.com/latonaio/mysql-kube)を参照ください。
