## 便利だと思った方法や知見をメモしていく

自動コミット（lintでフォーマットした時など）
- https://github.com/EndBug/add-and-commit


## Actionsを計測しよう

- WorkflowAPIのドキュメント
 - https://docs.github.com/en/rest/actions/workflow-jobs?apiVersion=2022-11-28#get-a-job-for-a-workflow-run
 - https://docs.github.com/en/rest/actions/workflow-runs?apiVersion=2022-11-28#get-a-workflow-run
 - https://docs.github.com/en/rest/actions/workflows?apiVersion=2022-11-28#get-a-workflow
- こんなデータ取れそう
  - どれだけ時間かかっているか？
  - ステータス（成功・失敗・キャンセル）
  - 1つのPRあたり何回実行しているか？
  - jobごと
  - jobのステップごと
hoge