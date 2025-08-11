---
title: 蒲田チェスクラブ | 蒲田で初心者歓迎のチェスサークル
description: 蒲田チェスクラブは、蒲田駅近くで毎月金曜に活動する初心者歓迎のチェスサークルです。地域最大級のアットホームなクラブで、誰でも気軽にチェスを楽しめます。見学自由！
og_image: /ogp.jpg
---

<!doctype html>
<html lang="ja">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>{{ page.title }}</title>
  <meta name="description" content="{{ page.description }}">
  <meta property="og:title" content="{{ page.title }}">
  <meta property="og:description" content="{{ page.description }}">
  <meta property="og:type" content="website">
  <meta property="og:url" content="https://tsutayuki.github.io/kamata.chess.club/">
  {% if page.og_image %}<meta property="og:image" content="{{ page.og_image }}">{% endif %}
  <meta name="twitter:card" content="summary_large_image">
  <!-- 必要ならSearch Console確認用 -->
  <!-- <meta name="google-site-verification" content="XXXXX"> -->
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-white text-gray-800 font-sans">
  {% capture md %}
# 蒲田チェスクラブで対局しよう
毎月金曜日、誰でも参加OK

- 学生から社会人まで、初心者歓迎
- 参加費：1回500円
- 活動場所：新蒲田区民活動施設（JR蒲田駅西口徒歩7分）

## 🗓 活動予定
- **(💡次回) 8月22日（金）18:00〜22:00** @ 新蒲田区民活動施設  
- **9月12日（金）18:00〜22:00** @ 新蒲田区民活動施設

### 📍 アクセス
主な活動場所は「新蒲田区民活動施設（カムカム新蒲田）」2階。  
地図：  
<iframe width="100%" height="360" src="https://www.google.com/maps/embed?pb=!1m18!..."></iframe>

## ♟ チェスのルール解説動画
<iframe width="100%" height="400" src="https://www.youtube.com/embed/jX2H_A6teCY" title="チェスのルール解説1" frameborder="0" allowfullscreen></iframe>

## 📩 お問い合わせ
見学・質問はフォームへ：  
[Googleフォームを開く](https://docs.google.com/forms/d/1H5A2Gcat4hG5h4h7RaIVEuB17KGYdKOIeGYmRLx1zPw/edit)

## 👤 代表紹介
- 代表：donta  
- チェス歴15年／FIDE 1938／慶應卒／ITエンジニア

  {% endcapture %}
  {{ md | markdownify }}

  <footer class="bg-black text-white text-center py-6 mt-12">
    <p class="text-sm">© 2025 蒲田チェスクラブ</p>
    <p class="text-sm mt-2"><a href="https://x.com/kamata_chess" class="underline">X（旧Twitter）</a></p>
  </footer>
</body>
</html>
