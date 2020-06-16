[Top](./top.md)  

# このページについて

**新しいプロジェクトの作成** は、ご自身が一からアプリを作成する場合の手順です。  
今回のサンプルでは作成済みのプロジェクト(ソリューション)を使うため、**新しいプロジェクトの作成** で行う操作はありません。

# 新しいプロジェクトの作成

新しいプロジェクトの作成で次のテンプレートを選択しプロジェクトを作成します。

- **Cross-Platform App (Uno Platform)**

# プロジェクトを開く

今回のサンプルでは作成済みのプロジェクトを用意しています。  
作成済み [プロジェクト(ソリューション)](../src/template/UnoApp1/) を Visual Studio で開いてください。  

# 実行
## 実行 (wasm)

プロジェクトを新規作成すると、5 つのプロジェクトが含まれたソリューションが作成されます。

| プロジェクト | プラットフォーム |
|:-|:-|
| <プロジェクト名>.Droid | Android アプリ(実行できるプロジェクト) |
| <プロジェクト名>.iOS | iOS アプリ(実行できるプロジェクト) |
| <プロジェクト名>.Shared | 共通コード(実行できないプロジェクト) |
| <プロジェクト名>.UWP | UWP アプリ(実行できるプロジェクト) |
| <プロジェクト名>.Wasm | WebAssembly アプリ(実行できるプロジェクト) |

プロジェクトを開いたら、一旦リビルドを行い実行できるプロジェクトを実行します。  
一番無難なプロジェクトは **wasm** です。まずは **wasm** プロジェクトから実行するのがオススメです。  

**※ mac の場合は、Android または iOS を実行してください。**  

## 実行 (UWP)

UWP プロジェクトは実行に注意が必要です。  
まず、開発マシンの Windows の [ 開発者モード ] を有効にします。

- デバイスを開発用に有効にする  
https://docs.microsoft.com/ja-jp/windows/uwp/get-started/enable-your-device-for-development

開発者モード を有効にしたら、リビルドをしたのち配置を行います。  
配置が完了したら、おもむろにデバッグ実行します。

## 実行 (Android)  
Android はエミュレーターまたは実機が整っていれば、デバッグ実行できます。

## 実行 (iOS)
iOS は macOS が必要になります。もし macOS をお持ちであれば、xcode の開発環境を整えてください。  
次いで、Visual Studio for Mac をインストールします。  

[< | 前へ](./textbook1.md) | [次へ | >](./textbook3.md)