---
theme: default
colorSchema: light
fonts:
  sans: "Lato"
---

<h1 class="text-4xl font-medium text-center">Portfolio Slide</h1>
<div class="text-sm font-extralight text-center">Takahashi Kihiro</div>

---

<div class="flex items-center justify-start gap-8 p-8">
  <h1 class="text-4xl font-bold">自己紹介</h1>
</div>

<div class="flex items-center justify-center gap-16 pl-24">
  <div class="flex-shrink-0">
    <img src="./images/avator.jpeg" alt="Profile" class="rounded-full w-64 h-64" />
  </div>
  <div class="flex-grow">
    <ul class="list-disc list-inside">
      <li>さいたまIT・WEB専門学校 4 年制</li>
      <li>名前：高橋 希尋</li>
      <li>趣味
        <ul class="list-disc list-inside">
          <li>AI駆動開発、ガジェット、テックイベント</li>
        </ul>
      </li>
      <li>資格
        <ul class="list-disc list-inside">
          <li>基本情報技術者</li>
          <li>情報セキュリティマネジメント</li>
          <li>普通自動車第一種運転免許</li>
        </ul>
      </li>
      <li>
        <dev class="text-blue-400">https://www.lvncer.dev/</dev>
      </li>
      <li>
        <dev class="text-blue-400">@kihhi_</dev>
      </li>
    </ul>
  </div>
</div>

---

<div class="flex items-center justify-start gap-8 p-8">
  <h1 class="text-4xl font-bold">スキル紹介</h1>
</div>

<div class="flex items-start justify-start pl-32 gap-36">
  <div class="flex-shrink-0">
    <div class="text-left">
      <h4 class="font-semibold mb-1">Python</h4>
      <ul class="list-disc list-inside pl-6 mb-3 text-sm">
        <li>Fast API / Flask / Django</li>
        <li>機械学習</li>
      </ul>
      <h4 class="font-semibold mb-1">Javascript / Typescript</h4>
      <ul class="list-disc list-inside pl-6 mb-3 text-sm">
        <li>Tailwind CSS</li>
        <li>React / Next.js</li>
        <li>Node.js / Express</li>
        <li>Biome</li>
        <li>Prisma / Drizzle</li>
      </ul>
      <h5 class="font-bold mb-1">PHP</h5>
      <h5 class="font-bold mb-1">Ruby on Rails / Swift / Go ...</h5>
      <h5 class="font-bold">Web セキュリティ</h5>
    </div>
  </div>
  <div class="flex-shrink-0">
    <div class="text-left">
      <h4 class="font-semibold mb-1">データベース</h4>
      <ul class="list-disc list-inside pl-6 mb-3 text-sm">
        <li>MySQL</li>
        <li>PostgreSQL (Supabase / Neon / RDS)</li>
        <li>NoSQL (Firebase)</li>
      </ul>
      <h4 class="font-semibold mb-1">開発者ツール、インフラ</h4>
      <ul class="list-disc list-inside pl-6 mb-3 text-sm">
        <li>Figma</li>
        <li>Github / Gitlab</li>
        <li>Docker / k8s</li>
        <li>AWS / Vercel</li>
        <li>Clerk</li>
      </ul>
      <h5 class="font-bold">AI</h5>
      <ul class="list-disc list-inside pl-6 mb-3 text-sm">
        <li>Cursor / Devin</li>
      </ul>
    </div>
  </div>
</div>

---

<div class="flex items-center justify-start gap-8 p-8">
  <h1 class="text-4xl font-bold">個人開発作品 1. LT 登録サイト</h1>
</div>

<div class="flex items-start justify-start pl-28 pb-2 gap-24">
  <div>
    <img src="./images/lt_1.jpeg" class="rounded-2xl mb-4 mx-auto block w-64" />
  </div>
  <div>
    <h3 class="text-xl font-bold"></h3>
    <div class="text-sm font-medium pb-3 text-right">
      <div class="text-blue-400">siw-lt.vercel.app/</div>
    </div>
    <div class="text-left">
      <h5 class="font-bold mb-2">使用技術スタック</h5>
      <ul class="list-disc list-inside mb-3 text-sm">
        <li>TypeScript / Next.js / Tailwind CSS</li>
        <li>Clerk / Neon / Vercel / Github Actions</li>
      </ul>
    </div>
  </div>
</div>

<div class="flex items-start justify-start pl-36 gap-20">
  <div class="flex-shrink-0">
    <div class="text-left">
      <h5 class="font-bold">なぜ開発したか</h5>
      <ul class="list-disc list-inside mb-3 text-sm">
        <li>SIWの学生がライトニングトークを管理するため</li>
        <li>他ユーザーも閲覧できるようにするため</li>
      </ul>
      <h5 class="font-bold">主要機能</h5>
      <ul class="list-disc list-inside text-sm">
        <li>LT発表者の登録・管理機能</li>
        <li>発表スケジュールの自動管理機能</li>
      </ul>
    </div>
  </div>
  <div class="flex-shrink-0 text-center">
    <img src="./images/lt_2.jpeg" alt="LT Registration Site" class="rounded-2xl mb-4 mx-auto block w-72" />
  </div>
</div>

---

<div class="flex items-center justify-start gap-8 p-8">
  <h1 class="text-4xl font-bold">個人開発作品 2.</h1>
</div>

<div class="flex items-center justify-center gap-18">
  <div>
    <img src="./images/echoes.jpeg" class="rounded-2xl mb-4 mx-auto block w-64" />
  </div>
  <div>
    <h3 class="text-xl font-bold">echoes</h3>
    <div class="text-sm font-medium pb-3 text-right">
      <div class="text-blue-400">https://echoes-livid.vercel.app/</div>
    </div>
    <div class="text-left">
      <div class="text-sm mb-2">VRMモデルとAI を介してリアルタイムに音声会話</div>
      <h5 class="font-bold">使用技術スタック</h5>
      <ul class="list-disc list-inside mb-3 text-sm">
        <li>Next.js / Zustand / AI SDK / Three.js</li>
      </ul>
    </div>
  </div>
</div>

<div class="flex items-center justify-start pl-32 pt-2 gap-16">
  <div class="flex-shrink-0">
    <div class="font-semibold mb-2">それ以外にも</div>
    <ul class="list-disc list-inside mb-3 text-sm">
      <li>VRM モデルを AI が自然言語で制御できる MCP リモートサーバー「VRMCP」</li>
      <li>AI との会話練習でコミュニケーション力を向上させる Web アプリ「kaiwa-dash」</li>
      <li>Claude CodeのCLI会話履歴ブラウザーの npm パッケージ「cclog」</li>
      <li>マークダウンファイルから名刺を作成できる npm パッケージ「name-card」</li>
      <li>ブックマーク管理アプリ「bookmarks」</li>
      <li>シンプルなSNSアプリ「NextSNS」...</li>
    </ul>
  </div>
</div>

---

<div class="flex items-center justify-start gap-8 p-8">
  <h1 class="text-4xl font-bold">チーム開発作品 1.</h1>
</div>

<div class="flex items-center justify-center gap-16">
  <div class="flex-shrink-0">
    <h3 class="text-xl font-bold">社内工数管理システム worktrack</h3>
    <div class="flex items-end justify-end text-sm text-right text-blue-400 mb-3">
      zenn.dev/tkszenn/articles/1d5e63cfd0d5bc
    </div>
    <div class="text-left">
      <h5 class="font-bold">使用技術スタック</h5>
      <ul class="list-disc list-inside text-sm">
        <li>Amazon Linux / Apache / MySQL (RDS) / PHP</li>
      </ul>
      <h5 class="font-bold">担当</h5>
      <ul class="list-disc list-inside text-sm">
        <li>プロダクトマネージャー、DB設計</li>
      </ul>
      <h5 class="font-bold">期間</h5>
      <ul class="list-disc list-inside text-sm">
        <li>約 4 ヶ月</li>
      </ul>
      <h5 class="font-bold">特徴</h5>
      <ul class="list-disc list-inside text-sm">
        <li>企業連携授業にて受託開発</li>
        <li>複雑な権限管理システムの実装</li>
        <li>全データ変更の履歴追跡機能</li>
        <li>今後は実運用環境での保守・運用</li>
      </ul>
    </div>
  </div>
  <div class="flex-shrink-0 text-center justify-center">
    <img src="./images/worktrack_1.jpeg" class="rounded-2xl mb-4 mx-auto block w-72" />
    <img src="./images/worktrack_2.jpeg" class="rounded-2xl mb-4 mx-auto block w-72" />
  </div>
</div>

---

<div class="flex items-center justify-start gap-8 p-8">
  <h1 class="text-4xl font-bold">チーム開発作品 2. 「ドロカツ」</h1>
</div>

<div class="flex items-center justify-center gap-8 mb-4">
  <div>
    <img src="https://static.wixstatic.com/media/852b40_2eb450ee20d7448381dc49f0ed6133a8~mv2.jpg/v1/fill/w_740,h_417,fp_0.50_0.50,q_90/852b40_2eb450ee20d7448381dc49f0ed6133a8~mv2.webp" alt="drokatsu-all" class="rounded-2xl mb-4 mx-auto block w-96" />
  </div>
  <div>
    <img src="https://www.siw.ac.jp/wp-content/uploads/2024/05/FDDA22A3-9D70-4E8D-A898-5E74BB3F1BD3-1.jpeg" alt="win-drokatsu" class="rounded-2xl mb-4 mx-auto block w-82" />
  </div>
</div>

<div class="flex items-center justify-start pl-32 gap-16">
  <div class="flex-shrink-0">
    <div class="font-semibold mb-1">全国大会 プログラミング部門優勝</div>
    <div class="font-light mb-1">Pythonを用いてドローン「CoDrone EDU」を操作</div>
    <div class="font-light">自動操縦の精度や、課題クリアにかかった時間などで競う</div>
  </div>
</div>

---

<div class="flex items-center justify-start gap-8 p-8">
  <h1 class="text-4xl font-bold">チーム開発作品 3.「ライブ演出システム LiveFx」</h1>
</div>

<div class="flex items-center justify-center gap-12">
  <div class="flex-shrink-0 text-center justify-center">
    <img src="https://www.siw.ac.jp/wp-content/uploads/2025/04/aba1dd9afd994bc383f5259806be7bb4.jpeg" class="rounded-2xl mb-4 mx-auto block w-86" />
  </div>
  <div class="flex-shrink-0">
    <h3 class="text-xl font-bold"></h3>
    <div class="text-sm font-medium pl-18 pb-3 text-right text-blue-400">
      zenn.dev/tkszenn/articles/2e73439f678488/
    </div>
    <div class="text-left">
      <h5 class="font-bold">使用技術スタック</h5>
      <ul class="list-disc list-inside text-sm">
        <li>TypeScript / React / Tailwind CSS / WebSocket</li>
        <li>Node.js / Express </li>
        <li>k8s / Grafana / Prometheus / AWS</li>
      </ul>
      <h5 class="font-bold">担当</h5>
      <ul class="list-disc list-inside text-sm">
        <li>プロジェクトマネージャー / フロントエンド</li>
      </ul>
      <h5 class="font-bold">期間</h5>
      <ul class="list-disc list-inside text-sm">
        <li>2 ヶ月</li>
      </ul>
      <h5 class="font-bold">特徴</h5>
      <ul class="list-disc list-inside text-sm">
        <li>MIDI コントローラーからの画面遷移指示</li>
        <li>最大6000台のアクセス処理想定</li>
        <li>タイミング同期とスリープ防止</li>
      </ul>
    </div>
  </div>
</div>

---

<div class="flex items-center justify-start gap-8 p-8">
  <h1 class="text-4xl font-bold">自己PR</h1>
</div>

<div class="flex items-center justify-center">
  <div class="flex-shrink-0">
    <ol class="list-disc list-inside mb-4">
      <li>コミュニケーション能力の高さ
        <ul class="list-disc list-inside mb-4">
          <li>チーム開発でメンバー間でのスムーズなやりとり</li>
          <li>クライアントとの折衝経験</li>
        </ul>
      </li>
      <li>主体性・誠実性の高さ
        <ul class="list-disc list-inside mb-4">
          <li>個人開発でAIなどの最新情報を常にキャッチアップ</li>
          <li>オープンな会話を推進し、インシデント発生時は即時連絡</li>
        </ul>
      </li>
      <li>豊富な経験
        <ul class="list-disc list-inside mb-4">
          <li>さまざまなプロジェクトマネージャーを担当</li>
          <li>学校内外でフルスタックに開発を経験</li>
          <li>学内の授業アシスタントで後輩にサポート</li>
        </ul>
      </li>
    </ol>
  </div>
</div>
