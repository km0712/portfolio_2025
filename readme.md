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
|<video  src="https://github.com/user-attachments/assets/cb0f4673-5e31-4f3e-9cb5-bcb6a46c14d2">  |


記事閲覧  
<video src="https://github.com/user-attachments/assets/c4cc2fe3-bfea-401a-8b46-5ec0331e46fa">  |



長押しでメニュー表示、サーバにある記事検索  
<video src="https://github.com/user-attachments/assets/4a99bc83-d880-4e71-9fbf-1aa854aac3d7"> |


ブックマーク、履歴、サーバに保存されているRSS検索  
<video src="https://github.com/user-attachments/assets/9909d473-f658-465f-aa40-b8f35b03c998">|
