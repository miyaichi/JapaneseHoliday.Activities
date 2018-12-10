# Japanese Holiday Activities

曜日のデータと内閣府の[国民の祝日について](http://www8.cao.go.jp/chosei/shukujitsu/gaiyou.html)に掲載されている「国民の祝日等（いわゆる振替休日等を含む）」のファイルから、休日・祝祭日（振替日）であるかを判定します。

| Argument      | Default    | Description                               |
|:--------------|:-----------|:------------------------------------------|
| DateToCheck   | 今日の日付 | チェックする日付（YYYY-MM-DD形式)の文字列 |
| RefreshPeriod | 1          | ダウンロードした内閣府データの有効日数    |
| IsHoliday     | -          | チェック結果。休日・祝祭日ならTrue        |
