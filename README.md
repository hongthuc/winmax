<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0" />
  <title>CÔNG TY TNHH MTV CƠ KHÍ XÂY DỰNG WINMAX | Cửa Nhôm Xingfa & Kính Cường Lực Đà Nẵng</title>
  <meta name="description" content="CÔNG TY TNHH MỘT THÀNH VIÊN CƠ KHÍ XÂY DỰNG WINMAX - Chuyên thiết kế, sản xuất và thi công Cửa nhôm Xingfa, Cửa kính cường lực, Cầu thang kính, Phòng tắm kính tại Đà Nẵng. Hotline: 0986.486.426." />

  <!-- Open Graph / Thumbnail chia sẻ link là Logo WINMAX -->
  <meta property="og:type" content="website" />
  <meta property="og:url" content="https://winmax.com/" />
  <meta property="og:site_name" content="WINMAX - Cơ Khí Xây Dựng Đà Nẵng" />
  <meta property="og:title" content="CÔNG TY TNHH MTV CƠ KHÍ XÂY DỰNG WINMAX - Cửa Nhôm Xingfa Đà Nẵng" />
  <meta property="og:description" content="Thi công cửa nhôm Xingfa nhập khẩu, cửa kính cường lực, cầu thang kính, phòng tắm kính uy tín tại Đà Nẵng. Hotline: 0986.486.426." />
  <meta property="og:image" content="https://lh3.googleusercontent.com/d/1XnfU1DR3Th9wEXJ8aGm4mdkrEEg2Ju9e=w1200" />
  <meta property="og:image:width" content="1200" />
  <meta property="og:image:height" content="630" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="CÔNG TY TNHH MTV CƠ KHÍ XÂY DỰNG WINMAX" />
  <meta name="twitter:description" content="Cửa nhôm Xingfa, Cửa kính cường lực chính hãng tại Đà Nẵng - Hotline: 0986.486.426" />
  <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1XnfU1DR3Th9wEXJ8aGm4mdkrEEg2Ju9e=w1200" />
  <link rel="icon" type="image/png" href="https://lh3.googleusercontent.com/d/1XnfU1DR3Th9wEXJ8aGm4mdkrEEg2Ju9e=w256" />

  <!-- Font Inter & Font Awesome Icons -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet" />
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" />

  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'sans-serif'],
          },
          colors: {
            brand: {
              DEFAULT: '#0B4A7D',
              dark: '#07355C',
              light: '#1466A8',
              soft: '#EEF5FB',
            },
            accent: {
              DEFAULT: '#D92626',
              dark: '#B51D1D',
              soft: '#FEF2F2',
            }
          }
        }
      }
    };
  </script>

  <style>
    /* Thiết lập cơ bản chống tràn viền ngang trên mọi thiết bị */
    *, *::before, *::after {
      box-sizing: border-box;
    }
    html, body {
      margin: 0;
      padding: 0;
      width: 100%;
      max-width: 100%;
      overflow-x: hidden;
      font-family: 'Inter', sans-serif;
      color: #1E293B;
      background-color: #FFFFFF;
      scroll-behavior: smooth;
    }

    /* Chiều ngang chuẩn 95% trên máy tính theo yêu cầu */
    .winmax-container {
      width: 100%;
      max-width: 100%;
      margin-left: auto;
      margin-right: auto;
      padding-left: 12px;
      padding-right: 12px;
    }
    @media (min-width: 1024px) {
      .winmax-container {
        width: 95%;
        max-width: 95%;
        padding-left: 0px;
        padding-right: 0px;
      }
    }

    /* Dropdown menu Flatsome trên máy tính */
    .nav-dropdown-wrap {
      position: relative;
    }
    .nav-dropdown-menu {
      opacity: 0;
      visibility: hidden;
      transform: translateY(8px);
      transition: all 0.2s ease;
    }
    .nav-dropdown-wrap:hover .nav-dropdown-menu,
    .nav-dropdown-wrap:focus-within .nav-dropdown-menu {
      opacity: 1;
      visibility: visible;
      transform: translateY(0px);
    }

    /* Banner 2 slide đồng nhất kích thước tuyệt đối không mất chữ */
    .hero-grid-slider {
      display: grid;
      grid-template-columns: 1fr;
    }
    .hero-slide {
      grid-area: 1 / 1 / 2 / 2;
      transition: opacity 0.65s ease, transform 0.65s ease;
      opacity: 0;
      pointer-events: none;
      z-index: 1;
    }
    .hero-slide.active {
      opacity: 1;
      pointer-events: auto;
      z-index: 2;
    }

    /* Tiêu đề Flatsome có gạch chân tinh gọn */
    .flatsome-title {
      position: relative;
      display: inline-block;
      padding-bottom: 10px;
    }
    .flatsome-title::after {
      content: '';
      position: absolute;
      left: 50%;
      bottom: 0px;
      transform: translateX(-50%);
      width: 64px;
      height: 3px;
      background-color: #D92626;
      border-radius: 999px;
    }
    .flatsome-title-left::after {
      left: 0px;
      transform: none;
    }

    /* Hiệu ứng rung nhẹ cho nút Hotline nổi */
    @keyframes ringPulse {
      0%, 100% { transform: scale(1); box-shadow: 0 0 0 0 rgba(217, 38, 38, 0.45); }
      50% { transform: scale(1.06); box-shadow: 0 0 0 10px rgba(217, 38, 38, 0); }
    }
    .btn-hotline-pulse {
      animation: ringPulse 2.2s infinite;
    }
  </style>
</head>
<body class="bg-white text-slate-800 antialiased">

  <!-- ===================================================================== -->
  <!-- UX BUILDER: TOP BAR THÔNG TIN (Gọn gàng chuẩn Flatsome)               -->
  <!-- ===================================================================== -->
  <div class="bg-brand-dark text-white text-xs py-2 border-b border-white/10">
    <div class="winmax-container flex flex-wrap items-center justify-between gap-2">
      <div class="flex flex-wrap items-center gap-x-4 gap-y-1">
        <span class="inline-flex items-center gap-1.5">
          <i class="fa-solid fa-location-dot text-accent"></i>
          <span>54 Nguyễn Thị Cận, Phường Hòa Khánh, TP Đà Nẵng</span>
        </span>
        <span class="hidden sm:inline-flex items-center gap-1.5 text-slate-200">
          <i class="fa-regular fa-clock text-sky-300"></i>
          <span>Làm việc: 07:30 - 17:30 (T2 - T7)</span>
        </span>
      </div>
      <div class="hidden md:flex items-center gap-4 text-slate-200">
        <span><i class="fa-solid fa-globe mr-1 text-sky-300"></i>winmax.com</span>
        <span><i class="fa-solid fa-phone mr-1 text-sky-300"></i>0986.486.426</span>
      </div>
    </div>
  </div>

  <!-- ===================================================================== -->
  <!-- UX BUILDER: HEADER CHÍNH (Logo gọn nhỏ, tìm kiếm, không có nút Gọi ngay) -->
  <!-- ===================================================================== -->
  <header id="site-header" class="sticky top-0 z-40 bg-white shadow-sm border-b border-slate-200">
    <div class="winmax-container py-2.5 flex items-center justify-between gap-3">
      <!-- Nút mở menu trên điện thoại -->
      <button
        id="mobileMenuBtn"
        type="button"
        aria-label="Mở danh mục"
        class="lg:hidden inline-flex items-center justify-center w-10 h-10 rounded-lg border border-slate-200 text-brand hover:bg-brand-soft transition"
      >
        <i class="fa-solid fa-bars text-lg"></i>
      </button>

      <!-- Logo WINMAX chỉnh gọn nhỏ lại -->
      <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 min-w-0">
        <img
          src="https://lh3.googleusercontent.com/d/1XnfU1DR3Th9wEXJ8aGm4mdkrEEg2Ju9e=w400"
          data-drive-id="1XnfU1DR3Th9wEXJ8aGm4mdkrEEg2Ju9e"
          alt="Logo Công Ty Cơ Khí Xây Dựng WINMAX"
          class="h-10 sm:h-11 lg:h-12 w-auto max-w-[140px] object-contain rounded"
          onerror="handleDriveFallback(this, 'WINMAX')"
        />
        <div class="hidden sm:flex flex-col leading-tight">
          <span class="text-sm lg:text-base font-extrabold text-brand tracking-tight">WINMAX</span>
          <span class="text-[11px] text-slate-500 font-medium">Cơ Khí Xây Dựng Đà Nẵng</span>
        </div>
      </a>

      <!-- Thanh tìm kiếm sản phẩm chuẩn Flatsome (Desktop & Tablet) -->
      <form id="searchForm" class="hidden md:flex flex-1 max-w-xl mx-4 items-center bg-slate-50 border border-slate-300 rounded-lg overflow-hidden focus-within:border-brand focus-within:ring-1 focus-within:ring-brand transition">
        <select id="searchCategory" aria-label="Chọn danh mục tìm kiếm" class="bg-slate-100 text-slate-700 text-xs font-medium px-3 py-2.5 border-r border-slate-300 outline-none cursor-pointer">
          <option value="all">Tất cả danh mục</option>
          <option value="xingfa">Cửa nhôm Xingfa</option>
          <option value="nhua">Cửa nhựa lõi thép</option>
          <option value="tudong">Cửa kính tự động</option>
          <option value="cauthang">Cầu thang kính</option>
          <option value="bep">Kính ốp bếp</option>
          <option value="tam">Phòng tắm kính</option>
        </select>
        <input
          id="searchInput"
          type="text"
          placeholder="Tìm cửa nhôm Xingfa 1 cánh, 2 cánh, 4 cánh, xếp trượt..."
          class="flex-1 bg-transparent px-3 py-2 text-xs lg:text-sm text-slate-700 outline-none min-w-0"
        />
        <button type="submit" aria-label="Tìm kiếm" class="bg-brand hover:bg-brand-dark text-white px-4 py-2.5 text-sm transition">
          <i class="fa-solid fa-magnifying-glass"></i>
        </button>
      </form>

      <!-- Khu vực phải: Chỉ để nút Yêu cầu báo giá gọn hoặc nút tìm kiếm mobile (KHÔNG để nút Gọi ngay) -->
      <div class="flex items-center gap-2 shrink-0">
        <button
          id="mobileSearchToggle"
          type="button"
          aria-label="Tìm kiếm sản phẩm"
          class="md:hidden inline-flex items-center justify-center w-10 h-10 rounded-lg border border-slate-200 text-slate-700 hover:bg-slate-100 transition"
        >
          <i class="fa-solid fa-magnifying-glass text-sm"></i>
        </button>
        <a
          href="#form-bao-gia"
          class="hidden lg:inline-flex items-center gap-2 px-3.5 py-2 rounded-lg bg-brand-soft text-brand border border-brand/20 hover:bg-brand hover:text-white text-xs font-semibold transition whitespace-nowrap"
        >
          <i class="fa-regular fa-file-lines"></i>
          <span>Nhận báo giá</span>
        </a>
      </div>
    </div>

    <!-- Thanh tìm kiếm thả xuống trên điện thoại -->
    <div id="mobileSearchBox" class="hidden md:hidden border-t border-slate-200 bg-slate-50 px-3 py-2.5">
      <form id="mobileSearchForm" class="flex items-center bg-white border border-slate-300 rounded-lg overflow-hidden">
        <input
          id="mobileSearchInput"
          type="text"
          placeholder="Tìm sản phẩm cửa nhôm Xingfa, kính..."
          class="flex-1 px-3 py-2 text-sm outline-none min-w-0"
        />
        <button type="submit" class="bg-brand text-white px-4 py-2 text-sm">
          <i class="fa-solid fa-magnifying-glass"></i>
        </button>
      </form>
    </div>

    <!-- =================================================================== -->
    <!-- UX BUILDER: THANH DANH MỤC CHÍNH DESKTOP (1 HÀNG DUY NHẤT, KHÔNG XUỐNG DÒNG TÊN) -->
    <!-- =================================================================== -->
    <nav aria-label="Danh mục chính" class="hidden lg:block bg-brand text-white">
      <div class="winmax-container">
        <ul class="flex flex-wrap items-center justify-center gap-x-1 xl:gap-x-2 py-0 text-[12px] xl:text-[13px] font-semibold uppercase tracking-tight">
          <li>
            <a href="#trang-chu" class="block px-2.5 xl:px-3.5 py-3 whitespace-nowrap hover:bg-brand-dark transition rounded-t">
              Trang chủ
            </a>
          </li>
          <li>
            <a href="#gioi-thieu" class="block px-2.5 xl:px-3.5 py-3 whitespace-nowrap hover:bg-brand-dark transition rounded-t">
              Giới thiệu
            </a>
          </li>

          <!-- Dropdown: Cửa nhôm xingfa -->
          <li class="nav-dropdown-wrap">
            <a href="#san-pham-xingfa" class="flex items-center gap-1 px-2.5 xl:px-3.5 py-3 whitespace-nowrap hover:bg-brand-dark transition rounded-t">
              <span>Cửa nhôm xingfa</span>
              <i class="fa-solid fa-chevron-down text-[10px] opacity-80"></i>
            </a>
            <ul class="nav-dropdown-menu absolute left-0 top-full w-56 bg-white text-slate-700 shadow-xl rounded-b-lg border border-slate-200 py-1.5 z-50 normal-case font-medium text-[13px]">
              <li><a href="#san-pham-xingfa" onclick="filterProducts('1-canh')" class="block px-4 py-2 hover:bg-brand-soft hover:text-brand whitespace-nowrap transition">Cửa nhôm xingfa 1 cánh</a></li>
              <li><a href="#san-pham-xingfa" onclick="filterProducts('2-canh')" class="block px-4 py-2 hover:bg-brand-soft hover:text-brand whitespace-nowrap transition">Cửa nhôm xingfa 2 cánh</a></li>
              <li><a href="#san-pham-xingfa" onclick="filterProducts('3-canh')" class="block px-4 py-2 hover:bg-brand-soft hover:text-brand whitespace-nowrap transition">Cửa nhôm xingfa 3 cánh</a></li>
              <li><a href="#san-pham-xingfa" onclick="filterProducts('4-canh')" class="block px-4 py-2 hover:bg-brand-soft hover:text-brand whitespace-nowrap transition">Cửa nhôm xingfa 4 cánh</a></li>
              <li><a href="#san-pham-xingfa" onclick="filterProducts('5-canh')" class="block px-4 py-2 hover:bg-brand-soft hover:text-brand whitespace-nowrap transition">Cửa nhôm xingfa 5 cánh</a></li>
            </ul>
          </li>

          <li>
            <a href="#danh-muc-san-pham" class="block px-2.5 xl:px-3.5 py-3 whitespace-nowrap hover:bg-brand-dark transition rounded-t">
              Cửa kính cường lực
            </a>
          </li>

          <!-- Dropdown: Sản phẩm -->
          <li class="nav-dropdown-wrap">
            <a href="#danh-muc-san-pham" class="flex items-center gap-1 px-2.5 xl:px-3.5 py-3 whitespace-nowrap hover:bg-brand-dark transition rounded-t">
              <span>Sản phẩm</span>
              <i class="fa-solid fa-chevron-down text-[10px] opacity-80"></i>
            </a>
            <ul class="nav-dropdown-menu absolute left-0 top-full w-56 bg-white text-slate-700 shadow-xl rounded-b-lg border border-slate-200 py-1.5 z-50 normal-case font-medium text-[13px]">
              <li><a href="#san-pham-xingfa" onclick="filterProducts('all')" class="block px-4 py-2 hover:bg-brand-soft hover:text-brand whitespace-nowrap transition">Cửa nhôm xingfa</a></li>
              <li><a href="#danh-muc-san-pham" onclick="openCategoryModal('Cửa nhựa lõi thép')" class="block px-4 py-2 hover:bg-brand-soft hover:text-brand whitespace-nowrap transition">Cửa nhựa lõi thép</a></li>
              <li><a href="#danh-muc-san-pham" onclick="openCategoryModal('Cửa kính tự động')" class="block px-4 py-2 hover:bg-brand-soft hover:text-brand whitespace-nowrap transition">Cửa kính tự động</a></li>
              <li><a href="#danh-muc-san-pham" onclick="openCategoryModal('Cầu thang kính')" class="block px-4 py-2 hover:bg-brand-soft hover:text-brand whitespace-nowrap transition">Cầu thang kính</a></li>
              <li><a href="#danh-muc-san-pham" onclick="openCategoryModal('Kính ốp bếp')" class="block px-4 py-2 hover:bg-brand-soft hover:text-brand whitespace-nowrap transition">Kính ốp bếp</a></li>
              <li><a href="#danh-muc-san-pham" onclick="openCategoryModal('Phòng tắm kính')" class="block px-4 py-2 hover:bg-brand-soft hover:text-brand whitespace-nowrap transition">Phòng tắm kính</a></li>
            </ul>
          </li>

          <li>
            <a href="#cong-trinh" class="block px-2.5 xl:px-3.5 py-3 whitespace-nowrap hover:bg-brand-dark transition rounded-t">
              Công trình
            </a>
          </li>
          <li>
            <a href="#bao-gia" class="block px-2.5 xl:px-3.5 py-3 whitespace-nowrap hover:bg-brand-dark transition rounded-t">
              Báo giá
            </a>
          </li>
          <li>
            <a href="#tin-tuc" class="block px-2.5 xl:px-3.5 py-3 whitespace-nowrap hover:bg-brand-dark transition rounded-t">
              Tin tức
            </a>
          </li>
          <li>
            <a href="#lien-he" class="block px-2.5 xl:px-3.5 py-3 whitespace-nowrap hover:bg-brand-dark transition rounded-t">
              Liên hệ
            </a>
          </li>
        </ul>
      </div>
    </nav>
  </header>

  <!-- ===================================================================== -->
  <!-- MENU ĐIỆN THOẠI (DRAWER SLIDE-OVER CHUẨN FLATSOME)                     -->
  <!-- ===================================================================== -->
  <div id="mobileDrawerBackdrop" class="fixed inset-0 bg-slate-900/50 z-50 hidden transition-opacity"></div>
  <aside id="mobileDrawer" class="fixed top-0 left-0 bottom-0 w-72 max-w-[85vw] bg-white z-50 shadow-2xl transform -translate-x-full transition-transform duration-300 flex flex-col">
    <div class="flex items-center justify-between px-4 py-3 border-b border-slate-200 bg-brand text-white">
      <div class="flex items-center gap-2">
        <span class="font-bold text-sm uppercase tracking-wide">Danh mục WINMAX</span>
      </div>
      <button id="closeDrawerBtn" type="button" aria-label="Đóng danh mục" class="w-8 h-8 rounded-lg bg-white/10 hover:bg-white/20 flex items-center justify-center">
        <i class="fa-solid fa-xmark"></i>
      </button>
    </div>

    <div class="flex-1 overflow-y-auto py-2">
      <ul class="divide-y divide-slate-100 text-sm font-medium text-slate-800">
        <li><a href="#trang-chu" onclick="closeMobileDrawer()" class="block px-4 py-3 hover:bg-brand-soft hover:text-brand">Trang chủ</a></li>
        <li><a href="#gioi-thieu" onclick="closeMobileDrawer()" class="block px-4 py-3 hover:bg-brand-soft hover:text-brand">Giới thiệu</a></li>

        <!-- Accordion: Cửa nhôm xingfa -->
        <li>
          <button type="button" onclick="toggleSubmenu('mobSubXingfa', 'iconSubXingfa')" class="w-full flex items-center justify-between px-4 py-3 hover:bg-brand-soft hover:text-brand text-left">
            <span>Cửa nhôm xingfa</span>
            <i id="iconSubXingfa" class="fa-solid fa-chevron-down text-xs text-slate-400 transition-transform"></i>
          </button>
          <ul id="mobSubXingfa" class="hidden bg-slate-50 pl-6 pr-4 py-1 text-xs space-y-1 text-slate-600">
            <li><a href="#san-pham-xingfa" onclick="filterProducts('1-canh'); closeMobileDrawer();" class="block py-2 hover:text-brand">+ Cửa nhôm xingfa 1 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="filterProducts('2-canh'); closeMobileDrawer();" class="block py-2 hover:text-brand">+ Cửa nhôm xingfa 2 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="filterProducts('3-canh'); closeMobileDrawer();" class="block py-2 hover:text-brand">+ Cửa nhôm xingfa 3 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="filterProducts('4-canh'); closeMobileDrawer();" class="block py-2 hover:text-brand">+ Cửa nhôm xingfa 4 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="filterProducts('5-canh'); closeMobileDrawer();" class="block py-2 hover:text-brand">+ Cửa nhôm xingfa 5 cánh</a></li>
          </ul>
        </li>

        <li><a href="#danh-muc-san-pham" onclick="closeMobileDrawer()" class="block px-4 py-3 hover:bg-brand-soft hover:text-brand">Cửa kính cường lực</a></li>

        <!-- Accordion: Sản phẩm -->
        <li>
          <button type="button" onclick="toggleSubmenu('mobSubSanPham', 'iconSubSanPham')" class="w-full flex items-center justify-between px-4 py-3 hover:bg-brand-soft hover:text-brand text-left">
            <span>Sản phẩm</span>
            <i id="iconSubSanPham" class="fa-solid fa-chevron-down text-xs text-slate-400 transition-transform"></i>
          </button>
          <ul id="mobSubSanPham" class="hidden bg-slate-50 pl-6 pr-4 py-1 text-xs space-y-1 text-slate-600">
            <li><a href="#san-pham-xingfa" onclick="filterProducts('all'); closeMobileDrawer();" class="block py-2 hover:text-brand">+ Cửa nhôm xingfa</a></li>
            <li><a href="#danh-muc-san-pham" onclick="openCategoryModal('Cửa nhựa lõi thép'); closeMobileDrawer();" class="block py-2 hover:text-brand">+ Cửa nhựa lõi thép</a></li>
            <li><a href="#danh-muc-san-pham" onclick="openCategoryModal('Cửa kính tự động'); closeMobileDrawer();" class="block py-2 hover:text-brand">+ Cửa kính tự động</a></li>
            <li><a href="#danh-muc-san-pham" onclick="openCategoryModal('Cầu thang kính'); closeMobileDrawer();" class="block py-2 hover:text-brand">+ Cầu thang kính</a></li>
            <li><a href="#danh-muc-san-pham" onclick="openCategoryModal('Kính ốp bếp'); closeMobileDrawer();" class="block py-2 hover:text-brand">+ Kính ốp bếp</a></li>
            <li><a href="#danh-muc-san-pham" onclick="openCategoryModal('Phòng tắm kính'); closeMobileDrawer();" class="block py-2 hover:text-brand">+ Phòng tắm kính</a></li>
          </ul>
        </li>

        <li><a href="#cong-trinh" onclick="closeMobileDrawer()" class="block px-4 py-3 hover:bg-brand-soft hover:text-brand">Công trình</a></li>
        <li><a href="#bao-gia" onclick="closeMobileDrawer()" class="block px-4 py-3 hover:bg-brand-soft hover:text-brand">Báo giá</a></li>
        <li><a href="#tin-tuc" onclick="closeMobileDrawer()" class="block px-4 py-3 hover:bg-brand-soft hover:text-brand">Tin tức</a></li>
        <li><a href="#lien-he" onclick="closeMobileDrawer()" class="block px-4 py-3 hover:bg-brand-soft hover:text-brand">Liên hệ</a></li>
      </ul>
    </div>

    <div class="p-4 border-t border-slate-200 bg-slate-50 text-xs text-slate-600 space-y-1.5">
      <p class="font-bold text-brand">CƠ KHÍ XÂY DỰNG WINMAX</p>
      <p><i class="fa-solid fa-location-dot text-accent mr-1.5"></i>54 Nguyễn Thị Cận, Hòa Khánh, Đà Nẵng</p>
      <p><i class="fa-solid fa-phone text-brand mr-1.5"></i>0986.486.426</p>
    </div>
  </aside>

  <!-- ===================================================================== -->
  <!-- UX BUILDER: SECTION 1 - 2 BANNER TỰ TRƯỢT CHUYÊN NGHIỆP BẰNG NHAU     -->
  <!-- Toàn bộ hình ảnh & chữ nằm trọn bên trong, cách xa viền ảnh banner    -->
  <!-- ===================================================================== -->
  <section id="trang-chu" class="py-3 sm:py-4 bg-slate-50">
    <div class="winmax-container">
      <div id="heroSliderContainer" class="relative rounded-2xl overflow-hidden shadow-lg bg-brand-dark">
        <div class="hero-grid-slider">

          <!-- BANNER 1 -->
          <div class="hero-slide active relative bg-gradient-to-br from-[#072B49] via-[#0B4A7D] to-[#115E9C] text-white">
            <!-- Khung an toàn cách xa viền ảnh banner trên cả điện thoại và máy tính -->
            <div class="px-9 py-9 sm:px-14 sm:py-12 lg:px-20 lg:py-14 grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center h-full">
              <!-- Cột chữ nằm gọn bên trong -->
              <div class="lg:col-span-7 space-y-3 sm:space-y-4 text-left">
                <p class="text-[11px] sm:text-xs font-semibold uppercase tracking-widest text-sky-200">
                  CÔNG TY TNHH MTV CƠ KHÍ XÂY DỰNG WINMAX
                </p>
                <h1 class="text-xl sm:text-3xl lg:text-4xl font-extrabold leading-snug text-white">
                  Cửa Nhôm Xingfa Nhập Khẩu Chính Hãng Tại Đà Nẵng
                </h1>
                <p class="text-xs sm:text-sm lg:text-base text-slate-200 leading-relaxed max-w-2xl">
                  Thiết kế, sản xuất trực tiếp tại xưởng và thi công trọn gói cửa nhôm Xingfa tem đỏ Quảng Đông, phụ kiện Kinlong đồng bộ. Độ bền vượt trội, cách âm cách nhiệt chuẩn công trình.
                </p>
                <div class="pt-1 flex flex-wrap items-center gap-3">
                  <a href="#form-bao-gia" class="inline-flex items-center gap-2 bg-accent hover:bg-accent-dark text-white text-xs sm:text-sm font-semibold px-5 py-2.5 rounded-lg shadow transition">
                    <span>Nhận báo giá ngay</span>
                    <i class="fa-solid fa-arrow-right text-xs"></i>
                  </a>
                  <a href="#san-pham-xingfa" class="inline-flex items-center gap-2 bg-white/15 hover:bg-white/25 text-white border border-white/30 text-xs sm:text-sm font-semibold px-5 py-2.5 rounded-lg transition">
                    <span>Xem mẫu cửa</span>
                  </a>
                </div>
              </div>
              <!-- Cột hình ảnh thực tế nằm trọn trong banner -->
              <div class="lg:col-span-5">
                <div class="bg-white/10 p-2 sm:p-2.5 rounded-xl border border-white/20 shadow-xl">
                  <div class="aspect-[16/10] w-full overflow-hidden rounded-lg bg-slate-900/40">
                    <img
                      src="https://lh3.googleusercontent.com/d/1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-=w1000"
                      data-drive-id="1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-"
                      alt="Cửa đi mở quay 4 cánh nhôm Xingfa WINMAX"
                      class="w-full h-full object-cover"
                      onerror="handleDriveFallback(this, 'Cửa Nhôm Xingfa WINMAX')"
                    />
                  </div>
                </div>
              </div>
            </div>
          </div>

          <!-- BANNER 2 -->
          <div class="hero-slide relative bg-gradient-to-br from-[#0F2942] via-[#0B4A7D] to-[#083B66] text-white">
            <!-- Khung an toàn cách xa viền ảnh banner giống hệt Banner 1 -->
            <div class="px-9 py-9 sm:px-14 sm:py-12 lg:px-20 lg:py-14 grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center h-full">
              <!-- Cột chữ nằm gọn bên trong -->
              <div class="lg:col-span-7 space-y-3 sm:space-y-4 text-left">
                <p class="text-[11px] sm:text-xs font-semibold uppercase tracking-widest text-sky-200">
                  THI CÔNG CHUYÊN NGHIỆP • BẢO HÀNH DÀI HẠN
                </p>
                <h2 class="text-xl sm:text-3xl lg:text-4xl font-extrabold leading-snug text-white">
                  Giải Pháp Kính Cường Lực, Khách Sạn & Resort Cao Cấp
                </h2>
                <p class="text-xs sm:text-sm lg:text-base text-slate-200 leading-relaxed max-w-2xl">
                  Đối tác tin cậy của hàng loạt dự án khách sạn, resort 4 sao và nhà phố tại Đà Nẵng. Khảo sát tận nơi miễn phí, lắp đặt nhanh chóng, báo giá minh bạch cạnh tranh nhất thị trường.
                </p>
                <div class="pt-1 flex flex-wrap items-center gap-3">
                  <a href="#cong-trinh" class="inline-flex items-center gap-2 bg-accent hover:bg-accent-dark text-white text-xs sm:text-sm font-semibold px-5 py-2.5 rounded-lg shadow transition">
                    <span>Xem dự án thực tế</span>
                    <i class="fa-solid fa-arrow-right text-xs"></i>
                  </a>
                  <a href="tel:0986486426" class="inline-flex items-center gap-2 bg-white/15 hover:bg-white/25 text-white border border-white/30 text-xs sm:text-sm font-semibold px-5 py-2.5 rounded-lg transition">
                    <i class="fa-solid fa-phone text-xs"></i>
                    <span>0986.486.426</span>
                  </a>
                </div>
              </div>
              <!-- Cột hình ảnh thực tế nằm trọn trong banner -->
              <div class="lg:col-span-5">
                <div class="bg-white/10 p-2 sm:p-2.5 rounded-xl border border-white/20 shadow-xl">
                  <div class="aspect-[16/10] w-full overflow-hidden rounded-lg bg-slate-900/40">
                    <img
                      src="https://lh3.googleusercontent.com/d/1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ=w1000"
                      data-drive-id="1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ"
                      alt="Thi công dự án Resort Mỹ Sơn 4 Sao - WINMAX"
                      class="w-full h-full object-cover"
                      onerror="handleDriveFallback(this, 'Dự Án WINMAX Đà Nẵng')"
                    />
                  </div>
                </div>
              </div>
            </div>
          </div>

        </div>

        <!-- Nút điều hướng Trái / Phải đặt gọn sát mép không đè chữ -->
        <button
          id="prevSlideBtn"
          type="button"
          aria-label="Banner trước"
          class="absolute left-2 sm:left-3 top-1/2 -translate-y-1/2 z-10 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center transition"
        >
          <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
        </button>
        <button
          id="nextSlideBtn"
          type="button"
          aria-label="Banner tiếp theo"
          class="absolute right-2 sm:right-3 top-1/2 -translate-y-1/2 z-10 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center transition"
        >
          <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
        </button>

        <!-- Dấu chấm chỉ báo 2 banner -->
        <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 z-10 flex items-center gap-2">
          <button type="button" onclick="goToSlide(0)" aria-label="Banner 1" class="hero-dot w-6 h-2 rounded-full bg-white transition-all"></button>
          <button type="button" onclick="goToSlide(1)" aria-label="Banner 2" class="hero-dot w-2.5 h-2 rounded-full bg-white/45 transition-all"></button>
        </div>
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- UX BUILDER: SECTION 2 - GIỚI THIỆU CÔNG TY & THÔNG SỐ NĂNG LỰC        -->
  <!-- ===================================================================== -->
  <section id="gioi-thieu" class="py-10 sm:py-12 bg-white">
    <div class="winmax-container">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-8 items-center">
        <div class="lg:col-span-7 space-y-3.5">
          <h2 class="flatsome-title flatsome-title-left text-lg sm:text-2xl font-extrabold text-brand uppercase">
            CÔNG TY TNHH MTV CƠ KHÍ XÂY DỰNG WINMAX
          </h2>
          <p class="text-sm text-slate-600 leading-relaxed">
            <strong>WINMAX</strong> là đơn vị hàng đầu chuyên tư vấn, thiết kế, gia công sản xuất và thi công lắp đặt trọn gói các hạng mục nhôm kính và cơ khí xây dựng tại <strong>Đà Nẵng và khu vực Miền Trung</strong>.
          </p>
          <p class="text-sm text-slate-600 leading-relaxed">
            Các dòng sản phẩm chủ lực của WINMAX bao gồm: <strong>Cửa nhôm Xingfa nhập khẩu tem đỏ</strong>, <strong>Cửa kính cường lực</strong>, <strong>Cửa nhựa lõi thép</strong>, <strong>Cửa kính tự động</strong>, <strong>Cầu thang kính</strong>, <strong>Kính ốp bếp</strong> và <strong>Phòng tắm kính</strong>. Với phương châm <em>“Uy tín – Chất lượng – Thẩm mỹ”</em>, chúng tôi mang đến giải pháp không gian hiện đại, bền vững và an toàn tuyệt đối cho mọi công trình.
          </p>
          <div class="grid grid-cols-1 sm:grid-cols-2 gap-2.5 pt-1 text-xs sm:text-sm text-slate-700">
            <div class="flex items-center gap-2">
              <i class="fa-solid fa-circle-check text-brand"></i>
              <span>Khảo sát, tư vấn & đo đạc miễn phí tận nơi</span>
            </div>
            <div class="flex items-center gap-2">
              <i class="fa-solid fa-circle-check text-brand"></i>
              <span>Vật tư chính hãng, phụ kiện đồng bộ 100%</span>
            </div>
            <div class="flex items-center gap-2">
              <i class="fa-solid fa-circle-check text-brand"></i>
              <span>Giá xuất xưởng trực tiếp, không qua trung gian</span>
            </div>
            <div class="flex items-center gap-2">
              <i class="fa-solid fa-circle-check text-brand"></i>
              <span>Bảo hành chính hãng dài hạn, bảo trì nhanh</span>
            </div>
          </div>
        </div>

        <!-- 4 ô chỉ số năng lực chuẩn Flatsome -->
        <div class="lg:col-span-5 grid grid-cols-2 gap-3 sm:gap-4">
          <div class="bg-brand-soft border border-brand/15 rounded-xl p-4 sm:p-5 text-center">
            <div class="text-2xl sm:text-3xl font-extrabold text-brand">150+</div>
            <div class="text-xs sm:text-sm font-medium text-slate-600 mt-1">Dự án hoàn thành</div>
          </div>
          <div class="bg-brand-soft border border-brand/15 rounded-xl p-4 sm:p-5 text-center">
            <div class="text-2xl sm:text-3xl font-extrabold text-accent">50+</div>
            <div class="text-xs sm:text-sm font-medium text-slate-600 mt-1">Kỹ thuật kinh nghiệm</div>
          </div>
          <div class="bg-brand-soft border border-brand/15 rounded-xl p-4 sm:p-5 text-center">
            <div class="text-2xl sm:text-3xl font-extrabold text-brand">100+</div>
            <div class="text-xs sm:text-sm font-medium text-slate-600 mt-1">Mẫu mã sản phẩm</div>
          </div>
          <div class="bg-brand-soft border border-brand/15 rounded-xl p-4 sm:p-5 text-center">
            <div class="text-2xl sm:text-3xl font-extrabold text-accent">100%</div>
            <div class="text-xs sm:text-sm font-medium text-slate-600 mt-1">Khách hàng hài lòng</div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- UX BUILDER: SECTION 3 - SẢN PHẨM CỬA NHÔM XINGFA (2 CỘT TRÊN MOBILE)  -->
  <!-- Có giá gốc, giá ưu đãi và giảm giá % góc trên bên trái sản phẩm       -->
  <!-- ===================================================================== -->
  <section id="san-pham-xingfa" class="py-10 sm:py-12 bg-slate-50 border-y border-slate-200/70">
    <div class="winmax-container">
      <div class="text-center mb-6 sm:mb-8">
        <h2 class="flatsome-title text-lg sm:text-2xl font-extrabold text-brand uppercase">
          Báo Giá Sản Phẩm Cửa Nhôm Xingfa
        </h2>
        <p class="text-xs sm:text-sm text-slate-500 mt-2">
          Nhôm Xingfa nhập khẩu tem đỏ Quảng Đông • Kính cường lực an toàn • Phụ kiện Kinlong chính hãng
        </p>

        <!-- Bộ lọc nhanh hệ cánh -->
        <div class="flex flex-wrap items-center justify-center gap-2 mt-4">
          <button type="button" onclick="filterProducts('all')" data-filter="all" class="product-filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-brand text-white transition">Tất cả</button>
          <button type="button" onclick="filterProducts('1-canh')" data-filter="1-canh" class="product-filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand transition">1 cánh</button>
          <button type="button" onclick="filterProducts('2-canh')" data-filter="2-canh" class="product-filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand transition">2 cánh</button>
          <button type="button" onclick="filterProducts('3-canh')" data-filter="3-canh" class="product-filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand transition">3 cánh</button>
          <button type="button" onclick="filterProducts('4-canh')" data-filter="4-canh" class="product-filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand transition">4 cánh</button>
          <button type="button" onclick="filterProducts('5-canh')" data-filter="5-canh" class="product-filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand transition">Xếp trượt / 5 cánh</button>
        </div>
      </div>

      <!-- Lưới sản phẩm: Đúng 2 cột trên điện thoại, 3 cột trên máy tính -->
      <div id="productGrid" class="grid grid-cols-2 lg:grid-cols-3 gap-3 sm:gap-5">
        <!-- Render động bằng JavaScript từ danh sách 6 sản phẩm thực tế -->
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- UX BUILDER: SECTION 4 - DANH MỤC SẢN PHẨM NỔI BẬT (THEO WEB MẪU)      -->
  <!-- Chữ danh mục nhỏ gọn, dễ nhìn trên cả máy tính và điện thoại          -->
  <!-- ===================================================================== -->
  <section id="danh-muc-san-pham" class="py-10 sm:py-12 bg-white">
    <div class="winmax-container">
      <div class="text-center mb-6 sm:mb-8">
        <h2 class="flatsome-title text-lg sm:text-2xl font-extrabold text-brand uppercase">
          Danh Mục Sản Phẩm Nổi Bật
        </h2>
        <p class="text-xs sm:text-sm text-slate-500 mt-2">
          Đa dạng hạng mục nhôm kính & cơ khí xây dựng cho nhà phố, biệt thự, khách sạn
        </p>
      </div>

      <div class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-5">
        <!-- 1. Cửa nhôm Xingfa -->
        <div onclick="openCategoryModal('Cửa nhôm xingfa')" class="group cursor-pointer bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-md hover:border-brand/40 transition flex flex-col">
          <div class="aspect-[4/3] overflow-hidden bg-slate-100">
            <img
              src="https://lh3.googleusercontent.com/d/1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX=w800"
              data-drive-id="1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX"
              alt="Cửa nhôm xingfa WINMAX"
              class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
              onerror="handleDriveFallback(this, 'Cửa Nhôm Xingfa')"
            />
          </div>
          <div class="p-2.5 sm:p-3.5 text-center bg-white">
            <h3 class="text-xs sm:text-sm font-bold text-slate-800 group-hover:text-brand uppercase leading-snug">
              Cửa nhôm Xingfa
            </h3>
          </div>
        </div>

        <!-- 2. Cửa nhựa lõi thép -->
        <div onclick="openCategoryModal('Cửa nhựa lõi thép')" class="group cursor-pointer bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-md hover:border-brand/40 transition flex flex-col">
          <div class="aspect-[4/3] overflow-hidden bg-slate-100">
            <img
              src="https://lh3.googleusercontent.com/d/1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA=w800"
              data-drive-id="1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA"
              alt="Cửa nhựa lõi thép WINMAX"
              class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
              onerror="handleDriveFallback(this, 'Cửa Nhựa Lõi Thép')"
            />
          </div>
          <div class="p-2.5 sm:p-3.5 text-center bg-white">
            <h3 class="text-xs sm:text-sm font-bold text-slate-800 group-hover:text-brand uppercase leading-snug">
              Cửa nhựa lõi thép
            </h3>
          </div>
        </div>

        <!-- 3. Cửa tự động -->
        <div onclick="openCategoryModal('Cửa kính tự động')" class="group cursor-pointer bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-md hover:border-brand/40 transition flex flex-col">
          <div class="aspect-[4/3] overflow-hidden bg-slate-100">
            <img
              src="https://lh3.googleusercontent.com/d/1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ=w800"
              data-drive-id="1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ"
              alt="Cửa kính tự động WINMAX"
              class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
              onerror="handleDriveFallback(this, 'Cửa Kính Tự Động')"
            />
          </div>
          <div class="p-2.5 sm:p-3.5 text-center bg-white">
            <h3 class="text-xs sm:text-sm font-bold text-slate-800 group-hover:text-brand uppercase leading-snug">
              Cửa kính tự động
            </h3>
          </div>
        </div>

        <!-- 4. Cầu thang kính -->
        <div onclick="openCategoryModal('Cầu thang kính')" class="group cursor-pointer bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-md hover:border-brand/40 transition flex flex-col">
          <div class="aspect-[4/3] overflow-hidden bg-slate-100">
            <img
              src="https://lh3.googleusercontent.com/d/1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul=w800"
              data-drive-id="1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul"
              alt="Cầu thang kính cường lực WINMAX"
              class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
              onerror="handleDriveFallback(this, 'Cầu Thang Kính')"
            />
          </div>
          <div class="p-2.5 sm:p-3.5 text-center bg-white">
            <h3 class="text-xs sm:text-sm font-bold text-slate-800 group-hover:text-brand uppercase leading-snug">
              Cầu thang kính
            </h3>
          </div>
        </div>

        <!-- 5. Kính ốp bếp -->
        <div onclick="openCategoryModal('Kính ốp bếp')" class="group cursor-pointer bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-md hover:border-brand/40 transition flex flex-col">
          <div class="aspect-[4/3] overflow-hidden bg-slate-100">
            <img
              src="https://lh3.googleusercontent.com/d/1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb=w800"
              data-drive-id="1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb"
              alt="Kính màu ốp bếp cường lực WINMAX"
              class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
              onerror="handleDriveFallback(this, 'Kính Ốp Bếp')"
            />
          </div>
          <div class="p-2.5 sm:p-3.5 text-center bg-white">
            <h3 class="text-xs sm:text-sm font-bold text-slate-800 group-hover:text-brand uppercase leading-snug">
              Kính ốp bếp
            </h3>
          </div>
        </div>

        <!-- 6. Phòng tắm kính -->
        <div onclick="openCategoryModal('Phòng tắm kính')" class="group cursor-pointer bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-md hover:border-brand/40 transition flex flex-col">
          <div class="aspect-[4/3] overflow-hidden bg-slate-100">
            <img
              src="https://lh3.googleusercontent.com/d/1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH=w800"
              data-drive-id="1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH"
              alt="Phòng tắm kính cường lực WINMAX"
              class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
              onerror="handleDriveFallback(this, 'Phòng Tắm Kính')"
            />
          </div>
          <div class="p-2.5 sm:p-3.5 text-center bg-white">
            <h3 class="text-xs sm:text-sm font-bold text-slate-800 group-hover:text-brand uppercase leading-snug">
              Phòng tắm kính
            </h3>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- UX BUILDER: SECTION 5 - CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG               -->
  <!-- ===================================================================== -->
  <section id="cong-trinh" class="py-10 sm:py-12 bg-slate-50 border-y border-slate-200/70">
    <div class="winmax-container">
      <div class="text-center mb-6 sm:mb-8">
        <h2 class="flatsome-title text-lg sm:text-2xl font-extrabold text-brand uppercase">
          Các Dự Án Nổi Bật Tại Đà Nẵng
        </h2>
        <p class="text-xs sm:text-sm text-slate-500 mt-2">
          Những công trình khách sạn, resort và nhà phố tiêu biểu do đội ngũ WINMAX thi công hoàn thiện
        </p>
      </div>

      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-5">
        <!-- Dự án 1 -->
        <article class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-md transition flex flex-col">
          <div class="aspect-[16/10] overflow-hidden bg-slate-100">
            <img
              src="https://lh3.googleusercontent.com/d/1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ=w900"
              data-drive-id="1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ"
              alt="DỰ ÁN RESORT MỸ SƠN 4 SAO MY SON HERITAGE RESORT & SPA"
              class="w-full h-full object-cover hover:scale-105 transition duration-500"
              onerror="handleDriveFallback(this, 'My Son Heritage Resort')"
            />
          </div>
          <div class="p-4 flex-1 flex flex-col justify-between">
            <h3 class="text-sm font-bold text-slate-800 leading-snug">
              DỰ ÁN RESORT MỸ SƠN 4 SAO “MY SON HERITAGE RESORT &amp; SPA”
            </h3>
            <p class="text-xs text-slate-500 mt-2">
              Hạng mục: Cửa nhôm Xingfa nhập khẩu, vách kính mặt dựng &amp; phòng tắm kính cường lực.
            </p>
          </div>
        </article>

        <!-- Dự án 2 -->
        <article class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-md transition flex flex-col">
          <div class="aspect-[16/10] overflow-hidden bg-slate-100">
            <img
              src="https://lh3.googleusercontent.com/d/1YeuDLiSXUK_Epupq9QiGzM90_EGW3Kfy=w900"
              data-drive-id="1YeuDLiSXUK_Epupq9QiGzM90_EGW3Kfy"
              alt="THI CÔNG DỰ ÁN KHÁCH SẠN GODEN LINE"
              class="w-full h-full object-cover hover:scale-105 transition duration-500"
              onerror="handleDriveFallback(this, 'Khách sạn Golden Line')"
            />
          </div>
          <div class="p-4 flex-1 flex flex-col justify-between">
            <h3 class="text-sm font-bold text-slate-800 leading-snug">
              THI CÔNG DỰ ÁN KHÁCH SẠN GODEN LINE
            </h3>
            <p class="text-xs text-slate-500 mt-2">
              Hạng mục: Hệ thống cửa sổ mở hất, cửa đi ban công Xingfa chịu gió biển tại Đà Nẵng.
            </p>
          </div>
        </article>

        <!-- Dự án 3 -->
        <article class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-md transition flex flex-col">
          <div class="aspect-[16/10] overflow-hidden bg-slate-100">
            <img
              src="https://lh3.googleusercontent.com/d/1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ=w900"
              data-drive-id="1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ"
              alt="DỰ ÁN KHÁCH SẠN RUBY LIGHT"
              class="w-full h-full object-cover hover:scale-105 transition duration-500"
              onerror="handleDriveFallback(this, 'Khách sạn Ruby Light')"
            />
          </div>
          <div class="p-4 flex-1 flex flex-col justify-between">
            <h3 class="text-sm font-bold text-slate-800 leading-snug">
              DỰ ÁN KHÁCH SẠN RUBY LIGHT
            </h3>
            <p class="text-xs text-slate-500 mt-2">
              Hạng mục: Cửa kính tự động sảnh chính, vách kính ngăn phòng và lan can kính cường lực.
            </p>
          </div>
        </article>

        <!-- Dự án 4 -->
        <article class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-md transition flex flex-col">
          <div class="aspect-[16/10] overflow-hidden bg-slate-100">
            <img
              src="https://lh3.googleusercontent.com/d/1za_IJpAm850uulT6IuhBsk1THb3LuPuc=w900"
              data-drive-id="1za_IJpAm850uulT6IuhBsk1THb3LuPuc"
              alt="THI CÔNG DỰ ÁN RAON ĐÀ NẴNG BEACH HOTEL"
              class="w-full h-full object-cover hover:scale-105 transition duration-500"
              onerror="handleDriveFallback(this, 'Raon Da Nang Beach Hotel')"
            />
          </div>
          <div class="p-4 flex-1 flex flex-col justify-between">
            <h3 class="text-sm font-bold text-slate-800 leading-snug">
              THI CÔNG DỰ ÁN RAON ĐÀ NẴNG BEACH HOTEL
            </h3>
            <p class="text-xs text-slate-500 mt-2">
              Hạng mục: Toàn bộ hệ cửa nhôm Xingfa cách âm kính hộp và cabin tắm kính cao cấp.
            </p>
          </div>
        </article>

        <!-- Dự án 5 -->
        <article class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-md transition flex flex-col">
          <div class="aspect-[16/10] overflow-hidden bg-slate-100">
            <img
              src="https://lh3.googleusercontent.com/d/1WRgx-EUIrn8IKFZdpmdv6Z2Xyb7L8_64=w900"
              data-drive-id="1WRgx-EUIrn8IKFZdpmdv6Z2Xyb7L8_64"
              alt="THI CÔNG DỰ ÁN KHÁCH SẠN JOLIA"
              class="w-full h-full object-cover hover:scale-105 transition duration-500"
              onerror="handleDriveFallback(this, 'Khách sạn Jolia')"
            />
          </div>
          <div class="p-4 flex-1 flex flex-col justify-between">
            <h3 class="text-sm font-bold text-slate-800 leading-snug">
              THI CÔNG DỰ ÁN KHÁCH SẠN JOLIA
            </h3>
            <p class="text-xs text-slate-500 mt-2">
              Hạng mục: Cửa nhôm Xingfa hệ 55, hệ 93 cửa lùa và vách kính mặt tiền sang trọng.
            </p>
          </div>
        </article>

        <!-- Dự án 6 -->
        <article class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-md transition flex flex-col">
          <div class="aspect-[16/10] overflow-hidden bg-slate-100">
            <img
              src="https://lh3.googleusercontent.com/d/1-C5bdt4K-PpLX_KqSN6QAR5ULo1WnNzt=w900"
              data-drive-id="1-C5bdt4K-PpLX_KqSN6QAR5ULo1WnNzt"
              alt="THI CÔNG DỰ ÁN KHÁCH SẠN SOHO"
              class="w-full h-full object-cover hover:scale-105 transition duration-500"
              onerror="handleDriveFallback(this, 'Khách sạn Soho')"
            />
          </div>
          <div class="p-4 flex-1 flex flex-col justify-between">
            <h3 class="text-sm font-bold text-slate-800 leading-snug">
              THI CÔNG DỰ ÁN KHÁCH SẠN SOHO
            </h3>
            <p class="text-xs text-slate-500 mt-2">
              Hạng mục: Thi công trọn gói hạng mục cửa kính cường lực, cửa đi nhôm Xingfa và lan can kính.
            </p>
          </div>
        </article>
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- UX BUILDER: SECTION 6 - BẢNG BÁO GIÁ & FORM YÊU CẦU BÁO GIÁ TRANG CHỦ -->
  <!-- ===================================================================== -->
  <section id="bao-gia" class="py-10 sm:py-12 bg-white">
    <div class="winmax-container">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-8 items-start">

        <!-- Cột trái: Bảng báo giá tham khảo gọn gàng -->
        <div class="lg:col-span-7">
          <h2 class="flatsome-title flatsome-title-left text-lg sm:text-2xl font-extrabold text-brand uppercase mb-5">
            Bảng Báo Giá Tham Khảo 2026
          </h2>
          <div class="overflow-x-auto rounded-xl border border-slate-200 shadow-sm">
            <table class="w-full text-left border-collapse text-xs sm:text-sm">
              <thead>
                <tr class="bg-brand text-white">
                  <th class="py-3 px-3 sm:px-4 font-semibold">Hạng mục sản phẩm</th>
                  <th class="py-3 px-3 sm:px-4 font-semibold">Quy cách chuẩn</th>
                  <th class="py-3 px-3 sm:px-4 font-semibold text-right whitespace-nowrap">Đơn giá / m²</th>
                </tr>
              </thead>
              <tbody class="divide-y divide-slate-200 bg-white">
                <tr class="hover:bg-slate-50">
                  <td class="py-3 px-3 sm:px-4 font-medium text-slate-800">Cửa sổ mở quay / mở hất Xingfa</td>
                  <td class="py-3 px-3 sm:px-4 text-slate-600">Hệ 55 dày 1.4mm, kính 8mm</td>
                  <td class="py-3 px-3 sm:px-4 text-right font-bold text-accent whitespace-nowrap">1.950.000 ₫</td>
                </tr>
                <tr class="hover:bg-slate-50">
                  <td class="py-3 px-3 sm:px-4 font-medium text-slate-800">Cửa đi mở quay 1, 2, 4 cánh Xingfa</td>
                  <td class="py-3 px-3 sm:px-4 text-slate-600">Hệ 55 dày 2.0mm, kính 8mm</td>
                  <td class="py-3 px-3 sm:px-4 text-right font-bold text-accent whitespace-nowrap">2.100.000 ₫</td>
                </tr>
                <tr class="hover:bg-slate-50">
                  <td class="py-3 px-3 sm:px-4 font-medium text-slate-800">Cửa đi xếp trượt nhôm Xingfa</td>
                  <td class="py-3 px-3 sm:px-4 text-slate-600">Hệ 63 dày 2.0mm, phụ kiện đồng bộ</td>
                  <td class="py-3 px-3 sm:px-4 text-right font-bold text-accent whitespace-nowrap">2.450.000 ₫</td>
                </tr>
                <tr class="hover:bg-slate-50">
                  <td class="py-3 px-3 sm:px-4 font-medium text-slate-800">Cửa kính cường lực mở quay / lùa</td>
                  <td class="py-3 px-3 sm:px-4 text-slate-600">Kính cường lực 10mm - 12mm</td>
                  <td class="py-3 px-3 sm:px-4 text-right font-bold text-accent whitespace-nowrap">750.000 ₫</td>
                </tr>
                <tr class="hover:bg-slate-50">
                  <td class="py-3 px-3 sm:px-4 font-medium text-slate-800">Cầu thang kính / Phòng tắm kính</td>
                  <td class="py-3 px-3 sm:px-4 text-slate-600">Kính 10mm, phụ kiện Inox 304</td>
                  <td class="py-3 px-3 sm:px-4 text-right font-bold text-accent whitespace-nowrap">1.250.000 ₫</td>
                </tr>
                <tr class="hover:bg-slate-50">
                  <td class="py-3 px-3 sm:px-4 font-medium text-slate-800">Kính màu ốp bếp cường lực</td>
                  <td class="py-3 px-3 sm:px-4 text-slate-600">Kính 8mm sơn chịu nhiệt (mét dài)</td>
                  <td class="py-3 px-3 sm:px-4 text-right font-bold text-accent whitespace-nowrap">850.000 ₫</td>
                </tr>
              </tbody>
            </table>
          </div>
          <p class="text-xs text-slate-500 mt-3">
            * Lưu ý: Đơn giá tham khảo đã bao gồm vận chuyển &amp; lắp đặt nội thành Đà Nẵng. Liên hệ trực tiếp <strong>0986.486.426</strong> để nhận chiết khấu ưu đãi theo khối lượng công trình.
          </p>
        </div>

        <!-- Cột phải: Form Yêu Cầu & Báo Giá Trang Chủ -->
        <div id="form-bao-gia" class="lg:col-span-5 bg-brand-soft border border-brand/20 rounded-2xl p-5 sm:p-6 shadow-sm">
          <h3 class="text-base sm:text-lg font-extrabold text-brand uppercase mb-1">
            Đăng Ký Yêu Cầu &amp; Báo Giá
          </h3>
          <p class="text-xs sm:text-sm text-slate-600 mb-4">
            Để lại thông tin, kỹ thuật viên WINMAX sẽ liên hệ tư vấn và gửi báo giá chi tiết trong 15 phút.
          </p>

          <form id="quoteForm" class="space-y-3">
            <div>
              <label for="qName" class="block text-xs font-semibold text-slate-700 mb-1">Họ và tên *</label>
              <input
                id="qName"
                type="text"
                required
                placeholder="Nhập họ tên của bạn"
                class="w-full px-3.5 py-2.5 text-sm bg-white border border-slate-300 rounded-lg focus:border-brand focus:ring-1 focus:ring-brand outline-none"
              />
            </div>

            <div>
              <label for="qPhone" class="block text-xs font-semibold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
              <input
                id="qPhone"
                type="tel"
                required
                placeholder="VD: 0986 486 426"
                class="w-full px-3.5 py-2.5 text-sm bg-white border border-slate-300 rounded-lg focus:border-brand focus:ring-1 focus:ring-brand outline-none"
              />
            </div>

            <div>
              <label for="qProduct" class="block text-xs font-semibold text-slate-700 mb-1">Hạng mục cần báo giá</label>
              <select
                id="qProduct"
                class="w-full px-3.5 py-2.5 text-sm bg-white border border-slate-300 rounded-lg focus:border-brand focus:ring-1 focus:ring-brand outline-none"
              >
                <option value="Cửa nhôm Xingfa">Cửa nhôm Xingfa nhập khẩu</option>
                <option value="Cửa kính cường lực">Cửa kính cường lực</option>
                <option value="Cửa nhựa lõi thép">Cửa nhựa lõi thép</option>
                <option value="Cửa kính tự động">Cửa kính tự động</option>
                <option value="Cầu thang kính">Cầu thang kính</option>
                <option value="Kính ốp bếp">Kính ốp bếp</option>
                <option value="Phòng tắm kính">Phòng tắm kính</option>
              </select>
            </div>

            <div>
              <label for="qNote" class="block text-xs font-semibold text-slate-700 mb-1">Yêu cầu / Diện tích dự kiến</label>
              <textarea
                id="qNote"
                rows="3"
                placeholder="Nhập kích thước, số lượng bộ cửa hoặc địa chỉ công trình tại Đà Nẵng..."
                class="w-full px-3.5 py-2.5 text-sm bg-white border border-slate-300 rounded-lg focus:border-brand focus:ring-1 focus:ring-brand outline-none resize-none"
              ></textarea>
            </div>

            <button
              type="submit"
              class="w-full py-3 px-4 rounded-lg bg-accent hover:bg-accent-dark text-white font-bold text-sm uppercase tracking-wide shadow transition flex items-center justify-center gap-2"
            >
              <i class="fa-solid fa-paper-plane"></i>
              <span>Gửi yêu cầu báo giá</span>
            </button>
          </form>
        </div>

      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- UX BUILDER: SECTION 7 - DANH MỤC CÁC BÀI VIẾT / TIN TỨC TRANG CHỦ     -->
  <!-- ===================================================================== -->
  <section id="tin-tuc" class="py-10 sm:py-12 bg-slate-50 border-y border-slate-200/70">
    <div class="winmax-container">
      <div class="text-center mb-6 sm:mb-8">
        <h2 class="flatsome-title text-lg sm:text-2xl font-extrabold text-brand uppercase">
          Tin Tức &amp; Kiến Thức Nhôm Kính
        </h2>

        <!-- Danh mục bài viết trang chủ -->
        <div class="flex flex-wrap items-center justify-center gap-2 mt-4">
          <button type="button" onclick="filterArticles('all')" data-art-filter="all" class="article-filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-brand text-white transition">Tất cả bài viết</button>
          <button type="button" onclick="filterArticles('tu-van')" data-art-filter="tu-van" class="article-filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand transition">Tư vấn chọn cửa</button>
          <button type="button" onclick="filterArticles('ky-thuat')" data-art-filter="ky-thuat" class="article-filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand transition">Kỹ thuật &amp; Báo giá</button>
          <button type="button" onclick="filterArticles('cong-trinh')" data-art-filter="cong-trinh" class="article-filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand transition">Kinh nghiệm thi công</button>
        </div>
      </div>

      <div id="articlesGrid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4 sm:gap-5">
        <!-- Render động các bài viết hữu ích -->
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- UX BUILDER: SECTION 8 - ĐỐI TÁC CỦA CHÚNG TÔI                         -->
  <!-- ===================================================================== -->
  <section class="py-10 bg-white">
    <div class="winmax-container">
      <div class="text-center mb-6">
        <h2 class="flatsome-title text-lg sm:text-2xl font-extrabold text-brand uppercase">
          Đối Tác Của Chúng Tôi
        </h2>
      </div>
      <div class="grid grid-cols-3 md:grid-cols-6 gap-3 sm:gap-4 items-center">
        <div class="bg-white border border-slate-200 rounded-xl p-3 h-20 flex items-center justify-center hover:shadow-sm transition">
          <img src="https://lh3.googleusercontent.com/d/13il4TeS8ZnrK0CD4VDPMdNX3EKxY8AFk=w400" data-drive-id="13il4TeS8ZnrK0CD4VDPMdNX3EKxY8AFk" alt="Đối tác WINMAX 1" class="max-h-12 w-auto object-contain" onerror="handleDriveFallback(this, 'Partner 1')" />
        </div>
        <div class="bg-white border border-slate-200 rounded-xl p-3 h-20 flex items-center justify-center hover:shadow-sm transition">
          <img src="https://lh3.googleusercontent.com/d/1QRcPtjWfg5PEQXw6UMg6ZylQhg8BpzUq=w400" data-drive-id="1QRcPtjWfg5PEQXw6UMg6ZylQhg8BpzUq" alt="Đối tác WINMAX 2" class="max-h-12 w-auto object-contain" onerror="handleDriveFallback(this, 'Partner 2')" />
        </div>
        <div class="bg-white border border-slate-200 rounded-xl p-3 h-20 flex items-center justify-center hover:shadow-sm transition">
          <img src="https://lh3.googleusercontent.com/d/1-Ka-zScPzx653Tg2oWE9-qmFtTdn3Svn=w400" data-drive-id="1-Ka-zScPzx653Tg2oWE9-qmFtTdn3Svn" alt="Đối tác WINMAX 3" class="max-h-12 w-auto object-contain" onerror="handleDriveFallback(this, 'Partner 3')" />
        </div>
        <div class="bg-white border border-slate-200 rounded-xl p-3 h-20 flex items-center justify-center hover:shadow-sm transition">
          <img src="https://lh3.googleusercontent.com/d/1Oy52Wdfy5x6DKF1lyfYxpZTD5fvGH5vT=w400" data-drive-id="1Oy52Wdfy5x6DKF1lyfYxpZTD5fvGH5vT" alt="Đối tác WINMAX 4" class="max-h-12 w-auto object-contain" onerror="handleDriveFallback(this, 'Partner 4')" />
        </div>
        <div class="bg-white border border-slate-200 rounded-xl p-3 h-20 flex items-center justify-center hover:shadow-sm transition">
          <img src="https://lh3.googleusercontent.com/d/1SDcarhnX0yypmqdbawICjYBRtFnKngn-=w400" data-drive-id="1SDcarhnX0yypmqdbawICjYBRtFnKngn-" alt="Đối tác WINMAX 5" class="max-h-12 w-auto object-contain" onerror="handleDriveFallback(this, 'Partner 5')" />
        </div>
        <div class="bg-white border border-slate-200 rounded-xl p-3 h-20 flex items-center justify-center hover:shadow-sm transition">
          <img src="https://lh3.googleusercontent.com/d/1Ua4C1iiZqrjkWx-3h2quvqM0w_Xj33fg=w400" data-drive-id="1Ua4C1iiZqrjkWx-3h2quvqM0w_Xj33fg" alt="Đối tác WINMAX 6" class="max-h-12 w-auto object-contain" onerror="handleDriveFallback(this, 'Partner 6')" />
        </div>
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- UX BUILDER: SECTION 9 - GOOGLE MAP & FANPAGE FACEBOOK NGOÀI TRANG CHỦ -->
  <!-- ===================================================================== -->
  <section id="lien-he" class="py-10 sm:py-12 bg-slate-50 border-t border-slate-200">
    <div class="winmax-container">
      <div class="text-center mb-6 sm:mb-8">
        <h2 class="flatsome-title text-lg sm:text-2xl font-extrabold text-brand uppercase">
          Bản Đồ Chỉ Đường &amp; Fanpage Chính Thức
        </h2>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 sm:gap-6 items-stretch">
        <!-- Cột 1: Bản đồ Google Map tại 54 Nguyễn Thị Cận, Phường Hòa Khánh, TP Đà Nẵng -->
        <div class="lg:col-span-7 bg-white rounded-2xl border border-slate-200 shadow-sm overflow-hidden flex flex-col">
          <div class="px-4 py-3 bg-brand text-white flex items-center justify-between gap-2">
            <div class="flex items-center gap-2 text-xs sm:text-sm font-semibold">
              <i class="fa-solid fa-map-location-dot"></i>
              <span>54 Nguyễn Thị Cận, Phường Hòa Khánh, TP Đà Nẵng</span>
            </div>
            <a
              href="https://www.google.com/maps/search/?api=1&query=54+Nguy%E1%BB%85n+Th%E1%BB%8B+C%E1%BA%ADn,+H%C3%B2a+Kh%C3%A1nh,+%C4%90%C3%A0+N%E1%BA%B5ng"
              target="_blank"
              rel="noopener noreferrer"
              class="text-xs underline hover:text-sky-200 whitespace-nowrap"
            >
              Mở Google Maps
            </a>
          </div>
          <div class="w-full h-72 sm:h-80 lg:flex-1 bg-slate-200">
            <iframe
              title="Bản đồ Công Ty TNHH MTV Cơ Khí Xây Dựng WINMAX"
              src="https://maps.google.com/maps?q=54+Nguy%E1%BB%85n+Th%E1%BB%8B+C%E1%BA%ADn,+H%C3%B2a+Kh%C3%A1nh,+%C4%90%C3%A0+N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
              class="w-full h-full border-0"
              loading="lazy"
              referrerpolicy="no-referrer-when-downgrade"
            ></iframe>
          </div>
        </div>

        <!-- Cột 2: Khung Fanpage Facebook ngoài trang chủ -->
        <div class="lg:col-span-5 bg-white rounded-2xl border border-slate-200 shadow-sm overflow-hidden flex flex-col">
          <div class="px-4 py-3 bg-[#1877F2] text-white flex items-center justify-between">
            <div class="flex items-center gap-2 text-xs sm:text-sm font-semibold">
              <i class="fa-brands fa-facebook"></i>
              <span>Fanpage Facebook WINMAX</span>
            </div>
            <a href="https://facebook.com" target="_blank" rel="noopener noreferrer" class="text-xs underline hover:text-blue-100">
              Xem trang
            </a>
          </div>

          <div class="p-4 flex-1 flex flex-col justify-between gap-4">
            <!-- Header giả lập plugin Fanpage Facebook chuẩn UX Builder -->
            <div class="relative rounded-xl overflow-hidden border border-slate-200">
              <div class="h-32 w-full bg-slate-800 relative">
                <img
                  src="https://lh3.googleusercontent.com/d/1za_IJpAm850uulT6IuhBsk1THb3LuPuc=w800"
                  data-drive-id="1za_IJpAm850uulT6IuhBsk1THb3LuPuc"
                  alt="Ảnh bìa Fanpage WINMAX Đà Nẵng"
                  class="w-full h-full object-cover opacity-80"
                  onerror="handleDriveFallback(this, 'WINMAX Fanpage')"
                />
                <div class="absolute inset-0 bg-gradient-to-t from-black/75 via-black/30 to-transparent"></div>
                <div class="absolute bottom-2.5 left-3 right-3 flex items-end gap-3">
                  <div class="w-12 h-12 rounded-lg bg-white p-1 shadow shrink-0 flex items-center justify-center">
                    <img
                      src="https://lh3.googleusercontent.com/d/1XnfU1DR3Th9wEXJ8aGm4mdkrEEg2Ju9e=w200"
                      data-drive-id="1XnfU1DR3Th9wEXJ8aGm4mdkrEEg2Ju9e"
                      alt="Avatar Fanpage WINMAX"
                      class="w-full h-full object-contain"
                      onerror="handleDriveFallback(this, 'WINMAX')"
                    />
                  </div>
                  <div class="min-w-0 text-white">
                    <h3 class="text-sm font-bold truncate">Cơ Khí Xây Dựng WINMAX Đà Nẵng</h3>
                    <p class="text-[11px] text-slate-200">4.850 lượt thích • 5.120 người theo dõi</p>
                  </div>
                </div>
              </div>
              <div class="p-3 bg-slate-50 flex items-center justify-between gap-2">
                <a
                  href="https://facebook.com"
                  target="_blank"
                  rel="noopener noreferrer"
                  class="flex-1 inline-flex items-center justify-center gap-1.5 px-3 py-2 rounded-lg bg-[#1877F2] hover:bg-blue-700 text-white text-xs font-semibold transition"
                >
                  <i class="fa-solid fa-thumbs-up"></i>
                  <span>Thích Trang</span>
                </a>
                <a
                  href="https://m.me/"
                  target="_blank"
                  rel="noopener noreferrer"
                  class="flex-1 inline-flex items-center justify-center gap-1.5 px-3 py-2 rounded-lg bg-white hover:bg-slate-100 text-slate-700 border border-slate-300 text-xs font-semibold transition"
                >
                  <i class="fa-brands fa-facebook-messenger text-[#1877F2]"></i>
                  <span>Nhắn tin</span>
                </a>
              </div>
            </div>

            <!-- Bài đăng mới nhất trên Fanpage -->
            <div class="bg-slate-50 rounded-xl p-3.5 border border-slate-200 text-xs text-slate-600 space-y-1.5">
              <div class="flex items-center justify-between">
                <span class="font-bold text-slate-800">WINMAX - Cửa Nhôm Xingfa Đà Nẵng</span>
                <span class="text-[11px] text-slate-400">Hôm nay</span>
              </div>
              <p class="leading-relaxed">
                Hoàn thiện bàn giao hệ cửa đi mở quay 4 cánh &amp; cửa xếp trượt nhôm Xingfa nhập khẩu tem đỏ tại Hòa Khánh, Đà Nẵng. Quý khách cần khảo sát báo giá gọi ngay <strong>0986.486.426</strong>!
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- UX BUILDER: FOOTER 4 CỘT CHUẨN FLATSOME                               -->
  <!-- ===================================================================== -->
  <footer class="bg-brand-dark text-slate-200 pt-10 pb-6">
    <div class="winmax-container">
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6 lg:gap-8 pb-8 border-b border-white/15">

        <!-- Cột 1: Thông tin công ty -->
        <div class="space-y-3">
          <div class="inline-flex items-center gap-2 bg-white px-2.5 py-1.5 rounded-lg">
            <img
              src="https://lh3.googleusercontent.com/d/1XnfU1DR3Th9wEXJ8aGm4mdkrEEg2Ju9e=w300"
              data-drive-id="1XnfU1DR3Th9wEXJ8aGm4mdkrEEg2Ju9e"
              alt="Logo WINMAX Footer"
              class="h-8 w-auto object-contain"
              onerror="handleDriveFallback(this, 'WINMAX')"
            />
          </div>
          <h3 class="text-sm font-bold text-white uppercase leading-snug">
            CÔNG TY TNHH MỘT THÀNH VIÊN CƠ KHÍ XÂY DỰNG WINMAX
          </h3>
          <ul class="space-y-2 text-xs text-slate-300">
            <li class="flex items-start gap-2">
              <i class="fa-solid fa-location-dot text-accent mt-0.5"></i>
              <span>54 Nguyễn Thị Cận, Phường Hòa Khánh, TP Đà Nẵng</span>
            </li>
            <li class="flex items-center gap-2">
              <i class="fa-solid fa-phone text-sky-300"></i>
              <a href="tel:0986486426" class="hover:text-white font-semibold">0986.486.426</a>
            </li>
            <li class="flex items-center gap-2">
              <i class="fa-solid fa-globe text-sky-300"></i>
              <span>www.winmax.com</span>
            </li>
            <li class="flex items-center gap-2">
              <i class="fa-solid fa-building text-sky-300"></i>
              <span>MST: 0401682367</span>
            </li>
          </ul>
        </div>

        <!-- Cột 2: Cửa nhôm Xingfa -->
        <div>
          <h4 class="text-sm font-bold text-white uppercase mb-3 pb-2 border-b border-white/15">
            Cửa Nhôm Xingfa
          </h4>
          <ul class="space-y-2 text-xs text-slate-300">
            <li><a href="#san-pham-xingfa" onclick="filterProducts('1-canh')" class="hover:text-white transition">Cửa nhôm xingfa 1 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="filterProducts('2-canh')" class="hover:text-white transition">Cửa nhôm xingfa 2 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="filterProducts('3-canh')" class="hover:text-white transition">Cửa nhôm xingfa 3 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="filterProducts('4-canh')" class="hover:text-white transition">Cửa nhôm xingfa 4 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="filterProducts('5-canh')" class="hover:text-white transition">Cửa nhôm xingfa 5 cánh</a></li>
          </ul>
        </div>

        <!-- Cột 3: Danh mục sản phẩm -->
        <div>
          <h4 class="text-sm font-bold text-white uppercase mb-3 pb-2 border-b border-white/15">
            Sản Phẩm &amp; Dịch Vụ
          </h4>
          <ul class="space-y-2 text-xs text-slate-300">
            <li><a href="#san-pham-xingfa" class="hover:text-white transition">Cửa nhôm xingfa Đà Nẵng</a></li>
            <li><a href="#danh-muc-san-pham" onclick="openCategoryModal('Cửa nhựa lõi thép')" class="hover:text-white transition">Cửa nhựa lõi thép</a></li>
            <li><a href="#danh-muc-san-pham" onclick="openCategoryModal('Cửa kính tự động')" class="hover:text-white transition">Cửa kính tự động</a></li>
            <li><a href="#danh-muc-san-pham" onclick="openCategoryModal('Cầu thang kính')" class="hover:text-white transition">Cầu thang kính cường lực</a></li>
            <li><a href="#danh-muc-san-pham" onclick="openCategoryModal('Kính ốp bếp')" class="hover:text-white transition">Kính ốp bếp cường lực</a></li>
            <li><a href="#danh-muc-san-pham" onclick="openCategoryModal('Phòng tắm kính')" class="hover:text-white transition">Phòng tắm kính cường lực</a></li>
          </ul>
        </div>

        <!-- Cột 4: Liên kết nhanh -->
        <div>
          <h4 class="text-sm font-bold text-white uppercase mb-3 pb-2 border-b border-white/15">
            Hỗ Trợ Khách Hàng
          </h4>
          <ul class="space-y-2 text-xs text-slate-300">
            <li><a href="#gioi-thieu" class="hover:text-white transition">Giới thiệu công ty</a></li>
            <li><a href="#cong-trinh" class="hover:text-white transition">Công trình đã thi công</a></li>
            <li><a href="#bao-gia" class="hover:text-white transition">Báo giá cửa nhôm kính 2026</a></li>
            <li><a href="#tin-tuc" class="hover:text-white transition">Tin tức &amp; Tư vấn kỹ thuật</a></li>
            <li><a href="#form-bao-gia" class="hover:text-white transition">Đăng ký khảo sát miễn phí</a></li>
          </ul>
        </div>

      </div>

      <!-- Bản quyền chân trang -->
      <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400">
        <p>Copyright &copy; 2026 <strong>WINMAX (winmax.com)</strong>. Bản quyền thuộc về CÔNG TY TNHH MTV CƠ KHÍ XÂY DỰNG WINMAX.</p>
        <p>54 Nguyễn Thị Cận, Hòa Khánh, Đà Nẵng</p>
      </div>
    </div>
  </footer>

  <!-- ===================================================================== -->
  <!-- CÁC NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE (MOBILE & DESKTOP)   -->
  <!-- ===================================================================== -->
  <div class="fixed right-3 sm:right-5 bottom-4 sm:bottom-6 z-40 flex flex-col items-end gap-2.5">
    <!-- Nút Zalo -->
    <a
      href="https://zalo.me/0986486426"
      target="_blank"
      rel="noopener noreferrer"
      aria-label="Chat Zalo WINMAX"
      class="group flex items-center gap-2 bg-[#0068FF] hover:bg-blue-700 text-white rounded-full shadow-lg px-3 py-2.5 sm:px-4 sm:py-2.5 transition"
    >
      <span class="hidden sm:inline text-xs font-bold">Chat Zalo</span>
      <span class="w-6 h-6 rounded-full bg-white text-[#0068FF] font-extrabold text-[11px] flex items-center justify-center">Zalo</span>
    </a>

    <!-- Nút Facebook -->
    <a
      href="https://facebook.com"
      target="_blank"
      rel="noopener noreferrer"
      aria-label="Fanpage Facebook WINMAX"
      class="group flex items-center gap-2 bg-[#1877F2] hover:bg-blue-800 text-white rounded-full shadow-lg px-3 py-2.5 sm:px-4 sm:py-2.5 transition"
    >
      <span class="hidden sm:inline text-xs font-bold">Facebook</span>
      <i class="fa-brands fa-facebook-f w-6 h-6 rounded-full bg-white/15 flex items-center justify-center text-sm"></i>
    </a>

    <!-- Nút Hotline nổi bật -->
    <a
      href="tel:0986486426"
      aria-label="Gọi Hotline 0986.486.426"
      class="btn-hotline-pulse flex items-center gap-2 bg-accent hover:bg-accent-dark text-white rounded-full shadow-xl px-3.5 py-2.5 sm:px-4 sm:py-3 transition"
    >
      <i class="fa-solid fa-phone-volume text-sm sm:text-base"></i>
      <span class="text-xs sm:text-sm font-extrabold tracking-wide">0986.486.426</span>
    </a>
  </div>

  <!-- ===================================================================== -->
  <!-- MODAL CHI TIẾT SẢN PHẨM / BÀI VIẾT / DANH MỤC                         -->
  <!-- ===================================================================== -->
  <div id="detailModal" class="fixed inset-0 z-50 hidden items-center justify-center bg-slate-900/60 p-3 sm:p-4">
    <div class="bg-white rounded-2xl shadow-2xl w-full max-w-2xl max-h-[90vh] overflow-y-auto relative">
      <button
        type="button"
        onclick="closeDetailModal()"
        aria-label="Đóng cửa sổ"
        class="absolute top-3 right-3 z-10 w-9 h-9 rounded-full bg-slate-100 hover:bg-slate-200 text-slate-700 flex items-center justify-center transition"
      >
        <i class="fa-solid fa-xmark"></i>
      </button>
      <div id="detailModalBody" class="p-5 sm:p-6"></div>
    </div>
  </div>

  <!-- ===================================================================== -->
  <!-- HỘP THÔNG BÁO TOAST (KHÔNG DÙNG alert())                              -->
  <!-- ===================================================================== -->
  <div id="toastNotification" class="fixed top-20 right-4 z-50 max-w-sm bg-brand-dark text-white px-4 py-3 rounded-xl shadow-xl border border-white/15 transform translate-x-[130%] transition-transform duration-300 flex items-start gap-3">
    <i class="fa-solid fa-circle-check text-emerald-400 text-lg mt-0.5"></i>
    <div class="text-xs sm:text-sm leading-snug" id="toastMessage"></div>
  </div>

  <!-- ===================================================================== -->
  <!-- JAVASCRIPT XỬ LÝ TƯƠNG TÁC, SLIDER, LỌC SẢN PHẨM, FALLBACK ẢNH DRIVE  -->
  <!-- ===================================================================== -->
  <script>
    /**
     * Cơ chế dự phòng tải ảnh Google Drive đa tầng để đảm bảo ảnh luôn hiển thị
     */
    function handleDriveFallback(imgElement, fallbackLabel) {
      try {
        const attempt = parseInt(imgElement.getAttribute('data-attempt') || '0', 10);
        const driveId = imgElement.getAttribute('data-drive-id');

        if (attempt === 0 && driveId) {
          imgElement.setAttribute('data-attempt', '1');
          imgElement.src = 'https://drive.google.com/thumbnail?id=' + driveId + '&sz=w1000';
        } else {
          imgElement.onerror = null;
          const safeText = encodeURIComponent(fallbackLabel || 'WINMAX');
          imgElement.src = 'https://placehold.co/800x600/0B4A7D/FFFFFF?text=' + safeText;
        }
      } catch (err) {
        imgElement.onerror = null;
      }
    }

    /**
     * Dữ liệu 6 sản phẩm Cửa nhôm Xingfa thực tế (đầy đủ ảnh, giá & giảm giá %)
     */
    const PRODUCTS = [
      {
        id: 'sp-1',
        name: 'Cửa đi quay mở 1 cánh nhôm xingfa',
        category: '1-canh',
        driveId: '1-0eBWGjPwzQ-C9c1Wjws9wt0gbsulkPm',
        price: 2100000,
        oldPrice: 2450000,
        discount: 14,
        profile: 'Nhôm Xingfa nhập khẩu hệ 55, dày 2.0mm',
        glass: 'Kính cường lực 8mm hoặc kính dán an toàn 6.38mm',
        hardware: 'Phụ kiện Kinlong cao cấp nhập khẩu đồng bộ',
        warranty: 'Bảo hành chính hãng 5 năm'
      },
      {
        id: 'sp-2',
        name: 'Cửa đi quay mở 2 cánh nhôm xingfa',
        category: '2-canh',
        driveId: '1h2r2rbPrEL7dgLE-MiE5lBBuE8gFNehb',
        price: 2150000,
        oldPrice: 2500000,
        discount: 14,
        profile: 'Nhôm Xingfa nhập khẩu hệ 55, dày 2.0mm',
        glass: 'Kính cường lực 8mm - 10mm chịu lực tốt',
        hardware: 'Khóa đa điểm & bản lề 3D Kinlong chính hãng',
        warranty: 'Bảo hành chính hãng 5 năm'
      },
      {
        id: 'sp-3',
        name: 'Cửa đi quay mở 3 cánh nhôm xingfa',
        category: '3-canh',
        driveId: '17Qi2D8ntACnVrTeRPZ2V7rC0FmI8ecaR',
        price: 2200000,
        oldPrice: 2600000,
        discount: 15,
        profile: 'Nhôm Xingfa nhập khẩu hệ 55, dày 2.0mm',
        glass: 'Kính cường lực 8mm Hải Long / Chu Lai',
        hardware: 'Gioăng kép EPDM kín khít, phụ kiện Kinlong',
        warranty: 'Bảo hành chính hãng 5 năm'
      },
      {
        id: 'sp-4',
        name: 'Cửa đi quay mở 4 cánh nhôm xingfa',
        category: '4-canh',
        driveId: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
        price: 2250000,
        oldPrice: 2650000,
        discount: 15,
        profile: 'Nhôm Xingfa nhập khẩu tem đỏ hệ 55, dày 2.0mm',
        glass: 'Kính cường lực 8mm - 10mm, keo Dowcorning chống thấm',
        hardware: 'Phụ kiện Kinlong đồng bộ, bản lề chịu tải cao',
        warranty: 'Bảo hành chính hãng 5 năm'
      },
      {
        id: 'sp-5',
        name: 'Cửa Nhôm Xingfa Cửa Đi Xếp Trượt',
        category: '5-canh',
        driveId: '1lJpUJBpR_cJp8mIaZ4FnRTynQ_-paNwZ',
        price: 2450000,
        oldPrice: 2850000,
        discount: 14,
        profile: 'Nhôm Xingfa nhập khẩu hệ 63 chuyên dụng, dày 2.0mm',
        glass: 'Kính cường lực 8mm hoặc kính hộp cách âm',
        hardware: 'Hệ bánh xe treo & ray trượt Kinlong vận hành êm ái',
        warranty: 'Bảo hành chính hãng 5 năm'
      },
      {
        id: 'sp-6',
        name: 'Cửa sổ mở hất 2 cánh nhôm Xingfa',
        category: '2-canh',
        driveId: '11fS_oEeJtnDICQZ77fJlYl6GhHf-GOhA',
        price: 1950000,
        oldPrice: 2300000,
        discount: 15,
        profile: 'Nhôm Xingfa nhập khẩu hệ 55, dày 1.4mm',
        glass: 'Kính cường lực 8mm chống hắt mưa hiệu quả',
        hardware: 'Bản lề chữ A, thanh chống gió định vị góc mở 45°',
        warranty: 'Bảo hành chính hãng 5 năm'
      }
    ];

    /**
     * Dữ liệu mô tả các danh mục sản phẩm khi khách bấm xem chi tiết
     */
    const CATEGORY_INFO = {
      'Cửa nhôm xingfa': {
        driveId: '1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX',
        desc: 'Cửa nhôm Xingfa nhập khẩu tem đỏ Quảng Đông chính hãng hệ 55, hệ 93, hệ 63 với độ dày 1.4mm - 2.0mm. Sơn tĩnh điện cao cấp chống ăn mòn muối biển cực tốt tại Đà Nẵng, cách âm, kín nước tuyệt đối.'
      },
      'Cửa nhựa lõi thép': {
        driveId: '1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA',
        desc: 'Cửa nhựa lõi thép uPVC gia cường thép mạ kẽm bên trong giúp tăng khả năng chịu lực, cách âm, cách nhiệt tối ưu cho phòng ngủ, văn phòng và căn hộ.'
      },
      'Cửa kính tự động': {
        driveId: '1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ',
        desc: 'Cửa kính trượt tự động sử dụng cảm biến mắt thần thông minh, motor nhập khẩu Nhật Bản/Hàn Quốc vận hành êm ái, sang trọng cho khách sạn, showroom, trung tâm thương mại.'
      },
      'Cầu thang kính': {
        driveId: '1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul',
        desc: 'Cầu thang kính cường lực dày 10mm - 12mm kết hợp trụ Inox 304 và tay vịn gỗ tự nhiên hoặc Inox, giúp không gian nhà phố hiện đại, rộng rãi và đón sáng tối đa.'
      },
      'Kính ốp bếp': {
        driveId: '1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb',
        desc: 'Kính màu ốp bếp cường lực 8mm sơn chịu nhiệt cao cấp, bề mặt phẳng bóng không mạch vữa, chống bám dầu mỡ và cực kỳ dễ vệ sinh lau chùi.'
      },
      'Phòng tắm kính': {
        driveId: '1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH',
        desc: 'Vách tắm kính cường lực 10mm (mở quay 90°, 135°, 180° hoặc cửa lùa) sử dụng phụ kiện Inox 304 chống gỉ, giúp không gian phòng tắm luôn khô ráo, sạch sẽ và sang trọng.'
      }
    };

    /**
     * Dữ liệu các bài viết / tin tức hiển thị ở trang chủ
     */
    const ARTICLES = [
      {
        id: 'art-1',
        category: 'tu-van',
        catName: 'Tư vấn chọn cửa',
        date: '18/11/2026',
        title: 'Cửa nhôm Xingfa có phù hợp với khí hậu biển tại Đà Nẵng không?',
        excerpt: 'Nhờ lớp sơn tĩnh điện cao cấp và kết cấu khoang rỗng gân trợ lực, cửa nhôm Xingfa chịu gió bão và chống ăn mòn muối biển cực kỳ hiệu quả.',
        driveId: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
        content: 'Đà Nẵng là thành phố ven biển có khí hậu nắng nóng và mùa mưa bão mạnh. Nhôm Xingfa nhập khẩu tem đỏ Quảng Đông sử dụng công nghệ sơn tĩnh điện ngoài trời chuẩn quốc tế giúp thanh nhôm không bị oxy hóa, không cong vênh mối mọt. Khi kết hợp với kính cường lực 8mm - 10mm, gioăng EPDM kép và keo silicone trung tính chống thấm, bộ cửa đạt độ kín khít tuyệt đối, ngăn nước mưa tạt vào nhà và chịu áp lực gió lên đến 1600 Pascal.'
      },
      {
        id: 'art-2',
        category: 'ky-thuat',
        catName: 'Kỹ thuật & Báo giá',
        date: '12/11/2026',
        title: 'Kinh nghiệm chọn độ dày nhôm Xingfa & kính cường lực giúp tối ưu chi phí',
        excerpt: 'Phân biệt nhôm hệ 55 dày 1.4mm cho cửa sổ và 2.0mm cho cửa đi để đảm bảo an toàn bền vững mà không lãng phí ngân sách.',
        driveId: '11fS_oEeJtnDICQZ77fJlYl6GhHf-GOhA',
        content: 'Nhiều gia chủ băn khoăn nên chọn hệ nhôm và độ dày kính nào cho hợp lý. Theo tiêu chuẩn kỹ thuật tại WINMAX: Cửa sổ mở quay, mở hất nên dùng nhôm Xingfa hệ 55 dày 1.4mm; Cửa đi chính mở quay 1-4 cánh dùng hệ 55 dày 2.0mm; Cửa đi xếp trượt khẩu độ lớn dùng hệ 63 dày 2.0mm. Với kính đi kèm, kính cường lực 8mm là tỷ lệ vàng giúp cửa vận hành nhẹ nhàng và tăng tuổi thọ bản lề.'
      },
      {
        id: 'art-3',
        category: 'tu-van',
        catName: 'Tư vấn chọn cửa',
        date: '05/11/2026',
        title: 'So sánh cửa nhôm Xingfa và cửa gỗ truyền thống: Nên lắp loại nào?',
        excerpt: 'Phân tích chi tiết về độ bền, khả năng chống nước, cách âm, thẩm mỹ và chi phí bảo trì lâu dài giữa hai dòng cửa phổ biến nhất.',
        driveId: '1h2r2rbPrEL7dgLE-MiE5lBBuE8gFNehb',
        content: 'Cửa gỗ mang nét ấm cúng nhưng dễ cong vênh, co ngót, phai màu khi lắp ở mặt tiền nắng mưa hoặc khu vực ẩm ướt. Ngược lại, cửa nhôm Xingfa khắc phục hoàn toàn nhược điểm này, không mối mọt, dễ lau chùi và có đầy đủ màu sắc hiện đại (xám ghi, đen tuyền, nâu cà phê, trắng sứ, vân gỗ) giúp ngôi nhà sang trọng và thoáng sáng hơn.'
      },
      {
        id: 'art-4',
        category: 'cong-trinh',
        catName: 'Kinh nghiệm thi công',
        date: '28/10/2026',
        title: 'Quy trình khảo sát, sản xuất & lắp đặt cửa nhôm kính chuẩn tại WINMAX',
        excerpt: 'Từ khâu đo đạc laser chính xác, ép góc tự động tại xưởng đến bơm keo hoàn thiện, đảm bảo thẩm mỹ sắc nét cho từng công trình.',
        driveId: '1lJpUJBpR_cJp8mIaZ4FnRTynQ_-paNwZ',
        content: 'Tại CÔNG TY TNHH MTV CƠ KHÍ XÂY DỰNG WINMAX, mọi công trình đều tuân thủ quy trình 5 bước nghiêm ngặt: (1) Khảo sát và đo kích thước thực tế bằng máy laser; (2) Thiết kế bản vẽ chi tiết và bóc tách báo giá minh bạch; (3) Gia công cắt góc 45 độ, ép góc thủy lực đồng bộ tại xưởng Hòa Khánh; (4) Vận chuyển và lắp đặt chuẩn kỹ thuật; (5) Nghiệm thu bàn giao và kích hoạt bảo hành dài hạn.'
      }
    ];

    /**
     * Định dạng tiền tệ VNĐ
     */
    function formatVND(amount) {
      return amount.toString().replace(/\B(?=(\d{3})+(?!\d))/g, '.') + ' ₫';
    }

    /**
     * Hiển thị danh sách sản phẩm (2 cột trên điện thoại, tên đầy đủ không tràn/cắt chữ)
     */
    function renderProducts(list) {
      const grid = document.getElementById('productGrid');
      if (!grid) return;

      if (!list.length) {
        grid.innerHTML = '<div class="col-span-full text-center py-8 text-sm text-slate-500">Không tìm thấy sản phẩm phù hợp. Vui lòng thử từ khóa khác.</div>';
        return;
      }

      grid.innerHTML = list.map(function(sp) {
        return `
          <div class="bg-white rounded-xl border border-slate-200 shadow-sm hover:shadow-md hover:border-brand/40 transition flex flex-col overflow-hidden">
            <!-- Ảnh sản phẩm + Giảm giá % góc trên bên trái -->
            <div class="relative aspect-[4/3] bg-slate-100 overflow-hidden cursor-pointer" onclick="openProductModal('${sp.id}')">
              <span class="absolute top-2 left-2 z-10 bg-accent text-white text-[11px] sm:text-xs font-extrabold px-2 py-0.5 sm:px-2.5 sm:py-1 rounded-md shadow">
                -${sp.discount}%
              </span>
              <img
                src="https://lh3.googleusercontent.com/d/${sp.driveId}=w800"
                data-drive-id="${sp.driveId}"
                alt="${sp.name}"
                class="w-full h-full object-cover hover:scale-105 transition duration-500"
                onerror="handleDriveFallback(this, '${sp.name}')"
              />
            </div>

            <!-- Thông tin sản phẩm: Tên đầy đủ không bị tràn hay thiếu chữ -->
            <div class="p-2.5 sm:p-4 flex-1 flex flex-col justify-between gap-2">
              <div>
                <h3
                  onclick="openProductModal('${sp.id}')"
                  class="text-xs sm:text-sm font-bold text-slate-800 hover:text-brand cursor-pointer leading-snug break-words"
                >
                  ${sp.name}
                </h3>
                <div class="mt-1.5 flex flex-wrap items-baseline gap-x-2 gap-y-0.5">
                  <span class="text-xs sm:text-base font-extrabold text-accent">${formatVND(sp.price)}</span>
                  <span class="text-[11px] sm:text-xs text-slate-400 line-through">${formatVND(sp.oldPrice)}</span>
                </div>
              </div>

              <div class="pt-1 flex flex-col sm:flex-row gap-1.5">
                <button
                  type="button"
                  onclick="openProductModal('${sp.id}')"
                  class="flex-1 py-1.5 sm:py-2 px-2 rounded-lg bg-brand-soft hover:bg-brand text-brand hover:text-white text-[11px] sm:text-xs font-semibold transition text-center"
                >
                  Chi tiết
                </button>
                <button
                  type="button"
                  onclick="requestProductQuote('${sp.name}')"
                  class="flex-1 py-1.5 sm:py-2 px-2 rounded-lg bg-brand hover:bg-brand-dark text-white text-[11px] sm:text-xs font-semibold transition text-center"
                >
                  Báo giá
                </button>
              </div>
            </div>
          </div>
        `;
      }).join('');
    }

    /**
     * Lọc sản phẩm theo số cánh
     */
    function filterProducts(categoryKey) {
      const buttons = document.querySelectorAll('.product-filter-btn');
      buttons.forEach(function(btn) {
        const isActive = btn.getAttribute('data-filter') === categoryKey;
        btn.className = isActive
          ? 'product-filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-brand text-white transition'
          : 'product-filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand transition';
      });

      if (categoryKey === 'all') {
        renderProducts(PRODUCTS);
      } else {
        renderProducts(PRODUCTS.filter(function(item) { return item.category === categoryKey; }));
      }
    }

    /**
     * Render bài viết trang chủ
     */
    function renderArticles(list) {
      const grid = document.getElementById('articlesGrid');
      if (!grid) return;

      grid.innerHTML = list.map(function(art) {
        return `
          <article onclick="openArticleModal('${art.id}')" class="cursor-pointer bg-white rounded-xl border border-slate-200 shadow-sm hover:shadow-md transition overflow-hidden flex flex-col">
            <div class="aspect-[16/10] bg-slate-100 overflow-hidden">
              <img
                src="https://lh3.googleusercontent.com/d/${art.driveId}=w700"
                data-drive-id="${art.driveId}"
                alt="${art.title}"
                class="w-full h-full object-cover hover:scale-105 transition duration-500"
                onerror="handleDriveFallback(this, 'Tin tức WINMAX')"
              />
            </div>
            <div class="p-4 flex-1 flex flex-col justify-between gap-2">
              <div>
                <div class="flex items-center justify-between text-[11px] text-slate-400 mb-1.5">
                  <span class="font-semibold text-brand">${art.catName}</span>
                  <span>${art.date}</span>
                </div>
                <h3 class="text-sm font-bold text-slate-800 hover:text-brand leading-snug">
                  ${art.title}
                </h3>
                <p class="text-xs text-slate-600 mt-1.5 leading-relaxed">
                  ${art.excerpt}
                </p>
              </div>
              <span class="inline-flex items-center gap-1 text-xs font-semibold text-brand pt-1">
                Xem chi tiết <i class="fa-solid fa-arrow-right text-[10px]"></i>
              </span>
            </div>
          </article>
        `;
      }).join('');
    }

    /**
     * Lọc bài viết theo danh mục
     */
    function filterArticles(catKey) {
      const buttons = document.querySelectorAll('.article-filter-btn');
      buttons.forEach(function(btn) {
        const isActive = btn.getAttribute('data-art-filter') === catKey;
        btn.className = isActive
          ? 'article-filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-brand text-white transition'
          : 'article-filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand transition';
      });

      if (catKey === 'all') {
        renderArticles(ARTICLES);
      } else {
        renderArticles(ARTICLES.filter(function(a) { return a.category === catKey; }));
      }
    }

    /**
     * Mở modal chi tiết sản phẩm
     */
    function openProductModal(productId) {
      const sp = PRODUCTS.find(function(item) { return item.id === productId; });
      if (!sp) return;

      const body = document.getElementById('detailModalBody');
      body.innerHTML = `
        <div class="grid grid-cols-1 sm:grid-cols-2 gap-5 items-start">
          <div class="relative rounded-xl overflow-hidden bg-slate-100 border border-slate-200">
            <span class="absolute top-2.5 left-2.5 bg-accent text-white text-xs font-extrabold px-2.5 py-1 rounded-md shadow">-${sp.discount}%</span>
            <img
              src="https://lh3.googleusercontent.com/d/${sp.driveId}=w900"
              data-drive-id="${sp.driveId}"
              alt="${sp.name}"
              class="w-full aspect-[4/3] object-cover"
              onerror="handleDriveFallback(this, '${sp.name}')"
            />
          </div>
          <div class="space-y-3">
            <h3 class="text-lg font-extrabold text-brand leading-snug">${sp.name}</h3>
            <div class="flex items-baseline gap-2.5">
              <span class="text-xl font-extrabold text-accent">${formatVND(sp.price)} / m²</span>
              <span class="text-sm text-slate-400 line-through">${formatVND(sp.oldPrice)}</span>
            </div>
            <ul class="text-xs sm:text-sm text-slate-600 space-y-1.5 border-t border-slate-200 pt-3">
              <li><strong>Thanh nhôm:</strong> ${sp.profile}</li>
              <li><strong>Kính:</strong> ${sp.glass}</li>
              <li><strong>Phụ kiện:</strong> ${sp.hardware}</li>
              <li><strong>Bảo hành:</strong> ${sp.warranty}</li>
            </ul>
            <div class="pt-2 flex flex-wrap gap-2">
              <button
                type="button"
                onclick="closeDetailModal(); requestProductQuote('${sp.name}');"
                class="flex-1 py-2.5 px-4 rounded-lg bg-accent hover:bg-accent-dark text-white text-xs sm:text-sm font-bold transition"
              >
                Đăng ký báo giá mẫu này
              </button>
              <a
                href="tel:0986486426"
                class="py-2.5 px-4 rounded-lg bg-brand hover:bg-brand-dark text-white text-xs sm:text-sm font-bold transition"
              >
                Gọi 0986.486.426
              </a>
            </div>
          </div>
        </div>
      `;
      showDetailModal();
    }

    /**
     * Mở modal chi tiết danh mục sản phẩm
     */
    function openCategoryModal(categoryName) {
      const info = CATEGORY_INFO[categoryName];
      if (!info) return;

      const body = document.getElementById('detailModalBody');
      body.innerHTML = `
        <div class="space-y-4">
          <div class="rounded-xl overflow-hidden aspect-[16/9] bg-slate-100 border border-slate-200">
            <img
              src="https://lh3.googleusercontent.com/d/${info.driveId}=w900"
              data-drive-id="${info.driveId}"
              alt="${categoryName}"
              class="w-full h-full object-cover"
              onerror="handleDriveFallback(this, '${categoryName}')"
            />
          </div>
          <h3 class="text-xl font-extrabold text-brand uppercase">${categoryName}</h3>
          <p class="text-sm text-slate-600 leading-relaxed">${info.desc}</p>
          <div class="flex flex-wrap gap-2.5 pt-1">
            <button
              type="button"
              onclick="closeDetailModal(); requestProductQuote('${categoryName}');"
              class="px-5 py-2.5 rounded-lg bg-accent hover:bg-accent-dark text-white text-xs sm:text-sm font-bold transition"
            >
              Nhận báo giá ${categoryName}
            </button>
            <a
              href="https://zalo.me/0986486426"
              target="_blank"
              rel="noopener noreferrer"
              class="px-5 py-2.5 rounded-lg bg-[#0068FF] hover:bg-blue-700 text-white text-xs sm:text-sm font-bold transition"
            >
              Tư vấn qua Zalo
            </a>
          </div>
        </div>
      `;
      showDetailModal();
    }

    /**
     * Mở modal đọc chi tiết bài viết
     */
    function openArticleModal(articleId) {
      const art = ARTICLES.find(function(a) { return a.id === articleId; });
      if (!art) return;

      const body = document.getElementById('detailModalBody');
      body.innerHTML = `
        <div class="space-y-4">
          <div class="flex items-center gap-3 text-xs text-slate-500">
            <span class="font-bold text-brand uppercase">${art.catName}</span>
            <span>•</span>
            <span>${art.date}</span>
          </div>
          <h3 class="text-lg sm:text-xl font-extrabold text-slate-900 leading-snug">${art.title}</h3>
          <div class="rounded-xl overflow-hidden aspect-[16/9] bg-slate-100">
            <img
              src="https://lh3.googleusercontent.com/d/${art.driveId}=w900"
              data-drive-id="${art.driveId}"
              alt="${art.title}"
              class="w-full h-full object-cover"
              onerror="handleDriveFallback(this, 'WINMAX')"
            />
          </div>
          <p class="text-sm text-slate-700 leading-relaxed">${art.content}</p>
          <div class="p-4 rounded-xl bg-brand-soft border border-brand/15 text-xs sm:text-sm text-slate-700">
            Cần tư vấn kỹ thuật miễn phí tại Đà Nẵng? Liên hệ ngay <strong>WINMAX - 0986.486.426</strong> hoặc đến trực tiếp <strong>54 Nguyễn Thị Cận, Hòa Khánh, Đà Nẵng</strong>.
          </div>
        </div>
      `;
      showDetailModal();
    }

    function showDetailModal() {
      const modal = document.getElementById('detailModal');
      modal.classList.remove('hidden');
      modal.classList.add('flex');
    }

    function closeDetailModal() {
      const modal = document.getElementById('detailModal');
      modal.classList.add('hidden');
      modal.classList.remove('flex');
    }

    /**
     * Điền sẵn tên sản phẩm vào form báo giá và cuộn xuống form
     */
    function requestProductQuote(productName) {
      const noteEl = document.getElementById('qNote');
      const formEl = document.getElementById('form-bao-gia');
      if (noteEl) {
        noteEl.value = 'Tôi muốn nhận báo giá chi tiết cho: ' + productName;
      }
      if (formEl) {
        formEl.scrollIntoView({ behavior: 'smooth', block: 'center' });
      }
    }

    /**
     * Hiển thị thông báo toast tinh gọn (thay thế hoàn toàn alert)
     */
    let toastTimer = null;
    function showToast(message) {
      const toast = document.getElementById('toastNotification');
      const msgEl = document.getElementById('toastMessage');
      if (!toast || !msgEl) return;

      msgEl.textContent = message;
      toast.style.transform = 'translateX(0)';
      clearTimeout(toastTimer);
      toastTimer = setTimeout(function() {
        toast.style.transform = 'translateX(130%)';
      }, 4200);
    }

    /**
     * Điều khiển Slider 2 banner tự trượt
     */
    let currentSlide = 0;
    let slideInterval = null;

    function goToSlide(index) {
      const slides = document.querySelectorAll('.hero-slide');
      const dots = document.querySelectorAll('.hero-dot');
      if (!slides.length) return;

      currentSlide = (index + slides.length) % slides.length;
      slides.forEach(function(slide, i) {
        if (i === currentSlide) {
          slide.classList.add('active');
        } else {
          slide.classList.remove('active');
        }
      });
      dots.forEach(function(dot, i) {
        if (i === currentSlide) {
          dot.className = 'hero-dot w-6 h-2 rounded-full bg-white transition-all';
        } else {
          dot.className = 'hero-dot w-2.5 h-2 rounded-full bg-white/45 transition-all';
        }
      });
    }

    function startAutoSlide() {
      stopAutoSlide();
      slideInterval = setInterval(function() {
        goToSlide(currentSlide + 1);
      }, 5000);
    }

    function stopAutoSlide() {
      if (slideInterval) clearInterval(slideInterval);
    }

    /**
     * Điều khiển Mobile Drawer & Accordion Submenu
     */
    function openMobileDrawer() {
      document.getElementById('mobileDrawerBackdrop').classList.remove('hidden');
      document.getElementById('mobileDrawer').classList.remove('-translate-x-full');
    }

    function closeMobileDrawer() {
      document.getElementById('mobileDrawerBackdrop').classList.add('hidden');
      document.getElementById('mobileDrawer').classList.add('-translate-x-full');
    }

    function toggleSubmenu(subId, iconId) {
      const sub = document.getElementById(subId);
      const icon = document.getElementById(iconId);
      if (!sub || !icon) return;
      sub.classList.toggle('hidden');
      icon.classList.toggle('rotate-180');
    }

    /**
     * Xử lý tìm kiếm sản phẩm
     */
    function executeSearch(keyword) {
      const q = (keyword || '').trim().toLowerCase();
      const section = document.getElementById('san-pham-xingfa');
      if (!q) {
        filterProducts('all');
      } else {
        const filtered = PRODUCTS.filter(function(p) {
          return p.name.toLowerCase().indexOf(q) !== -1 || p.profile.toLowerCase().indexOf(q) !== -1;
        });
        renderProducts(filtered);
      }
      if (section) {
        section.scrollIntoView({ behavior: 'smooth' });
      }
    }

    /**
     * Khởi tạo toàn bộ tính năng sau khi trang tải xong
     */
    window.addEventListener('DOMContentLoaded', function() {
      renderProducts(PRODUCTS);
      renderArticles(ARTICLES);
      startAutoSlide();

      // Nút điều hướng banner
      document.getElementById('prevSlideBtn').addEventListener('click', function() {
        goToSlide(currentSlide - 1);
        startAutoSlide();
      });
      document.getElementById('nextSlideBtn').addEventListener('click', function() {
        goToSlide(currentSlide + 1);
        startAutoSlide();
      });

      // Tạm dừng khi di chuột vào banner
      const sliderBox = document.getElementById('heroSliderContainer');
      sliderBox.addEventListener('mouseenter', stopAutoSlide);
      sliderBox.addEventListener('mouseleave', startAutoSlide);

      // Hỗ trợ vuốt cảm ứng banner trên điện thoại
      let touchStartX = 0;
      sliderBox.addEventListener('touchstart', function(e) {
        touchStartX = e.changedTouches[0].screenX;
      }, { passive: true });
      sliderBox.addEventListener('touchend', function(e) {
        const diff = e.changedTouches[0].screenX - touchStartX;
        if (Math.abs(diff) > 40) {
          goToSlide(diff < 0 ? currentSlide + 1 : currentSlide - 1);
          startAutoSlide();
        }
      }, { passive: true });

      // Sự kiện menu mobile & tìm kiếm mobile
      document.getElementById('mobileMenuBtn').addEventListener('click', openMobileDrawer);
      document.getElementById('closeDrawerBtn').addEventListener('click', closeMobileDrawer);
      document.getElementById('mobileDrawerBackdrop').addEventListener('click', closeMobileDrawer);
      document.getElementById('mobileSearchToggle').addEventListener('click', function() {
        document.getElementById('mobileSearchBox').classList.toggle('hidden');
      });

      // Đóng modal khi click ra ngoài
      document.getElementById('detailModal').addEventListener('click', function(e) {
        if (e.target === this) closeDetailModal();
      });

      // Form tìm kiếm desktop & mobile
      document.getElementById('searchForm').addEventListener('submit', function(e) {
        e.preventDefault();
        executeSearch(document.getElementById('searchInput').value);
      });
      document.getElementById('mobileSearchForm').addEventListener('submit', function(e) {
        e.preventDefault();
        executeSearch(document.getElementById('mobileSearchInput').value);
        document.getElementById('mobileSearchBox').classList.add('hidden');
      });

      // Xử lý Form yêu cầu báo giá trang chủ
      document.getElementById('quoteForm').addEventListener('submit', function(e) {
        e.preventDefault();
        const name = document.getElementById('qName').value.trim();
        const phone = document.getElementById('qPhone').value.trim();
        if (!name || !phone) {
          showToast('Vui lòng nhập đầy đủ Họ tên và Số điện thoại để nhận báo giá.');
          return;
        }
        showToast('Cảm ơn ' + name + '! WINMAX đã tiếp nhận yêu cầu và sẽ gọi lại số ' + phone + ' trong 15 phút.');
        this.reset();
      });
    });
  </script>
</body>
</html>
