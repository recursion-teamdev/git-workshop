## チーム開発 Tips

---

1. Issueを作成する
2. プルリクエストを送る
3. プルリクに対するレビューを行う

---

<br>


チーム開発の課題は、いくつかのタスクに分け、各チームメンバーに対して割り振ることで効率よく開発を進めていくことができます。
以下のスクリーンショットのように、Issueを作成し、各チームメンバーにアサインします。
![Screen Shot 2022-06-13 at 22 18 20](https://user-images.githubusercontent.com/66197642/173499052-dcc964fa-84f8-4e3c-8cc3-c126106a7bf1.png)


![Screen Shot 2022-06-13 at 22 16 26](https://user-images.githubusercontent.com/66197642/173498886-b6fd3f9b-5f9e-4207-a8f1-42e00458152c.png)


参考リンク
- [Issueの作成方法](https://docs.github.com/ja/issues/tracking-your-work-with-issues/creating-an-issue)
- [Issueで課題管理Assignee, Label, Project機能](https://style.potepan.com/articles/31077.html)
- [Markdown記法の書き方1](https://qiita.com/tbpgr/items/989c6badefff69377da7)
- [Markdown記法の書き方2](https://www.markdownguide.org/basic-syntax/)

---


各Issueに対してプルリクエストを送るようにすると、どのタスクに対してブランチを切り、どのような変更を行なったのかをわかりやすく管理することができます
先ほどのCPU対戦機能のIssueがリンクされていることがわかるかと思います

![Screen Shot 2022-06-13 at 22 19 42](https://user-images.githubusercontent.com/66197642/173499212-7d450825-4f03-4c13-8926-03c30fc5c0e6.png)

プルリクエスト内で、レビュワーをアサインすることができ、レビュワーはコードを見てレビューを行います。
以下のようにコメントで意見を交わしながら進めていくことができます。
![Screen Shot 2022-06-13 at 22 21 05](https://user-images.githubusercontent.com/66197642/173499302-0e7e5137-a559-4fdc-bcbf-bc2aacc00e97.png)

レビューの様子
![Screen Shot 2022-06-13 at 21 55 13](https://user-images.githubusercontent.com/66197642/173499335-b20b8228-e1f1-4007-bef4-1f358faec021.png)
![Screen Shot 2022-06-13 at 21 56 14](https://user-images.githubusercontent.com/66197642/173499352-dd2af9e1-a0b2-47a2-a861-0ed14b643af3.png)




参考リンク
- [PullRequestで提案された変更をレビューする](https://docs.github.com/ja/pull-requests/collaborating-with-pull-requests/reviewing-changes-in-pull-requests/reviewing-proposed-changes-in-a-pull-request)
- [複数行へのレビュー](https://qiita.com/YumaInaura/items/65d59adbce322567ef14)
- [マージコンフリクトを解決する](https://docs.github.com/ja/pull-requests/collaborating-with-pull-requests/addressing-merge-conflicts/resolving-a-merge-conflict-on-github)
- [特定のpull requestをローカルに持ってくる](https://qiita.com/tarr1124/items/d807887418671adbc46f)
- [PullRequestでマージしたのを打ち消す](https://saikeblog.com/2020/03/09/github%E3%81%A7pull-request%E3%81%AE%E3%83%9E%E3%83%BC%E3%82%B8%E3%82%92%E6%89%93%E3%81%A1%E6%B6%88%E3%81%99%E6%96%B9%E6%B3%95/)
