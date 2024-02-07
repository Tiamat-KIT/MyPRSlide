---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://img.freepik.com/free-vector/blue-copy-space-digital-background_23-2148821698.jpg?w=1380&t=st=1707286817~exp=1707287417~hmac=51a7c27635df6785cad2e4a615383763d6bd0bbe73b8a2de04b266a4ece6d44e
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# persist drawings in exports and build
drawings:
  persist: false
# use UnoCSS (experimental)
css: unocss
---

# Self PR Slide 

天羽大樹ってどんな人？

<div class="text-gray">
  背景画像著作者：
  <a href="https://jp.freepik.com/free-vector/blue-copy-space-digital-background_12067358.htm#query=%E9%9D%92%E3%81%84%E5%A3%81%E7%B4%99&position=0&from_view=keyword&track=sph&uuid=23a178ee-d3cc-4d4c-af45-7b573662feff" class="text-gray">Freepik</a>
</div>

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://github.com/slidevjs/slidev" target="_blank" alt="GitHub"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---

# スキル情報

- 📝 **主に扱うプログラミング言語** - Python,TypeScript,Rust
- 🎨 **興味のある分野** - フロントエンド開発、フルスタック開発
- 🧑‍💻 **チームでの開発経験** -ハッカソンや授業内でチーム内の開発活動をマネジメントした経験アリ
- 🤹 **研究している内容** - WebAssembly(Rust),Reactで高速描画WebAR開発
- 📤 **課外プロジェクトでの活動** - 「Tourism」という学内非公式プロジェクトで後輩の成果物開発支援
- 🎥 **プログラミング以外のスキル** - Canvaでのスライド作成、Aviutilでの動画作成



<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---

# プログラミング言語の選定について

## 主な理由
- **型安全**：型定義が厳密に定義できることによる安全性が見込める
- **書いた後の見やすさ**：ブロック内に内容を記述できるタイプの言語であるかどうか
- **その言語でのみできることがあるか**：開発したいものがその言語だからこそできるものであるかどうか


---

# 興味のある分野について学んできたこと

## フロントエンド開発
- **React,Vue.js,Solid.js**の学習：
## フルスタック開発
- **Next.js,Solid.js**の学習：
- **Firebase,Supabase,Convex**の学習：
- **microCMS,Newt**の学習：

---

# チームでの開発経験

---

# 研究している内容の詳細
## 概要
WebAssembly(Rust),Reactで高速描画WebAR開発
## 開発言語
Rust,WebAssembly,TypeScript
## 使用ライブラリ
- 画像処理：Photon
- AIモデル活用：ORT
- 基本的なDOM操作：React
- ARコンテンツ操作：未定（A-Frame,AR.js,Mind-AR）
---

# プログラミング以外のスキルについての詳細
### Canvaを扱ったスライド作成
### Aviutilを扱った動画作成

---

# 課外プロジェクトでの活動概要