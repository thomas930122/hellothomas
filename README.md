<!DOCTYPE html>
<html lang="zh-Hant" class="scroll-smooth">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Thomas Hsieh 謝鎰丞 | Short-Form Video & Social Content Producer</title>
  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- Google Fonts -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=Noto+Sans+TC:wght@300;400;500;700&family=Playfair+Display:ital,wght@0,600;1,400&display=swap" rel="stylesheet">
  <!-- Lucide Icons -->
  <script src="https://unpkg.com/lucide@latest"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'Noto Sans TC', 'sans-serif'],
            serif: ['Playfair Display', 'serif'],
          }
        }
      }
    }
  </script>
</head>
<body class="bg-zinc-950 text-zinc-100 font-sans antialiased selection:bg-indigo-500 selection:text-white">

  <!-- 頂部導覽列 -->
  <header class="fixed top-0 left-0 right-0 z-50 bg-zinc-950/85 backdrop-blur-md border-b border-zinc-800/80">
    <div class="max-w-6xl mx-auto px-6 h-20 flex items-center justify-between">
      <a href="#" class="text-xl font-bold tracking-tighter flex items-center gap-2">
        <span class="w-2.5 h-2.5 rounded-full bg-indigo-500 inline-block"></span>
        <span>THOMAS HSIEH</span>
        <span class="text-zinc-500 font-normal text-sm ml-1 hidden sm:inline">謝鎰丞</span>
      </a>

      <!-- 桌面版選單 -->
      <nav class="hidden md:flex items-center gap-8 text-sm font-medium text-zinc-400">
        <a href="#projects" class="hover:text-white transition">Projects 專案實績</a>
        <a href="#experience" class="hover:text-white transition">Experience 經歷</a>
        <a href="#education" class="hover:text-white transition">Education 學歷與榮譽</a>
        <a href="#skills" class="hover:text-white transition">Skills 平台與認證</a>
        <a href="#contact" class="px-4 py-2 rounded-full bg-white text-zinc-950 font-semibold hover:bg-zinc-200 transition">Contact 聯絡</a>
      </nav>

      <!-- 手機版選單按鈕 -->
      <button id="menu-btn" class="md:hidden text-zinc-400 hover:text-white">
        <i data-lucide="menu" class="w-6 h-6"></i>
      </button>
    </div>

    <!-- 手機版下拉選單 -->
    <div id="mobile-menu" class="hidden md:hidden bg-zinc-900 border-b border-zinc-800 px-6 py-4 space-y-3 text-sm">
      <a href="#projects" class="block py-2 text-zinc-300 hover:text-white">Projects 專案實績</a>
      <a href="#experience" class="block py-2 text-zinc-300 hover:text-white">Experience 經歷</a>
      <a href="#education" class="block py-2 text-zinc-300 hover:text-white">Education 學歷與榮譽</a>
      <a href="#skills" class="block py-2 text-zinc-300 hover:text-white">Skills 平台與認證</a>
      <a href="#contact" class="block py-2 text-indigo-400 font-semibold">Contact 聯絡</a>
    </div>
  </header>

  <!-- 主視覺 Hero Section -->
  <section class="relative pt-36 pb-20 md:pt-44 md:pb-28 px-6 overflow-hidden">
    <!-- 背景光暈裝飾 -->
    <div class="absolute top-1/4 -right-20 w-96 h-96 bg-indigo-600/15 rounded-full blur-3xl pointer-events-none"></div>
    <div class="absolute bottom-10 -left-20 w-80 h-80 bg-fuchsia-600/10 rounded-full blur-3xl pointer-events-none"></div>

    <div class="max-w-6xl mx-auto">
      <div class="flex flex-wrap items-center gap-2 mb-6">
        <span class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-zinc-900 border border-zinc-800 text-xs text-zinc-300">
          <span class="w-2 h-2 rounded-full bg-emerald-400 animate-pulse"></span>
          Based in Brighton, UK
        </span>
        <span class="inline-flex items-center gap-1.5 px-3 py-1 rounded-full bg-indigo-500/10 border border-indigo-500/20 text-xs text-indigo-300">
          Bilingual Mandarin–English
        </span>
      </div>

      <h1 class="text-4xl sm:text-6xl lg:text-7xl font-bold tracking-tight leading-[1.12] mb-6">
        Short-Form Video &<br>
        <span class="font-serif italic font-normal text-indigo-400">Social Content</span> Producer.
      </h1>

      <p class="max-w-3xl text-base sm:text-lg text-zinc-400 font-light leading-relaxed mb-10">
        具備英國藝文組織（Writing Our Legacy、National Trust 活動）與中台大型媒體製作（湖南衛視芒果 TV+、TVBS）實戰經驗的雙語短影音與社群內容製作人。精通歐美社群（Instagram, TikTok, YouTube, LinkedIn）與華語平台（抖音、小紅書、微博）流量生態。曾獲全國短影音競賽第一名，並以優異成績（Merit）取得英國薩塞克斯大學（University of Sussex）文化創意產業碩士學位。
      </p>

      <div class="flex flex-wrap items-center gap-4">
        <a href="#projects" class="px-7 py-3.5 rounded-full bg-indigo-600 hover:bg-indigo-500 text-white font-medium text-sm flex items-center gap-2 transition shadow-lg shadow-indigo-600/20">
          <span>查看指標專案 View Impact</span>
          <i data-lucide="arrow-down-right" class="w-4 h-4"></i>
        </a>
        <a href="mailto:thomas930122uk@gmail.com" class="px-7 py-3.5 rounded-full bg-zinc-900 hover:bg-zinc-800 border border-zinc-800 text-zinc-300 font-medium text-sm flex items-center gap-2 transition">
          <i data-lucide="mail" class="w-4 h-4 text-indigo-400"></i>
          <span>thomas930122uk@gmail.com</span>
        </a>
        <a href="https://linkedin.com/in/thomas-hsieh" target="_blank" rel="noopener" class="p-3.5 rounded-full bg-zinc-900 hover:bg-zinc-800 border border-zinc-800 text-zinc-300 hover:text-white transition" aria-label="LinkedIn">
          <i data-lucide="linkedin" class="w-4 h-4"></i>
        </a>
      </div>

      <!-- 關鍵數據亮點 Key Metrics -->
      <div class="grid grid-cols-2 lg:grid-cols-4 gap-6 mt-16 pt-10 border-t border-zinc-800/80">
        <div>
          <p class="text-3xl sm:text-4xl font-bold text-white">100K+</p>
          <p class="text-xs text-zinc-400 mt-1">美妝創業專案上線 9 天內短影音總觀看數</p>
        </div>
        <div>
          <p class="text-3xl sm:text-4xl font-bold text-white">+15%</p>
          <p class="text-xs text-zinc-400 mt-1">12 週產出 15+ 支影片帶動英國藝文組織粉絲增長</p>
        </div>
        <div>
          <p class="text-3xl sm:text-4xl font-bold text-white">-50%</p>
          <p class="text-xs text-zinc-400 mt-1">國科會研究證實 AI/API 工作流縮減新聞產製時間</p>
        </div>
        <div>
          <p class="text-3xl sm:text-4xl font-bold text-white">£10,000</p>
          <p class="text-xs text-zinc-400 mt-1">帶領 50 人團隊執行全國賽事募得贊助（觸及 5 萬人）</p>
        </div>
      </div>
    </div>
  </section>

  <!-- 指標專案與實績 Featured Impact Projects -->
  <section id="projects" class="py-24 px-6 bg-zinc-900/30 border-t border-zinc-900">
    <div class="max-w-6xl mx-auto">
      <div class="flex flex-col md:flex-row md:items-end justify-between mb-12 gap-6">
        <div>
          <p class="text-xs font-semibold uppercase tracking-widest text-indigo-400 mb-2">01 / Key Projects & Campaigns</p>
          <h2 class="text-3xl sm:text-4xl font-bold tracking-tight">代表專案與流量實績</h2>
        </div>

        <!-- 分類篩選按鈕 -->
        <div class="flex flex-wrap gap-2" id="filter-buttons">
          <button data-filter="all" class="filter-btn active px-4 py-1.5 rounded-full text-xs font-medium bg-white text-zinc-950 transition">全部 All</button>
          <button data-filter="social" class="filter-btn px-4 py-1.5 rounded-full text-xs font-medium bg-zinc-900 text-zinc-400 hover:text-white border border-zinc-800 transition">短影音與社群成長 Short-Form & Social</button>
          <button data-filter="campaign" class="filter-btn px-4 py-1.5 rounded-full text-xs font-medium bg-zinc-900 text-zinc-400 hover:text-white border border-zinc-800 transition">大型活動與視覺製作 Event & Collateral</button>
          <button data-filter="research" class="filter-btn px-4 py-1.5 rounded-full text-xs font-medium bg-zinc-900 text-zinc-400 hover:text-white border border-zinc-800 transition">AI 媒體與新聞編採 AI & Journalism</button>
        </div>
      </div>

      <!-- 作品網格 -->
      <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-6" id="project-grid">

        <!-- Card 1: Beauty & Lifestyle Venture -->
        <article data-category="social" class="project-card group rounded-2xl bg-zinc-900/80 border border-zinc-800/90 overflow-hidden hover:border-indigo-500/50 transition flex flex-col justify-between">
          <div>
            <div class="h-44 bg-gradient-to-br from-fuchsia-900/50 via-zinc-900 to-zinc-950 p-6 flex flex-col justify-between relative overflow-hidden">
              <div class="flex justify-between items-center z-10">
                <span class="text-xs font-mono uppercase px-2.5 py-1 rounded bg-fuchsia-500/20 text-fuchsia-300 border border-fuchsia-500/30">100,000+ Views in 9 Days</span>
                <span class="text-xs text-zinc-400 font-mono">2026</span>
              </div>
              <i data-lucide="flame" class="w-16 h-16 text-fuchsia-500/15 absolute -bottom-2 -right-2 group-hover:scale-110 transition"></i>
              <h3 class="text-lg font-bold text-white z-10">跨國美妝生活品牌短影音冷啟動（Pre-Launch）</h3>
            </div>
            <div class="p-6">
              <p class="text-xs text-zinc-400 leading-relaxed">
                擔任共同創辦人暨品牌策略主導，負責市場競品調研與 SEO 規劃。運用 CapCut 與 Canva 在單週內高強度產出 9 支 AI 生成短影音與 12 組圖文輪播（Carousels），活動上線 9 天內即突破 100,000+ 觀看次數。
              </p>
            </div>
          </div>
          <div class="px-6 pb-6 pt-3 border-t border-zinc-800/60 flex flex-wrap gap-1.5">
            <span class="text-[11px] px-2 py-0.5 rounded bg-zinc-800 text-zinc-300">AI Video Generation</span>
            <span class="text-[11px] px-2 py-0.5 rounded bg-zinc-800 text-zinc-300">CapCut & Canva</span>
            <span class="text-[11px] px-2 py-0.5 rounded bg-zinc-800 text-zinc-300">SEO Strategy</span>
          </div>
        </article>

        <!-- Card 2: Writing Our Legacy Social Growth -->
        <article data-category="social" class="project-card group rounded-2xl bg-zinc-900/80 border border-zinc-800/90 overflow-hidden hover:border-indigo-500/50 transition flex flex-col justify-between">
          <div>
            <div class="h-44 bg-gradient-to-br from-indigo-900/60 via-zinc-900 to-zinc-950 p-6 flex flex-col justify-between relative overflow-hidden">
              <div class="flex justify-between items-center z-10">
                <span class="text-xs font-mono uppercase px-2.5 py-1 rounded bg-indigo-500/20 text-indigo-300 border border-indigo-500/30">+15% Follower Growth</span>
                <span class="text-xs text-zinc-400 font-mono">UK Arts</span>
              </div>
              <i data-lucide="clapperboard" class="w-16 h-16 text-indigo-500/15 absolute -bottom-2 -right-2 group-hover:scale-110 transition"></i>
              <h3 class="text-lg font-bold text-white z-10">Writing Our Legacy 英國藝文組織全平台影音專案</h3>
            </div>
            <div class="p-6">
              <p class="text-xs text-zinc-400 leading-relaxed">
                於 12 週內獨立製作超過 15 支宣傳與活動紀實短片，跨平台發布於 IG、LinkedIn、FB 與 YouTube。平均單支影片突破 1,000+ 觀看，帶動粉絲數成長 15%（達 2,600+），並獲得參展藝術家自然轉發分享。
              </p>
            </div>
          </div>
          <div class="px-6 pb-6 pt-3 border-t border-zinc-800/60 flex flex-wrap gap-1.5">
            <span class="text-[11px] px-2 py-0.5 rounded bg-zinc-800 text-zinc-300">IG / LinkedIn / YouTube</span>
            <span class="text-[11px] px-2 py-0.5 rounded bg-zinc-800 text-zinc-300">Event Video</span>
            <span class="text-[11px] px-2 py-0.5 rounded bg-zinc-800 text-zinc-300">Organic Reach</span>
          </div>
        </article>

        <!-- Card 3: National Trust Cultural Events Print & Merch -->
        <article data-category="campaign" class="project-card group rounded-2xl bg-zinc-900/80 border border-zinc-800/90 overflow-hidden hover:border-indigo-500/50 transition flex flex-col justify-between">
          <div>
            <div class="h-44 bg-gradient-to-br from-emerald-900/50 via-zinc-900 to-zinc-950 p-6 flex flex-col justify-between relative overflow-hidden">
              <div class="flex justify-between items-center z-10">
                <span class="text-xs font-mono uppercase px-2.5 py-1 rounded bg-emerald-500/20 text-emerald-300 border border-emerald-500/30">Print & Merch Design</span>
                <span class="text-xs text-zinc-400 font-mono">Brighton, UK</span>
              </div>
              <i data-lucide="palette" class="w-16 h-16 text-emerald-500/15 absolute -bottom-2 -right-2 group-hover:scale-110 transition"></i>
              <h3 class="text-lg font-bold text-white z-10">英國 National Trust 文化遺產活動視覺與周邊設計</h3>
            </div>
            <div class="p-6">
              <p class="text-xs text-zinc-400 leading-relaxed">
                為 Writing Our Legacy 與英國國家名勝古蹟信託（National Trust）合作之多場文化活動（每場約 50 名參與者）設計全套品牌周邊與印刷宣傳物，涵蓋服飾、大型橫幅（Banners）、海報與傳單。
              </p>
            </div>
          </div>
          <div class="px-6 pb-6 pt-3 border-t border-zinc-800/60 flex flex-wrap gap-1.5">
            <span class="text-[11px] px-2 py-0.5 rounded bg-zinc-800 text-zinc-300">Print Collateral</span>
            <span class="text-[11px] px-2 py-0.5 rounded bg-zinc-800 text-zinc-300">Branded Merchandise</span>
            <span class="text-[11px] px-2 py-0.5 rounded bg-zinc-800 text-zinc-300">Canva</span>
          </div>
        </article>

        <!-- Card 4: Mango TV+ Short-Form Production -->
        <article data-category="social" class="project-card group rounded-2xl bg-zinc-900/80 border border-zinc-800/90 overflow-hidden hover:border-indigo-500/50 transition flex flex-col justify-between">
          <div>
            <div class="h-44 bg-gradient-to-br from-amber-900/50 via-zinc-900 to-zinc-950 p-6 flex flex-col justify-between relative overflow-hidden">
              <div class="flex justify-between items-center z-10">
                <span class="text-xs font-mono uppercase px-2.5 py-1 rounded bg-amber-500/20 text-amber-300 border border-amber-500/30">10,000+ Combined Views</span>
                <span class="text-xs text-zinc-400 font-mono">2025</span>
              </div>
              <i data-lucide="smartphone" class="w-16 h-16 text-amber-500/15 absolute -bottom-2 -right-2 group-hover:scale-110 transition"></i>
              <h3 class="text-lg font-bold text-white z-10">湖南衛視芒果 TV+ 大型活動短影音矩陣分發</h3>
            </div>
            <div class="p-6">
              <p class="text-xs text-zinc-400 leading-relaxed">
                於高節奏大型拍攝現場負責藝人接待協調與活動後勤，並獨立拍攝剪輯 5 支活動宣傳短影音，跨平台分發至芒果 TV、抖音、微博、小紅書及中時新聞網 FB，累積突破 10,000+ 觀看數。
              </p>
            </div>
          </div>
          <div class="px-6 pb-6 pt-3 border-t border-zinc-800/60 flex flex-wrap gap-1.5">
            <span class="text-[11px] px-2 py-0.5 rounded bg-zinc-800 text-zinc-300">Douyin / Xiaohongshu / Weibo</span>
            <span class="text-[11px] px-2 py-0.5 rounded bg-zinc-800 text-zinc-300">Talent Liaison</span>
          </div>
        </article>

        <!-- Card 5: Golden Anchor & JNN TV/Radio -->
        <article data-category="campaign" class="project-card group rounded-2xl bg-zinc-900/80 border border-zinc-800/90 overflow-hidden hover:border-indigo-500/50 transition flex flex-col justify-between">
          <div>
            <div class="h-44 bg-gradient-to-br from-blue-900/50 via-zinc-900 to-zinc-950 p-6 flex flex-col justify-between relative overflow-hidden">
              <div class="flex justify-between items-center z-10">
                <span class="text-xs font-mono uppercase px-2.5 py-1 rounded bg-blue-500/20 text-blue-300 border border-blue-500/30">£10K Sponsorship · 50K+ Audience</span>
                <span class="text-xs text-zinc-400 font-mono">2024–25</span>
              </div>
              <i data-lucide="mic" class="w-16 h-16 text-blue-500/15 absolute -bottom-2 -right-2 group-hover:scale-110 transition"></i>
              <h3 class="text-lg font-bold text-white z-10">全國金牌主播與 Podcast 大賽暨廣電台務統籌</h3>
            </div>
            <div class="p-6">
              <p class="text-xs text-zinc-400 leading-relaxed">
                帶領 50 人團隊舉辦全國大賽，成功洽談約 NT$450,000（約 £10,000）贊助，產出 50+ 件宣傳素材並觸及 50,000+ 受眾；每學期監督產出 100+ 則影音新聞與 100+ 集 Podcast 節目。
              </p>
            </div>
          </div>
          <div class="px-6 pb-6 pt-3 border-t border-zinc-800/60 flex flex-wrap gap-1.5">
            <span class="text-[11px] px-2 py-0.5 rounded bg-zinc-800 text-zinc-300">50-Member Team Lead</span>
            <span class="text-[11px] px-2 py-0.5 rounded bg-zinc-800 text-zinc-300">Sponsorship Pitch</span>
          </div>
        </article>

        <!-- Card 6: NSTC AI in Newsrooms & Cultural Weekly -->
        <article data-category="research" class="project-card group rounded-2xl bg-zinc-900/80 border border-zinc-800/90 overflow-hidden hover:border-indigo-500/50 transition flex flex-col justify-between">
          <div>
            <div class="h-44 bg-gradient-to-br from-purple-900/50 via-zinc-900 to-zinc-950 p-6 flex flex-col justify-between relative overflow-hidden">
              <div class="flex justify-between items-center z-10">
                <span class="text-xs font-mono uppercase px-2.5 py-1 rounded bg-purple-500/20 text-purple-300 border border-purple-500/30">NSTC Level-A · 50K+ PTS Views</span>
                <span class="text-xs text-zinc-400 font-mono">2023–24</span>
              </div>
              <i data-lucide="cpu" class="w-16 h-16 text-purple-500/15 absolute -bottom-2 -right-2 group-hover:scale-110 transition"></i>
              <h3 class="text-lg font-bold text-white z-10">國科會 AI 新聞產製研究 &《文化一周》總編輯</h3>
            </div>
            <div class="p-6">
              <p class="text-xs text-zinc-400 leading-relaxed">
                訪談 7 位資深媒體人（TVBS、中央社、三立、中時、上下游），撰寫 28 頁報告證實 AI/API 流程可縮減 50% 新聞產製時間；任總編輯期間發行約 20 期報紙（總印量約 10 萬份），個人撰寫 15 篇報導於公視數位平台創下 50,000+ 瀏覽。
              </p>
            </div>
          </div>
          <div class="px-6 pb-6 pt-3 border-t border-zinc-800/60 flex flex-wrap gap-1.5">
            <span class="text-[11px] px-2 py-0.5 rounded bg-zinc-800 text-zinc-300">AI Newsroom Workflows</span>
            <span class="text-[11px] px-2 py-0.5 rounded bg-zinc-800 text-zinc-300">Editor-in-Chief</span>
          </div>
        </article>

      </div>
    </div>
  </section>

  <!-- 工作經歷 Work Experience -->
  <section id="experience" class="py-24 px-6 border-t border-zinc-900">
    <div class="max-w-6xl mx-auto">
      <p class="text-xs font-semibold uppercase tracking-widest text-indigo-400 mb-2">02 / Professional Experience</p>
      <h2 class="text-3xl sm:text-4xl font-bold tracking-tight mb-12">專業工作經歷</h2>

      <div class="space-y-8 border-l border-zinc-800 pl-6 sm:pl-8 ml-2">

        <!-- Exp 1 -->
        <div class="relative bg-zinc-900/50 border border-zinc-800/80 rounded-2xl p-6 sm:p-8 hover:border-zinc-700 transition">
          <span class="w-3.5 h-3.5 rounded-full bg-indigo-500 absolute -left-[31px] sm:-left-[39px] top-8 ring-4 ring-zinc-950"></span>
          <div class="flex flex-wrap items-center justify-between gap-2 mb-2">
            <h3 class="text-xl font-bold text-white">Digital Content Producer & Marketing Contractor <span class="text-sm font-normal text-indigo-400">（由實習生留任）</span></h3>
            <span class="text-xs font-mono px-3 py-1 rounded-full bg-indigo-500/10 text-indigo-300 border border-indigo-500/20">May 2026 – Present</span>
          </div>
          <p class="text-sm font-medium text-zinc-300 mb-4">Writing Our Legacy (BPOC Arts, Literature & Cultural Heritage Organization) · Brighton, UK</p>
          <ul class="space-y-2 text-xs sm:text-sm text-zinc-400 list-disc list-inside leading-relaxed">
            <li>於 12 週內製作 15+ 支宣傳與活動短片並發布於 IG、LinkedIn、FB 與 YouTube，推動粉絲數成長 15% 至 2,600+，平均單支影片觀看數破 1,000+，並獲參展藝術家主動轉發。</li>
            <li>運用 Canva 為英國國家名勝古蹟信託（National Trust）合作文化活動（每場約 50 人）設計品牌周邊與印刷宣傳品（服飾、展架橫幅、海報、傳單）。</li>
          </ul>
        </div>

        <!-- Exp 2 -->
        <div class="relative bg-zinc-900/50 border border-zinc-800/80 rounded-2xl p-6 sm:p-8 hover:border-zinc-700 transition">
          <span class="w-3.5 h-3.5 rounded-full bg-fuchsia-500 absolute -left-[31px] sm:-left-[39px] top-8 ring-4 ring-zinc-950"></span>
          <div class="flex flex-wrap items-center justify-between gap-2 mb-2">
            <h3 class="text-xl font-bold text-white">Co-Founder & Brand Strategy Lead <span class="text-sm font-normal text-zinc-400">(Entrepreneurial Project)</span></h3>
            <span class="text-xs font-mono px-3 py-1 rounded-full bg-zinc-800 text-zinc-300">2026 – Present</span>
          </div>
          <p class="text-sm font-medium text-zinc-300 mb-4">Beauty & Lifestyle Venture (Pre-Launch) · UK & Asia (Remote)</p>
          <ul class="space-y-2 text-xs sm:text-sm text-zinc-400 list-disc list-inside leading-relaxed">
            <li>主導市場與競品調研、SEO 關鍵字規劃，以及運用 CapCut 與 Canva 進行短影音內容製作。</li>
            <li>單週內高效率產出 9 支 AI 生成短影音與 12 組靜態/輪播圖文，於宣傳啟動後 9 天內達成 100,000+ 總觀看次數。</li>
          </ul>
        </div>

        <!-- Exp 3 -->
        <div class="relative bg-zinc-900/50 border border-zinc-800/80 rounded-2xl p-6 sm:p-8 hover:border-zinc-700 transition">
          <span class="w-3.5 h-3.5 rounded-full bg-zinc-600 absolute -left-[31px] sm:-left-[39px] top-8 ring-4 ring-zinc-950"></span>
          <div class="flex flex-wrap items-center justify-between gap-2 mb-2">
            <h3 class="text-xl font-bold text-white">Short-Form Video & Event Production Intern</h3>
            <span class="text-xs font-mono px-3 py-1 rounded-full bg-zinc-800 text-zinc-300">Jul 2025 – Aug 2025</span>
          </div>
          <p class="text-sm font-medium text-zinc-300 mb-4">Hunan Satellite Mango TV+ (Large-Scale Events Center 湖南衛視芒果 TV+ 大型活動中心) · China</p>
          <ul class="space-y-2 text-xs sm:text-sm text-zinc-400 list-disc list-inside leading-relaxed">
            <li>獨立拍攝並剪輯 5 支宣傳短影音，跨平台分發至芒果 TV、抖音、微博、小紅書與中時新聞網 FB，累積突破 10,000+ 觀看次數。</li>
            <li>在緊湊的大型節目錄製現場協調活動後勤與藝人公關接待。</li>
          </ul>
        </div>

        <!-- Exp 4 -->
        <div class="relative bg-zinc-900/50 border border-zinc-800/80 rounded-2xl p-6 sm:p-8 hover:border-zinc-700 transition">
          <span class="w-3.5 h-3.5 rounded-full bg-zinc-600 absolute -left-[31px] sm:-left-[39px] top-8 ring-4 ring-zinc-950"></span>
          <div class="flex flex-wrap items-center justify-between gap-2 mb-2">
            <h3 class="text-xl font-bold text-white">Research Assistant – Digital Media Trends & AI in Newsrooms <span class="text-sm font-normal text-zinc-400">(Level-A Project)</span></h3>
            <span class="text-xs font-mono px-3 py-1 rounded-full bg-zinc-800 text-zinc-300">Jul 2023 – Jul 2024</span>
          </div>
          <p class="text-sm font-medium text-zinc-300 mb-4">National Science and Technology Council (NSTC 國科會) · Taipei, Taiwan</p>
          <ul class="space-y-2 text-xs sm:text-sm text-zinc-400 list-disc list-inside leading-relaxed">
            <li>深度訪談 7 位台灣資深新聞媒體專業人士（涵蓋 TVBS、中央社、三立新聞、中國時報、上下游 News&Market）。</li>
            <li>撰寫 28 頁研究報告，完整記錄新聞編輯室如何透過 AI 與 API 工作流將新聞產製時間縮短 50%。</li>
          </ul>
        </div>

      </div>
    </div>
  </section>

  <!-- 學歷、獎項與校園領導 Education, Honours & Leadership -->
  <section id="education" class="py-24 px-6 bg-zinc-900/30 border-t border-zinc-900">
    <div class="max-w-6xl mx-auto">
      <p class="text-xs font-semibold uppercase tracking-widest text-indigo-400 mb-2">03 / Education & Leadership</p>
      <h2 class="text-3xl sm:text-4xl font-bold tracking-tight mb-12">雙聯學歷、競賽首獎與校園媒體實績</h2>

      <div class="grid md:grid-cols-2 gap-8 mb-12">
        <!-- Sussex -->
        <div class="p-8 rounded-2xl bg-zinc-900 border border-zinc-800 flex flex-col justify-between">
          <div>
            <div class="flex justify-between items-start gap-4 mb-3">
              <h3 class="text-xl font-bold text-white">University of Sussex</h3>
              <span class="text-xs font-mono px-2.5 py-1 rounded bg-indigo-500/10 text-indigo-400 border border-indigo-500/20 shrink-0">2025 – 2026</span>
            </div>
            <p class="text-base text-zinc-200 font-medium mb-2">MA Cultural and Creative Industries</p>
            <p class="text-xs text-emerald-400 font-medium mb-4">★ Awarded with Merit（優等成績畢業）</p>
          </div>
          <p class="text-xs text-zinc-500 border-t border-zinc-800/80 pt-4">
            結合英國文化創意產業理論與布萊頓在地藝文組織實務，專精於跨國數位內容策略與視覺敘事。
          </p>
        </div>

        <!-- CCU -->
        <div class="p-8 rounded-2xl bg-zinc-900 border border-zinc-800 flex flex-col justify-between">
          <div>
            <div class="flex justify-between items-start gap-4 mb-3">
              <h3 class="text-xl font-bold text-white">Chinese Culture University 中國文化大學</h3>
              <span class="text-xs font-mono px-2.5 py-1 rounded bg-zinc-800 text-zinc-300 shrink-0">2022 – 2026</span>
            </div>
            <p class="text-base text-zinc-200 font-medium mb-2">BA Journalism 新聞學系學士（Dual-Degree Integrated with MA）</p>
            <p class="text-xs text-emerald-400 font-medium mb-4">★ GPA: 3.89 / 4.0</p>
          </div>
          <p class="text-xs text-zinc-500 border-t border-zinc-800/80 pt-4">
            期間統籌電視、廣播與平面報紙三大校園媒體，並獲多項全國新聞競賽與全額/交換獎學金殊榮。
          </p>
        </div>
      </div>

      <!-- Awards & Campus Leadership Grid -->
      <div class="grid md:grid-cols-3 gap-6">
        <div class="p-6 rounded-2xl bg-zinc-900/60 border border-zinc-800/80">
          <div class="flex items-center gap-2 text-amber-400 font-semibold text-sm mb-3">
            <i data-lucide="trophy" class="w-4 h-4"></i>
            <span>Major Awards & Scholarships</span>
          </div>
          <ul class="space-y-2.5 text-xs text-zinc-300 leading-relaxed">
            <li><strong class="text-white">全國第一名（1st of 15 Universities）：</strong>2024 全國總編輯短影音競賽（National Editor-in-Chief Short-Form Video Competition）</li>
            <li><strong class="text-white">海外留學與交換學生獎學金：</strong>2025 Overseas Student & Exchange Scholarships</li>
            <li><strong class="text-white">世界傳播基金會獎學金：</strong>2023 Mass Media World Foundation Scholarship（全台灣僅 10 位得主之一）</li>
          </ul>
        </div>

        <div class="p-6 rounded-2xl bg-zinc-900/60 border border-zinc-800/80">
          <div class="flex items-center gap-2 text-indigo-400 font-semibold text-sm mb-3">
            <i data-lucide="radio" class="w-4 h-4"></i>
            <span>JNN 華岡電視台 & 廣播電台台長 (2024–25)</span>
          </div>
          <p class="text-xs text-zinc-400 leading-relaxed">
            擔任台長暨全國賽事總召（Station Manager & Chief Campaign Coordinator），領導 50 人團隊執行全國金牌主播與 Podcast 大賽，募得約 NT$450,000（£10,000）贊助，製作 50+ 件宣傳素材觸及 50,000+ 受眾；每學期督導產出 100+ 支影音新聞與 100+ 集 Podcast。
          </p>
        </div>

        <div class="p-6 rounded-2xl bg-zinc-900/60 border border-zinc-800/80">
          <div class="flex items-center gap-2 text-emerald-400 font-semibold text-sm mb-3">
            <i data-lucide="newspaper" class="w-4 h-4"></i>
            <span>《文化一周》報社總編輯 (2023–24)</span>
          </div>
          <p class="text-xs text-zinc-400 leading-relaxed">
            擔任總編輯（Editor-in-Chief），主導編採並交付約 20 期實體報紙發行（累計總印量達 ~100,000 份），個人親筆撰寫 15 篇深度報導，並於公視（PTS）數位平台創下最高 50,000+ 瀏覽量。
          </p>
        </div>
      </div>
    </div>
  </section>

  <!-- 平台生態、技能與證照 Skills, Platforms & Certifications -->
  <section id="skills" class="py-24 px-6 border-t border-zinc-900">
    <div class="max-w-6xl mx-auto">
      <p class="text-xs font-semibold uppercase tracking-widest text-indigo-400 mb-2">04 / Skills, Platforms & Certifications</p>
      <h2 class="text-3xl sm:text-4xl font-bold tracking-tight mb-12">跨國社群平台、製作工具與專業認證</h2>

      <div class="grid sm:grid-cols-2 lg:grid-cols-4 gap-6">
        <!-- 製作與設計 -->
        <div class="p-6 rounded-2xl bg-zinc-900/70 border border-zinc-800">
          <div class="w-10 h-10 rounded-xl bg-indigo-500/10 border border-indigo-500/20 flex items-center justify-center text-indigo-400 mb-4">
            <i data-lucide="video" class="w-5 h-5"></i>
          </div>
          <h3 class="font-bold text-white mb-3 text-sm">Video & Design 影音與視覺</h3>
          <div class="flex flex-wrap gap-2 mb-3">
            <span class="px-2.5 py-1 rounded-md bg-zinc-800 text-xs text-zinc-200 font-medium">Premiere Pro</span>
            <span class="px-2.5 py-1 rounded-md bg-zinc-800 text-xs text-zinc-200 font-medium">CapCut</span>
            <span class="px-2.5 py-1 rounded-md bg-zinc-800 text-xs text-zinc-200 font-medium">Canva</span>
          </div>
          <p class="text-xs text-zinc-400 leading-relaxed">
            專精社群短影音、活動紀錄片、AI 輔助短片產製，以及實體展會印刷物（海報、易拉展、傳單）與品牌周邊商品設計。
          </p>
        </div>

        <!-- 歐美與華語雙棲平台 -->
        <div class="p-6 rounded-2xl bg-zinc-900/70 border border-zinc-800">
          <div class="w-10 h-10 rounded-xl bg-fuchsia-500/10 border border-fuchsia-500/20 flex items-center justify-center text-fuchsia-400 mb-4">
            <i data-lucide="share-2" class="w-5 h-5"></i>
          </div>
          <h3 class="font-bold text-white mb-3 text-sm">Western & Chinese Social</h3>
          <p class="text-[11px] font-mono uppercase text-zinc-500 mb-1">Western Platforms</p>
          <p class="text-xs text-zinc-300 mb-3">Instagram, TikTok, YouTube, LinkedIn, Facebook</p>
          <p class="text-[11px] font-mono uppercase text-zinc-500 mb-1">Chinese Platforms</p>
          <p class="text-xs text-zinc-300">Douyin (抖音), Xiaohongshu (小紅書), Weibo (微博)</p>
        </div>

        <!-- 數據分析與官方認證 -->
        <div class="p-6 rounded-2xl bg-zinc-900/70 border border-zinc-800">
          <div class="w-10 h-10 rounded-xl bg-emerald-500/10 border border-emerald-500/20 flex items-center justify-center text-emerald-400 mb-4">
            <i data-lucide="badge-check" class="w-5 h-5"></i>
          </div>
          <h3 class="font-bold text-white mb-3 text-sm">Analytics & Certifications</h3>
          <ul class="space-y-2 text-xs text-zinc-300">
            <li class="flex items-center gap-2">
              <span class="w-1.5 h-1.5 rounded-full bg-emerald-400"></span>
              <span>Google Analytics Certified</span>
            </li>
            <li class="flex items-center gap-2">
              <span class="w-1.5 h-1.5 rounded-full bg-emerald-400"></span>
              <span>Google Ads Video Certified</span>
            </li>
            <li class="flex items-center gap-2">
              <span class="w-1.5 h-1.5 rounded-full bg-emerald-400"></span>
              <span>HubSpot Content Marketing Certified</span>
            </li>
            <li class="flex items-center gap-2">
              <span class="w-1.5 h-1.5 rounded-full bg-emerald-400"></span>
              <span>SEO & Competitor Research</span>
            </li>
          </ul>
        </div>

        <!-- 語言與英國工作權 -->
        <div class="p-6 rounded-2xl bg-zinc-900/70 border border-zinc-800">
          <div class="w-10 h-10 rounded-xl bg-amber-500/10 border border-amber-500/20 flex items-center justify-center text-amber-400 mb-4">
            <i data-lucide="languages" class="w-5 h-5"></i>
          </div>
          <h3 class="font-bold text-white mb-3 text-sm">Languages & UK Work Status</h3>
          <ul class="space-y-2 text-xs text-zinc-300">
            <li><strong class="text-white">Mandarin 中文：</strong>Native 母語</li>
            <li><strong class="text-white">English 英文：</strong>Fluent / Professional Working Proficiency</li>
            <li class="pt-2 border-t border-zinc-800 text-zinc-400">
              <strong class="text-emerald-400 block mb-0.5">UK Right to Work:</strong>
              Eligible for 2-year Graduate Route Visa (PSW).
            </li>
          </ul>
        </div>
      </div>
    </div>
  </section>

  <!-- 聯絡區塊 Contact & Footer -->
  <footer id="contact" class="pt-20 pb-12 px-6 bg-zinc-950 border-t border-zinc-800/80">
    <div class="max-w-6xl mx-auto">
      <div class="p-8 sm:p-12 rounded-3xl bg-gradient-to-br from-indigo-950/60 via-zinc-900 to-zinc-900 border border-indigo-500/20 flex flex-col lg:flex-row items-start lg:items-center justify-between gap-8 mb-12">
        <div>
          <span class="text-xs font-mono uppercase tracking-widest text-indigo-400">05 / Let's Connect</span>
          <h2 class="text-3xl sm:text-4xl font-bold text-white mt-2 mb-3">尋找兼具英中雙語與跨平台爆發力的內容製作人？</h2>
          <p class="text-zinc-400 text-sm max-w-xl leading-relaxed">
            目前常駐英國布萊頓（Brighton, UK），無論是全職社群影音職缺、品牌冷啟動短影音專案或跨文化行銷合作，歡迎直接透過電話、Email 或 LinkedIn 聯繫。
          </p>
        </div>
        <div class="flex flex-wrap gap-3 shrink-0">
          <a href="mailto:thomas930122uk@gmail.com" class="px-6 py-3.5 rounded-full bg-white text-zinc-950 font-semibold text-sm hover:bg-zinc-200 transition flex items-center gap-2">
            <i data-lucide="mail" class="w-4 h-4"></i>
            <span>thomas930122uk@gmail.com</span>
          </a>
          <a href="tel:+447570908988" class="px-5 py-3.5 rounded-full bg-zinc-800 text-white font-medium text-sm hover:bg-zinc-700 transition flex items-center gap-2">
            <i data-lucide="phone" class="w-4 h-4 text-indigo-400"></i>
            <span>+44 0757090 8988</span>
          </a>
          <a href="https://linkedin.com/in/thomas-hsieh" target="_blank" rel="noopener" class="px-5 py-3.5 rounded-full bg-zinc-800 text-white font-medium text-sm hover:bg-zinc-700 transition flex items-center gap-2">
            <i data-lucide="linkedin" class="w-4 h-4 text-indigo-400"></i>
            <span>LinkedIn</span>
          </a>
        </div>
      </div>

      <div class="flex flex-col sm:flex-row items-center justify-between text-xs text-zinc-500 pt-8 border-t border-zinc-900 gap-4">
        <p>© 2026 Thomas Hsieh 謝鎰丞. All rights reserved.</p>
        <p>Brighton, UK · +44 0757090 8988 · thomas930122uk@gmail.com</p>
      </div>
    </div>
  </footer>

  <!-- 互動腳本 -->
  <script>
    lucide.createIcons();

    // 手機選單切換
    const menuBtn = document.getElementById('menu-btn');
    const mobileMenu = document.getElementById('mobile-menu');
    menuBtn.addEventListener('click', () => {
      mobileMenu.classList.toggle('hidden');
    });
    mobileMenu.querySelectorAll('a').forEach(link => {
      link.addEventListener('click', () => mobileMenu.classList.add('hidden'));
    });

    // 專案篩選器
    const filterBtns = document.querySelectorAll('.filter-btn');
    const projectCards = document.querySelectorAll('.project-card');

    filterBtns.forEach(btn => {
      btn.addEventListener('click', () => {
        const filter = btn.getAttribute('data-filter');

        filterBtns.forEach(b => {
          b.classList.remove('bg-white', 'text-zinc-950');
          b.classList.add('bg-zinc-900', 'text-zinc-400');
        });
        btn.classList.add('bg-white', 'text-zinc-950');
        btn.classList.remove('bg-zinc-900', 'text-zinc-400');

        projectCards.forEach(card => {
          const category = card.getAttribute('data-category');
          if (filter === 'all' || category === filter) {
            card.classList.remove('hidden');
          } else {
            card.classList.add('hidden');
          }
        });
      });
    });
  </script>
</body>
</html>
