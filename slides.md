---
marp: true
theme: custom
class: lead
paginate: true
style: |
  section {
    font-size: 1.4em;
  }
  h1 {
    font-size: 2.4em;
  }
  h2 {
    font-size: 1.8em;
  }
---

<!---
_class: title
--->
### ChatGPT × Marp
<br>
<br>
<br>

> # 📱 スマホだけでLT資料をつくる！  
> ## ツールインストール不要・5分でスライド作成

<br>
<br>
<br>
Makoto Shirai

---

<!-- _header: ChatGPT × Marp -->
# はじめに
<!-- footer: スマホで完結するLT資料づくり -->

- 話したいことがあっても、LT資料って作るのは**地味に時間がかかる…**
- デザインも考えると**結構めんどくさいから、登壇も避けがちになる**
- でも、**ChatGPT**があれば  
  👉 テキストからスライドの「**下地**」を自動で作れる！

## 📝 “考える時間”を増やして、“作業”を減らそう！

---

<!-- _header: ChatGPT × Marp -->
# 🧠 Step 1  
## ChatGPTでテキストを作成
<!-- footer: スマホで完結するLT資料づくり -->

- プロンプトを工夫して構成を自動化  
- **Marp形式（Markdown）** で出力させる
- Markdown形式で受け取る ✨
![bg right:33% width:70%](https://upload.wikimedia.org/wikipedia/commons/0/04/ChatGPT_logo.svg)

---

<!-- _header: ChatGPT × Marp -->
## 🪄 プロンプト例
<!-- footer: スマホで完結するLT資料づくり -->
```
次のテーマでLT用のスライド原稿を  
Marp形式（Markdown）で出力して。

- テーマ：ChatGPTを使った資料作成  
- ページ数：5枚  
- 背景：黒  
- シンプル＆プレゼン映えする構成で！
```

なんなら以下でもOK

```
「ChatGPTを使った資料作成」をテーマにLT用のスライド原稿を  
Marp形式（Markdown）で出力して。
```

![bg right:33% width:70%](https://upload.wikimedia.org/wikipedia/commons/0/04/ChatGPT_logo.svg)

---

<!-- _header: ChatGPT × Marp -->
## 📄 出力イメージ（サンプル）
<!-- footer: スマホで完結するLT資料づくり -->

```markdown
---
marp: true
theme: default
---

# ChatGPTでスライドをつくる
## 〜 Marpでスマホ完結 〜

---

<!-- _header: ChatGPT × Marp -->
## Step 1
<!-- footer: スマホで完結するLT資料づくり -->

- ChatGPTで Marp 形式を出力
- Markdownをコピペするだけ！
```

✅ こういう形式で出力されるから
すぐに marpwebeditor.app にコピペして使える📲 

![bg right:33% width:70%](https://marp.app/assets/marp.svg)

---

<!-- _header: ChatGPT × Marp -->
# 🌐 Step 2  
## [marpwebeditor.app](https://marpwebeditor.app/) を開く
<!-- footer: スマホで完結するLT資料づくり -->

1. スマホのブラウザでアクセス  
2. コピーしたMarkdownをペースト  
3. 自動でスライドに変換される！
![bg right:33% width:70%](https://marpwebeditor.app/favicon.ico)

---

<!-- _header: ChatGPT × Marp -->
# 🧑‍💻 Step 3  
## デザインを少し盛る！(任意)
<!-- footer: スマホで完結するLT資料づくり -->

- 背景色や絵文字で印象アップ✨
　- シンプルな黒背景でも十分映える  
- **Markdownだけで簡単にデザイン可能！**

### 💡 Markdownでできるデザイン例

- 見出しや箇条書きに絵文字を追加  
```markdown
# 🚀 タイトル
- ✅ 重要ポイント
- 🔹 サブポイント
```
![bg right:33% width:70%](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)

---

<!-- _header: ChatGPT × Marp -->
# 🪄 Step 4  
## プレビュー＆発表！
<!-- footer: スマホで完結するLT資料づくり -->

- 左メニューの「Export」ボタンをクリック  
- **HTML** を選択して保存  
- 保存した HTML をブラウザで開けば **発表用スライド** に！

![bg right:33% width:70%](https://upload.wikimedia.org/wikipedia/commons/6/61/HTML5_logo_and_wordmark.svg)

---

<!-- _header: ChatGPT × Marp -->
# 🎤 まとめ
<!-- footer: スマホで完結するLT資料づくり -->

- ✅ ChatGPTでテキスト作成  
- ✅ Marp Web Editorで即スライド  
- ✅ スマホだけで完結！

## 👉 今日からあなたも、即席LT職人✨

---

<!-- _header: ChatGPT × Marp -->
# 📎 Appendix
<!-- footer: スマホで完結するLT資料づくり -->

---

<!-- _header: ChatGPT × Marp -->
## demo用プロンプト
<!-- footer: スマホで完結するLT資料づくり -->

```
「未経験者に向けて競馬の魅力を伝える」をテーマにLT用のスライド原稿を  
Marp形式（Markdown）で出力して。
ギャンブルとしてだけじゃなくて、ブラッドスポーツとしての魅力も語りたい。
```

---

<!-- _header: ChatGPT × Marp -->
## スライドをGitHub Pagesで公開する
<!-- footer: スマホで完結するLT資料づくり -->
![bg right:29% width:70%](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

1. **MarpでHTMLをエクスポート**  
   - 左メニューの「Export」→「HTML」を選択  
   - 例: `my-slide.html` を保存

2. **GitHubにリポジトリを作成**  
   - 名前例: `my-lt-slide`  
   - **Public** に設定すると誰でも閲覧可能

3. **HTMLファイルをリポジトリに追加 & Commit**  
   - GitHub Web UI でも可  
   - `my-slide.html` をアップロード

---

<!-- _header: ChatGPT × Marp -->
<!-- footer: スマホで完結するLT資料づくり -->
![bg right:29% width:70%](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

4. **GitHub Pagesを有効化**  
   - リポジトリの Settings → Pages  
   - `main` ブランチ / `/root` を選択して保存

5. **URLを確認**  
   - 例: `https://username.github.io/my-lt-slide/my-slide.html`  
   - このURLを共有すればスライドを誰でも閲覧可能📱💻

### 💡 補足ポイント
- 画像もスライドに含める場合は **相対パス** で同じリポジトリに置く  
- 更新したら再度HTMLをアップロードして Commit すれば公開内容も更新される  
- GitHub Pagesは無料で利用できるので、LT資料の簡易共有に最適✨
