# ChatGPT Answer Done Notifier

ChatGPT の回答が終わったタイミングをお知らせしてくれる Userscript です。

* 回答が終わると、短いビープ音が 1 回鳴る
* タブが裏にあるときはデスクトップ通知が表示される
* タブのアイコン（ファビコン）に緑色の ● がつく

ChatGPT を別タブに置いたまま作業しているときでも、「返事ができたタイミング」に気付きやすくなります。

---

## インストール

1. ブラウザに Userscript マネージャ（Tampermonkey / Violentmonkey など）をインストールする


   ```
   
2. 以下のリンクをクリック

   👉 [インストールはこちら](https://github.com/scarecrowx913x/ChatGPT-Answer-Done-Notifier/raw/main/ChatGPT-Answer-Done-Notifier.user.js)
       (https://github.com/scarecrowx913x/ChatGPT-Answer-Done-Notifier/raw/main/ChatGPT-Answer-Done-Notifier.user.js)



   ```

3. Userscript マネージャのインストール画面が出るので、「インストール」を選ぶ

---


## 使い方

1. ChatGPT（`https://chatgpt.com` または `https://chat.openai.com`）を普段どおりに開く
2. プロンプトを送って、別タブでほかの作業をする
3. 回答が終わると

   * ブラウザ内でビープ音が 1 回鳴る
   * タブが裏にある場合は、デスクトップ通知と緑色の ● ファビコンで知らせてくれる
4. ChatGPT のタブに戻ると、ファビコンは自動的に元のアイコンに戻る

---

## 通知の ON/OFF

Userscript マネージャ（Tampermonkey など）の拡張機能アイコンから、このスクリプトのメニューを開くと

* `通知機能のON/OFFを切り替える`

という項目が表示されます。
ここから通知全体を一括で ON / OFF できます。
状態はブラウザ側に保存され、ページを閉じても保持されます。

---

## トラブルシュート

### 音が鳴らない場合

* ブラウザやタブがミュートになっていないか確認してください。
* 一部のブラウザでは、ユーザー操作（クリックなど）の前は音声再生がブロックされる場合があります。

### 通知が表示されない場合

* OS やブラウザの通知設定を確認してください。
* 最初の一回は Notification 権限の許可ダイアログが出るので、「許可」を選択してください。

### ファビコンが戻らない場合

* タブを再読み込みすると初期状態に戻ります。

---

## ライセンス

MIT License
