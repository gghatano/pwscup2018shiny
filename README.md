PWSCUP2018 書式チェッカー (Ver. 1.5.1)
===

## 使い方
1. docker composeが使える環境で、以下のコマンドを実行します

```bash
$ docker-compose up -d
```

2. ブラウザで http://localhost:3838/pwscup2018webapp/  にアクセスします

3. 評価したいデータをアップロードします

- Aの有用性・安全性評価
![匿名加工データの有用性・安全性評価](./utility.png)

- Aのチェック
![匿名加工データAの書式チェック](./checker_A.png)

- Fのチェック
![推定対応表Fの書式チェック](./checker_F.png)


## 問い合わせ先

- 公式Twitter: https://twitter.com/PWScup_Admin
- 大会運営ML 

## メモ
- 2018/09/28 本戦データを配置しました
- 2018/09/20 データアップロード上限サイズを50MBにしました
- 2018/09/20 有用性評価が正しく出来ないバグを修正しました
