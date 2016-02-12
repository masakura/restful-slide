### REST?

ウェブの持つ URL とリソースのマッピングを使っている方式

| 呼び出し | 意味
| ---- | ----
| GET http://example.com/notes      | ノートの一覧を取得
| GET http://example.com/notes/1    | ID: 1 のノートを取得
| PUT http://example.com/notes      | 新しいノートを追加
| POST http://example.com/notes/1   | ID: 1 のノートの修正
| DELETE http://example.com/notes/1 | ID: 1 のノートの削除
<!-- .element: style="font-size: 80%" -->

* 必ずこの通りというわけではないので API ドキュメントを確認してください! <!-- .element: style="font-size: 80%" -->
