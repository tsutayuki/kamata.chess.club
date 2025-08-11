<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>蒲田チェスクラブ | 蒲田で初心者歓迎のチェスサークル</title>
  <meta name="description" content="蒲田チェスクラブは、蒲田駅近くで毎月金曜に活動する初心者歓迎のチェスサークルです。地域最大級のアットホームなクラブで、誰でも気軽にチェスを楽しめます。見学自由！">
  <meta property="og:title" content="蒲田チェスクラブ｜初心者歓迎！" />
  <meta name="keywords" content="蒲田チェス, 蒲田チェスクラブ, チェス 大田区, チェスクラブ 初心者, Kamata Chess Club" />
  <meta property="og:description" content="蒲田駅近くで毎月活動中。誰でも参加OKのチェスクラブです。" />
  <meta property="og:image" content="https://tsutayuki.github.io/kamata.chess.club/ogp.jpg" />
  <meta property="og:url" content="https://tsutayuki.github.io/kamata.chess.club/" />
  <meta property="og:type" content="website" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="google-site-verification" content="qWTbGYtlpMc3IByDY8rByehlV5YYwZ8DpcqPtnNfhJw" />
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    @keyframes zoomIn {
      from { transform: scale(1); opacity: 0; }
      to { transform: scale(1.05); opacity: 1; }
    }
    .animate-zoom {
      animation: zoomIn 5s ease-out forwards;
    }
  </style>
</head>
<body class="bg-white text-gray-800 font-sans">

  <!-- Heroセクション -->
  <section class="relative h-screen w-full overflow-hidden">
    <img src="kamata.jpeg" 
         class="absolute inset-0 w-full h-full object-cover animate-zoom" 
         alt="蒲田チェスクラブの対局風景">
    <div class="absolute inset-0 bg-black bg-opacity-60"></div>
    <div class="relative z-10 h-full flex flex-col items-center justify-center text-center text-white px-6">
      <h1 class="text-4xl md:text-6xl font-bold mb-4 drop-shadow-lg">
        蒲田チェスクラブで対局しよう
      </h1>
      <p class="text-xl md:text-2xl mb-8">毎月金曜日、誰でも参加OK</p>
      <a href="#schedule" class="bg-white text-black px-6 py-3 rounded-full text-lg font-semibold hover:bg-gray-200 transition">
        次回の予定を見る
      </a>
    </div>
  </section>

  <!-- クラブ紹介 -->
  <section class="py-16 px-6 max-w-3xl mx-auto text-center" id="about">
    <h2 class="text-3xl font-bold mb-4">蒲田チェスクラブとは？</h2>
    <p class="text-lg mb-6">
      学生から社会人まで、誰でも気軽に参加できるチェスクラブです。<br/>
      毎月金曜日(1回500円)、大田区蒲田周辺で活動中。初心者大歓迎！<br/>
      楽しみながらチェスを学び、仲間と成長できます。
    </p>
    <p class="text-lg">📷 活動の様子は <a href="https://x.com/kamata_chess" class="text-blue-600 underline hover:text-blue-800">twitter(現X)</a> にて更新中！</p>
  </section>

  <!-- チェスルール動画紹介 -->
  <section class="py-16 px-6 max-w-3xl mx-auto text-center" id="rules">
    <h2 class="text-3xl font-bold mb-4">♟ チェスのルール解説動画</h2>
    <p class="text-lg mb-6">
      初心者向けに基本ルールがわかりやすく解説された動画です。<br/>
      (初心者向けチェス講師 上原先生の動画となります。)
    </p>
    
    <div class="w-full max-w-3xl mx-auto">
      <iframe width="100%" height="400"
              src="https://www.youtube.com/embed/jX2H_A6teCY"
              title="チェスのルール解説動画1"
              frameborder="0"
              allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
              allowfullscreen>
      </iframe>
    </div>

    <div class="w-full max-w-3xl mx-auto">
      <iframe width="100%" height="400"
              src="https://www.youtube.com/embed/Og_G1Ds8fk8?si=OwHpartDN8dVFTm3"
              title="チェスのルール解説動画2"
              frameborder="0"
              allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
              allowfullscreen>
      </iframe>
    </div>

    <div class="w-full max-w-3xl mx-auto">
      <iframe width="100%" height="400"
              src="https://www.youtube.com/embed/4bNOdDHYYL4?si=1TAfJ6rhQApYX1Dl"
              title="チェスのルール解説動画3"
              frameborder="0"
              allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
              allowfullscreen>
      </iframe>
    </div>
  </section>

  <!-- 活動予定 -->
  <section class="bg-gray-100 py-16 px-6" id="schedule">
    <div class="max-w-3xl mx-auto text-center">
      <h2 class="text-3xl font-bold mb-6">🗓 活動予定</h2>
      <ul class="text-lg space-y-4">
        <li>📅 <strong>(💡次回)8月22日（金）18:00〜22:00</strong> @ 新蒲田区民活動施設</li>
        <li>📅 <strong>9月12日（金）18:00〜22:00</strong> @ 新蒲田区民活動施設</li>
        <br>
        <h3 class="text-3xl mb-6">🗓 活動終了</h2>
        <li>📅 （終了）7月11日（金）18:00〜22:00 @ 新蒲田区民活動施設</li>
      </ul>
    </div>
  </section>
  
    <!-- アクセス -->
  <section class="bg-gray-100 py-16 px-6" id="access">
    <div class="max-w-3xl mx-auto text-center">
      <h2 class="text-3xl font-bold mb-6">📍 アクセス</h2>
        <p class="text-lg mb-6">
          主な活動場所は「新蒲田区民活動施設」(別名：カムカム新蒲田)です。<br/>
          JR蒲田駅西口より徒歩7分。建物の2階にあります。
        </p>

        <div class="w-full max-w-3xl mx-auto aspect-[4/3]">
          <iframe class="w-full h-full"
                  src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d6491.603638025585!2d139.70553071467847!3d35.558596390051086!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x601861fcba2c7001%3A0x8f9aa8ee2fbe011a!2z44Kr44Og44Kr44Og5paw6JKy55Sw!5e0!3m2!1sja!2sjp!4v1752248506546!5m2!1sja!2sjp"
                  frameborder="0">
          </iframe>
        </div>
      </div>
  </section>

  <!-- お問い合わせ -->
  <section class="py-16 px-6 max-w-3xl mx-auto text-center" id="contact">
    <h2 class="text-3xl font-bold mb-4">📩 お問い合わせ</h2>
    <p class="text-lg mb-6">見学希望・ご質問など、お気軽にどうぞ。</p>
    <a href="https://docs.google.com/forms/d/1H5A2Gcat4hG5h4h7RaIVEuB17KGYdKOIeGYmRLx1zPw/edit" target="_blank" class="inline-block bg-blue-600 text-white px-6 py-3 rounded-full font-semibold hover:bg-blue-700 transition">
      フォームを開く
    </a></section>

  <!-- 代表者紹介 -->
  <section class="py-16 px-6 max-w-3xl mx-auto text-center" id="leader">
    <h2 class="text-3xl font-bold mb-4">👤 代表紹介</h2>
    <div class="flex flex-col items-center space-y-4">
      <img src="leader.jpeg" alt="代表の写真" class="w-32 h-32 rounded-full shadow-md object-cover">
      <p class="text-xl font-semibold">donta</p>
      <p class="text-lg text-gray-700">
        蒲田チェスクラブ代表。<br/>
        チェス歴15年／FIDEレート1938。<br/>
        慶應義塾大学卒業。<br/>
        初心者から上級者まで楽しめるクラブ作りを目指しています。<br/>
        普段はITエンジニア。
      </p>
    </div>
  </section>

  <section class="py-16 px-6 max-w-3xl mx-auto text-center">
  <h2 class="text-3xl font-bold mb-4">💰 おすすめチェス商品</h2>
    <div class="max-w-md mx-auto text-center">
      <h2 class="text-2xl font-bold mb-4">ChessJapan 日本チェス連盟公認 チェスセット</h2>
      <a href="https://amzn.to/4luFS6S" target="_blank" rel="nofollow noopener noreferrer">
        <img src="chessset.jpg" alt="ChessJapan チェスセット" class="w-full h-auto rounded shadow-md mb-3" />
        <p class="text-lg font-semibold">購入する</p>
      </a>
      <p class="text-gray-600 text-sm mt-2">
        ChessJapanの日本チェス連盟公認チェスセットです。蒲田チェスクラブでも用いています。
      </p>
    </div>
    <br/><br/>
    <div class="max-w-md mx-auto text-center">
      <h2 class="text-2xl font-bold mb-4">チェスクロック Basicest製</h2>
      <a href="https://amzn.to/40RdAef" target="_blank" rel="nofollow noopener noreferrer">
        <img src="chessclock.jpg" alt="ChessClock チェスクロック" class="w-full h-auto rounded shadow-md mb-3" />
        <p class="text-lg font-semibold">購入する</p>
      </a>
      <p class="text-gray-600 text-sm mt-2">
        チェスクロックです。蒲田チェスクラブでも用いています。
      </p>
    </div>
</section>

  <!-- フッター -->
  <footer class="bg-black text-white text-center py-6">
    <p class="text-sm">© 2025 蒲田チェスクラブ</p>
    <p class="text-sm mt-2">
      <a href="https://x.com/kamata_chess" class="underline hover:text-gray-300 mx-2">twitter(現X)</a>
    </p>
  </footer>

</body>
</html>
