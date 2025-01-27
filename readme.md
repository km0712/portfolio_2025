以下、個人で制作したアプリの簡単な説明です。
# ニュース取得RSSリーダーアプリ
個人開発で制作したものの一つです。1ヶ月半ほどで環境構築からプロトタイプ完成。

## 主な機能・実装について
バックエンド
・バックエンド側でRSSから記事を定期的に取得、DBに保存  
・RSSのリスト機能   
・自然言語処理を使ったトレンド生成  
・RSSや記事へのタグづけ、カテゴリー分けの自動化


IOSフロントエンド
・RSSの登録、サーバにあるRSS・記事の検索やソートして取得  
・記事に対してコメント投稿  
・ブックマーク  
・RSSのTwitterライクなリスト  
・話題の単語をバックエンドで解析→表示・検索、ブラウザ  
・ローカルのRealmDBへのCRUDの処理など  

WEBフロントエンド  
・RSS閲覧機能  
・Next.js (App Router)  






## 言語・技術
・フロントエンド　→ ReactNative,TypeScript,RealmDB,SWR,UI Kitten,Redux,Native Module　　

・バックエンド　→ Django(REST framework),MySQL,Nginx,uWSGI,cron,Supabase,Linux(Ubuntu)
※基本的にサーバはVPSで構築,一部機能をSupabaseで実装






## 参考動画(画質荒目ですが)
RSSで取得した記事閲覧,RSS新規登録  
|<video  src="https://github.com/km0712/portfolio_2024/assets/82639564/0fc9e93d-0d25-4f07-b0ea-be4661982a72">  |


記事閲覧  
<video src="https://github.com/km0712/portfolio_2024/assets/82639564/e80e14c5-c77d-4877-a42b-7fd16e847fd0">  |



長押しでメニュー表示、サーバにある記事検索  
<video src="https://github.com/km0712/portfolio_2024/assets/82639564/2853cf44-8d4d-421d-b274-b2114e2392ad"> |


ブックマーク、履歴、サーバに保存されているRSS検索  
<video src="https://github.com/user-attachments/assets/98903061-56df-405e-ad80-3843b72fb294">|
