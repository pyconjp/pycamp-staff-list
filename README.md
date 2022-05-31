# pycamp-staff-list

Python Boot Campの現地スタッフ、TAのリストを作成する

## 使い方

* 以下のようにコマンドを実行して、スタッフ、TAの一覧を出力する

```bash
$ python3.10 -m venv env
$ . env/bin/activate
(env) $ pip install -r requirements.txt
(env) $ python pycamp-staff-list.py
京都	https://pyconjp.connpass.com/event/33014/	yu-i9	ta
京都	https://pyconjp.connpass.com/event/33014/	tanishiking	ta
京都	https://pyconjp.connpass.com/event/33014/	litesystems	staff
愛媛	https://pyconjp.connpass.com/event/34564/	ynaruc	ta
愛媛	https://pyconjp.connpass.com/event/34564/	YoshitakeKageura	ta
愛媛	https://pyconjp.connpass.com/event/34564/	npmyj	staff
...
```

* 上記のリストをコピーして、「pycamp Tシャツサイズ一覧」スプレッドシートの「TA、スタッフ一覧」シートにペーストする
* 「TA、スタッフ集計』シートを確認して、2回以上になった人がいないか確認する
