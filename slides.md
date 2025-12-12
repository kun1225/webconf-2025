---
# Global
theme: ../styles

fonts:
  sans: Noto Sans TC
  serif: GenRyuMin2TW
  mono: Fira Code
  sansation: 'Sansation'
  antonio: 'Antonio'

# some information about your slides (markdown enabled)
title: React 效能優化實戰工作坊
titleTemplate: '%s | ThisWeb'
author: ThisWeb

browserExporter: dev
download: false

lineNumbers: true

transition: blur-in
default:
  layout: section

mdc: true
selectable: true

colorSchema: light

drawings:
  persist: false

seoMeta:
  ogTitle: ThisWeb - React 效能優化實戰工作坊
  ogDescription: 3 小時掌握 React 進階技術 x 底層思維
  ogImage: /og-img.png
  ogUrl: https://thisweb.dev
  twitterTitle: ThisWeb - React 效能優化實戰工作坊
  twitterDescription: 3 小時掌握 React 進階技術 x 底層思維
  twitterImage: /og-img.png
  twitterUrl: https://thisweb.dev

layout: cover
---

<p class="text-xl !mb-12 text-[var(--mute)]">ThisWeb 請網這邊走</p>

<h1 class="shadow font-white font-serif">
React 優化實戰分析
</h1>

## 掌握 React 進階技術 x 底層思維

<!--
大家好，先感謝大家來聽我的演講。

今天的主題是有關於 React 的效能優化。我會著重在 React 本身，要怎麼寫好 React，讓程式碼更好維護，以及避免 Re-render 的問題。

那今天的演講呢，是預設你有一定的 React 基礎，包括你知道什麼是 useState 狀態、useEffect 副作用、useMemo、useCallback 等等 Hooks。

那會展示蠻多的程式碼的，因為這個場地比我想的還長，所以希望大家可以稍微往前坐一點，會看得比較清楚。

那這邊先調查一下，平常是寫 React 的可以幫我舉一下手嗎？

哦幾乎都是，但還是有人可能平常不是寫 React 的。如果我中間有講太快的地方，或是有沒跟上地方，最後會留一點時間做 QA，所以也不用擔心。
-->

---
src: ./pages/menu.md
---

---
layout: center
---

<div class="card w-full h-full flex flex-col ">
  <p class="mt-0! text-left text-sm ">
  <span class="shadow">
  插播一下ＸＤ
  </span>
  <br/>
  如果你目前是前端工程師，想提升自己但沒有麼方向，我有一場免費的講座，會帶著大家規劃明年度的目標，也會分享現在 AI 發展之下，工程師應該優先培養哪些能力，可以掃 QR code 免費報名～！</p>
  <img src="/promote-qrcode.png" class="block w-6/8 mx-auto aspect-16/9 object-contain rounded-[4px] shadow-xl shadow-black/60" />
</div>

---

# ThisWeb - Kun

經營 ThisWeb 有 3 年、寫過超過 200 篇的技術教學、分享前端相關的技術、經驗。

<v-click>
目的是希望讓大家在軟體這條路可以走得更遠、變得更強
</v-click>

<HStack class="h-7/10 overflow-hidden !gap-16 mt-4">
  <div>
    <img src="/thisweb-ig.png" />
  </div>
  <div>
    <img src="/thisweb-threads.png" />
  </div>
  <div>
    <img src="/thisweb-site.png" />
  </div>
</HStack>

<!--
那在開始之前，我先簡單自我介紹一下，我是 ThisWeb 的創辦人 Kun，之前在一間外商新創公司擔任前端工程師。

經營 ThisWeb 有 3 年了，寫過 200 多篇的技術教學，這幾年也諮詢超過 50 位學員，主要分享前端相關的技術、經驗，也開始慢慢往後端分享

[click]
目的是希望讓大家在軟體這條路可以走得更遠變得更強

下面是我的 IG

Threads

和部落格，會定期分享和網頁技術和職涯有關的內容，所以有興趣的可以先追蹤一下。

那我們廢話不多說，就來開始今天的主題吧！
-->

---
src: ./pages/ch-5-1.md
---

---
src: ./pages/ch-5-2.md
---

---
src: ./pages/ch-5-3.md
---

---
src: ./pages/ch-5-4.md
---

---
src: ./pages/ch-5-5.md
---

---
src: ./pages/ch-5-6.md
---

---
src: ./pages/ch-5-7.md
---

---
src: ./pages/end.md
---
