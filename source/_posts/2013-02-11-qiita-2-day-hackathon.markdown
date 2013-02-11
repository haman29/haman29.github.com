---
layout: post
title: "Qiita 2-day Hackathon に参加しました"
date: 2013-02-11 17:56
comments: true
categories: [hackathon, programming]
---

先週の土日まるっとハッカソンイベントがあったので参加してきました．

ちょっと遅くなりましたが，作ったプロダクトの紹介と思うことを書きます．

-----------------

### 概要 && 作品

* [スペシャルゲストも登場して盛り上がったQiita 2-day Hackathon総まとめ！ - The Official Qiita Blog](http://blog.qiita.com/post/42345394076/qiita-2-day-hackathon-report)

* [Qiita 2-day Hackathon で発表されたプロダクト全41作品総レビュー！ - The Official Qiita Blog](http://blog.qiita.com/post/42473838977/github-api-hackathon-products)

概要や他の作品は，主催者のQiitaさんがよくまとめてくれているので割愛します．

-----------------

### 作ったもの
### GitChat [https://gitchat.herokuapp.com/](https://gitchat.herokuapp.com/)

* Github認証のチャット
    * プラットフォームはweb
    * リアルタイム
    * マルチユーザ
    * 部屋を自由に作れる

-----------------

### 使ったもの

* Hosting
    * Heroku
* Framework
    * Ruby on Rails 3.2.11
    * Twitter Bootstrap
* Web Server
    * thin
    * private_pub (for chat)
* Database
    * PostgreSQL

-----------------

### なぜ作ったか

* 技術者と気軽に交流できる場が欲しかったからです．
* 今あるチャットって完全に匿名か，プライベートな空間でばかり活発なイメージがあって，もっとパブリックな場があっても良いんじゃないかなと思い，ないなら作ってしまおう！となったわけです．
* とはいえ，まだ技術者が気軽に交流できる場にはなっていません．使い勝手が非常に悪いです．
* ちょっとずつ改修して，もっとたくさんの人の使ってもらえる場にしたいです．

-----------------

### 思うこと

* 初めてのハッカソン，初めてのRails，初めてのHeroku，初めてのGithub API... と初めてのことだらけでしたが，動くものが作れて良かったです．(ただ，それをデモで見せれなかったのは良くなかった..)
* 課題の残るハッカソンでしたが，次にこの経験を生かせるようにしたいです．
* 次はチーム開発したいなあ...

-----------------

そういえば，ブログを移行して [Octopress](http://octopress.org/) にしました．非常に具合が良いです．
