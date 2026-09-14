<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <title>紫句守鉄道 - しのもり鉄道</title>
  <style>
    body {
      margin: 0;
      font-family: system-ui, sans-serif;
      background: #f5f3ff;
      color: #222;
    }

    /* ヘッダー */
    header {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 8px 12px;
      background: #5b3ea8;
      color: #fff;
    }

    .menu-btn {
      font-size: 24px;
      cursor: pointer;
      user-select: none;
    }

    .title {
      font-size: 16px;
      font-weight: bold;
    }

    /* サイドメニュー */
    .side-menu {
      position: fixed;
      top: 0;
      left: -240px;
      width: 240px;
      height: 100vh;
      background: #2f2258;
      color: #fff;
      transition: left 0.25s;
      padding-top: 48px;
      box-shadow: 2px 0 8px rgba(0,0,0,0.3);
      z-index: 10;
    }

    .side-menu.open {
      left: 0;
    }

    .side-menu h2 {
      margin: 0 16px 8px;
      font-size: 14px;
      opacity: 0.8;
    }

    .side-menu ul {
      list-style: none;
      padding: 0;
      margin: 0;
    }

    .side-menu li {
      padding: 10px 16px;
      cursor: pointer;
      font-size: 14px;
    }

    .side-menu li:hover {
      background: rgba(255,255,255,0.1);
    }

    /* メインコンテンツ */
    main {
      padding: 12px;
    }

    .page {
      display: none;
    }

    .page.active {
      display: block;
    }

    h1 {
      font-size: 20px;
      margin-bottom: 8px;
    }

    h2 {
      font-size: 16px;
      margin-top: 16px;
      margin-bottom: 4px;
    }

    .section {
      margin-bottom: 12px;
      padding: 8px;
      background: #ffffff;
      border-radius: 6px;
      box-shadow: 0 1px 3px rgba(0,0,0,0.08);
      font-size: 13px;
    }

    .mono {
      font-family: "SF Mono", Menlo, monospace;
      font-size: 12px;
      white-space: pre-wrap;
    }
  </style>
</head>
<body>

  <!-- ヘッダー -->
  <header>
    <div class="menu-btn" id="menuBtn">☰</div>
    <div class="title" id="pageTitle">会社について</div>
    <div></div>
  </header>

  <!-- サイドメニュー -->
  <nav class="side-menu" id="sideMenu">
    <h2>紫句守鉄道 メニュー</h2>
    <ul>
      <li data-page="about">会社について</li>
      <li data-page="map">路線図</li>
      <li data-page="timetable">時刻表</li>
      <li data-page="position">走行位置</li>
      <li data-page="traininfo">列車情報</li>
      <li data-page="trainadd">列車追加</li>
      <li data-page="diagram">ダイヤ表</li>
      <li data-page="settings">設定</li>
    </ul>
  </nav>

  <!-- メインコンテンツ -->
  <main>
    <!-- 会社について -->
    <section class="page active" id="page-about">
      <h1>会社について</h1>
      <div class="section">
        <p>社名：紫句守鉄道（しのもり鉄道）</p>
        <p>本社所在地：紫句守中央駅周辺</p>
        <p>路線：紫雲本線・句守支線・紫霞観光線・星句高原線</p>
        <p>駅数：60駅</p>
      </div>
      <div class="section">
        <h2>路線一覧</h2>
        <div class="mono">
紫雲本線　1〜30
句守支線　31〜45
紫霞観光線　46〜50
星句高原線　51〜60
        </div>
      </div>
    </section>

    <!-- 路線図 -->
    <section class="page" id="page-map">
      <h1>路線図</h1>
      <div class="section">
        <p>ここに路線図画像や図形をあとで追加できる。</p>
        <div class="mono">
紫雲本線：紫句守中央〜紫句守展示場（1〜30）
句守支線：星句高原〜詩句の丘（31〜45）
紫霞観光線：紫句守展望台〜紫句守詩碑（46〜50）
星句高原線：星句高原入口〜星句高原（51〜60）
        </div>
      </div>
    </section>

    <!-- 時刻表 -->
    <section class="page" id="page-timetable">
      <h1>時刻表</h1>
      <div class="section">
        <p>種別ごとの停車駅データを使って、駅別時刻表をあとで作り込める。</p>
        <h2>種別一覧</h2>
        <div class="mono">
普通 / 準急 / 快速 / 急行 / 通勤急行 / 通勤快速 / 特急
        </div>
      </div>
    </section>

    <!-- 走行位置 -->
    <section class="page" id="page-position">
      <h1>走行位置</h1>
      <div class="section">
        <p>ここに列車アイコンを動かす地図や路線図をあとで追加できる。</p>
        <h2>運用番号</h2>
        <div class="mono">
o：紫峰高原
w：鷲羽句守
t：紫句守展示場
a：句守湾岸
g：紫句守劇場前
        </div>
      </div>
    </section>

    <!-- 列車情報 -->
    <section class="page" id="page-traininfo">
      <h1>列車情報</h1>
      <div class="section">
        <h2>列車番号帯</h2>
        <div class="mono">
0000　特急
1000　急行
2000　通勤急行
3000　快速
4000　通勤快速
5000　準急
6000　普通
7000　普通
8000　回送
9000　臨時
        </div>
      </div>
      <div class="section">
        <h2>両数編成</h2>
        <div class="mono">
特急　4＋6, 4, 6, 10
急行　4＋6, 8, 10
快速　4＋6, 6, 8, 10
準急　4＋6, 6, 8, 10
普通　4＋6, 4, 6, 8, 10
        </div>
      </div>
    </section>

    <!-- 列車追加 -->
    <section class="page" id="page-trainadd">
      <h1>列車追加</h1>
      <div class="section">
        <p>ここにフォームを作って、列車番号・種別・編成・運用・区間を入力できるようにできる。</p>
      </div>
    </section>

    <!-- ダイヤ表 -->
    <section class="page" id="page-diagram">
      <h1>ダイヤ表</h1>
      <div class="section">
        <p>列車番号と停車駅データを使って、ダイヤグラムをあとで作れる。</p>
        <h2>系統例</h2>
        <div class="mono">
1100　紫句守中央↔紫句守展示場・星句高原
1200　紫句守中央↔紫句守詩碑
1300　紫句守中央↔詩句の丘・紫句守劇場前
…（以下、あなたの設定どおり）
        </div>
      </div>
    </section>

    <!-- 設定 -->
    <section class="page" id="page-settings">
      <h1>設定</h1>
      <div class="section">
        <p>テーマ・表示方法・更新間隔などをあとで追加できる。</p>
      </div>
    </section>
  </main>

  <script>
    const menuBtn = document.getElementById('menuBtn');
    const sideMenu = document.getElementById('sideMenu');
    const pageTitle = document.getElementById('pageTitle');
    const menuItems = sideMenu.querySelectorAll('li');
    const pages = document.querySelectorAll('.page');

    // メニュー開閉
    menuBtn.addEventListener('click', () => {
      sideMenu.classList.toggle('open');
    });

    // ページ切り替え
    menuItems.forEach(item => {
      item.addEventListener('click', () => {
        const pageKey = item.dataset.page;

        // タイトル変更
        pageTitle.textContent = item.textContent;

        // ページ表示切り替え
        pages.forEach(p => {
          p.classList.remove('active');
        });
        const target = document.getElementById('page-' + pageKey);
        if (target) target.classList.add('active');

        // メニュー閉じる
        sideMenu.classList.remove('open');
      });
    });
  </script>
</body>
</html>

