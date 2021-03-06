[Top](./top.md)  

# 開発環境の整理

開発環境は  
  
- Windows 10
- Visual Studio 2019
- .NET Core 3.1

を用意します。  

## Windows

普通にお手持ちの Windows マシンを用意してください。  
Uno Platform の完全な環境は残念ながら Windows です。mac では完全なプロジェクトの新規作成ができません(制約付きで一部は可能です)。  

#### mac の場合

このリポジトリ内にこのサンプルのテンプレートのソリューションを置いてあります。  

- [ソリューション  ディレクトリ](../src/template/UnoApp1/)  

このディレクトリに手を加えて行ってください。


## Visual Studio 2019

Visual Studio をインストールします。ダウンロードは [こちら](https://visualstudio.microsoft.com/ja/)。  

## ワークロードの選択

インストール時のワークロードの選択では、次のものを選択します (他のものを追加で選択しても構いません)。

#### Web ＆ クラウド

- ASP[]().NET と Web 開発

#### デスクトップとモバイル

- ユニバーサル Windows プラットフォーム開発
- .NET によるモバイル開発

#### 他のツールセット

- .NET Core クロスプラットフォームの開発

#### 個別のコンポーネント

- Windows 10 SDK (10.0.18362.0)

## 拡張機能

Visual Studio の拡張機能で次のものを選択します。

- Uno Platform Solution Templates

## .NET Core

.NET Core をインストール。ダウンロードは [こちら](https://dotnet.microsoft.com/download)。

## エミュレーターや実機などモバイルの実行環境

**※ Android / iOS で動かしたい場合のみ**  

エミュレーター/シミュレーターの作成や実機の接続など実行環境を整えます。  

- Android Emulator のセットアップ  
https://docs.microsoft.com/ja-jp/xamarin/android/get-started/installation/android-emulator/
- Xamarin.iOS のインストール  
https://docs.microsoft.com/ja-jp/xamarin/ios/get-started/installation/

# (必須手順) プロジェクトを実行

環境構築は ```**まだ終わっていません**```。ここで ```**必ず**``` Uno Platform アプリのプロジェクトを実行してください。  
```**IDE 等をインストールしただけでは準備は整っていません。**```  

Uno Platform は (Uno Platform に限らず最近は) 作るアプリの種類/プラットフォーム毎に初回の実行時に必要なファイルをダウンロードして環境を構築します。  
```**プロジェクトを実行できてはじめて開発環境が整ったと言えます。**```  

このリポジトリ内にこのサンプルのテンプレートとゴールのソリューションを置いてあります。  

- [テンプレート ソリューション  ディレクトリ](../src/template/UnoApp1/)  
- [ゴール ソリューション  ディレクトリ](../src/complate/UnoApp1/)  

このソリューションを開いて実行できることを確認してください。  


[< | Topへ](./top.md) | [次へ | >](./textbook2.md)
