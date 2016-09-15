web-mode.el [![Donate](https://www.paypalobjects.com/en_US/i/btn/btn_donate_SM.gif)](http://web-mode.org) 
=========

web-mode.el is an emacs major mode for editing **web templates** aka HTML files embedding parts (CSS/JavaScript) and blocks (pre rendered by client/server side engines).

web-mode.el is compatible with many template engines: PHP, JSP, ASP, Django, Twig, Jinja, Mustache, ERB, FreeMarker, Velocity, Cheetah, Smarty, CTemplate, Mustache, Blade, ErlyDTL, Go Template, Dust.js, Google Closure (soy), React/JSX, Angularjs, ejs, etc.

More infos on http://web-mode.org/

![ScreenShot](http://web-mode.org/web-mode.png?v=5)

[![MELPA](http://melpa.org/packages/web-mode-badge.svg)](http://melpa.org/#/web-mode)

[![MELPA Stable](http://stable.melpa.org/packages/web-mode-badge.svg)](http://stable.melpa.org/#/web-mode)


---------------------------------
Generalなキーアサイン
---------------------------------
  キー	          機能
C-c C-;	コメント/アンコメント
C-c C-e	閉じていないタグを見つける
C-c C-f	指定したタグのブロックを開閉する
C-c C-i	現在開いているバッファをインデントする
C-c C-m	マークする(マークする場所によって選択範囲が変わります)
C-c C-n	開始・終了タグまでジャンプ
C-c C-r	HTML entitiesをリプレースする
C-c C-s	スニペットを挿入
C-c C-w	スペースを表示・非表示

---------------------------------
HTML element系のキーアサイン
---------------------------------
  キー	          機能
C-c /	    閉じタグを挿入(エレメントを閉じる)
C-c eb	    エレメントの最初へ移動
C-c ed	    エレメントを削除
C-c ee	    エレメントの最後へ移動
C-c ee      エレメントを複製
C-c en      次のエレメントへ移動
C-c ep      前のエレメントへ移動
C-c eu      親エレメントへ移動
C-c er      エレメントをリネーム
C-c es      エレメント全体を選択
C-c ei      エレメントのコンテンツを選択

---------------------------------
HTML tag系のキーアサイン
---------------------------------
  キー	          機能
C-c tb	    タグの先頭へ移動(エレメントの先頭では無くタグの先頭です。
           </div>で実行した場合は</div>タグの先頭(<)に移動します)
C-c te	   タグの後尾へ移動
C-c tm	   マッチするタグへ移動
C-c ts	   タグを選択
C-c tp	   前のタグに移動
C-c tn	   次のタグに移動