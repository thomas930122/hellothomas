<!DOCTYPE html>
<html lang="zh-Hant" class="scroll-smooth">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Thomas Hsieh 謝鎰丞 | Creative Media & Cultural Strategist</title>
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
          },
          colors: {
            brand: {
              dark: '#09090b',
              accent: '#6366f1',
            }
          }
        }
      }
    }
  </script>
  <style>
    /* 隱藏自訂捲軸但保留滾動功能 */
    .no-scrollbar::-webkit-scrollbar { display: none; }
    .no-scrollbar { -ms-overflow-style: none; scrollbar-width: none; }
  </style>
</head>
<body class="bg-zinc-950 text-zinc-100 font-sans antialiased selection:bg-indigo-500 selection:text-white">

  <!-- 頂部導覽列 -->
  <header class="fixed top-0 left-0 right-0 z-50 bg-zinc-950/80 backdrop-blur-md border-b border-zinc-800/80">
    <div class="max-w-6xl mx-auto px-6 h-20 flex items-center justify-between">
      <a href="#" class="text-xl font-bold tracking-tighter flex items-center gap-2">
        <span class="w-2.5 h-2.5 rounded-full bg-indigo-500 inline-block"></span>
        <span>THOMAS HSIEH</span>
        <span class="text-zinc-500 font-normal text-sm ml-1 hidden sm:inline">謝鎰丞</span>
      </a>

      <!-- 桌面版選單 -->
      <nav class="hidden md:flex items-center gap-8 text-sm font-medium text-zinc-400">
        <a href="#about" class="hover:text-white transition">About 關於</a>
        <a href="#projects" class="hover:text-white transition">Projects 精選專案</a>
        <a href="#experience" class="hover:text-white transition">Experience 經歷</a>
        <a href="#skills" class="hover:text-white transition">Skills 技能</a>
        <a href="#contact" class="px-4 py-2 rounded-full bg-white text-zinc-950 font-semibold hover:bg-zinc-200 transition">Contact 聯絡</a>
      </nav>

      <!-- 手機版選單按鈕 -->
      <button id="menu-btn" class="md:hidden text-zinc-400 hover:text-white">
        <i data-lucide="menu" class="w-6 h-6"></i>
      </button>
    </div>

    <!-- 手機版下拉選單 -->
    <div id="mobile-menu" class="hidden md:hidden bg-zinc-900 border-b border-zinc-800 px-6 py-4 space-y-3 text-sm">
      <a href="#about" class="block py-2 text-zinc-300 hover:text-white">About 關於</a>
      <a href="#projects" class="block py-2 text-zinc-300 hover:text-white">Projects 精選專案</a>
      <a href="#experience" class="block py-2 text-zinc-300 hover:text-white">Experience 經歷</a>
      <a href="#skills" class="block py-2 text-zinc-300 hover:text-white">Skills 技能</a>
      <a href="#contact" class="block py-2 text-indigo-400 font-semibold">Contact 聯絡</a>
    </div>
  </header>

  <!-- 主視覺 Hero Section -->
  <section class="relative pt-36 pb-24 md:pt-48 md:pb-32 px-6 overflow-hidden">
    <!-- 背景光暈裝飾 -->
    <div class="absolute top-1/4 -right-20 w-96 h-96 bg-indigo-600/15 rounded-full blur-3xl pointer-events-none"></div>
    <div class="absolute bottom-10 -left-20 w-80 h-80 bg-fuchsia-600/10 rounded-full blur-3xl pointer-events-none"></div>

    <div class="max-w-6xl mx-auto">
      <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-zinc-900 border border-zinc-800 text-xs text-zinc-400 mb-6">
        <span class="w-2 h-2 rounded-full bg-emerald-400 animate-pulse"></span>
        <span>Available for Global Creative & Media Projects</span>
      </div>

      <h1 class="text-4xl sm:text-6xl lg:text-7xl font-bold tracking-tight leading-[1.12] mb-8">
        Bridging <span class="font-serif italic font-normal text-indigo-400">Journalism</span>,<br>
        Cultural Strategy &<br>
        Visual Storytelling.
      </h1>

      <p class="max-w-2xl text-lg sm:text-xl text-zinc-400 font-light leading-relaxed mb-10">
        謝鎰丞（Thomas Hsieh），跨領域媒體製作人、視覺設計與文化創意策略師。畢業於英國薩塞克斯大學（University of Sussex）文化創意產業碩士與中國文化大學新聞學系，致力於結合新聞敘事、AI 媒體研究與品牌視覺策展。
      </p>

      <div class="flex flex-wrap items-center gap-4">
        <a href="#projects" class="px-7 py-3.5 rounded-full bg-indigo-600 hover:bg-indigo-500 text-white font-medium text-sm flex items-center gap-2 transition shadow-lg shadow-indigo-600/20">
          <span>瀏覽作品集 View Works</span>
          <i data-lucide="arrow-down-right" class="w-4 h-4"></i>
        </a>
        <a href="#contact" class="px-7 py-3.5 rounded-full bg-zinc-900 hover:bg-zinc-800 border border-zinc-800 text-zinc-300 font-medium text-sm transition">
          取得聯繫 Get in Touch
        </a>
      </div>

      <!-- 關鍵數據亮點 -->
      <div class="grid grid-cols-2 sm:grid-cols-4 gap-6 mt-20 pt-10 border-t border-zinc-800/80">
        <div>
          <p class="text-3xl font-bold text-white">1st Place</p>
          <p class="text-xs text-zinc-500 mt-1">2024 PeoPo 公民新聞短影音全國第一</p>
        </div>
        <div>
          <p class="text-3xl font-bold text-white">4+ Leads</p>
          <p class="text-xs text-zinc-500 mt-1">電視、廣播、報社與融媒體台長/總編</p>
        </div>
        <div>
          <p class="text-3xl font-bold text-white">MA & BA</p>
          <p class="text-xs text-zinc-500 mt-1">Sussex 碩士 & 文化新聞雙聯學位</p>
        </div>
        <div>
          <p class="text-3xl font-bold text-white">UK & TW</p>
          <p class="text-xs text-zinc-500 mt-1">跨國影展、媒體機構與藝文策展經驗</p>
        </div>
      </div>
    </div>
  </section>

  <!-- 關於與學歷 About & Education -->
  <section id="about" class="py-24 px-6 bg-zinc-900/40 border-y border-zinc-900">
    <div class="max-w-6xl mx-auto grid md:grid-cols-12 gap-12 items-start">
      <div class="md:col-span-5">
        <p class="text-xs font-semibold uppercase tracking-widest text-indigo-400 mb-2">01 / About & Education</p>
        <h2 class="text-3xl font-bold tracking-tight mb-6">從新聞現場到國際文創策展的跨域實踐者</h2>
        <p class="text-zinc-400 text-sm leading-relaxed mb-6">
          具備深厚的新聞傳播底蘊與跨國文化產業視野。在學期間曾同時統籌平面報紙、廣播、電視與融媒體中心，並參與國科會（NSTC）AI 新聞媒體應用研究；赴英攻讀碩士期間，深入英國布萊頓與倫敦在地藝文組織及歐洲國際影展，擅長將複雜的社會議題與品牌核心轉化為具渲染力的視覺與影音作品。
        </p>
      </div>

      <div class="md:col-span-7 space-y-6">
        <!-- 學歷卡片 1 -->
        <div class="p-6 rounded-2xl bg-zinc-900/90 border border-zinc-800/80 hover:border-zinc-700 transition">
          <div class="flex flex-wrap justify-between items-start gap-2 mb-2">
            <h3 class="text-lg font-bold text-white">University of Sussex 英國薩塞克斯大學</h3>
            <span class="text-xs px-2.5 py-1 rounded-full bg-indigo-500/10 text-indigo-400 border border-indigo-500/20">MA Degree</span>
          </div>
          <p class="text-sm text-zinc-300 font-medium mb-2">Master of Arts in Culture and Creative Industries 文化創意產業碩士</p>
          <p class="text-xs text-zinc-500 leading-relaxed">
            專注於數位行銷策略、文化政策、策展實務與自傳民族誌研究（完成 5,000 字英國藝文機構實務研究論文與產業作品集）。
          </p>
        </div>

        <!-- 學歷卡片 2 -->
        <div class="p-6 rounded-2xl bg-zinc-900/90 border border-zinc-800/80 hover:border-zinc-700 transition">
          <div class="flex flex-wrap justify-between items-start gap-2 mb-2">
            <h3 class="text-lg font-bold text-white">Chinese Culture University 中國文化大學</h3>
            <span class="text-xs px-2.5 py-1 rounded-full bg-zinc-800 text-zinc-300">3+1 雙聯學士</span>
          </div>
          <p class="text-sm text-zinc-300 font-medium mb-2">Bachelor of Arts in Journalism 新聞學系學士</p>
          <p class="text-xs text-zinc-500 leading-relaxed">
            擔任第 61 屆新聞系學會會長、國科會（NSTC）研究助理（指導教授：郭文平院長），並曾赴英國卡迪夫大學（Cardiff University）進行學術交流。
          </p>
        </div>
      </div>
    </div>
  </section>

  <!-- 精選作品集 Featured Projects -->
  <section id="projects" class="py-24 px-6">
    <div class="max-w-6xl mx-auto">
      <div class="flex flex-col md:flex-row md:items-end justify-between mb-12 gap-6">
        <div>
          <p class="text-xs font-semibold uppercase tracking-widest text-indigo-400 mb-2">02 / Selected Works</p>
          <h2 class="text-3xl sm:text-4xl font-bold tracking-tight">精選專案與策展作品</h2>
        </div>

        <!-- 分類篩選按鈕 -->
        <div class="flex flex-wrap gap-2" id="filter-buttons">
          <button data-filter="all" class="filter-btn active px-4 py-1.5 rounded-full text-xs font-medium bg-white text-zinc-950 transition">全部 All</button>
          <button data-filter="media" class="filter-btn px-4 py-1.5 rounded-full text-xs font-medium bg-zinc-900 text-zinc-400 hover:text-white border border-zinc-800 transition">新聞與影音 Media</button>
          <button data-filter="brand" class="filter-btn px-4 py-1.5 rounded-full text-xs font-medium bg-zinc-900 text-zinc-400 hover:text-white border border-zinc-800 transition">品牌與策展 Branding & Exhibition</button>
          <button data-filter="research" class="filter-btn px-4 py-1.5 rounded-full text-xs font-medium bg-zinc-900 text-zinc-400 hover:text-white border border-zinc-800 transition">學術與行銷策略 Strategy & Research</button>
        </div>
      </div>

      <!-- 作品網格 -->
      <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-6" id="project-grid">

        <!-- Project 1: Species Stories -->
        <article data-category="brand" class="project-card group rounded-2xl bg-zinc-900/70 border border-zinc-800/90 overflow-hidden hover:border-indigo-500/50 transition flex flex-col justify-between">
          <div>
            <div class="h-48 bg-gradient-to-br from-emerald-900/60 via-zinc-900 to-zinc-950 p-6 flex flex-col justify-between relative overflow-hidden">
              <span class="text-xs font-mono uppercase px-2.5 py-1 rounded bg-emerald-500/20 text-emerald-300 border border-emerald-500/30 w-fit">Exhibition Design</span>
              <i data-lucide="compass" class="w-16 h-16 text-emerald-500/20 absolute -bottom-2 -right-2 group-hover:scale-110 transition"></i>
              <h3 class="text-xl font-bold text-white z-10">"Species Stories" 英國國家公園巡迴展視覺設計</h3>
            </div>
            <div class="p-6">
              <p class="text-xs text-zinc-400 leading-relaxed mb-4">
                與英國 Writing Our Legacy 及 South Downs National Park Authority 合作，主導 850 × 2000 mm 大型展場易拉展（Pull-up Banner）與宣傳視覺系統設計，結合自然生態與多元族裔文化敘事。
              </p>
            </div>
          </div>
          <div class="px-6 pb-6 pt-3 border-t border-zinc-800/60 flex flex-wrap gap-1.5">
            <span class="text-[11px] px-2 py-0.5 rounded bg-zinc-800 text-zinc-300">Print Layout</span>
            <span class="text-[11px] px-2 py-0.5 rounded bg-zinc-800 text-zinc-300">Visual Identity</span>
            <span class="text-[11px] px-2 py-0.5 rounded bg-zinc-800 text-zinc-300">UK Arts Council Partner</span>
          </div>
        </article>

        <!-- Project 2: EYECORN -->
        <article data-category="brand" class="project-card group rounded-2xl bg-zinc-900/70 border border-zinc-800/90 overflow-hidden hover:border-indigo-500/50 transition flex flex-col justify-between">
          <div>
            <div class="h-48 bg-gradient-to-br from-fuchsia-900/50 via-zinc-900 to-zinc-950 p-6 flex flex-col justify-between relative overflow-hidden">
              <span class="text-xs font-mono uppercase px-2.5 py-1 rounded bg-fuchsia-500/20 text-fuchsia-300 border border-fuchsia-500/30 w-fit">E-Commerce & Packaging</span>
              <i data-lucide="sparkles" class="w-16 h-16 text-fuchsia-500/20 absolute -bottom-2 -right-2 group-hover:scale-110 transition"></i>
              <h3 class="text-xl font-bold text-white z-10">EYECORN 復古卡帶盒可重複使用假睫毛品牌</h3>
            </div>
            <div class="p-6">
              <p class="text-xs text-zinc-400 leading-relaxed mb-4">
                從零打造的電商美妝產品企劃，結合 Y2K 復古卡帶盒（Cassette-style Case）客製化包裝與環保可重複配戴概念，涵蓋產品結構視覺、品牌定位與社群商業模式。
              </p>
            </div>
          </div>
          <div class="px-6 pb-6 pt-3 border-t border-zinc-800/60 flex flex-wrap gap-1.5">
            <span class="text-[11px] px-2 py-0.5 rounded bg-zinc-800 text-zinc-300">Product Branding</span>
            <span class="text-[11px] px-2 py-0.5 rounded bg-zinc-800 text-zinc-300">Packaging Design</span>
            <span class="text-[11px] px-2 py-0.5 rounded bg-zinc-800 text-zinc-300">E-Commerce</span>
          </div>
        </article>

        <!-- Project 3: PeoPo Short Video -->
        <article data-category="media" class="project-card group rounded-2xl bg-zinc-900/70 border border-zinc-800/90 overflow-hidden hover:border-indigo-500/50 transition flex flex-col justify-between">
          <div>
            <div class="h-48 bg-gradient-to-br from-indigo-900/60 via-zinc-900 to-zinc-950 p-6 flex flex-col justify-between relative overflow-hidden">
              <span class="text-xs font-mono uppercase px-2.5 py-1 rounded bg-amber-500/20 text-amber-300 border border-amber-500/30 w-fit">1st Place Award</span>
              <i data-lucide="video" class="w-16 h-16 text-indigo-500/20 absolute -bottom-2 -right-2 group-hover:scale-110 transition"></i>
              <h3 class="text-xl font-bold text-white z-10">AI 信任危機與數位新聞近用權紀實短影音</h3>
            </div>
            <div class="p-6">
              <p class="text-xs text-zinc-400 leading-relaxed mb-4">
                榮獲 2024 PeoPo 公民新聞短影音競賽全國第一名（12 所大專院校角逐）。深入探討生成式 AI 時代下的假新聞辨識、閱聽人信任問題與弱勢群體的數位近用落差。
              </p>
            </div>
          </div>
          <div class="px-6 pb-6 pt-3 border-t border-zinc-800/60 flex flex-wrap gap-1.5">
            <span class="text-[11px] px-2 py-0.5 rounded bg-zinc-800 text-zinc-300">Mobile Journalism</span>
            <span class="text-[11px] px-2 py-0.5 rounded bg-zinc-800 text-zinc-300">Premiere Pro</span>
            <span class="text-[11px] px-2 py-0.5 rounded bg-zinc-800 text-zinc-300">AI Ethics</span>
          </div>
        </article>

        <!-- Project 4: 16th Golden Anchor Competition -->
        <article data-category="media" class="project-card group rounded-2xl bg-zinc-900/70 border border-zinc-800/90 overflow-hidden hover:border-indigo-500/50 transition flex flex-col justify-between">
          <div>
            <div class="h-48 bg-gradient-to-br from-blue-900/50 via-zinc-900 to-zinc-950 p-6 flex flex-col justify-between relative overflow-hidden">
              <span class="text-xs font-mono uppercase px-2.5 py-1 rounded bg-blue-500/20 text-blue-300 border border-blue-500/30 w-fit">National Event</span>
              <i data-lucide="mic" class="w-16 h-16 text-blue-500/20 absolute -bottom-2 -right-2 group-hover:scale-110 transition"></i>
              <h3 class="text-xl font-bold text-white z-10">第 16 屆全國大專院校金牌主播大賽（與 TVBS 合作）</h3>
            </div>
            <div class="p-6">
              <p class="text-xs text-zinc-400 leading-relaxed mb-4">
                擔任總召與核心策劃，串聯全國大專院校傳播科系與 TVBS 新聞台專業評審團，統籌賽事公關宣傳、轉播技術、舞台視覺與 40 人學生團隊跨部門協作。
              </p>
            </div>
          </div>
          <div class="px-6 pb-6 pt-3 border-t border-zinc-800/60 flex flex-wrap gap-1.5">
            <span class="text-[11px] px-2 py-0.5 rounded bg-zinc-800 text-zinc-300">Event Directing</span>
            <span class="text-[11px] px-2 py-0.5 rounded bg-zinc-800 text-zinc-300">Media Relations</span>
            <span class="text-[11px] px-2 py-0.5 rounded bg-zinc-800 text-zinc-300">Live Production</span>
          </div>
        </article>

        <!-- Project 5: NSTC AI in News Media Research -->
        <article data-category="research" class="project-card group rounded-2xl bg-zinc-900/70 border border-zinc-800/90 overflow-hidden hover:border-indigo-500/50 transition flex flex-col justify-between">
          <div>
            <div class="h-48 bg-gradient-to-br from-purple-900/50 via-zinc-900 to-zinc-950 p-6 flex flex-col justify-between relative overflow-hidden">
              <span class="text-xs font-mono uppercase px-2.5 py-1 rounded bg-purple-500/20 text-purple-300 border border-purple-500/30 w-fit">NSTC Research</span>
              <i data-lucide="cpu" class="w-16 h-16 text-purple-500/20 absolute -bottom-2 -right-2 group-hover:scale-110 transition"></i>
              <h3 class="text-xl font-bold text-white z-10">國科會計畫：生成式 AI 於新聞媒體產製流程與規範研究</h3>
            </div>
            <div class="p-6">
              <p class="text-xs text-zinc-400 leading-relaxed mb-4">
                擔任國科會研究助理，深度訪談 7 位台灣一線新聞媒體高層與資深記者，剖析 AI 工具在新聞編輯室的實際導入產值、編採倫理邊界與禁用規範。
              </p>
            </div>
          </div>
          <div class="px-6 pb-6 pt-3 border-t border-zinc-800/60 flex flex-wrap gap-1.5">
            <span class="text-[11px] px-2 py-0.5 rounded bg-zinc-800 text-zinc-300">Qualitative Interview</span>
            <span class="text-[11px] px-2 py-0.5 rounded bg-zinc-800 text-zinc-300">AI Journalism</span>
            <span class="text-[11px] px-2 py-0.5 rounded bg-zinc-800 text-zinc-300">Policy Analysis</span>
          </div>
        </article>

        <!-- Project 6: Vinted & Hackney Moves Strategy -->
        <article data-category="research" class="project-card group rounded-2xl bg-zinc-900/70 border border-zinc-800/90 overflow-hidden hover:border-indigo-500/50 transition flex flex-col justify-between">
          <div>
            <div class="h-48 bg-gradient-to-br from-rose-900/50 via-zinc-900 to-zinc-950 p-6 flex flex-col justify-between relative overflow-hidden">
              <span class="text-xs font-mono uppercase px-2.5 py-1 rounded bg-rose-500/20 text-rose-300 border border-rose-500/30 w-fit">Digital PR & Strategy</span>
              <i data-lucide="trending-up" class="w-16 h-16 text-rose-500/20 absolute -bottom-2 -right-2 group-hover:scale-110 transition"></i>
              <h3 class="text-xl font-bold text-white z-10">Vinted 數位行銷剖析 & 倫敦 Hackney Moves 公關策劃</h3>
            </div>
            <div class="p-6">
              <p class="text-xs text-zinc-400 leading-relaxed mb-4">
                包含針對歐洲二手時尚電商 Vinted 之 2,500 字循環經濟數位行銷深度報告，以及為倫敦 Hackney Moves Festival 2026 制定的大型社區運動節慶整合公關提案。
              </p>
            </div>
          </div>
          <div class="px-6 pb-6 pt-3 border-t border-zinc-800/60 flex flex-wrap gap-1.5">
            <span class="text-[11px] px-2 py-0.5 rounded bg-zinc-800 text-zinc-300">Digital Marketing</span>
            <span class="text-[11px] px-2 py-0.5 rounded bg-zinc-800 text-zinc-300">PR Campaign</span>
            <span class="text-[11px] px-2 py-0.5 rounded bg-zinc-800 text-zinc-300">UK Market</span>
          </div>
        </article>

      </div>
    </div>
  </section>

  <!-- 實務與領導經歷 Experience Timeline -->
  <section id="experience" class="py-24 px-6 bg-zinc-900/40 border-y border-zinc-900">
    <div class="max-w-6xl mx-auto">
      <p class="text-xs font-semibold uppercase tracking-widest text-indigo-400 mb-2">03 / Career & Leadership</p>
      <h2 class="text-3xl sm:text-4xl font-bold tracking-tight mb-12">跨國實務與校園媒體領導經歷</h2>

      <div class="grid md:grid-cols-2 gap-12">
        <!-- 左欄：國際與產業實務 -->
        <div>
          <h3 class="text-sm font-mono uppercase tracking-wider text-zinc-400 mb-6 flex items-center gap-2">
            <i data-lucide="globe" class="w-4 h-4 text-indigo-400"></i>
            <span>Industry & International Experience</span>
          </h3>

          <div class="space-y-8 border-l border-zinc-800 pl-6">
            <div class="relative">
              <span class="w-3 h-3 rounded-full bg-indigo-500 absolute -left-[30.5px] top-1.5 ring-4 ring-zinc-950"></span>
              <span class="text-xs font-mono text-indigo-400">2026 · Brighton, UK</span>
              <h4 class="text-lg font-bold text-white mt-0.5">Writing Our Legacy 藝文傳播與視覺設計顧問</h4>
              <p class="text-xs text-zinc-400 mt-1 leading-relaxed">
                於英國布萊頓非營利多元文化藝術組織完成實習並轉任自由接案設計師（與執行長 Amy Glass 合作），負責雙語影音字幕製作、活動宣傳品與英國國家公園展覽視覺設計。
              </p>
            </div>

            <div class="relative">
              <span class="w-3 h-3 rounded-full bg-zinc-700 absolute -left-[30.5px] top-1.5 ring-4 ring-zinc-950"></span>
              <span class="text-xs font-mono text-zinc-400">2026 · Berlin, Germany</span>
              <h4 class="text-lg font-bold text-white mt-0.5">德國柏林國際影展 & 柏林台灣影展 活動執行志工</h4>
              <p class="text-xs text-zinc-400 mt-1 leading-relaxed">
                參與德國柏林影展（Berlinale）及 Impression Taiwan e.V. 主辦之 2026 柏林台灣影展（Taiwan Film Festival Berlin），協助國際影人接待、映後座談與現場活動管理。
              </p>
            </div>

            <div class="relative">
              <span class="w-3 h-3 rounded-full bg-zinc-700 absolute -left-[30.5px] top-1.5 ring-4 ring-zinc-950"></span>
              <span class="text-xs font-mono text-zinc-400">Hunan, China</span>
              <h4 class="text-lg font-bold text-white mt-0.5">湖南衛視 芒果 TV+ 大型活動中心 實習生</h4>
              <p class="text-xs text-zinc-400 mt-1 leading-relaxed">
                參與大型綜藝與晚會專案執行，協助跨平台短影音內容剪輯、腳本發想與現場執行調度。
              </p>
            </div>
          </div>
        </div>

        <!-- 右欄：校園四大媒體領袖 -->
        <div>
          <h3 class="text-sm font-mono uppercase tracking-wider text-zinc-400 mb-6 flex items-center gap-2">
            <i data-lucide="award" class="w-4 h-4 text-indigo-400"></i>
            <span>Campus Media & Leadership</span>
          </h3>

          <div class="space-y-8 border-l border-zinc-800 pl-6">
            <div class="relative">
              <span class="w-3 h-3 rounded-full bg-indigo-500 absolute -left-[30.5px] top-1.5 ring-4 ring-zinc-950"></span>
              <span class="text-xs font-mono text-indigo-400">Editor-in-Chief & Director</span>
              <h4 class="text-lg font-bold text-white mt-0.5">《文化一周》第 62 屆總編輯 & 華岡融媒體第 4 屆台長</h4>
              <p class="text-xs text-zinc-400 mt-1 leading-relaxed">
                統籌每週發行量達 5,000 份之實體報紙編採與版面視覺，並帶領融媒體中心進行跨媒介數位轉型與專題報導。
              </p>
            </div>

            <div class="relative">
              <span class="w-3 h-3 rounded-full bg-zinc-700 absolute -left-[30.5px] top-1.5 ring-4 ring-zinc-950"></span>
              <span class="text-xs font-mono text-zinc-400">Station Manager</span>
              <h4 class="text-lg font-bold text-white mt-0.5">華岡電視台（JNN）第 23 屆台長 & 華岡廣播電台第 28 屆台長</h4>
              <p class="text-xs text-zinc-400 mt-1 leading-relaxed">
                罕見橫跨電視與廣播雙棲台長經歷，管理攝影棚主播排班、新聞專題製播、Podcast 聲音節目企劃與成音工程。
              </p>
            </div>

            <div class="relative">
              <span class="w-3 h-3 rounded-full bg-zinc-700 absolute -left-[30.5px] top-1.5 ring-4 ring-zinc-950"></span>
              <span class="text-xs font-mono text-zinc-400">Student President</span>
              <h4 class="text-lg font-bold text-white mt-0.5">中國文化大學第 61 屆新聞系學會會長</h4>
              <p class="text-xs text-zinc-400 mt-1 leading-relaxed">
                帶領 40 人幹部團隊，主辦全國大專院校金牌主播大賽與系際大型活動，強化產學連結與學生社群凝聚力。
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- 技能與工具箱 Skills & Toolkit -->
  <section id="skills" class="py-24 px-6">
    <div class="max-w-6xl mx-auto">
      <p class="text-xs font-semibold uppercase tracking-widest text-indigo-400 mb-2">04 / Capabilities & Toolkit</p>
      <h2 class="text-3xl sm:text-4xl font-bold tracking-tight mb-12">專業技能與數位工作流</h2>

      <div class="grid sm:grid-cols-2 lg:grid-cols-4 gap-6">
        <!-- 類別 1 -->
        <div class="p-6 rounded-2xl bg-zinc-900/60 border border-zinc-800">
          <div class="w-10 h-10 rounded-xl bg-indigo-500/10 border border-indigo-500/20 flex items-center justify-center text-indigo-400 mb-4">
            <i data-lucide="film" class="w-5 h-5"></i>
          </div>
          <h3 class="font-bold text-white mb-3">影音製作與後製</h3>
          <ul class="space-y-2 text-xs text-zinc-400">
            <li>• Adobe Premiere Pro / CapCut</li>
            <li>• ASS 特效字幕與中英雙語字幕規範</li>
            <li>• 新聞專題採訪、棚內導播與音控</li>
            <li>• Suno AI 音樂生成與詞曲概念創作</li>
          </ul>
        </div>

        <!-- 類別 2 -->
        <div class="p-6 rounded-2xl bg-zinc-900/60 border border-zinc-800">
          <div class="w-10 h-10 rounded-xl bg-fuchsia-500/10 border border-fuchsia-500/20 flex items-center justify-center text-fuchsia-400 mb-4">
            <i data-lucide="pen-tool" class="w-5 h-5"></i>
          </div>
          <h3 class="font-bold text-white mb-3">視覺與空間設計</h3>
          <ul class="space-y-2 text-xs text-zinc-400">
            <li>• Figma UI/UX 介面與原型設計</li>
            <li>• Canva 品牌視覺系統與社群素材</li>
            <li>• 大型展場輸出物（A2 海報、易拉展）</li>
            <li>• 3D 室內空間配置與產品包裝概念</li>
          </ul>
        </div>

        <!-- 類別 3 -->
        <div class="p-6 rounded-2xl bg-zinc-900/60 border border-zinc-800">
          <div class="w-10 h-10 rounded-xl bg-emerald-500/10 border border-emerald-500/20 flex items-center justify-center text-emerald-400 mb-4">
            <i data-lucide="Sparkles" class="w-5 h-5"></i>
          </div>
          <h3 class="font-bold text-white mb-3">AI 協作與專案管理</h3>
          <ul class="space-y-2 text-xs text-zinc-400">
            <li>• Gemini / Claude / ChatGPT / Grok</li>
            <li>• Notion 知識庫與跨部門敏捷管理</li>
            <li>• AI 媒體倫理研究與數位轉型顧問</li>
            <li>• 跨文化團隊溝通（繁中 / 英文）</li>
          </ul>
        </div>

        <!-- 類別 4 -->
        <div class="p-6 rounded-2xl bg-zinc-900/60 border border-zinc-800">
          <div class="w-10 h-10 rounded-xl bg-amber-500/10 border border-amber-500/20 flex items-center justify-center text-amber-400 mb-4">
            <i data-lucide="megaphone" class="w-5 h-5"></i>
          </div>
          <h3 class="font-bold text-white mb-3">文化策展與公關行銷</h3>
          <ul class="space-y-2 text-xs text-zinc-400">
            <li>• 國際影展與大型賽事活動統籌</li>
            <li>• 品牌數位行銷與循環經濟策略</li>
            <li>• 媒體公關稿撰寫與議題設定</li>
            <li>• 影視文本分析與自傳民族誌研究</li>
          </ul>
        </div>
      </div>
    </div>
  </section>

  <!-- 聯絡區塊 Contact & Footer -->
  <footer id="contact" class="pt-24 pb-12 px-6 bg-zinc-950 border-t border-zinc-800/80">
    <div class="max-w-6xl mx-auto">
      <div class="p-8 sm:p-12 rounded-3xl bg-gradient-to-br from-indigo-950/60 via-zinc-900 to-zinc-900 border border-indigo-500/20 flex flex-col md:flex-row items-start md:items-center justify-between gap-8 mb-16">
        <div>
          <span class="text-xs font-mono uppercase tracking-widest text-indigo-400">05 / Let's Collaborate</span>
          <h2 class="text-3xl sm:text-4xl font-bold text-white mt-2 mb-3">準備好展開下一個跨界專案了嗎？</h2>
          <p class="text-zinc-400 text-sm max-w-xl">
            無論是國際文化策展、品牌視覺設計、中英雙語影音製作，或是新聞媒體與 AI 策略合作，歡迎隨時與我聯繫。
          </p>
        </div>
        <div class="flex flex-wrap gap-4 shrink-0">
          <a href="mailto:thomas.hsieh@example.com" class="px-6 py-3.5 rounded-full bg-white text-zinc-950 font-semibold text-sm hover:bg-zinc-200 transition flex items-center gap-2">
            <i data-lucide="mail" class="w-4 h-4"></i>
            <span>發送郵件 Email Me</span>
          </a>
          <a href="https://www.linkedin.com" target="_blank" rel="noopener" class="px-6 py-3.5 rounded-full bg-zinc-800 text-white font-medium text-sm hover:bg-zinc-700 transition flex items-center gap-2">
            <i data-lucide="linkedin" class="w-4 h-4"></i>
            <span>LinkedIn</span>
          </a>
        </div>
      </div>

      <div class="flex flex-col sm:flex-row items-center justify-between text-xs text-zinc-500 pt-8 border-t border-zinc-900 gap-4">
        <p>© 2026 Thomas Hsieh 謝鎰丞. All rights reserved.</p>
        <p class="flex items-center gap-4">
          <span>Taipei, Taiwan</span>
          <span>•</span>
          <span>Brighton & London, UK</span>
        </p>
      </div>
    </div>
  </footer>

  <!-- 互動腳本：圖示渲染、手機選單與作品篩選 -->
  <script>
    // 初始化 Lucide Icons
    lucide.createIcons();

    // 手機版選單切換
    const menuBtn = document.getElementById('menu-btn');
    const mobileMenu = document.getElementById('mobile-menu');
    menuBtn.addEventListener('click', () => {
      mobileMenu.classList.toggle('hidden');
    });

    // 點擊手機選單連結後自動收合
    mobileMenu.querySelectorAll('a').forEach(link => {
      link.addEventListener('click', () => mobileMenu.classList.add('hidden'));
    });

    // 專案作品分類篩選器
    const filterBtns = document.querySelectorAll('.filter-btn');
    const projectCards = document.querySelectorAll('.project-card');

    filterBtns.forEach(btn => {
      btn.addEventListener('click', () => {
        const filter = btn.getAttribute('data-filter');

        // 更新按鈕樣式
        filterBtns.forEach(b => {
          b.classList.remove('bg-white', 'text-zinc-950');
          b.classList.add('bg-zinc-900', 'text-zinc-400');
        });
        btn.classList.add('bg-white', 'text-zinc-950');
        btn.classList.remove('bg-zinc-900', 'text-zinc-400');

        // 篩選卡片
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
