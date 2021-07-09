# index

#### コンテナ -&gt; ホスト  へコピー

## Monaca クラウド IDE テスト

```bash
docker cp <コンテナID>:/etc/my.cnf my.cnf
```

* PC 版 Google Chrome \( 最新バージョン \)
* 安定したインターネット環境

#### host -&gt; container  へコピー

## Monaca デバッガー

```bash
docker cp my.cnf <コンテナID>:/etc/my.cnf
```

* iOS 11 以上
* Android 5.1 以上 \(6.0 以上を推奨\)
* Wi-Fi 接続を推奨

## Monaca Localkit

Monaca Localkit は、次の環境で動作検証を行っています。

* macOS Catalina
* Windows 10 \(64-bit\)
* Ubuntu Linux 16.04 \(64-bit\)

## Monaca CLI

Monaca CLI は、次の環境で動作検証を行っています。

* Node.js 10.20.1
* npm 6.14.4

## ビルドアプリ

| ビルドアプリ | Android | iOS | Windows |
| :--- | :---: | :---: | :---: |
| Cordova 10.1 | 5.1 以上 \(6.0 以上を推奨\) | 11 以上 | -- |
| Cordova 9.0 | 4.4 以上[1]() | 10 以上 | -- |
| Cordova 7.1 | 4.1 以上[1]() | 9 以上 | 8.1 |

## カスタムデバッガー

| カスタムデバッガー | Android | iOS |
| :--- | :---: | :---: |
| Cordova 10.0 | 5.1 以上 \(6.0 以上を推奨\) | 11 以上 |
| Cordova 9.0 | 4.4 以上[1]() | 10 以上 |
| Cordova 7.1 | 4.1 以上[1]() | 9 以上 |

## ビルド環境

| Cordovaバージョン | Android  \( SDK バージョン \) | iOS \( Xcodeバージョン \) |
| :--- | :---: | :---: |
| Cordova 10.0 | 29 | 11.3 / 12.2 |
| Cordova 9.0 | 28 | 10.1 / 10.2 / 10.2.1 / 11.3 |
| Cordova 7.1 | 26 | 9 / 10.1 |

## ファイル名

以下の特殊文字は、ファイル名に使用することはできません。

* 使用できない特殊文字:   


  $ % \# ^ & \* \` ; : &lt; &gt; ? , ' "  /  \|

\[1\] Android 5.0未満は暗号化形式の問題があるため、最新のhttpsサーバーに接続することが出来ません。

