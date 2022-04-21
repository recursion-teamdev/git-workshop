# Git ワークショップについて

## Updated: 04/21/22

## 概要

Gitワークショップは、チーム開発経験のない初級〜中級ユーザ向けのイベントです。
3 人 1 チームで Git/GitHub を使い、メンバー同士協力して課題に取り組みます。

## 目的

- Recursionユーザ内で知り合いを作る
- 今後のイベント参加障壁を下げる
- チーム開発の雰囲気を掴む

## 全体の流れ

1. 個人でgit学習
2. 全体で集まってワークショップ
3. チームで課題制作

**日程はRecursionのDiscordチャンネルにてアナウンスされます**


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


## Gitワークショップ

Recursionの[自習室](https://recursion.ovice.in/)にて2時間ほどチームでgitの操作について学びます

**以下のリンクやコマンドはワークショップの当日も改めて説明しますので目を通しておくだけで大丈夫です**


### チーム開発でよく使用する主なコマンド一覧

|                                         | 用途                 |
|-----------------------|-----------------------|
|git clone {url}                          |	リモートからローカルにコピー    | 
|git add .	                              |                         |
|git commit 	                            |                         |
|git push	                                |                         |
|git switch	                              | ブランチ切り替え            |
|git switch -c	                          | ブランチ作成&切り替え        |
|git checkout {branch}                    | ブランチ切り替え            |
|git checkout -b {branch}                 |	ブランチ作成&切り替え        |
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


<p align="right">(<a href="#top">back to top</a>)</p>


## チームで課題制作

期間：1週間


課題の詳細についてはGitワークショップの当日にもお伝えいたします。

### 課題１

ワークショップの後にチームで取り組む課題について説明します。課題は次の 3 つから好きなものを選んでもらいます
1. Motivational Speech Wallpaper
 - レベル 1：HTML/CSS だけで作成し、アニメーションはなし。
 - レベル 2：JavaScript を使って作成

2. ソフトウェア開発みくじ 
 - レベル 1：大吉や中吉などの各おみくじのページを HTML/CSS で作成
 - レベル 2：大吉や中吉などの各おみくじのページのオリジナル版を HTML/CSS で作成
 - レベル 3：JavaScript を使ってアニメーション付きで作成

3. Cafe Recursion Home Page 
 - レベル 1：スライダーなしで作成
 - レベル 2：スライダーありで作成
 - レベル 3：メニューのページやリンク、その他にも機能を追加して作成


### 課題２

今回はできるだけGitHubを使用して開発を進めましょう。上記の課題１に加え、Git操作に関する課題もあります。

各チームメンバーが最低でも１回は以下の課題に取り組む
- イシューを作成する
- プルリクエストを出す
- 他のメンバーのコードレビューを行う

<p align="right">(<a href="#top">back to top</a>)</p>

### issueのルール（前回参加したメンバーが実際にチームメンバー間で共有していた内容です）

![Screen Shot 2022-04-21 at 12 27 59](https://user-images.githubusercontent.com/66197642/164538247-7f962a4a-326e-426c-9e53-c693f85be543.png)


<p align="right">(<a href="#top">back to top</a>)</p>



## おすすめアプリの紹介

- 通知の見逃しを防止する
[Gitify](https://www.gitify.io/)
[使い方](https://bake0937.hatenablog.com/entry/2019/10/20/160626)


 ***質問等ある方は各チームのグループチャットに送っていただけると助かります***
