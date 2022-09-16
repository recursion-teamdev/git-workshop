# Git ワークショップについて

## Updated: 06/10/22

## 概要

Gitワークショップは、チーム開発経験のない初級〜中級ユーザ向けのイベントです。
3 人 1 チームで Git/GitHub を使い、メンバー同士協力して課題に取り組みます。

---

## 目的

- Recursionユーザ内で知り合いを作る
- 今後のイベント参加障壁を下げる
- チーム開発の雰囲気を掴む

---

## 全体の流れ

1. 個人でgit学習
2. 全体で集まってワークショップ
3. チームで課題制作

**日程はRecursionのDiscordチャンネルにてアナウンスされます**

---


<!-- TABLE OF CONTENTS -->
目次
=================
 <ol>
  <li>
   <a href="#個人でgit学習">個人でgit学習</a>
  </li>
  <li>
    <a href="#Gitワークショップ">Gitワークショップ</a>
    <ul>
      <li><a href="#チーム開発でよく使用する主なコマンド一覧">チーム開発でよく使用する主なコマンド一覧</a></li>
      <li><a href="#その他のリンク">その他のリンク</a></li>
    </ul>
  </li>
  <li>
   <a href="#チームで課題制作">チームで課題制作</a>
   <ul>
      <li><a href="#課題１">課題１</a></li>
      <li><a href="#課題２">課題２</a></li>
    </ul>
  </li>
  <li>
   <a href="#おすすめアプリの紹介">おすすめアプリの紹介</a>
  </li>
 </ol>
 
  

## 個人でgit学習

ワークショップの当日、よりスムーズに進行していくためにも、はじめの1週間は個人でgit/githubの学習を進めてください。

期間：1週間

### ワークショップ当日までにやっておくこと

- RecursionのGitコース（YoutubeにあるLinuxのコースも含む）
- 基本的な操作の流れをこちらの[スライド](https://docs.google.com/presentation/d/1byfV5jM5MlYI55e5HFVEpvCevFODyYHcDJrqYTYodcs/edit#slide=id.gc6f73a04f_0_0)で確認してください。

余裕があれば以下のサイトでも復習しておきましょう。

### 参考サイト

- イラストでわかるgitの入門[イラストでわかる！git入門の入門](http://blog.asial.co.jp/894)
- バージョン管理システムの概念について[VCS入門](https://github.com/masaru-b-cl/introduction-to-vcs)
- GitHub内で実際にBotとやりとりをしながら学習できる[GitHub Learning Lab](https://lab.github.com/)
- 復習として読むと理解を深められる[サル先生のGit入門](https://backlog.com/ja/git-tutorial/)
- ブランチの使い方について学習できる[Learning Git Branching](http://k.swd.cc/learnGitBranching-ja/)
- Git book [Git-Book](http://git-scm.com/book/ja/v2)
- スライドで眺めるにはちょうどいい [Git講義](https://kaityo256.github.io/github/)

---

## Gitワークショップ

Recursionの[自習室](https://recursion.ovice.in/)にて2時間ほどチームでgitの操作について学びます


### チーム開発でよく使用する主なコマンド一覧

|                                         | 用途                 |
|-----------------------|-----------------------|
|git clone {url}                          |	リモートからローカルにコピー    | 
|git add .	                              |                         |
|git commit 	                            |                         |
|git push	                                |                         |
|git switch	                              | ブランチ切り替え            |
|git switch -c	                          | ブランチ作成&切り替え        |
|git pull origin develop --rebase	        | ブランチを最新の状態にする    | 

`--rebase`ってしているのは `git pull` をしたときに不要なコミットを防ぐためです。

### その他のリンク

- [コミットメッセージの書き方について](https://qiita.com/konatsu_p/items/dfe199ebe3a7d2010b3e)
- [プルリクエストの作成方法
](https://docs.github.com/ja/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request)
- [Pull Request レビューをリクエストする
](https://docs.github.com/ja/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/requesting-a-pull-request-review)
- [チーム開発におけるプルリクの作法](https://qiita.com/ikuwow/items/fb52a54c086398eb5b92)
- [質問の仕方](https://qiita.com/seki_uk/items/4001423b3cd3db0dada7)


---

## チームで課題制作

期間：1週間

- ワークショップの後にチームで取り組む課題について説明します。課題は次の 3 つから好きなものを選んでもらいます

Motivational Speech Wallpaper
---

要件：格言や画像は著作権を侵害しない限り好きなものを使ってよい
- レベル 1：HTML/CSS だけで作成し、アニメーションはなし
- レベル 2：HTML/CSS だけで作成。見本のようなアニメーションを入れる
- レベル 3：JavaScript を使って見本どおりに作成
- 見本は 3 種類ですが、時間があればもっと制作しても構いません。


ソフトウェア開発みくじ 
---

要件：トップページのボタンをクリックすると各おみくじがランダムで表示される。文言や画像は著作権を侵害しない限り好きなものを使ってよい
- レベル 1：大吉や中吉などの各おみくじのページを HTML/CSS で作成
- レベル 2：大吉や中吉などの各おみくじのページのオリジナル版を HTML/CSS で作成
- レベル 3：JavaScript を使って見本どおりに作成
なお、おみくじは大吉、吉、中吉、小吉、末吉、凶の 6 種類です。もちろん、何種類作っても OK です。

Cafe Recursion Home Page 
---

要件：トップページにスライダーアニメーションを配置する。文言や画像は著作権を侵害しない限り好きなものを使い、自由にレイアウトしてよい。メニューの数なども自由でよい。
- レベル 1：スライダーなしで作成
- レベル 2：見本どおりに作成
- レベル 3：見本にはないメニューのページやリンクなども作成
余裕のあるチームは見本にこだわらず自由に改造して構いません。


---

## おすすめアプリの紹介

- 通知の見逃しを防止する
[Gitify](https://www.gitify.io/)
[使い方](https://bake0937.hatenablog.com/entry/2019/10/20/160626)


 ***質問等ある方は各チームのグループチャットに送っていただけると助かります***
