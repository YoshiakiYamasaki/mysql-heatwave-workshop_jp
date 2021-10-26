# HeatWaveを活用した驚異的なパフォーマンスを持つ分析基盤構築

このワークショップでは、Oracle Cloud Infrastructureで分析ワークロードを実行する、もしくはクエリ処理を高速化するためにMySQL Database ServiceとHeatwaveをデプロイするプロセスについて説明します。

HeatWaveは、MySQL Database Service(MDS)用に新しく統合された高性能クエリ実行エンジンです。 HeatWaveは、分析クエリ実行のパフォーマンスを400倍高速化し、数千コアにスケールアウトし、Amazon Redshiftの3分の1のコストで2.7倍処理が高速になります。 HeatWaveを備えたMDSは、データベース管理者とアプリ開発者がMySQLデータベースから直接OLTPおよびOLAPワークロードを実行できるようにする唯一のサービスであり、複雑で時間と費用のかかるデータ移動や分析ワークロードと分離する必要性を排除します。</br>
このサービスは、Oracle Cloud Infrastructure（OCI）向けに最適化されています。

ハンズオンを進めるとMDSにロードされたサンプルデータに対してクエリを実行し、Heatwaveを利用する場合と利用しない場合の実行時間の比較ができるようになります。HeatWaveの性能を体感してください！

![](./images/Intro.png)


**学べること**

-	MySQL Database Service (MDS) および HeatWaveのデプロイ
-	HeatWaveクラスタを有効にする方法
-	MDSへのデータ格納
-	HeatWaveへのテーブルロード
-	HeatWaveを利用したクエリ実行方法


**前提条件**
-  このハンズオンでは、Oracle Cloud Infrastructureのアカウントが必要になります。有償アカウント、もしくはトライアルアカウントをご用意ください。
-  コンパートメントが作成されたテナンシが必要になります。


# ハンズオン概要

 **準備ができたら始めましょう**

## Lab 00 - Oracle Cloud Infrastructureのトライアルアカウントを作成する

**学べること**

- トライアルアカウントの作成方法
- OCIコンソールの基本操作、およびコンパートメントの作成方法

**[Click here for Lab 00](/Lab00/README.md)**

## Lab 01 - 仮想ネットワークを作成し、MySQL Database Serviceポートへの接続を確立する

**学べること**

-	仮想クラウド・ネットワークの作成方法
-	セキュリティリストにイングレスルールを追加してMySQL Database Serviceポートへの接続を確立する

**[Click here for Lab 01](/Lab01/README.md)**

## Lab 02 – 踏み台サーバーとなるコンピュートインスタンスを作成する

**学べること**

-	特定のコンパートメントにコンピュート・インスタンスを作成する方法

**[Click here for Lab 02](/Lab02/README.md)**

## Lab 03 - MySQL DB System (MDS) および Heatwaveをデプロイする

**学べること**

-  MySQL Database Service および Heatwaveをデプロイし、設定する方法
-  管理者の作成方法


**[Click here for Lab 03](/Lab03/README.md)**

## Lab 04 – 踏み台サーバーでのMySQL Shellのインストールとサンプルデータのダウンロード

**学べること**

-  Oracle Cloud Infrastructure (OCI) Cloud Shellと踏み台サーバーへの接続方法
-  MySQL Shellの起動方法
-  サンプルデータのダウンロード、およびセットアップ

**[Click here for Lab 04](/Lab04/README.md)**

## Lab 05 – HeatWaveクラスタをMySQL Database Serviceに追加する

**学べること**

-  HeatWaveクラスタを有効にする方法

**[Click here for Lab 05](/Lab05/README.md)**

## Lab 06 – MDSへのデータインポートとHeatWaveへのデータロード

**学べること**

-  MDSにデータを格納する方法 

**[Click here for Lab 06](/Lab06/README.md)**

## Lab 07 – HeatWaveを有効にしてクエリを実行する

**学べること**

-  HeatWaveを有効にし、HeatWaveが無効になっている場合とクエリ実行時間を比較する

**[Click here for Lab 07](/Lab07/README.md)**

## Lab 08 - OAC用のサンプルデータをMDS及びHeatWaveにロードする。Oracle Analytics Cloud(OAC) を構成して、OACからMDS for HeatWaveに接続する。

**学べること**

- OAC用のサンプルデータのダウンロード、MDSおよびHeatWaveへサンプルデータをロードする方法
- Oracle Analytics Cloud(OAC)及びPrivate Access Channel(PAC)の構成方法
- OACからPAC経由でMDSへ接続する方法

**[Click here for Lab 08](/Lab08/README.md)**

## Bonus Lab 9 - OCI Bastion Serviceを利用してMDSをリモートで使う

**学べること**

- リモートでMDSを管理するためのOCI Bastion Serviceの構築方法

**[Click here for Lab 09](/Lab09/README.md)**

## Bonus Lab 10 - MDS高可用性構成をデプロイする

**学べること**

- MDS高可用性構成を作成する方法

**[Click here for Lab 10](/Lab10/README.md)**

