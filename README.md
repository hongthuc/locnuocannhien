<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
  <title>Công Ty TNHH Công Nghệ Và Dịch Vụ Kỹ Thuật An Nhiên - locnuocannhien.com</title>
  <meta name="description" content="Công Ty TNHH Công Nghệ Và Dịch Vụ Kỹ Thuật An Nhiên (locnuocannhien.com) - Chuyên thiết bị xử lý nước, hệ thống lọc tổng đầu nguồn, máy lọc nước dân dụng, máy lọc nước nóng lạnh, dây chuyền lọc nước công nghiệp tại Đà Nẵng.">
  
  <!-- Open Graph / Zalo / Facebook Share Thumbnail là Logo trang web -->
  <meta property="og:type" content="website">
  <meta property="og:site_name" content="locnuocannhien.com - Kỹ Thuật An Nhiên">
  <meta property="og:url" content="https://locnuocannhien.com/">
  <meta property="og:title" content="Công Ty TNHH Công Nghệ Và Dịch Vụ Kỹ Thuật An Nhiên | locnuocannhien.com">
  <meta property="og:description" content="Chuyên cung cấp & lắp đặt Thiết Bị Xử Lý Nước, Hệ Thống Lọc Tổng, Máy Lọc Nước Dân Dụng & Công Nghiệp tại Đà Nẵng. Hotline: 0777.568.919 - 0905.569.019">
  <meta property="og:image" content="https://lh3.googleusercontent.com/d/1pcWkz4BAbk1-i32SuAnlu66hEVy3d5wI=w1200">
  <meta property="og:image:alt" content="Logo Công Ty TNHH Công Nghệ Và Dịch Vụ Kỹ Thuật An Nhiên">
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1pcWkz4BAbk1-i32SuAnlu66hEVy3d5wI=w1200">
  <link rel="icon" type="image/png" href="https://lh3.googleusercontent.com/d/1pcWkz4BAbk1-i32SuAnlu66hEVy3d5wI=w256">

  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- Font Awesome Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
  <!-- Google Fonts Roboto & Inter (Chuẩn Flatsome Việt Nam) -->
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700;900&display=swap" rel="stylesheet">

  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Roboto', 'sans-serif'],
          },
          colors: {
            brand: {
              dark: '#004a8f',
              DEFAULT: '#0066b3',
              light: '#0088cc',
              sky: '#e6f3fb',
              sale: '#d9381e',
            }
          }
        }
      }
    }
  </script>

  <style>
    /* Đảm bảo tuyệt đối không tràn viền ngang và không lệch phải trên mọi thiết bị */
    *, *::before, *::after {
      box-sizing: border-box;
    }
    html, body {
      margin: 0;
      padding: 0;
      width: 100%;
      max-width: 100vw;
      overflow-x: hidden;
      font-family: 'Roboto', sans-serif;
      background-color: #f5f7fa;
      color: #222222;
      scroll-behavior: smooth;
    }

    /* Chiều ngang giao diện trên máy tính bằng 95% kích thước màn hình máy tính */
    .container-95 {
      width: 100%;
      padding-left: 10px;
      padding-right: 10px;
      margin-left: auto;
      margin-right: auto;
    }
    @media (min-width: 1024px) {
      .container-95 {
        width: 95%;
        max-width: 95%;
        padding-left: 0;
        padding-right: 0;
        margin-left: auto;
        margin-right: auto;
      }
    }

    /* Tối ưu tên danh mục trên máy tính: viết liền trên 1 hàng chữ nhỏ gọn, không bị gãy chữ trong từng danh mục */
    .cat-nav-item {
      white-space: nowrap;
      display: inline-flex;
      align-items: center;
      transition: all 0.2s ease;
    }

    /* Tiêu đề section kiểu Flatsome */
    .flatsome-section-title {
      display: flex;
      align-items: center;
      justify-content: space-between;
      border-bottom: 2px solid #0066b3;
      background: #ffffff;
    }
    .flatsome-title-main {
      background: #0066b3;
      color: #ffffff;
      padding: 9px 16px;
      font-weight: 700;
      text-transform: uppercase;
      font-size: 14px;
      letter-spacing: 0.2px;
      position: relative;
      white-space: nowrap;
    }
    @media (min-width: 768px) {
      .flatsome-title-main {
        font-size: 15px;
        padding: 10px 20px;
      }
    }

    /* Nhãn % giảm giá góc trên bên trái chuẩn Flatsome */
    .flatsome-sale-badge {
      position: absolute;
      top: 8px;
      left: 8px;
      background-color: #d9381e;
      color: #ffffff;
      font-weight: 700;
      font-size: 11px;
      width: 38px;
      height: 38px;
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      z-index: 10;
      box-shadow: 0 2px 5px rgba(0,0,0,0.2);
      line-height: 1;
    }

    /* Hộp sản phẩm Flatsome: tên sản phẩm hiển thị đầy đủ không bị cắt mất chữ hoặc tràn ra ngoài */
    .product-card {
      background: #ffffff;
      border: 1px solid #e5e7eb;
      border-radius: 6px;
      overflow: hidden;
      transition: transform 0.2s ease, box-shadow 0.2s ease;
      display: flex;
      flex-direction: column;
      height: 100%;
    }
    .product-card:hover {
      transform: translateY(-2px);
      box-shadow: 0 8px 20px rgba(0, 102, 179, 0.12);
      border-color: #0088cc;
    }
    .product-title-full {
      word-break: break-word;
      overflow-wrap: break-word;
      white-space: normal;
      line-height: 1.38;
    }

    /* Hiệu ứng nút liên hệ nổi */
    @keyframes pulseRing {
      0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(0, 102, 179, 0.6); }
      70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(0, 102, 179, 0); }
      100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(0, 102, 179, 0); }
    }
    .floating-btn-pulse {
      animation: pulseRing 2s infinite;
    }
  </style>
</head>
<body>

  <!-- TOPBAR CHUẨN FLATSOME (Không hiển thị thanh UX Builder) -->
  <div class="bg-brand-dark text-white text-xs py-1.5 border-b border-blue-800">
    <div class="container-95 flex flex-wrap items-center justify-between gap-2">
      <div class="flex items-center gap-2 truncate">
        <i class="fa-solid fa-building-shield text-sky-300"></i>
        <span class="font-medium">CÔNG TY TNHH CÔNG NGHỆ VÀ DỊCH VỤ KỸ THUẬT AN NHIÊN</span>
        <span class="hidden sm:inline text-sky-200">|</span>
        <span class="hidden sm:inline text-sky-200 font-semibold">locnuocannhien.com</span>
      </div>
      <div class="hidden md:flex items-center gap-4 text-[11.5px] text-sky-100">
        <span><i class="fa-regular fa-clock mr-1"></i>07:30 - 18:00 (T2 - CN)</span>
        <span><i class="fa-solid fa-location-dot mr-1"></i>Đà Nẵng: Điện Bàn Đông & Ngũ Hành Sơn</span>
        <a href="https://www.facebook.com/profile.php?id=61550275109005" target="_blank" rel="noopener noreferrer" class="hover:text-white underline">
          <i class="fa-brands fa-facebook mr-1"></i>Fanpage An Nhiên
        </a>
      </div>
    </div>
  </div>

  <!-- HEADER CHÍNH (Logo chỉnh gọn nhỏ lại, KHÔNG để nút gọi ngay trên header tránh tràn viền) -->
  <header class="bg-white shadow-sm sticky top-0 z-40 border-b border-gray-200">
    <div class="container-95 py-2.5">
      <div class="flex items-center justify-between gap-3">
        
        <!-- Logo gọn nhỏ + Tên công ty -->
        <a href="#top" class="flex items-center gap-2.5 min-w-0 shrink-0">
          <img 
            src="https://lh3.googleusercontent.com/d/1pcWkz4BAbk1-i32SuAnlu66hEVy3d5wI=w400" 
            onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1pcWkz4BAbk1-i32SuAnlu66hEVy3d5wI&sz=w400';"
            alt="Logo Công Ty TNHH Công Nghệ Và Dịch Vụ Kỹ Thuật An Nhiên" 
            class="h-9 sm:h-11 w-auto object-contain rounded border border-gray-100 p-0.5 bg-white shrink-0"
          >
          <div class="min-w-0">
            <div class="text-[11px] sm:text-xs font-bold text-brand-dark uppercase tracking-tight leading-tight">
              KỸ THUẬT AN NHIÊN
            </div>
            <div class="text-[10px] sm:text-[11px] text-brand-light font-semibold leading-tight">
              locnuocannhien.com
            </div>
          </div>
        </a>

        <!-- Thanh tìm kiếm sản phẩm ở giữa (Giống mẫu locnuocdanaco.com.vn) -->
        <div class="hidden md:flex flex-1 max-w-xl mx-4">
          <div class="flex w-full border-2 border-brand rounded-md overflow-hidden bg-white">
            <input 
              id="desktopSearchInput"
              type="text" 
              placeholder="Tìm thiết bị xử lý nước, lọc tổng, máy lọc nước RO, vật liệu lọc..." 
              class="w-full px-3 py-1.5 text-xs sm:text-sm focus:outline-none"
              oninput="handleSearchProducts(this.value)"
            >
            <button 
              type="button"
              onclick="handleSearchProducts(document.getElementById('desktopSearchInput').value)"
              class="bg-brand hover:bg-brand-dark text-white px-4 text-xs font-bold uppercase transition shrink-0"
            >
              <i class="fa-solid fa-magnifying-glass mr-1"></i> Tìm
            </button>
          </div>
        </div>

        <!-- Menu điều hướng nhanh gọn (Không có nút Gọi Ngay để không tràn viền) -->
        <nav class="hidden lg:flex items-center gap-4 text-xs font-bold uppercase text-gray-700 shrink-0">
          <a href="#trang-chu" class="text-brand hover:text-brand-dark whitespace-nowrap">Trang chủ</a>
          <a href="#gioi-thieu" class="hover:text-brand whitespace-nowrap">Giới thiệu</a>
          <a href="#danh-muc-san-pham" class="hover:text-brand whitespace-nowrap">Sản phẩm</a>
          <a href="#du-an-da-nang" class="hover:text-brand whitespace-nowrap">Dự án Đà Nẵng</a>
          <a href="#bao-gia" class="hover:text-brand whitespace-nowrap">Báo giá</a>
          <a href="#tin-tuc" class="hover:text-brand whitespace-nowrap">Bài viết</a>
          <a href="#lien-he-ban-do" class="hover:text-brand whitespace-nowrap">Bản đồ & Liên hệ</a>
        </nav>

        <!-- Nút mở Menu danh mục trên Điện Thoại -->
        <button 
          type="button" 
          onclick="toggleMobileMenu()"
          class="lg:hidden inline-flex items-center gap-1.5 bg-brand text-white px-3 py-1.5 rounded text-xs font-bold shrink-0"
          aria-label="Mở danh mục"
        >
          <i class="fa-solid fa-bars"></i>
          <span>DANH MỤC</span>
        </button>
      </div>

      <!-- Ô tìm kiếm trên điện thoại -->
      <div class="mt-2 md:hidden">
        <div class="flex w-full border border-brand rounded overflow-hidden bg-white">
          <input 
            id="mobileSearchInput"
            type="text" 
            placeholder="Tìm tên máy lọc nước, vật liệu lọc, bồn lọc..." 
            class="w-full px-2.5 py-1.5 text-xs focus:outline-none"
            oninput="handleSearchProducts(this.value)"
          >
          <button 
            type="button"
            onclick="handleSearchProducts(document.getElementById('mobileSearchInput').value)"
            class="bg-brand text-white px-3 text-xs font-bold shrink-0"
          >
            <i class="fa-solid fa-magnifying-glass"></i>
          </button>
        </div>
      </div>
    </div>

    <!-- THANH DANH MỤC SẢN PHẨM TRÊN MÁY TÍNH:
         Tên danh mục viết liền trên 1 hàng chữ nhỏ gọn (whitespace-nowrap),
         nằm gọn trên 1 hàng hoặc xuống hàng 2, tuyệt đối không bị gãy chữ trong từng danh mục -->
    <div class="hidden md:block bg-brand text-white border-t border-blue-700">
      <div class="container-95 py-1.5">
        <div class="flex flex-wrap items-center justify-center xl:justify-between gap-x-1.5 gap-y-1">
          <a href="#sec-xulynuoc" class="cat-nav-item text-[11.5px] font-medium px-2 py-1 rounded hover:bg-brand-dark">
            <i class="fa-solid fa-filter mr-1 text-sky-200 text-[10px]"></i>Thiết Bị Xử Lý Nước
          </a>
          <a href="#sec-loctong" class="cat-nav-item text-[11.5px] font-medium px-2 py-1 rounded hover:bg-brand-dark">
            <i class="fa-solid fa-house-flood-water mr-1 text-sky-200 text-[10px]"></i>Hệ Thống Lọc Tổng Nhập Khẩu
          </a>
          <a href="#sec-dandung" class="cat-nav-item text-[11.5px] font-medium px-2 py-1 rounded hover:bg-brand-dark">
            <i class="fa-solid fa-faucet-drip mr-1 text-sky-200 text-[10px]"></i>Máy Lọc Nước Dân Dụng
          </a>
          <a href="#sec-nonglanh" class="cat-nav-item text-[11.5px] font-medium px-2 py-1 rounded hover:bg-brand-dark">
            <i class="fa-solid fa-temperature-half mr-1 text-sky-200 text-[10px]"></i>Máy Lọc Nước Nóng Lạnh
          </a>
          <a href="#sec-congnghiep" class="cat-nav-item text-[11.5px] font-medium px-2 py-1 rounded hover:bg-brand-dark">
            <i class="fa-solid fa-industry mr-1 text-sky-200 text-[10px]"></i>Dây Chuyền Lọc Nước CN
          </a>
          <a href="#sec-phukien" class="cat-nav-item text-[11.5px] font-medium px-2 py-1 rounded hover:bg-brand-dark">
            <i class="fa-solid fa-gears mr-1 text-sky-200 text-[10px]"></i>Phụ Kiện Lọc Nước
          </a>
          <a href="#sec-vatlieu" class="cat-nav-item text-[11.5px] font-medium px-2 py-1 rounded hover:bg-brand-dark">
            <i class="fa-solid fa-cubes-stacked mr-1 text-sky-200 text-[10px]"></i>Vật Liệu Lọc Nước
          </a>
          <a href="#sec-dietkhuan" class="cat-nav-item text-[11.5px] font-medium px-2 py-1 rounded hover:bg-brand-dark">
            <i class="fa-solid fa-shield-virus mr-1 text-sky-200 text-[10px]"></i>Thiết Bị Diệt Khuẩn
          </a>
          <a href="#sec-hoboi" class="cat-nav-item text-[11.5px] font-medium px-2 py-1 rounded hover:bg-brand-dark">
            <i class="fa-solid fa-person-swimming mr-1 text-sky-200 text-[10px]"></i>Thiết Bị Lọc Nước Hồ Bơi
          </a>
          <a href="#sec-bomcn" class="cat-nav-item text-[11.5px] font-medium px-2 py-1 rounded hover:bg-brand-dark">
            <i class="fa-solid fa-gauge-high mr-1 text-sky-200 text-[10px]"></i>Bơm Công Nghiệp
          </a>
          <a href="#sec-nuocbien" class="cat-nav-item text-[11.5px] font-medium px-2 py-1 rounded hover:bg-brand-dark">
            <i class="fa-solid fa-water mr-1 text-sky-200 text-[10px]"></i>Máy Lọc Nước Biển
          </a>
          <a href="#sec-nlmt" class="cat-nav-item text-[11.5px] font-medium px-2 py-1 rounded hover:bg-brand-dark">
            <i class="fa-solid fa-solar-panel mr-1 text-sky-200 text-[10px]"></i>Năng Lượng Mặt Trời
          </a>
        </div>
      </div>
    </div>

    <!-- Ngăn kéo Menu Danh Mục trên Điện Thoại -->
    <div id="mobileMenuDrawer" class="hidden lg:hidden bg-white border-t border-gray-200 shadow-lg">
      <div class="container-95 py-3">
        <div class="text-xs font-bold text-brand uppercase mb-2 pb-1 border-b border-gray-100">
          Danh Mục Sản Phẩm (Chuẩn Lọc Nước)
        </div>
        <div class="grid grid-cols-2 gap-1.5 text-xs">
          <a onclick="toggleMobileMenu()" href="#sec-xulynuoc" class="p-2 rounded bg-slate-50 hover:bg-brand-sky text-gray-800 font-medium truncate">1. Thiết Bị Xử Lý Nước</a>
          <a onclick="toggleMobileMenu()" href="#sec-loctong" class="p-2 rounded bg-slate-50 hover:bg-brand-sky text-gray-800 font-medium truncate">2. Hệ Thống Lọc Tổng</a>
          <a onclick="toggleMobileMenu()" href="#sec-dandung" class="p-2 rounded bg-slate-50 hover:bg-brand-sky text-gray-800 font-medium truncate">3. Máy Lọc Nước Dân Dụng</a>
          <a onclick="toggleMobileMenu()" href="#sec-nonglanh" class="p-2 rounded bg-slate-50 hover:bg-brand-sky text-gray-800 font-medium truncate">4. Máy Lọc Nóng Lạnh</a>
          <a onclick="toggleMobileMenu()" href="#sec-congnghiep" class="p-2 rounded bg-slate-50 hover:bg-brand-sky text-gray-800 font-medium truncate">5. Dây Chuyền Lọc Nước CN</a>
          <a onclick="toggleMobileMenu()" href="#sec-phukien" class="p-2 rounded bg-slate-50 hover:bg-brand-sky text-gray-800 font-medium truncate">6. Phụ Kiện Lọc Nước</a>
          <a onclick="toggleMobileMenu()" href="#sec-vatlieu" class="p-2 rounded bg-slate-50 hover:bg-brand-sky text-gray-800 font-medium truncate">7. Vật Liệu Lọc Nước</a>
          <a onclick="toggleMobileMenu()" href="#sec-dietkhuan" class="p-2 rounded bg-slate-50 hover:bg-brand-sky text-gray-800 font-medium truncate">8. Thiết Bị Diệt Khuẩn</a>
          <a onclick="toggleMobileMenu()" href="#sec-hoboi" class="p-2 rounded bg-slate-50 hover:bg-brand-sky text-gray-800 font-medium truncate">9. Lọc Nước Hồ Bơi</a>
          <a onclick="toggleMobileMenu()" href="#sec-bomcn" class="p-2 rounded bg-slate-50 hover:bg-brand-sky text-gray-800 font-medium truncate">10. Bơm Công Nghiệp</a>
          <a onclick="toggleMobileMenu()" href="#sec-nuocbien" class="p-2 rounded bg-slate-50 hover:bg-brand-sky text-gray-800 font-medium truncate">11. Máy Lọc Nước Biển</a>
          <a onclick="toggleMobileMenu()" href="#sec-nlmt" class="p-2 rounded bg-slate-50 hover:bg-brand-sky text-gray-800 font-medium truncate">12. Năng Lượng Mặt Trời</a>
        </div>
        <div class="flex flex-wrap gap-2 mt-3 pt-2 border-t border-gray-100 text-xs font-bold">
          <a onclick="toggleMobileMenu()" href="#du-an-da-nang" class="px-2.5 py-1 bg-brand text-white rounded">Dự Án Đà Nẵng</a>
          <a onclick="toggleMobileMenu()" href="#bao-gia" class="px-2.5 py-1 bg-brand-sale text-white rounded">Nhận Báo Giá</a>
          <a onclick="toggleMobileMenu()" href="#tin-tuc" class="px-2.5 py-1 bg-slate-200 text-gray-800 rounded">Bài Viết</a>
          <a onclick="toggleMobileMenu()" href="#lien-he-ban-do" class="px-2.5 py-1 bg-slate-200 text-gray-800 rounded">Bản Đồ</a>
        </div>
      </div>
    </div>
  </header>

  <!-- PHẦN BANNER TỰ TRƯỢT CHUYÊN NGHIỆP (2 SLIDE KÍCH THƯỚC BẰNG NHAU)
       Thiết kế RIÊNG ảnh banner trên Điện Thoại khác với ảnh banner trên Máy Tính
       để tối ưu chữ bên trong ảnh, chữ nhỏ gọn nằm hết trong khung banner, không tràn viền -->
  <section id="trang-chu" class="py-3">
    <div class="container-95">
      <div class="relative rounded-lg overflow-hidden shadow-sm border border-gray-200 bg-white">
        
        <!-- ================= BANNER TRÊN MÁY TÍNH (Chỉ hiển thị từ md trở lên) ================= -->
        <div class="hidden md:block relative h-[330px] lg:h-[370px] w-full overflow-hidden">
          
          <!-- Slide 1 Desktop -->
          <div id="desktopSlide0" class=" banner-slide-desktop absolute inset-0 w-full h-full transition-opacity duration-700 opacity-100 z-10 bg-gradient-to-r from-[#003973] via-[#005aa7] to-[#0082c8] flex items-center">
            <div class="w-full h-full grid grid-cols-12 items-center px-8 lg:px-14 gap-6">
              <div class="col-span-7 text-white space-y-2.5 pr-4">
                <div class="inline-block bg-white/15 border border-white/30 text-sky-100 text-xs font-semibold px-3 py-1 rounded">
                  CÔNG TY TNHH CÔNG NGHỆ VÀ DỊCH VỤ KỸ THUẬT AN NHIÊN • LOCNUOCANNHIEN.COM
                </div>
                <h1 class="text-xl lg:text-2xl xl:text-3xl font-extrabold uppercase leading-snug text-white">
                  GIẢI PHÁP XỬ LÝ NƯỚC TOÀN DIỆN & HỆ THỐNG LỌC TỔNG ĐẦU NGUỒN ĐÀ NẴNG
                </h1>
                <p class="text-xs lg:text-sm text-sky-100 leading-relaxed max-w-xl">
                  Chuyên tư vấn, thiết kế, thi công hệ thống lọc nước sinh hoạt, lọc nước giếng khoan, máy lọc nước RO dân dụng, máy nóng lạnh và dây chuyền lọc nước tinh khiết công nghiệp.
                </p>
                <div class="grid grid-cols-2 gap-2 pt-1 text-xs text-sky-50">
                  <div class="bg-black/20 rounded px-3 py-1.5 border border-white/15">
                    <i class="fa-solid fa-location-dot text-amber-300 mr-1"></i>CS1: TDP Hà My Đông A, P. Điện Bàn Đông, TP Đà Nẵng
                  </div>
                  <div class="bg-black/20 rounded px-3 py-1.5 border border-white/15">
                    <i class="fa-solid fa-location-dot text-amber-300 mr-1"></i>CS2: 24 Nguyễn Tuyển, P. Ngũ Hành Sơn, TP Đà Nẵng
                  </div>
                </div>
                <div class="flex items-center gap-3 pt-1">
                  <a href="#bao-gia" class="bg-amber-400 hover:bg-amber-300 text-slate-900 font-bold text-xs px-4 py-2 rounded shadow transition">
                    <i class="fa-solid fa-file-signature mr-1"></i> YÊU CẦU BÁO GIÁ NGAY
                  </a>
                  <span class="text-xs font-bold text-white bg-white/15 px-3 py-2 rounded">
                    <i class="fa-solid fa-phone-volume text-amber-300 mr-1"></i> Hotline/Zalo: 0777.568.919 - 0905.569.019
                  </span>
                </div>
              </div>
              <div class="col-span-5 grid grid-cols-2 gap-3 h-[260px] lg:h-[290px]">
                <div class="bg-white p-1.5 rounded-lg shadow-md h-full overflow-hidden">
                  <img src="https://lh3.googleusercontent.com/d/1UjKKfYpmK_YM0Ah3tuPKXbO8kKJv66mg=w800" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1UjKKfYpmK_YM0Ah3tuPKXbO8kKJv66mg&sz=w800';" alt="Hệ thống lọc tổng An Nhiên" class="w-full h-full object-cover rounded">
                </div>
                <div class="bg-white p-1.5 rounded-lg shadow-md h-full overflow-hidden">
                  <img src="https://lh3.googleusercontent.com/d/1SYfKD4hD9trx7N_LGYdw5EsjvUS1jnTm=w800" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1SYfKD4hD9trx7N_LGYdw5EsjvUS1jnTm&sz=w800';" alt="Thiết bị xử lý nước An Nhiên" class="w-full h-full object-cover rounded">
                </div>
              </div>
            </div>
          </div>

          <!-- Slide 2 Desktop -->
          <div id="desktopSlide1" class="banner-slide-desktop absolute inset-0 w-full h-full transition-opacity duration-700 opacity-0 z-0 bg-gradient-to-r from-[#004e92] via-[#0066b3] to-[#0284c7] flex items-center">
            <div class="w-full h-full grid grid-cols-12 items-center px-8 lg:px-14 gap-6">
              <div class="col-span-7 text-white space-y-2.5 pr-4">
                <div class="inline-block bg-white/15 border border-white/30 text-sky-100 text-xs font-semibold px-3 py-1 rounded">
                  DÂY CHUYỀN LỌC NƯỚC CÔNG NGHIỆP & MÁY NÓNG LẠNH • LOCNUOCANNHIEN.COM
                </div>
                <h2 class="text-xl lg:text-2xl xl:text-3xl font-extrabold uppercase leading-snug text-white">
                  CUNG CẤP VẬT LIỆU LỌC, MÀNG RO, BƠM CÔNG NGHIỆP & LẮP ĐẶT TRỌN GÓI
                </h2>
                <p class="text-xs lg:text-sm text-sky-100 leading-relaxed max-w-xl">
                  Cam kết linh kiện chính hãng, khảo sát chất lượng nước tận nơi miễn phí tại Đà Nẵng, bảo hành – bảo trì định kỳ nhanh chóng 24/7 bởi đội ngũ kỹ sư giàu kinh nghiệm.
                </p>
                <div class="grid grid-cols-3 gap-2 pt-1 text-xs text-white">
                  <div class="bg-white/10 rounded px-3 py-1.5 border border-white/20">
                    <i class="fa-solid fa-circle-check text-emerald-300 mr-1"></i>Khảo sát nước miễn phí
                  </div>
                  <div class="bg-white/10 rounded px-3 py-1.5 border border-white/20">
                    <i class="fa-solid fa-award text-emerald-300 mr-1"></i>Vật tư nhập khẩu chuẩn
                  </div>
                  <div class="bg-white/10 rounded px-3 py-1.5 border border-white/20">
                    <i class="fa-solid fa-screwdriver-wrench text-emerald-300 mr-1"></i>Bảo hành tận nơi Đà Nẵng
                  </div>
                </div>
                <div class="flex items-center gap-3 pt-1">
                  <a href="#danh-muc-san-pham" class="bg-white text-brand-dark hover:bg-sky-50 font-bold text-xs px-4 py-2 rounded shadow transition">
                    <i class="fa-solid fa-boxes-stacked mr-1"></i> XEM SẢN PHẨM THỰC TẾ
                  </a>
                  <span class="text-xs font-bold text-white bg-white/15 px-3 py-2 rounded">
                    <i class="fa-solid fa-globe text-sky-200 mr-1"></i> Website: locnuocannhien.com
                  </span>
                </div>
              </div>
              <div class="col-span-5 grid grid-cols-2 gap-3 h-[260px] lg:h-[290px]">
                <div class="bg-white p-1.5 rounded-lg shadow-md h-full overflow-hidden">
                  <img src="https://lh3.googleusercontent.com/d/1498tDcaIiFiXHbzRO37x7553qzf8OUdM=w800" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1498tDcaIiFiXHbzRO37x7553qzf8OUdM&sz=w800';" alt="Dây chuyền lọc nước công nghiệp" class="w-full h-full object-cover rounded">
                </div>
                <div class="bg-white p-1.5 rounded-lg shadow-md h-full overflow-hidden">
                  <img src="https://lh3.googleusercontent.com/d/1kW3jyv6wwCELQwepWLQpYMVBJlg94e-v=w800" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1kW3jyv6wwCELQwepWLQpYMVBJlg94e-v&sz=w800';" alt="Máy lọc nước thực tế An Nhiên" class="w-full h-full object-cover rounded">
                </div>
              </div>
            </div>
          </div>

        </div>

        <!-- ================= BANNER TRÊN ĐIỆN THOẠI (Thiết kế riêng cho Mobile, chữ nhỏ gọn nằm hết trong ảnh banner, không tràn viền) ================= -->
        <div class="block md:hidden relative h-[250px] sm:h-[265px] w-full overflow-hidden">
          
          <!-- Slide 1 Mobile -->
          <div id="mobileSlide0" class="banner-slide-mobile absolute inset-0 w-full h-full transition-opacity duration-700 opacity-100 z-10 bg-gradient-to-br from-[#003b73] via-[#005aa7] to-[#0077b6] p-3.5 flex flex-col justify-between">
            <div class="flex items-center justify-between gap-2 border-b border-white/15 pb-1.5">
              <span class="text-[10px] font-bold text-amber-300 uppercase tracking-tight">KỸ THUẬT AN NHIÊN • ĐÀ NẴNG</span>
              <span class="text-[10px] font-semibold text-sky-100 bg-white/15 px-2 py-0.5 rounded">locnuocannhien.com</span>
            </div>
            <div class="grid grid-cols-12 gap-2.5 items-center my-auto py-1">
              <div class="col-span-7 text-white space-y-1">
                <h2 class="text-[13px] sm:text-sm font-extrabold uppercase leading-tight text-white">
                  THIẾT BỊ XỬ LÝ NƯỚC & LỌC TỔNG ĐẦU NGUỒN
                </h2>
                <p class="text-[11px] text-sky-100 leading-snug">
                  Lắp đặt lọc nước phèn, nhiễm vôi, máy RO gia đình & công nghiệp tại Đà Nẵng.
                </p>
                <div class="text-[10.5px] text-amber-200 font-semibold pt-0.5">
                  <div>• CS1: Hà My Đông A, Điện Bàn Đông</div>
                  <div>• CS2: 24 Nguyễn Tuyển, Ngũ Hành Sơn</div>
                </div>
              </div>
              <div class="col-span-5 h-[135px] bg-white p-1 rounded shadow">
                <img src="https://lh3.googleusercontent.com/d/1UjKKfYpmK_YM0Ah3tuPKXbO8kKJv66mg=w500" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1UjKKfYpmK_YM0Ah3tuPKXbO8kKJv66mg&sz=w500';" alt="Lọc tổng An Nhiên" class="w-full h-full object-cover rounded">
              </div>
            </div>
            <div class="flex items-center justify-between bg-black/25 px-2.5 py-1.5 rounded text-[11px] text-white">
              <span class="font-bold"><i class="fa-solid fa-phone text-amber-300 mr-1"></i>0777.568.919 - 0905.569.019</span>
              <a href="#bao-gia" class="bg-amber-400 text-slate-900 font-bold px-2 py-0.5 rounded text-[10px]">Báo giá</a>
            </div>
          </div>

          <!-- Slide 2 Mobile -->
          <div id="mobileSlide1" class="banner-slide-mobile absolute inset-0 w-full h-full transition-opacity duration-700 opacity-0 z-0 bg-gradient-to-br from-[#004e92] via-[#0066b3] to-[#0284c7] p-3.5 flex flex-col justify-between">
            <div class="flex items-center justify-between gap-2 border-b border-white/15 pb-1.5">
              <span class="text-[10px] font-bold text-emerald-300 uppercase tracking-tight">CÔNG TY TNHH CN & DVKT AN NHIÊN</span>
              <span class="text-[10px] font-semibold text-sky-100 bg-white/15 px-2 py-0.5 rounded">locnuocannhien.com</span>
            </div>
            <div class="grid grid-cols-12 gap-2.5 items-center my-auto py-1">
              <div class="col-span-7 text-white space-y-1">
                <h2 class="text-[13px] sm:text-sm font-extrabold uppercase leading-tight text-white">
                  DÂY CHUYỀN RO, MÁY NÓNG LẠNH & VẬT LIỆU LỌC
                </h2>
                <p class="text-[11px] text-sky-100 leading-snug">
                  Cung cấp sỉ & lẻ cột lọc Composite, Inox, hạt nhựa, than hoạt tính, màng RO chính hãng.
                </p>
                <div class="text-[10.5px] text-emerald-200 font-semibold pt-0.5">
                  <div>✓ Khảo sát nguồn nước miễn phí</div>
                  <div>✓ Bảo hành tận nơi nhanh 24/7</div>
                </div>
              </div>
              <div class="col-span-5 h-[135px] bg-white p-1 rounded shadow">
                <img src="https://lh3.googleusercontent.com/d/1498tDcaIiFiXHbzRO37x7553qzf8OUdM=w500" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1498tDcaIiFiXHbzRO37x7553qzf8OUdM&sz=w500';" alt="Dây chuyền RO An Nhiên" class="w-full h-full object-cover rounded">
              </div>
            </div>
            <div class="flex items-center justify-between bg-black/25 px-2.5 py-1.5 rounded text-[11px] text-white">
              <span class="font-bold"><i class="fa-solid fa-comments text-sky-300 mr-1"></i>Zalo tư vấn: 0777.568.919</span>
              <a href="#danh-muc-san-pham" class="bg-white text-brand-dark font-bold px-2 py-0.5 rounded text-[10px]">Xem SP</a>
            </div>
          </div>

        </div>

        <!-- Nút chuyển Slide Trái/Phải và Chấm chỉ báo -->
        <button type="button" onclick="changeBannerSlide(-1)" aria-label="Slide trước" class="absolute left-2 top-1/2 -translate-y-1/2 z-20 w-7 h-7 md:w-8 md:h-8 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center text-xs">
          <i class="fa-solid fa-chevron-left"></i>
        </button>
        <button type="button" onclick="changeBannerSlide(1)" aria-label="Slide kế tiếp" class="absolute right-2 top-1/2 -translate-y-1/2 z-20 w-7 h-7 md:w-8 md:h-8 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center text-xs">
          <i class="fa-solid fa-chevron-right"></i>
        </button>
        <div class="absolute bottom-2 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
          <button type="button" onclick="setBannerSlide(0)" id="dotSlide0" class="w-2.5 h-2.5 rounded-full bg-amber-400 transition"></button>
          <button type="button" onclick="setBannerSlide(1)" id="dotSlide1" class="w-2.5 h-2.5 rounded-full bg-white/50 transition"></button>
        </div>

      </div>
    </div>
  </section>

  <!-- THANH CAM KẾT DỊCH VỤ CHUẨN FLATSOME -->
  <section class="pb-3">
    <div class="container-95">
      <div class="grid grid-cols-2 lg:grid-cols-4 gap-2.5 bg-white p-3 rounded-lg border border-gray-200 shadow-sm">
        <div class="flex items-center gap-2.5 p-1.5">
          <div class="w-9 h-9 rounded-full bg-brand-sky text-brand flex items-center justify-center shrink-0 text-sm">
            <i class="fa-solid fa-flask-vial"></i>
          </div>
          <div class="min-w-0">
            <div class="text-xs font-bold text-gray-800">KHẢO SÁT & TEST NƯỚC</div>
            <div class="text-[11px] text-gray-500">Miễn phí tận nơi tại Đà Nẵng</div>
          </div>
        </div>
        <div class="flex items-center gap-2.5 p-1.5">
          <div class="w-9 h-9 rounded-full bg-brand-sky text-brand flex items-center justify-center shrink-0 text-sm">
            <i class="fa-solid fa-certificate"></i>
          </div>
          <div class="min-w-0">
            <div class="text-xs font-bold text-gray-800">LINH KIỆN CHÍNH HÃNG</div>
            <div class="text-[11px] text-gray-500">Nhập khẩu đầy đủ CO, CQ</div>
          </div>
        </div>
        <div class="flex items-center gap-2.5 p-1.5">
          <div class="w-9 h-9 rounded-full bg-brand-sky text-brand flex items-center justify-center shrink-0 text-sm">
            <i class="fa-solid fa-screwdriver-wrench"></i>
          </div>
          <div class="min-w-0">
            <div class="text-xs font-bold text-gray-800">KỸ THUẬT CHUYÊN SÂU</div>
            <div class="text-[11px] text-gray-500">Lắp đặt gọn đẹp, đúng chuẩn</div>
          </div>
        </div>
        <div class="flex items-center gap-2.5 p-1.5">
          <div class="w-9 h-9 rounded-full bg-brand-sky text-brand flex items-center justify-center shrink-0 text-sm">
            <i class="fa-solid fa-headset"></i>
          </div>
          <div class="min-w-0">
            <div class="text-xs font-bold text-gray-800">BẢO HÀNH TẬN TÂM</div>
            <div class="text-[11px] text-gray-500">0777.568.919 - 0905.569.019</div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- DANH MỤC SẢN PHẨM TRANG CHỦ (CHỮ DANH MỤC NHỎ GỌN, ĐẸP TRÊN CẢ MÁY TÍNH & ĐIỆN THOẠI) -->
  <section id="danh-muc-san-pham" class="py-3">
    <div class="container-95">
      <div class="bg-white rounded-lg border border-gray-200 shadow-sm overflow-hidden">
        <div class="flatsome-section-title">
          <h2 class="flatsome-title-main">
            <i class="fa-solid fa-table-cells-large mr-1.5"></i> DANH MỤC SẢN PHẨM
          </h2>
          <span class="text-xs text-gray-500 pr-3 hidden sm:inline">Chọn danh mục để lọc nhanh sản phẩm</span>
        </div>

        <!-- Lưới 12 danh mục chuẩn web mẫu locnuocdanaco.com.vn, chữ nhỏ gọn không tràn viền -->
        <div class="p-3 grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-6 gap-2.5">
          
          <a href="#sec-xulynuoc" class="group border border-gray-200 hover:border-brand rounded-md p-2 flex flex-col items-center text-center bg-slate-50/60 hover:bg-brand-sky/40 transition">
            <div class="w-14 h-14 rounded-full overflow-hidden border border-gray-200 bg-white mb-1.5 p-0.5">
              <img src="https://lh3.googleusercontent.com/d/1UjKKfYpmK_YM0Ah3tuPKXbO8kKJv66mg=w300" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1UjKKfYpmK_YM0Ah3tuPKXbO8kKJv66mg&sz=w300';" alt="Thiết Bị Xử Lý Nước" class="w-full h-full object-cover rounded-full">
            </div>
            <span class="text-[11.5px] font-bold text-gray-800 group-hover:text-brand whitespace-nowrap">Thiết Bị Xử Lý Nước</span>
          </a>

          <a href="#sec-loctong" class="group border border-gray-200 hover:border-brand rounded-md p-2 flex flex-col items-center text-center bg-slate-50/60 hover:bg-brand-sky/40 transition">
            <div class="w-14 h-14 rounded-full overflow-hidden border border-gray-200 bg-white mb-1.5 p-0.5">
              <img src="https://lh3.googleusercontent.com/d/1SYfKD4hD9trx7N_LGYdw5EsjvUS1jnTm=w300" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1SYfKD4hD9trx7N_LGYdw5EsjvUS1jnTm&sz=w300';" alt="Hệ Thống Lọc Tổng Nhập Khẩu" class="w-full h-full object-cover rounded-full">
            </div>
            <span class="text-[11.5px] font-bold text-gray-800 group-hover:text-brand whitespace-nowrap">Hệ Thống Lọc Tổng</span>
          </a>

          <a href="#sec-dandung" class="group border border-gray-200 hover:border-brand rounded-md p-2 flex flex-col items-center text-center bg-slate-50/60 hover:bg-brand-sky/40 transition">
            <div class="w-14 h-14 rounded-full overflow-hidden border border-gray-200 bg-white mb-1.5 p-0.5">
              <img src="https://lh3.googleusercontent.com/d/1kW3jyv6wwCELQwepWLQpYMVBJlg94e-v=w300" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1kW3jyv6wwCELQwepWLQpYMVBJlg94e-v&sz=w300';" alt="Máy Lọc Nước Dân Dụng" class="w-full h-full object-cover rounded-full">
            </div>
            <span class="text-[11.5px] font-bold text-gray-800 group-hover:text-brand whitespace-nowrap">Máy Lọc Nước Dân Dụng</span>
          </a>

          <a href="#sec-nonglanh" class="group border border-gray-200 hover:border-brand rounded-md p-2 flex flex-col items-center text-center bg-slate-50/60 hover:bg-brand-sky/40 transition">
            <div class="w-14 h-14 rounded-full overflow-hidden border border-gray-200 bg-white mb-1.5 p-0.5">
              <img src="https://lh3.googleusercontent.com/d/1rNKvt9P-iWfj5yJrIkNjSwTMVSI5l8Jk=w300" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1rNKvt9P-iWfj5yJrIkNjSwTMVSI5l8Jk&sz=w300';" alt="Máy Lọc Nước Nóng Lạnh" class="w-full h-full object-cover rounded-full">
            </div>
            <span class="text-[11.5px] font-bold text-gray-800 group-hover:text-brand whitespace-nowrap">Máy Lọc Nước Nóng Lạnh</span>
          </a>

          <a href="#sec-congnghiep" class="group border border-gray-200 hover:border-brand rounded-md p-2 flex flex-col items-center text-center bg-slate-50/60 hover:bg-brand-sky/40 transition">
            <div class="w-14 h-14 rounded-full overflow-hidden border border-gray-200 bg-white mb-1.5 p-0.5">
              <img src="https://lh3.googleusercontent.com/d/1498tDcaIiFiXHbzRO37x7553qzf8OUdM=w300" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1498tDcaIiFiXHbzRO37x7553qzf8OUdM&sz=w300';" alt="Dây Chuyền Lọc Nước CN" class="w-full h-full object-cover rounded-full">
            </div>
            <span class="text-[11.5px] font-bold text-gray-800 group-hover:text-brand whitespace-nowrap">Dây Chuyền Lọc Nước CN</span>
          </a>

          <a href="#sec-phukien" class="group border border-gray-200 hover:border-brand rounded-md p-2 flex flex-col items-center text-center bg-slate-50/60 hover:bg-brand-sky/40 transition">
            <div class="w-14 h-14 rounded-full overflow-hidden border border-gray-200 bg-white mb-1.5 p-0.5">
              <img src="https://lh3.googleusercontent.com/d/1TGSTh48n1WnLblQwFGgpVzriOQTyp4TH=w300" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1TGSTh48n1WnLblQwFGgpVzriOQTyp4TH&sz=w300';" alt="Phụ Kiện Lọc Nước" class="w-full h-full object-cover rounded-full">
            </div>
            <span class="text-[11.5px] font-bold text-gray-800 group-hover:text-brand whitespace-nowrap">Phụ Kiện Lọc Nước</span>
          </a>

          <a href="#sec-vatlieu" class="group border border-gray-200 hover:border-brand rounded-md p-2 flex flex-col items-center text-center bg-slate-50/60 hover:bg-brand-sky/40 transition">
            <div class="w-14 h-14 rounded-full overflow-hidden border border-gray-200 bg-white mb-1.5 p-0.5">
              <img src="https://lh3.googleusercontent.com/d/1Uz6xOizvcN_fHmTK03eMVJ7QRjppUvDj=w300" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1Uz6xOizvcN_fHmTK03eMVJ7QRjppUvDj&sz=w300';" alt="Vật Liệu Lọc Nước" class="w-full h-full object-cover rounded-full">
            </div>
            <span class="text-[11.5px] font-bold text-gray-800 group-hover:text-brand whitespace-nowrap">Vật Liệu Lọc Nước</span>
          </a>

          <a href="#sec-dietkhuan" class="group border border-gray-200 hover:border-brand rounded-md p-2 flex flex-col items-center text-center bg-slate-50/60 hover:bg-brand-sky/40 transition">
            <div class="w-14 h-14 rounded-full overflow-hidden border border-gray-200 bg-white mb-1.5 p-0.5">
              <img src="https://lh3.googleusercontent.com/d/1Dt2DS5V1morPg6xwX-WDiokS1UUzOixI=w300" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1Dt2DS5V1morPg6xwX-WDiokS1UUzOixI&sz=w300';" alt="Thiết Bị Diệt Khuẩn" class="w-full h-full object-cover rounded-full">
            </div>
            <span class="text-[11.5px] font-bold text-gray-800 group-hover:text-brand whitespace-nowrap">Thiết Bị Diệt Khuẩn</span>
          </a>

          <a href="#sec-hoboi" class="group border border-gray-200 hover:border-brand rounded-md p-2 flex flex-col items-center text-center bg-slate-50/60 hover:bg-brand-sky/40 transition">
            <div class="w-14 h-14 rounded-full overflow-hidden border border-gray-200 bg-white mb-1.5 p-0.5">
              <img src="https://lh3.googleusercontent.com/d/1aoCZ0c5QfdLF19rtIC5XqeJZ2g_Hh9mo=w300" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1aoCZ0c5QfdLF19rtIC5XqeJZ2g_Hh9mo&sz=w300';" alt="Thiết Bị Lọc Nước Hồ Bơi" class="w-full h-full object-cover rounded-full">
            </div>
            <span class="text-[11.5px] font-bold text-gray-800 group-hover:text-brand whitespace-nowrap">Thiết Bị Lọc Hồ Bơi</span>
          </a>

          <a href="#sec-bomcn" class="group border border-gray-200 hover:border-brand rounded-md p-2 flex flex-col items-center text-center bg-slate-50/60 hover:bg-brand-sky/40 transition">
            <div class="w-14 h-14 rounded-full overflow-hidden border border-gray-200 bg-white mb-1.5 p-0.5">
              <img src="https://lh3.googleusercontent.com/d/1-m3yp1hX2lM7n8Dd8bPSp9wJZrsNJ-h8=w300" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1-m3yp1hX2lM7n8Dd8bPSp9wJZrsNJ-h8&sz=w300';" alt="Bơm Công Nghiệp" class="w-full h-full object-cover rounded-full">
            </div>
            <span class="text-[11.5px] font-bold text-gray-800 group-hover:text-brand whitespace-nowrap">Bơm Công Nghiệp</span>
          </a>

          <a href="#sec-nuocbien" class="group border border-gray-200 hover:border-brand rounded-md p-2 flex flex-col items-center text-center bg-slate-50/60 hover:bg-brand-sky/40 transition">
            <div class="w-14 h-14 rounded-full overflow-hidden border border-gray-200 bg-white mb-1.5 p-0.5">
              <img src="https://lh3.googleusercontent.com/d/1dFI9x0OCsc9HQ7RWYbFH-fLHd37795nx=w300" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1dFI9x0OCsc9HQ7RWYbFH-fLHd37795nx&sz=w300';" alt="Máy Lọc Nước Biển" class="w-full h-full object-cover rounded-full">
            </div>
            <span class="text-[11.5px] font-bold text-gray-800 group-hover:text-brand whitespace-nowrap">Máy Lọc Nước Biển</span>
          </a>

          <a href="#sec-nlmt" class="group border border-gray-200 hover:border-brand rounded-md p-2 flex flex-col items-center text-center bg-slate-50/60 hover:bg-brand-sky/40 transition">
            <div class="w-14 h-14 rounded-full overflow-hidden border border-gray-200 bg-white mb-1.5 p-0.5">
              <img src="https://lh3.googleusercontent.com/d/1Ebn-ZZPBe4tR4bd3Gafr4ThuAHtdeP9X=w300" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1Ebn-ZZPBe4tR4bd3Gafr4ThuAHtdeP9X&sz=w300';" alt="Năng Lượng Mặt Trời" class="w-full h-full object-cover rounded-full">
            </div>
            <span class="text-[11.5px] font-bold text-gray-800 group-hover:text-brand whitespace-nowrap">Năng Lượng Mặt Trời</span>
          </a>

        </div>
      </div>
    </div>
  </section>

  <!-- KẾT QUẢ TÌM KIẾM NHANH (Ẩn mặc định, hiện khi người dùng gõ tìm kiếm) -->
  <section id="searchResultSection" class="hidden py-3">
    <div class="container-95">
      <div class="bg-white rounded-lg border-2 border-brand p-3 shadow-sm">
        <div class="flex items-center justify-between mb-3 pb-2 border-b border-gray-200">
          <h3 id="searchResultTitle" class="text-sm font-bold text-brand uppercase">Kết quả tìm kiếm sản phẩm</h3>
          <button type="button" onclick="clearSearchProducts()" class="text-xs text-red-600 font-bold hover:underline">Đóng tìm kiếm ✕</button>
        </div>
        <div id="searchResultGrid" class="grid grid-cols-2 md:grid-cols-4 gap-2.5 sm:gap-4"></div>
      </div>
    </div>
  </section>

  <!-- =========================================================================================
       CÁC KHỐI DANH MỤC SẢN PHẨM TRANG CHỦ (DÙNG 14 ẢNH THỰC TẾ TRONG FILE GOOGLE DRIVE)
       - Chia 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính (lg:grid-cols-4)
       - Chỉ có vòng tròn % giảm giá góc trên bên trái chuẩn Flatsome, không gắn nhãn dán khác
       - Tên sản phẩm hiển thị đầy đủ, không bị cắt chữ hay tràn viền
  ========================================================================================== -->
  <div id="allProductSections" class="space-y-4"></div>

  <!-- =========================================================================================
       DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (Sử dụng ảnh thực tế lắp đặt từ Google Drive)
  ========================================================================================== -->
  <section id="du-an-da-nang" class="py-4">
    <div class="container-95">
      <div class="bg-white rounded-lg border border-gray-200 shadow-sm overflow-hidden">
        <div class="flatsome-section-title">
          <h2 class="flatsome-title-main">
            <i class="fa-solid fa-helmet-safety mr-1.5"></i> DỰ ÁN LẮP ĐẶT THỰC TẾ TẠI ĐÀ NẴNG
          </h2>
          <a href="#bao-gia" class="text-xs font-bold text-brand hover:underline pr-3">Đăng ký khảo sát miễn phí →</a>
        </div>

        <div class="p-3 sm:p-4 grid grid-cols-2 md:grid-cols-3 lg:grid-cols-6 gap-2.5 sm:gap-3.5">
          
          <div class="border border-gray-200 rounded-md overflow-hidden bg-white flex flex-col">
            <div class="h-36 sm:h-40 w-full overflow-hidden bg-slate-100">
              <img src="https://lh3.googleusercontent.com/d/1UjKKfYpmK_YM0Ah3tuPKXbO8kKJv66mg=w600" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1UjKKfYpmK_YM0Ah3tuPKXbO8kKJv66mg&sz=w600';" alt="Dự án lọc tổng Ngũ Hành Sơn" class="w-full h-full object-cover">
            </div>
            <div class="p-2.5 flex-1 flex flex-col justify-between">
              <h3 class="text-xs font-bold text-gray-800 leading-snug">Lắp đặt Hệ thống lọc tổng 3 cột Inox 304 tại P. Ngũ Hành Sơn, TP Đà Nẵng</h3>
              <p class="text-[11px] text-brand font-semibold mt-1.5">Khử phèn, làm mềm nước sinh hoạt</p>
            </div>
          </div>

          <div class="border border-gray-200 rounded-md overflow-hidden bg-white flex flex-col">
            <div class="h-36 sm:h-40 w-full overflow-hidden bg-slate-100">
              <img src="https://lh3.googleusercontent.com/d/1SYfKD4hD9trx7N_LGYdw5EsjvUS1jnTm=w600" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1SYfKD4hD9trx7N_LGYdw5EsjvUS1jnTm&sz=w600';" alt="Dự án lọc nước Điện Bàn Đông" class="w-full h-full object-cover">
            </div>
            <div class="p-2.5 flex-1 flex flex-col justify-between">
              <h3 class="text-xs font-bold text-gray-800 leading-snug">Thi công hệ thống xử lý nước giếng khoan tại P. Điện Bàn Đông, TP Đà Nẵng</h3>
              <p class="text-[11px] text-brand font-semibold mt-1.5">Công suất 1.500L/giờ van tự động</p>
            </div>
          </div>

          <div class="border border-gray-200 rounded-md overflow-hidden bg-white flex flex-col">
            <div class="h-36 sm:h-40 w-full overflow-hidden bg-slate-100">
              <img src="https://lh3.googleusercontent.com/d/1498tDcaIiFiXHbzRO37x7553qzf8OUdM=w600" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1498tDcaIiFiXHbzRO37x7553qzf8OUdM&sz=w600';" alt="Dây chuyền RO Hòa Khánh" class="w-full h-full object-cover">
            </div>
            <div class="p-2.5 flex-1 flex flex-col justify-between">
              <h3 class="text-xs font-bold text-gray-800 leading-snug">Bàn giao dây chuyền lọc nước tinh khiết RO 500L/h tại KCN Hòa Khánh, Đà Nẵng</h3>
              <p class="text-[11px] text-brand font-semibold mt-1.5">Đạt chuẩn nước uống trực tiếp</p>
            </div>
          </div>

          <div class="border border-gray-200 rounded-md overflow-hidden bg-white flex flex-col">
            <div class="h-36 sm:h-40 w-full overflow-hidden bg-slate-100">
              <img src="https://lh3.googleusercontent.com/d/1rNKvt9P-iWfj5yJrIkNjSwTMVSI5l8Jk=w600" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1rNKvt9P-iWfj5yJrIkNjSwTMVSI5l8Jk&sz=w600';" alt="Máy lọc nước nóng lạnh Sơn Trà" class="w-full h-full object-cover">
            </div>
            <div class="p-2.5 flex-1 flex flex-col justify-between">
              <h3 class="text-xs font-bold text-gray-800 leading-snug">Lắp đặt hệ thống máy lọc nước nóng lạnh công nghiệp trường học tại Sơn Trà, Đà Nẵng</h3>
              <p class="text-[11px] text-brand font-semibold mt-1.5">Vỏ Inox 304 an toàn tuyệt đối</p>
            </div>
          </div>

          <div class="border border-gray-200 rounded-md overflow-hidden bg-white flex flex-col">
            <div class="h-36 sm:h-40 w-full overflow-hidden bg-slate-100">
              <img src="https://lh3.googleusercontent.com/d/1q6_ziycQ_sXP5bA4hx8tZbpKQCs_cEP2=w600" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1q6_ziycQ_sXP5bA4hx8tZbpKQCs_cEP2&sz=w600';" alt="Lọc tổng biệt thự Hải Châu" class="w-full h-full object-cover">
            </div>
            <div class="p-2.5 flex-1 flex flex-col justify-between">
              <h3 class="text-xs font-bold text-gray-800 leading-snug">Lắp đặt hệ thống lọc tổng đầu nguồn cao cấp cho biệt thự tại Hải Châu, Đà Nẵng</h3>
              <p class="text-[11px] text-brand font-semibold mt-1.5">Tích hợp màng siêu lọc UF & UV</p>
            </div>
          </div>

          <div class="border border-gray-200 rounded-md overflow-hidden bg-white flex flex-col">
            <div class="h-36 sm:h-40 w-full overflow-hidden bg-slate-100">
              <img src="https://lh3.googleusercontent.com/d/1zkYVx57eDpdapSBWh9rDC3wq4_FuKsOK=w600" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1zkYVx57eDpdapSBWh9rDC3wq4_FuKsOK&sz=w600';" alt="Bảo trì thay vật liệu lọc Cẩm Lệ" class="w-full h-full object-cover">
            </div>
            <div class="p-2.5 flex-1 flex flex-col justify-between">
              <h3 class="text-xs font-bold text-gray-800 leading-snug">Nâng cấp & thay vật liệu lọc nước đầu nguồn cho khách sạn tại Cẩm Lệ, Đà Nẵng</h3>
              <p class="text-[11px] text-brand font-semibold mt-1.5">Than hoạt tính gáo dừa & hạt Cation</p>
            </div>
          </div>

        </div>
      </div>
    </div>
  </section>

  <!-- =========================================================================================
       FORM YÊU CẦU TƯ VẤN VÀ BÁO GIÁ TRANG CHỦ + THÔNG TIN GIỚI THIỆU CÔNG TY AN NHIÊN
  ========================================================================================== -->
  <section id="bao-gia" class="py-3">
    <div class="container-95">
      <div class="bg-white rounded-lg border border-gray-200 shadow-sm overflow-hidden">
        <div class="flatsome-section-title">
          <h2 class="flatsome-title-main">
            <i class="fa-solid fa-file-invoice-dollar mr-1.5"></i> YÊU CẦU TƯ VẤN & NHẬN BÁO GIÁ NHANH
          </h2>
          <span class="text-xs font-semibold text-brand pr-3 hidden sm:inline">Hỗ trợ kỹ thuật 24/7: 0777.568.919 (Zalo) - 0905.569.019</span>
        </div>

        <div id="gioi-thieu" class="p-3.5 sm:p-5 grid grid-cols-1 lg:grid-cols-12 gap-5 items-start">
          
          <!-- Cột giới thiệu Công ty An Nhiên -->
          <div class="lg:col-span-5 space-y-3 bg-slate-50 p-3.5 rounded-lg border border-gray-200">
            <div class="flex items-center gap-3 pb-2 border-b border-gray-200">
              <img 
                src="https://lh3.googleusercontent.com/d/1pcWkz4BAbk1-i32SuAnlu66hEVy3d5wI=w200" 
                onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1pcWkz4BAbk1-i32SuAnlu66hEVy3d5wI&sz=w200';"
                alt="Logo An Nhiên" 
                class="h-11 w-auto object-contain bg-white p-1 rounded border"
              >
              <div>
                <h3 class="text-xs sm:text-sm font-extrabold text-brand-dark uppercase leading-snug">
                  CÔNG TY TNHH CÔNG NGHỆ VÀ DỊCH VỤ KỸ THUẬT AN NHIÊN
                </h3>
                <p class="text-xs text-gray-600 font-semibold">Website: locnuocannhien.com | MST: 4001311904</p>
              </div>
            </div>

            <p class="text-xs text-gray-700 leading-relaxed">
              <strong>Kỹ Thuật An Nhiên</strong> là đơn vị uy tín hàng đầu tại TP Đà Nẵng chuyên khảo sát, tư vấn, cung cấp và lắp đặt thiết bị xử lý nước phèn, nước nhiễm vôi, hệ thống lọc tổng sinh hoạt đầu nguồn, máy lọc nước RO gia đình, máy lọc nước nóng lạnh và dây chuyền lọc nước công nghiệp.
            </p>

            <div class="space-y-2 text-xs text-gray-800">
              <div class="p-2 bg-white rounded border border-gray-200">
                <strong class="text-brand-dark block"><i class="fa-solid fa-location-dot text-brand mr-1"></i>Cơ sở 1:</strong>
                Thửa đất số 51, Tờ bản đồ số 15, Tổ Dân Phố Hà My Đông A, Phường Điện Bàn Đông, TP Đà Nẵng
              </div>
              <div class="p-2 bg-white rounded border border-gray-200">
                <strong class="text-brand-dark block"><i class="fa-solid fa-location-dot text-brand mr-1"></i>Cơ sở 2:</strong>
                24 Nguyễn Tuyển, Phường Ngũ Hành Sơn, TP Đà Nẵng
              </div>
              <div class="p-2 bg-white rounded border border-gray-200 flex flex-wrap items-center justify-between gap-2">
                <span><strong class="text-brand-dark"><i class="fa-solid fa-phone text-brand mr-1"></i>Hotline/Zalo:</strong> 0777568919</span>
                <span><strong class="text-brand-dark"><i class="fa-solid fa-phone-volume text-brand mr-1"></i>Hotline 2:</strong> 0905569019</span>
              </div>
            </div>
          </div>

          <!-- Cột Form Yêu Cầu Báo Giá -->
          <div class="lg:col-span-7 bg-white p-3.5 sm:p-4 rounded-lg border-2 border-brand/30">
            <h3 class="text-sm font-bold text-brand-dark uppercase mb-1">
              Gửi Yêu Cầu Khảo Sát Nguồn Nước & Báo Giá Trọn Gói
            </h3>
            <p class="text-xs text-gray-500 mb-3">
              Điền thông tin bên dưới, kỹ thuật viên Công ty An Nhiên sẽ liên hệ tư vấn và gửi bảng báo giá chi tiết trong 5 phút.
            </p>

            <form id="quoteRequestForm" onsubmit="submitQuoteForm(event)" class="grid grid-cols-1 sm:grid-cols-2 gap-3 text-xs">
              <div>
                <label class="block font-bold text-gray-700 mb-1">Họ và tên quý khách *</label>
                <input type="text" id="qName" required placeholder="Nhập họ và tên..." class="w-full px-3 py-2 border border-gray-300 rounded focus:outline-none focus:border-brand">
              </div>
              <div>
                <label class="block font-bold text-gray-700 mb-1">Số điện thoại / Zalo *</label>
                <input type="tel" id="qPhone" required placeholder="Ví dụ: 0905xxxxxx" class="w-full px-3 py-2 border border-gray-300 rounded focus:outline-none focus:border-brand">
              </div>
              <div>
                <label class="block font-bold text-gray-700 mb-1">Danh mục cần báo giá *</label>
                <select id="qCategory" class="w-full px-3 py-2 border border-gray-300 rounded focus:outline-none focus:border-brand bg-white">
                  <option value="Thiết Bị Xử Lý Nước Phèn / Giếng Khoan">Thiết Bị Xử Lý Nước Phèn / Giếng Khoan</option>
                  <option value="Hệ Thống Lọc Tổng Đầu Nguồn Gia Đình">Hệ Thống Lọc Tổng Đầu Nguồn Gia Đình</option>
                  <option value="Máy Lọc Nước Dân Dụng RO / Ion Kiềm">Máy Lọc Nước Dân Dụng RO / Ion Kiềm</option>
                  <option value="Máy Lọc Nước Nóng Lạnh">Máy Lọc Nước Nóng Lạnh</option>
                  <option value="Dây Chuyền Lọc Nước Công Nghiệp">Dây Chuyền Lọc Nước Công Nghiệp</option>
                  <option value="Vật Liệu Lọc Nước & Phụ Kiện Thay Thế">Vật Liệu Lọc Nước & Phụ Kiện Thay Thế</option>
                  <option value="Bơm Công Nghiệp / Thiết Bị Diệt Khuẩn / Hồ Bơi">Bơm Công Nghiệp / Thiết Bị Diệt Khuẩn / Hồ Bơi</option>
                  <option value="Máy Lọc Nước Biển / Năng Lượng Mặt Trời">Máy Lọc Nước Biển / Năng Lượng Mặt Trời</option>
                </select>
              </div>
              <div>
                <label class="block font-bold text-gray-700 mb-1">Khu vực lắp đặt tại Đà Nẵng</label>
                <input type="text" id="qAddress" placeholder="VD: Ngũ Hành Sơn, Điện Bàn Đông, Hải Châu..." class="w-full px-3 py-2 border border-gray-300 rounded focus:outline-none focus:border-brand">
              </div>
              <div class="sm:col-span-2">
                <label class="block font-bold text-gray-700 mb-1">Tình trạng nguồn nước / Yêu cầu chi tiết</label>
                <textarea id="qNote" rows="2" placeholder="VD: Nước máy có mùi clo, nước giếng khoan bị vàng phèn, cần thay vật liệu lọc hoặc lắp mới..." class="w-full px-3 py-2 border border-gray-300 rounded focus:outline-none focus:border-brand"></textarea>
              </div>
              <div class="sm:col-span-2 flex flex-wrap items-center justify-between gap-2 pt-1">
                <button type="submit" class="bg-brand hover:bg-brand-dark text-white font-bold px-5 py-2.5 rounded shadow transition uppercase">
                  <i class="fa-solid fa-paper-plane mr-1.5"></i> GỬI YÊU CẦU BÁO GIÁ
                </button>
                <a href="https://zalo.me/0777568919" target="_blank" rel="noopener noreferrer" class="bg-sky-50 hover:bg-sky-100 text-brand-dark border border-brand/30 font-bold px-4 py-2 rounded transition">
                  <i class="fa-solid fa-comment-dots mr-1"></i> Nhắn Zalo trực tiếp: 0777.568.919
                </a>
              </div>
            </form>

            <div id="quoteSuccessBox" class="hidden mt-3 p-3 rounded bg-emerald-50 border border-emerald-300 text-emerald-900 text-xs"></div>
          </div>

        </div>
      </div>
    </div>
  </section>

  <!-- =========================================================================================
       DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC - KIẾN THỨC LỌC NƯỚC - KỸ THUẬT)
  ========================================================================================== -->
  <section id="tin-tuc" class="py-3">
    <div class="container-95">
      <div class="bg-white rounded-lg border border-gray-200 shadow-sm overflow-hidden">
        <div class="flatsome-section-title flex-wrap">
          <h2 class="flatsome-title-main">
            <i class="fa-regular fa-newspaper mr-1.5"></i> DANH MỤC BÀI VIẾT & KINH NGHIỆM XỬ LÝ NƯỚC
          </h2>
          <!-- Các danh mục bài viết trang chủ -->
          <div class="flex flex-wrap items-center gap-1.5 p-2 text-xs">
            <button type="button" onclick="filterBlogPosts('all')" class="blog-tab-btn bg-brand text-white px-2.5 py-1 rounded font-bold" data-cat="all">Tất cả bài viết</button>
            <button type="button" onclick="filterBlogPosts('kien-thuc')" class="blog-tab-btn bg-slate-100 hover:bg-slate-200 text-gray-700 px-2.5 py-1 rounded font-medium" data-cat="kien-thuc">Kiến thức lọc nước</button>
            <button type="button" onclick="filterBlogPosts('ky-thuat')" class="blog-tab-btn bg-slate-100 hover:bg-slate-200 text-gray-700 px-2.5 py-1 rounded font-medium" data-cat="ky-thuat">Tư vấn kỹ thuật</button>
            <button type="button" onclick="filterBlogPosts('chinh-sach')" class="blog-tab-btn bg-slate-100 hover:bg-slate-200 text-gray-700 px-2.5 py-1 rounded font-medium" data-cat="chinh-sach">Chính sách & Bảo hành</button>
          </div>
        </div>

        <div id="blogPostsGrid" class="p-3 sm:p-4 grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-3.5">
          <!-- Render bằng JS -->
        </div>
      </div>
    </div>
  </section>

  <!-- =========================================================================================
       ĐƯA FANPAGE FACEBOOK & ẢNH GOOGLE MAP 2 CƠ SỞ RA NGOÀI TRANG CHỦ
  ========================================================================================== -->
  <section id="lien-he-ban-do" class="py-3">
    <div class="container-95">
      <div class="bg-white rounded-lg border border-gray-200 shadow-sm overflow-hidden">
        <div class="flatsome-section-title">
          <h2 class="flatsome-title-main">
            <i class="fa-solid fa-map-location-dot mr-1.5"></i> BẢN ĐỒ GOOGLE MAPS & FANPAGE CHÍNH THỨC
          </h2>
          <span class="text-xs text-gray-500 pr-3 hidden md:inline">Cơ sở 1: Điện Bàn Đông & Cơ sở 2: 24 Nguyễn Tuyển, Ngũ Hành Sơn</span>
        </div>

        <div class="p-3.5 sm:p-4 grid grid-cols-1 lg:grid-cols-12 gap-4">
          
          <!-- Bản đồ Cơ sở 1 -->
          <div class="lg:col-span-4 border border-gray-200 rounded-lg overflow-hidden flex flex-col bg-slate-50">
            <div class="p-2.5 bg-white border-b border-gray-200">
              <div class="text-xs font-extrabold text-brand-dark uppercase">
                <i class="fa-solid fa-location-dot text-red-600 mr-1"></i> BẢN ĐỒ CƠ SỞ 1 - ĐIỆN BÀN ĐÔNG
              </div>
              <p class="text-[11.5px] text-gray-600 mt-0.5 leading-snug">
                Thửa đất số 51, Tờ bản đồ số 15, Tổ Dân Phố Hà My Đông A, Phường Điện Bàn Đông, TP Đà Nẵng
              </p>
            </div>
            <div class="h-56 w-full bg-gray-200 relative">
              <iframe 
                title="Bản đồ Cơ sở 1 Công ty An Nhiên"
                src="https://www.google.com/maps?q=H%C3%A0+My+%C4%90%C3%B4ng+A,+%C4%90i%E1%BB%87n+B%C3%A0n+%C4%90%C3%B4ng,+%C4%90%C3%A0+N%E1%BA%B5ng&output=embed" 
                class="w-full h-full border-0" 
                loading="lazy"
                referrerpolicy="no-referrer-when-downgrade">
              </iframe>
            </div>
            <div class="p-2 bg-white border-t border-gray-200 flex items-center justify-between text-xs">
              <span class="font-semibold text-gray-700"><i class="fa-solid fa-phone text-brand mr-1"></i>0777.568.919</span>
              <a href="https://www.google.com/maps/place//data=!4m2!3m1!19sChIJVbwKvxIRQjER0kXkOZ-2iyQ" target="_blank" rel="noopener noreferrer" class="text-brand font-bold hover:underline">
                Mở chỉ đường Google Maps →
              </a>
            </div>
          </div>

          <!-- Bản đồ Cơ sở 2 -->
          <div class="lg:col-span-4 border border-gray-200 rounded-lg overflow-hidden flex flex-col bg-slate-50">
            <div class="p-2.5 bg-white border-b border-gray-200">
              <div class="text-xs font-extrabold text-brand-dark uppercase">
                <i class="fa-solid fa-location-dot text-red-600 mr-1"></i> BẢN ĐỒ CƠ SỞ 2 - NGŨ HÀNH SƠN
              </div>
              <p class="text-[11.5px] text-gray-600 mt-0.5 leading-snug">
                24 Nguyễn Tuyển, Phường Ngũ Hành Sơn, Thành phố Đà Nẵng (Gần trục Lê Văn Hiến)
              </p>
            </div>
            <div class="h-56 w-full bg-gray-200 relative">
              <iframe 
                title="Bản đồ Cơ sở 2 Công ty An Nhiên - 24 Nguyễn Tuyển"
                src="https://www.google.com/maps?q=24+Nguy%E1%BB%85n+Tuy%E1%BB%83n,+Ng%C5%A9+H%C3%A0nh+S%C6%A1n,+%C4%90%C3%A0+N%E1%BA%B5ng&output=embed" 
                class="w-full h-full border-0" 
                loading="lazy"
                referrerpolicy="no-referrer-when-downgrade">
              </iframe>
            </div>
            <div class="p-2 bg-white border-t border-gray-200 flex items-center justify-between text-xs">
              <span class="font-semibold text-gray-700"><i class="fa-solid fa-phone text-brand mr-1"></i>0905.569.019</span>
              <a href="https://www.google.com/maps/place//data=!4m2!3m1!19sChIJw4smopoQQjERCUxC1lGfDII" target="_blank" rel="noopener noreferrer" class="text-brand font-bold hover:underline">
                Mở chỉ đường Google Maps →
              </a>
            </div>
          </div>

          <!-- Fanpage Facebook đưa ra ngoài trang chủ -->
          <div class="lg:col-span-4 border border-gray-200 rounded-lg overflow-hidden flex flex-col bg-slate-50 justify-between">
            <div class="p-2.5 bg-white border-b border-gray-200">
              <div class="text-xs font-extrabold text-brand-dark uppercase">
                <i class="fa-brands fa-facebook text-blue-600 mr-1"></i> KẾT NỐI FANPAGE FACEBOOK AN NHIÊN
              </div>
              <p class="text-[11.5px] text-gray-600 mt-0.5 leading-snug">
                Cập nhật hình ảnh lắp đặt thực tế và ưu đãi mới nhất trên Fanpage
              </p>
            </div>

            <div class="p-3 flex-1 flex flex-col justify-between bg-white space-y-2.5">
              <!-- Thẻ nhận diện trực quan Fanpage + Nhúng Plugin Facebook -->
              <div class="flex items-center gap-2.5 p-2 rounded border border-blue-100 bg-blue-50/50">
                <img 
                  src="https://lh3.googleusercontent.com/d/1pcWkz4BAbk1-i32SuAnlu66hEVy3d5wI=w200" 
                  onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1pcWkz4BAbk1-i32SuAnlu66hEVy3d5wI&sz=w200';"
                  alt="Fanpage An Nhiên" 
                  class="w-11 h-11 object-contain rounded border bg-white p-0.5 shrink-0"
                >
                <div class="min-w-0">
                  <a href="https://www.facebook.com/profile.php?id=61550275109005" target="_blank" rel="noopener noreferrer" class="text-xs font-bold text-blue-800 hover:underline block leading-snug">
                    Công Ty TNHH Công Nghệ Và Dịch Vụ Kỹ Thuật An Nhiên
                  </a>
                  <span class="text-[11px] text-gray-600 block">Thiết bị xử lý nước & Lọc tổng Đà Nẵng</span>
                </div>
              </div>

              <!-- Khung ảnh thực tế từ Fanpage -->
              <div class="grid grid-cols-3 gap-1.5">
                <img src="https://lh3.googleusercontent.com/d/1UjKKfYpmK_YM0Ah3tuPKXbO8kKJv66mg=w300" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1UjKKfYpmK_YM0Ah3tuPKXbO8kKJv66mg&sz=w300';" alt="Ảnh thực tế 1" class="h-16 w-full object-cover rounded border">
                <img src="https://lh3.googleusercontent.com/d/1SYfKD4hD9trx7N_LGYdw5EsjvUS1jnTm=w300" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1SYfKD4hD9trx7N_LGYdw5EsjvUS1jnTm&sz=w300';" alt="Ảnh thực tế 2" class="h-16 w-full object-cover rounded border">
                <img src="https://lh3.googleusercontent.com/d/1498tDcaIiFiXHbzRO37x7553qzf8OUdM=w300" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1498tDcaIiFiXHbzRO37x7553qzf8OUdM&sz=w300';" alt="Ảnh thực tế 3" class="h-16 w-full object-cover rounded border">
              </div>

              <div class="flex items-center gap-2 pt-1">
                <a href="https://www.facebook.com/profile.php?id=61550275109005" target="_blank" rel="noopener noreferrer" class="flex-1 bg-[#1877F2] hover:bg-blue-700 text-white text-center font-bold text-xs py-2 rounded transition">
                  <i class="fa-brands fa-facebook-f mr-1"></i> Xem Fanpage Facebook
                </a>
                <a href="https://zalo.me/0777568919" target="_blank" rel="noopener noreferrer" class="flex-1 bg-[#0068ff] hover:bg-blue-800 text-white text-center font-bold text-xs py-2 rounded transition">
                  <i class="fa-solid fa-comment-dots mr-1"></i> Chat Zalo
                </a>
              </div>
            </div>
          </div>

        </div>
      </div>
    </div>
  </section>

  <!-- =========================================================================================
       DANH MỤC CÁC ĐỐI TÁC & THƯƠNG HIỆU ĐỒNG HÀNH
  ========================================================================================== -->
  <section class="py-3">
    <div class="container-95">
      <div class="bg-white rounded-lg border border-gray-200 shadow-sm overflow-hidden">
        <div class="flatsome-section-title">
          <h2 class="flatsome-title-main">
            <i class="fa-regular fa-handshake mr-1.5"></i> ĐỐI TÁC & THƯƠNG HIỆU ĐỒNG HÀNH
          </h2>
          <span class="text-xs text-gray-500 pr-3 hidden sm:inline">Phân phối thiết bị và linh kiện chính hãng</span>
        </div>

        <div class="p-3 grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-2.5 text-center">
          <div class="border border-gray-200 rounded p-2.5 bg-slate-50 flex flex-col items-center justify-center">
            <span class="text-xs font-black text-brand-dark tracking-wider">PENTAIR USA</span>
            <span class="text-[10px] text-gray-500">Van & Cột lọc tổng</span>
          </div>
          <div class="border border-gray-200 rounded p-2.5 bg-slate-50 flex flex-col items-center justify-center">
            <span class="text-xs font-black text-brand-dark tracking-wider">DUPONT FILMTEC</span>
            <span class="text-[10px] text-gray-500">Màng lọc RO Mỹ</span>
          </div>
          <div class="border border-gray-200 rounded p-2.5 bg-slate-50 flex flex-col items-center justify-center">
            <span class="text-xs font-black text-brand-dark tracking-wider">CLACK CORP</span>
            <span class="text-[10px] text-gray-500">Autovalve thông minh</span>
          </div>
          <div class="border border-gray-200 rounded p-2.5 bg-slate-50 flex flex-col items-center justify-center">
            <span class="text-xs font-black text-brand-dark tracking-wider">KAROFI</span>
            <span class="text-[10px] text-gray-500">Máy lọc nước RO</span>
          </div>
          <div class="border border-gray-200 rounded p-2.5 bg-slate-50 flex flex-col items-center justify-center">
            <span class="text-xs font-black text-brand-dark tracking-wider">KANGAROO</span>
            <span class="text-[10px] text-gray-500">Máy lọc nóng lạnh</span>
          </div>
          <div class="border border-gray-200 rounded p-2.5 bg-slate-50 flex flex-col items-center justify-center">
            <span class="text-xs font-black text-brand-dark tracking-wider">BIONTECH</span>
            <span class="text-[10px] text-gray-500">Máy điện giải Ion kiềm</span>
          </div>
          <div class="border border-gray-200 rounded p-2.5 bg-slate-50 flex flex-col items-center justify-center">
            <span class="text-xs font-black text-brand-dark tracking-wider">GRUNDFOS / EBARA</span>
            <span class="text-[10px] text-gray-500">Bơm công nghiệp</span>
          </div>
          <div class="border border-gray-200 rounded p-2.5 bg-slate-50 flex flex-col items-center justify-center">
            <span class="text-xs font-black text-brand-dark tracking-wider">AQUAPRO / RUNXIN</span>
            <span class="text-[10px] text-gray-500">Linh kiện xử lý nước</span>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- =========================================================================================
       FOOTER CHUẨN FLATSOME (Giống bố cục locnuocdanaco.com.vn)
  ========================================================================================== -->
  <footer class="bg-[#003b73] text-white mt-4 border-t-4 border-brand-light">
    <div class="container-95 py-8">
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-6 text-xs">
        
        <!-- Cột 1: Thông tin công ty -->
        <div class="lg:col-span-5 space-y-2.5">
          <div class="flex items-center gap-2.5">
            <img 
              src="https://lh3.googleusercontent.com/d/1pcWkz4BAbk1-i32SuAnlu66hEVy3d5wI=w200" 
              onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1pcWkz4BAbk1-i32SuAnlu66hEVy3d5wI&sz=w200';"
              alt="Logo Công Ty An Nhiên" 
              class="h-10 w-auto object-contain bg-white p-1 rounded"
            >
            <div>
              <h3 class="text-sm font-extrabold uppercase text-white leading-snug">
                CÔNG TY TNHH CÔNG NGHỆ VÀ DỊCH VỤ KỸ THUẬT AN NHIÊN
              </h3>
              <span class="text-sky-300 font-bold">Website: locnuocannhien.com</span>
            </div>
          </div>

          <p class="text-sky-100 leading-relaxed">
            Mã số thuế: <strong>4001311904</strong> – Chuyên lắp đặt hệ thống cấp thoát nước, thiết bị xử lý nước phèn, hệ thống lọc tổng đầu nguồn, máy lọc nước dân dụng, máy lọc nước nóng lạnh, dây chuyền lọc nước tinh khiết RO và cung cấp vật liệu lọc nước chính hãng tại Đà Nẵng.
          </p>

          <ul class="space-y-1.5 text-sky-50">
            <li><i class="fa-solid fa-location-dot text-amber-300 mr-1.5"></i><strong>Cơ sở 1:</strong> Thửa đất số 51, Tờ bản đồ số 15, Tổ Dân Phố Hà My Đông A, Phường Điện Bàn Đông, TP Đà Nẵng</li>
            <li><i class="fa-solid fa-location-dot text-amber-300 mr-1.5"></i><strong>Cơ sở 2:</strong> 24 Nguyễn Tuyển, Phường Ngũ Hành Sơn, TP Đà Nẵng</li>
            <li><i class="fa-solid fa-phone-volume text-amber-300 mr-1.5"></i><strong>Hotline 1 (Zalo):</strong> <a href="tel:0777568919" class="underline font-bold">0777 568 919</a></li>
            <li><i class="fa-solid fa-phone text-amber-300 mr-1.5"></i><strong>Hotline 2:</strong> <a href="tel:0905569019" class="underline font-bold">0905 569 019</a></li>
            <li><i class="fa-brands fa-facebook text-amber-300 mr-1.5"></i><strong>Fanpage:</strong> <a href="https://www.facebook.com/profile.php?id=61550275109005" target="_blank" rel="noopener noreferrer" class="underline">facebook.com/profile.php?id=61550275109005</a></li>
          </ul>
        </div>

        <!-- Cột 2: Danh mục sản phẩm -->
        <div class="lg:col-span-4 space-y-2">
          <h4 class="text-sm font-bold uppercase text-amber-300 border-b border-white/15 pb-1.5">
            DANH MỤC SẢN PHẨM
          </h4>
          <div class="grid grid-cols-2 gap-1.5 text-sky-100">
            <a href="#sec-xulynuoc" class="hover:text-white">› Thiết bị xử lý nước</a>
            <a href="#sec-loctong" class="hover:text-white">› Hệ thống lọc tổng nhập khẩu</a>
            <a href="#sec-dandung" class="hover:text-white">› Máy lọc nước dân dụng</a>
            <a href="#sec-nonglanh" class="hover:text-white">› Máy lọc nước nóng lạnh</a>
            <a href="#sec-congnghiep" class="hover:text-white">› Dây chuyền lọc nước CN</a>
            <a href="#sec-phukien" class="hover:text-white">› Phụ kiện lọc nước</a>
            <a href="#sec-vatlieu" class="hover:text-white">› Vật liệu lọc nước</a>
            <a href="#sec-dietkhuan" class="hover:text-white">› Thiết bị diệt khuẩn</a>
            <a href="#sec-hoboi" class="hover:text-white">› Thiết bị lọc nước hồ bơi</a>
            <a href="#sec-bomcn" class="hover:text-white">› Bơm công nghiệp</a>
            <a href="#sec-nuocbien" class="hover:text-white">› Máy lọc nước biển</a>
            <a href="#sec-nlmt" class="hover:text-white">› Năng lượng mặt trời</a>
          </div>
        </div>

        <!-- Cột 3: Chính sách khách hàng (Giống mẫu Danaco) -->
        <div class="lg:col-span-3 space-y-2">
          <h4 class="text-sm font-bold uppercase text-amber-300 border-b border-white/15 pb-1.5">
            CHÍNH SÁCH & HỖ TRỢ
          </h4>
          <ul class="space-y-1.5 text-sky-100">
            <li><a href="#bao-gia" class="hover:text-white">› Chính sách khảo sát nguồn nước</a></li>
            <li><a href="#bao-gia" class="hover:text-white">› Chính sách bảo hành & bảo trì định kỳ</a></li>
            <li><a href="#bao-gia" class="hover:text-white">› Chính sách giao hàng & lắp đặt tận nơi</a></li>
            <li><a href="#bao-gia" class="hover:text-white">› Quy định và hình thức thanh toán</a></li>
            <li><a href="#bao-gia" class="hover:text-white">› Chính sách đổi trả và hoàn tiền</a></li>
            <li><a href="#bao-gia" class="hover:text-white">› Chính sách bảo mật thông tin</a></li>
          </ul>
        </div>

      </div>
    </div>

    <div class="bg-[#002851] py-3 text-center text-[11px] text-sky-200 border-t border-white/10">
      <div class="container-95 flex flex-col sm:flex-row items-center justify-between gap-2">
        <span>© Bản quyền thuộc về <strong>CÔNG TY TNHH CÔNG NGHỆ VÀ DỊCH VỤ KỸ THUẬT AN NHIÊN</strong> - Website: <strong>locnuocannhien.com</strong></span>
        <span>Giao diện chuẩn UX Builder Flatsome</span>
      </div>
    </div>
  </footer>

  <!-- =========================================================================================
       CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE) TƯƠNG THÍCH MÁY TÍNH & ĐIỆN THOẠI
  ========================================================================================== -->
  <div class="fixed bottom-3 left-3 z-50 flex flex-col gap-2">
    <!-- Nút Zalo 0777568919 -->
    <a 
      href="https://zalo.me/0777568919" 
      target="_blank" 
      rel="noopener noreferrer"
      class="floating-btn-pulse flex items-center gap-2 bg-[#0068ff] hover:bg-blue-700 text-white px-3 py-2 rounded-full shadow-lg text-xs font-bold transition"
      title="Chat Zalo 0777568919"
    >
      <span class="w-6 h-6 rounded-full bg-white text-[#0068ff] font-black flex items-center justify-center text-[11px] shrink-0">Zalo</span>
      <span class="pr-1">Zalo: 0777.568.919</span>
    </a>

    <!-- Nút Fanpage Facebook -->
    <a 
      href="https://www.facebook.com/profile.php?id=61550275109005" 
      target="_blank" 
      rel="noopener noreferrer"
      class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-800 text-white px-3 py-2 rounded-full shadow-lg text-xs font-bold transition"
      title="Fanpage Facebook Kỹ Thuật An Nhiên"
    >
      <span class="w-6 h-6 rounded-full bg-white text-[#1877F2] flex items-center justify-center text-xs shrink-0">
        <i class="fa-brands fa-facebook-f"></i>
      </span>
      <span class="pr-1">Fanpage An Nhiên</span>
    </a>

    <!-- Nút Hotline 1: 0777568919 -->
    <a 
      href="tel:0777568919" 
      class="floating-btn-pulse flex items-center gap-2 bg-[#d9381e] hover:bg-red-700 text-white px-3 py-2 rounded-full shadow-lg text-xs font-bold transition"
      title="Gọi Hotline 0777568919"
    >
      <span class="w-6 h-6 rounded-full bg-white text-[#d9381e] flex items-center justify-center text-xs shrink-0">
        <i class="fa-solid fa-phone-volume"></i>
      </span>
      <span class="pr-1">0777.568.919</span>
    </a>

    <!-- Nút Hotline 2: 0905569019 -->
    <a 
      href="tel:0905569019" 
      class="flex items-center gap-2 bg-emerald-600 hover:bg-emerald-700 text-white px-3 py-2 rounded-full shadow-lg text-xs font-bold transition"
      title="Gọi Hotline 0905569019"
    >
      <span class="w-6 h-6 rounded-full bg-white text-emerald-600 flex items-center justify-center text-xs shrink-0">
        <i class="fa-solid fa-phone"></i>
      </span>
      <span class="pr-1">0905.569.019</span>
    </a>
  </div>

  <!-- MODAL XEM CHI TIẾT SẢN PHẨM & ĐẶT MUA NHANH -->
  <div id="productModal" class="fixed inset-0 bg-black/60 z-50 hidden items-center justify-center p-3">
    <div class="bg-white rounded-lg max-w-lg w-full overflow-hidden shadow-2xl border border-gray-200">
      <div class="bg-brand text-white px-4 py-2.5 flex items-center justify-between">
        <h3 id="modalProdTitle" class="text-xs sm:text-sm font-bold uppercase pr-2">Thông tin sản phẩm</h3>
        <button type="button" onclick="closeProductModal()" class="text-white hover:text-amber-300 text-lg font-bold leading-none">&times;</button>
      </div>
      <div class="p-4 space-y-3 text-xs">
        <div class="grid grid-cols-1 sm:grid-cols-12 gap-3 items-center">
          <div class="sm:col-span-5 h-44 bg-slate-100 rounded border overflow-hidden">
            <img id="modalProdImg" src="" alt="" class="w-full h-full object-cover">
          </div>
          <div class="sm:col-span-7 space-y-2">
            <div id="modalProdCat" class="text-[11px] font-bold text-brand uppercase"></div>
            <div id="modalProdName" class="text-sm font-bold text-gray-900 leading-snug"></div>
            <div class="flex items-center gap-2">
              <span id="modalProdOldPrice" class="line-through text-gray-400 text-xs"></span>
              <span id="modalProdPrice" class="text-base font-extrabold text-brand-sale"></span>
              <span id="modalProdSale" class="bg-brand-sale text-white text-[10px] font-bold px-2 py-0.5 rounded"></span>
            </div>
            <p class="text-gray-600 leading-relaxed">
              Sản phẩm được cung cấp và lắp đặt trực tiếp bởi <strong>Công Ty TNHH Công Nghệ Và Dịch Vụ Kỹ Thuật An Nhiên (locnuocannhien.com)</strong>. Miễn phí khảo sát nguồn nước tại Đà Nẵng.
            </p>
          </div>
        </div>
        <div class="pt-2 border-t border-gray-200 flex flex-wrap items-center justify-end gap-2">
          <a href="https://zalo.me/0777568919" target="_blank" rel="noopener noreferrer" class="bg-[#0068ff] text-white font-bold px-3.5 py-2 rounded">
            <i class="fa-solid fa-comment-dots mr-1"></i> Tư vấn qua Zalo: 0777.568.919
          </a>
          <a href="#bao-gia" onclick="closeProductModal()" class="bg-brand-sale text-white font-bold px-3.5 py-2 rounded">
            <i class="fa-solid fa-file-signature mr-1"></i> Yêu cầu báo giá
          </a>
        </div>
      </div>
    </div>
  </div>

  <!-- JAVASCRIPT XỬ LÝ DỮ LIỆU SẢN PHẨM (14 ẢNH THỰC TẾ GOOGLE DRIVE), BANNER SLIDER, BÀI VIẾT & FORM -->
  <script>
    // Hàm tạo URL ảnh từ ID Google Drive kèm fallback tự động
    function driveImg(fileId) {
      return `https://lh3.googleusercontent.com/d/${fileId}=w800`;
    }
    function driveFallback(fileId) {
      return `https://drive.google.com/thumbnail?id=${fileId}&sz=w800`;
    }

    // 14 File ID ảnh thực tế do người dùng cung cấp từ Google Drive:
    const REAL_DRIVE_IDS = [
      '1UjKKfYpmK_YM0Ah3tuPKXbO8kKJv66mg', // Ảnh 1
      '1SYfKD4hD9trx7N_LGYdw5EsjvUS1jnTm', // Ảnh 2
      '1498tDcaIiFiXHbzRO37x7553qzf8OUdM', // Ảnh 3
      '1kW3jyv6wwCELQwepWLQpYMVBJlg94e-v', // Ảnh 4
      '1Ebn-ZZPBe4tR4bd3Gafr4ThuAHtdeP9X', // Ảnh 5
      '1rNKvt9P-iWfj5yJrIkNjSwTMVSI5l8Jk', // Ảnh 6
      '1q6_ziycQ_sXP5bA4hx8tZbpKQCs_cEP2', // Ảnh 7
      '1zkYVx57eDpdapSBWh9rDC3wq4_FuKsOK', // Ảnh 8
      '1TGSTh48n1WnLblQwFGgpVzriOQTyp4TH', // Ảnh 9
      '1Uz6xOizvcN_fHmTK03eMVJ7QRjppUvDj', // Ảnh 10
      '1Dt2DS5V1morPg6xwX-WDiokS1UUzOixI', // Ảnh 11
      '1aoCZ0c5QfdLF19rtIC5XqeJZ2g_Hh9mo', // Ảnh 12
      '1-m3yp1hX2lM7n8Dd8bPSp9wJZrsNJ-h8', // Ảnh 13
      '1dFI9x0OCsc9HQ7RWYbFH-fLHd37795nx'  // Ảnh 14
    ];

    // Danh sách các danh mục chuẩn từ web mẫu locnuocdanaco.com.vn
    // Mỗi sản phẩm đều sử dụng ảnh thực tế từ 14 file Google Drive, có giá giảm & % giảm góc trên bên trái chuẩn Flatsome
    const PRODUCT_SECTIONS = [
      {
        id: 'sec-xulynuoc',
        title: 'THIẾT BỊ XỬ LÝ NƯỚC',
        subtitle: 'Xử lý nước phèn, nước giếng khoan, khử vôi, làm mềm nước',
        products: [
          {
            name: 'Hệ Thống Xử Lý Làm Mềm Nước Đầu Nguồn 3 Cột Inox 304 Van Tự Động',
            driveId: REAL_DRIVE_IDS[0],
            oldPrice: '14.500.000 ₫',
            price: '11.600.000 ₫',
            discount: '-20%'
          },
          {
            name: 'Hệ Thống Xử Lý Nước Giếng Khoan Nhiễm Phèn Sắt 2 Cột Composite 1054',
            driveId: REAL_DRIVE_IDS[1],
            oldPrice: '8.500.000 ₫',
            price: '6.950.000 ₫',
            discount: '-18%'
          },
          {
            name: 'Bộ Lọc Thô Đầu Nguồn 3 Cốc Lọc 20 Inch Xử Lý Cặn Phèn Nước Máy',
            driveId: REAL_DRIVE_IDS[6],
            oldPrice: '2.200.000 ₫',
            price: '1.750.000 ₫',
            discount: '-20%'
          },
          {
            name: 'Hệ Thống Lọc Nước Giếng Khoan Công Suất 1.5m3/h Tích Hợp Màng Siêu Lọc UF',
            driveId: REAL_DRIVE_IDS[7],
            oldPrice: '16.000.000 ₫',
            price: '13.200.000 ₫',
            discount: '-18%'
          }
        ]
      },
      {
        id: 'sec-loctong',
        title: 'HỆ THỐNG LỌC TỔNG NHẬP KHẨU',
        subtitle: 'Hệ thống lọc tổng toàn nhà cho biệt thự, căn hộ, khách sạn tại Đà Nẵng',
        products: [
          {
            name: 'Hệ Thống Lọc Tổng Đầu Nguồn Cao Cấp Tủ Kính Cường Lực Van Авто Clack USA',
            driveId: REAL_DRIVE_IDS[4],
            oldPrice: '38.000.000 ₫',
            price: '31.500.000 ₫',
            discount: '-17%'
          },
          {
            name: 'Hệ Thống Lọc Tổng Nhập Khẩu Làm Mềm Nước & Khử Clo Dư Toàn Diện',
            driveId: REAL_DRIVE_IDS[6],
            oldPrice: '29.500.000 ₫',
            price: '24.500.000 ₫',
            discount: '-17%'
          },
          {
            name: 'Hệ Thống Lọc Tổng Sinh Hoạt 3 Cột Inox 304 Kết Hợp Đèn Diệt Khuẩn UV',
            driveId: REAL_DRIVE_IDS[0],
            oldPrice: '18.900.000 ₫',
            price: '15.500.000 ₫',
            discount: '-18%'
          },
          {
            name: 'Hệ Thống Lọc Tổng Biệt Thự 2 Cột Composite + Màng UF Công Suất 2.000L/H',
            driveId: REAL_DRIVE_IDS[1],
            oldPrice: '15.800.000 ₫',
            price: '12.900.000 ₫',
            discount: '-18%'
          }
        ]
      },
      {
        id: 'sec-dandung',
        title: 'MÁY LỌC NƯỚC DÂN DỤNG',
        subtitle: 'Máy lọc nước tinh khiết RO gia đình, máy lọc nước gầm bếp, máy tạo kiềm',
        products: [
          {
            name: 'Máy Lọc Nước Tinh Khiết RO 10 Lõi Tủ Kính Cường Lực Bơm Êm Ái',
            driveId: REAL_DRIVE_IDS[3],
            oldPrice: '6.500.000 ₫',
            price: '4.950.000 ₫',
            discount: '-24%'
          },
          {
            name: 'Bộ Lọc Nước RO 50GPD - 100GPD Lắp Gầm Tủ Bếp Không Vỏ Tủ Gọn Nhẹ',
            driveId: REAL_DRIVE_IDS[4],
            oldPrice: '4.800.000 ₫',
            price: '3.650.000 ₫',
            discount: '-24%'
          },
          {
            name: 'Máy Lọc Nước Bán Công Nghiệp RO 30 Lít/Giờ - 50 Lít/Giờ Cho Văn Phòng',
            driveId: REAL_DRIVE_IDS[7],
            oldPrice: '9.500.000 ₫',
            price: '7.800.000 ₫',
            discount: '-18%'
          },
          {
            name: 'Máy Điện Giải Tạo Nước Ion Kiềm Giàu Hydro Chăm Sóc Sức Khỏe Gia Đình',
            driveId: REAL_DRIVE_IDS[8],
            oldPrice: '26.000.000 ₫',
            price: '21.500.000 ₫',
            discount: '-17%'
          }
        ]
      },
      {
        id: 'sec-nonglanh',
        title: 'MÁY LỌC NƯỚC NÓNG LẠNH',
        subtitle: 'Máy lọc nước nóng lạnh trực tiếp gia đình, công sở, trường học, nhà xưởng',
        products: [
          {
            name: 'Máy Lọc Nước Nóng Lạnh Nguội RO Trực Tiếp Thiết Kế Sang Trọng Hiện Đại',
            driveId: REAL_DRIVE_IDS[5],
            oldPrice: '8.900.000 ₫',
            price: '6.990.000 ₫',
            discount: '-21%'
          },
          {
            name: 'Máy Lọc Nước Nóng Lạnh Công Nghiệp 2 Vòi Vỏ Inox 304 Bền Bỉ',
            driveId: REAL_DRIVE_IDS[3],
            oldPrice: '11.500.000 ₫',
            price: '9.200.000 ₫',
            discount: '-20%'
          },
          {
            name: 'Máy Lọc Nước Uống Nóng Lạnh Công Nghiệp 4 Vòi RO Cho Trường Học & Xưởng',
            driveId: REAL_DRIVE_IDS[5],
            oldPrice: '18.500.000 ₫',
            price: '15.200.000 ₫',
            discount: '-18%'
          },
          {
            name: 'Máy Lọc Nước Nóng Lạnh Công Nghiệp 6 Vòi Cao Cấp Công Suất Lớn',
            driveId: REAL_DRIVE_IDS[2],
            oldPrice: '24.000.000 ₫',
            price: '19.800.000 ₫',
            discount: '-18%'
          }
        ]
      },
      {
        id: 'sec-congnghiep',
        title: 'DÂY CHUYỀN LỌC NƯỚC CÔNG NGHIỆP',
        subtitle: 'Dây chuyền lọc nước tinh khiết RO 125L/h - 2000L/h, sản xuất nước đóng bình',
        products: [
          {
            name: 'Dây Chuyền Lọc Nước Tinh Khiết RO Công Nghiệp Công Suất 250 Lít/Giờ',
            driveId: REAL_DRIVE_IDS[2],
            oldPrice: '42.000.000 ₫',
            price: '35.500.000 ₫',
            discount: '-15%'
          },
          {
            name: 'Dây Chuyền Sản Xuất Nước Tinh Khiết RO Công Suất 500 Lít/Giờ Inox 304',
            driveId: REAL_DRIVE_IDS[12],
            oldPrice: '65.000.000 ₫',
            price: '54.000.000 ₫',
            discount: '-17%'
          },
          {
            name: 'Dây Chuyền Lọc Nước Tinh Khiết RO 1000 Lít/Giờ + Hệ Chiết Rót Bình 20L',
            driveId: REAL_DRIVE_IDS[13],
            oldPrice: '115.000.000 ₫',
            price: '96.000.000 ₫',
            discount: '-17%'
          },
          {
            name: 'Hệ Thống Lọc Nước RO Công Nghiệp Cột Composite 400 Lít/Giờ Tự Động',
            driveId: REAL_DRIVE_IDS[2],
            oldPrice: '48.000.000 ₫',
            price: '39.900.000 ₫',
            discount: '-17%'
          }
        ]
      },
      {
        id: 'sec-phukien',
        title: 'PHỤ KIỆN LỌC NƯỚC & VẬT LIỆU LỌC NƯỚC',
        subtitle: 'Cột lọc Inox, Composite, van tự động, màng RO, than hoạt tính, hạt Cation',
        products: [
          {
            name: 'Bộ Lõi Lọc Nước Thô 1-2-3 & Màng Lọc RO Thay Thế Chính Hãng',
            driveId: REAL_DRIVE_IDS[8],
            oldPrice: '850.000 ₫',
            price: '650.000 ₫',
            discount: '-24%'
          },
          {
            name: 'Vật Liệu Lọc Nước: Than Hoạt Tính Gáo Dừa, Cát Mangan, Hạt Nhựa Cation',
            driveId: REAL_DRIVE_IDS[9],
            oldPrice: '1.250.000 ₫',
            price: '980.000 ₫',
            discount: '-22%'
          },
          {
            name: 'Van Tự Động Sục Rửa Autovalve 3 Ngã & 5 Ngã Lắp Cột Lọc Đầu Nguồn',
            driveId: REAL_DRIVE_IDS[8],
            oldPrice: '2.400.000 ₫',
            price: '1.950.000 ₫',
            discount: '-19%'
          },
          {
            name: 'Cột Lọc Nước Inox 304 & Cột Composite Đủ Kích Thước 1054, 1252, 1465',
            driveId: REAL_DRIVE_IDS[9],
            oldPrice: '2.600.000 ₫',
            price: '2.100.000 ₫',
            discount: '-19%'
          }
        ]
      },
      {
        id: 'sec-dietkhuan',
        title: 'THIẾT BỊ DIỆT KHUẨN, HỒ BƠI, BƠM CN, LỌC NƯỚC BIỂN & NLMT',
        subtitle: 'Đèn UV diệt khuẩn, bình lọc cát hồ bơi, bơm trục đứng, máy lọc nước biển & máy nước nóng NLMT',
        products: [
          {
            name: 'Đèn Tia Cực Tím UV Diệt Khuẩn Nước Sinh Hoạt & Dây Chuyền RO Vỏ Inox',
            driveId: REAL_DRIVE_IDS[10],
            oldPrice: '2.900.000 ₫',
            price: '2.350.000 ₫',
            discount: '-19%'
          },
          {
            name: 'Thiết Bị Bình Lọc Cát & Máy Bơm Tuần Hoàn Xử Lý Nước Hồ Bơi',
            driveId: REAL_DRIVE_IDS[11],
            oldPrice: '12.500.000 ₫',
            price: '10.200.000 ₫',
            discount: '-18%'
          },
          {
            name: 'Bơm Công Nghiệp Trục Ngang & Trục Đứng Đầu Inox 304 Chuyên Dụng Lọc Nước',
            driveId: REAL_DRIVE_IDS[12],
            oldPrice: '6.800.000 ₫',
            price: '5.500.000 ₫',
            discount: '-19%'
          },
          {
            name: 'Hệ Thống Máy Lọc Nước Biển Thành Nước Ngọt & Máy Nước Nóng Năng Lượng Mặt Trời',
            driveId: REAL_DRIVE_IDS[13],
            oldPrice: '19.500.000 ₫',
            price: '15.900.000 ₫',
            discount: '-18%'
          }
        ]
      }
    ];

    // Tạo thêm neo id cho các mục menu phụ (sec-vatlieu, sec-hoboi, sec-bomcn, sec-nuocbien, sec-nlmt)
    const EXTRA_ANCHOR_MAP = {
      'sec-phukien': ['sec-vatlieu'],
      'sec-dietkhuan': ['sec-hoboi', 'sec-bomcn', 'sec-nuocbien', 'sec-nlmt']
    };

    // Hàm tạo thẻ sản phẩm chuẩn Flatsome:
    // - Điện thoại 2 cột (grid-cols-2), tên sản phẩm hiển thị đầy đủ không cắt chữ, chỉ có vòng tròn % giảm giá góc trên bên trái
    function createProductCardHTML(prod, categoryTitle) {
      const safeName = prod.name.replace(/'/g, "\\'");
      const safeCat = categoryTitle.replace(/'/g, "\\'");
      return `
        <div class="product-card">
          <div class="relative h-40 sm:h-48 md:h-52 w-full bg-slate-100 overflow-hidden border-b border-gray-100">
            <!-- Vòng tròn % giảm giá góc trên bên trái chuẩn Flatsome -->
            <div class="flatsome-sale-badge">${prod.discount}</div>
            <img 
              src="${driveImg(prod.driveId)}" 
              onerror="this.onerror=null;this.src='${driveFallback(prod.driveId)}';"
              alt="${prod.name}" 
              loading="lazy"
              onclick="openProductModal('${safeName}', '${safeCat}', '${prod.driveId}', '${prod.oldPrice}', '${prod.price}', '${prod.discount}')"
              class="w-full h-full object-cover cursor-pointer hover:scale-105 transition duration-300"
            >
          </div>
          <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
            <div>
              <div class="text-[10.5px] text-gray-400 uppercase font-medium mb-1">${categoryTitle}</div>
              <h3 
                onclick="openProductModal('${safeName}', '${safeCat}', '${prod.driveId}', '${prod.oldPrice}', '${prod.price}', '${prod.discount}')"
                class="product-title-full text-xs sm:text-[13.5px] font-bold text-gray-800 hover:text-brand cursor-pointer mb-2"
              >
                ${prod.name}
              </h3>
            </div>
            <div class="pt-1.5 border-t border-gray-100">
              <div class="flex flex-wrap items-baseline gap-x-2 gap-y-0.5 mb-2">
                <span class="text-[11px] text-gray-400 line-through">${prod.oldPrice}</span>
                <span class="text-xs sm:text-sm font-extrabold text-brand-sale">${prod.price}</span>
              </div>
              <button 
                type="button"
                onclick="openProductModal('${safeName}', '${safeCat}', '${prod.driveId}', '${prod.oldPrice}', '${prod.price}', '${prod.discount}')"
                class="w-full bg-brand hover:bg-brand-dark text-white text-[11px] sm:text-xs font-bold py-1.5 px-2 rounded transition"
              >
                Tư vấn & Báo giá
              </button>
            </div>
          </div>
        </div>
      `;
    }

    // Render toàn bộ các danh mục sản phẩm ra trang chủ
    function renderAllProductSections() {
      const container = document.getElementById('allProductSections');
      let html = '';

      PRODUCT_SECTIONS.forEach(sec => {
        const extraAnchors = (EXTRA_ANCHOR_MAP[sec.id] || []).map(a => `<span id="${a}"></span>`).join('');
        const cardsHTML = sec.products.map(p => createProductCardHTML(p, sec.title)).join('');

        html += `
          <section id="${sec.id}" class="py-1">
            ${extraAnchors}
            <div class="container-95">
              <div class="bg-white rounded-lg border border-gray-200 shadow-sm overflow-hidden">
                <div class="flatsome-section-title">
                  <h2 class="flatsome-title-main">${sec.title}</h2>
                  <div class="hidden md:flex items-center gap-3 pr-3 text-xs">
                    <span class="text-gray-500">${sec.subtitle}</span>
                    <a href="#bao-gia" class="text-brand font-bold hover:underline whitespace-nowrap">Nhận báo giá →</a>
                  </div>
                </div>
                <!-- Chia 2 cột trên giao diện điện thoại (grid-cols-2), 4 cột trên máy tính -->
                <div class="p-2.5 sm:p-4 grid grid-cols-2 md:grid-cols-4 gap-2.5 sm:gap-4">
                  ${cardsHTML}
                </div>
              </div>
            </div>
          </section>
        `;
      });

      container.innerHTML = html;
    }

    // Dữ liệu các bài viết ở trang chủ
    const BLOG_POSTS = [
      {
        title: 'Giải pháp xử lý nước giếng khoan nhiễm phèn, nhiễm vôi triệt để tại Đà Nẵng',
        category: 'kien-thuc',
        catLabel: 'Kiến thức lọc nước',
        driveId: REAL_DRIVE_IDS[0],
        date: 'Cập nhật mới nhất',
        excerpt: 'Hướng dẫn lựa chọn cấu hình cột lọc Composite hoặc Inox 304 kết hợp hạt Birm, Cát Mangan, Than hoạt tính gáo dừa và hạt Cation làm mềm nước hiệu quả.'
      },
      {
        title: 'Báo giá lắp đặt hệ thống lọc tổng đầu nguồn cho nhà phố & biệt thự Đà Nẵng',
        category: 'ky-thuat',
        catLabel: 'Tư vấn kỹ thuật',
        driveId: REAL_DRIVE_IDS[1],
        date: 'Tư vấn chuyên sâu',
        excerpt: 'Lọc tổng sinh hoạt giúp bảo vệ thiết bị vệ sinh, bình nóng lạnh, máy giặt không bị đóng cặn trắng và loại bỏ hoàn toàn clo dư trong nước máy.'
      },
      {
        title: 'Khi nào cần thay vật liệu lọc nước đầu nguồn và lõi lọc máy RO gia đình?',
        category: 'kien-thuc',
        catLabel: 'Kiến thức lọc nước',
        driveId: REAL_DRIVE_IDS[9],
        date: 'Kinh nghiệm sử dụng',
        excerpt: 'Thời gian định kỳ thay lõi lọc thô 1-2-3 từ 3-6 tháng và hoàn nguyên, sục rửa vật liệu cột lọc tổng để đảm bảo chất lượng nước tinh khiết.'
      },
      {
        title: 'Chính sách bảo hành, vận chuyển và lắp đặt tận nơi của Kỹ Thuật An Nhiên',
        category: 'chinh-sach',
        catLabel: 'Chính sách & Bảo hành',
        driveId: REAL_DRIVE_IDS[2],
        date: 'Thông tin khách hàng',
        excerpt: 'Công Ty TNHH Công Nghệ Và Dịch Vụ Kỹ Thuật An Nhiên cam kết khảo sát nước miễn phí, lắp đặt nhanh trong ngày tại Điện Bàn Đông, Ngũ Hành Sơn và toàn TP Đà Nẵng.'
      }
    ];

    function renderBlogPosts(filterCat = 'all') {
      const grid = document.getElementById('blogPostsGrid');
      const filtered = filterCat === 'all' ? BLOG_POSTS : BLOG_POSTS.filter(b => b.category === filterCat);

      grid.innerHTML = filtered.map(post => `
        <article class="border border-gray-200 rounded-md overflow-hidden bg-white flex flex-col hover:shadow-md transition">
          <div class="h-40 w-full bg-slate-100 overflow-hidden">
            <img 
              src="${driveImg(post.driveId)}" 
              onerror="this.onerror=null;this.src='${driveFallback(post.driveId)}';"
              alt="${post.title}" 
              class="w-full h-full object-cover"
            >
          </div>
          <div class="p-3 flex-1 flex flex-col justify-between space-y-2">
            <div>
              <span class="text-[10.5px] font-bold text-brand uppercase">${post.catLabel}</span>
              <h3 class="text-xs sm:text-sm font-bold text-gray-800 mt-1 leading-snug">${post.title}</h3>
              <p class="text-xs text-gray-600 mt-1.5 leading-relaxed">${post.excerpt}</p>
            </div>
            <a href="#bao-gia" class="text-xs font-bold text-brand hover:underline pt-1 inline-block">
              Liên hệ tư vấn kỹ thuật →
            </a>
          </div>
        </article>
      `).join('');
    }

    function filterBlogPosts(cat) {
      document.querySelectorAll('.blog-tab-btn').forEach(btn => {
        if (btn.dataset.cat === cat) {
          btn.className = 'blog-tab-btn bg-brand text-white px-2.5 py-1 rounded font-bold';
        } else {
          btn.className = 'blog-tab-btn bg-slate-100 hover:bg-slate-200 text-gray-700 px-2.5 py-1 rounded font-medium';
        }
      });
      renderBlogPosts(cat);
    }

    // Xử lý tìm kiếm sản phẩm trực tiếp
    function handleSearchProducts(keyword) {
      const q = (keyword || '').trim().toLowerCase();
      const section = document.getElementById('searchResultSection');
      const grid = document.getElementById('searchResultGrid');
      const title = document.getElementById('searchResultTitle');

      if (!q) {
        section.classList.add('hidden');
        return;
      }

      const matched = [];
      PRODUCT_SECTIONS.forEach(sec => {
        sec.products.forEach(prod => {
          if (prod.name.toLowerCase().includes(q) || sec.title.toLowerCase().includes(q)) {
            matched.push({ prod, catTitle: sec.title });
          }
        });
      });

      section.classList.remove('hidden');
      title.textContent = `Kết quả tìm kiếm cho "${keyword}" (${matched.length} sản phẩm)`;

      if (matched.length === 0) {
        grid.innerHTML = `<div class="col-span-full text-xs text-gray-600 py-4">Không tìm thấy sản phẩm khớp từ khóa. Quý khách vui lòng gọi/Zalo <strong>0777.568.919</strong> để được báo giá nhanh nhất!</div>`;
      } else {
        grid.innerHTML = matched.map(item => createProductCardHTML(item.prod, item.catTitle)).join('');
      }
    }

    function clearSearchProducts() {
      const dInput = document.getElementById('desktopSearchInput');
      const mInput = document.getElementById('mobileSearchInput');
      if (dInput) dInput.value = '';
      if (mInput) mInput.value = '';
      document.getElementById('searchResultSection').classList.add('hidden');
    }

    // Xử lý Banner Tự Trượt (2 Slide kích thước bằng nhau cho cả Desktop và Mobile)
    let currentBannerIndex = 0;
    let bannerInterval = null;

    function showBannerSlide(index) {
      currentBannerIndex = (index + 2) % 2;
      for (let i = 0; i < 2; i++) {
        const dSlide = document.getElementById(`desktopSlide${i}`);
        const mSlide = document.getElementById(`mobileSlide${i}`);
        const dot = document.getElementById(`dotSlide${i}`);
        if (i === currentBannerIndex) {
          dSlide.classList.remove('opacity-0', 'z-0');
          dSlide.classList.add('opacity-100', 'z-10');
          mSlide.classList.remove('opacity-0', 'z-0');
          mSlide.classList.add('opacity-100', 'z-10');
          dot.className = 'w-2.5 h-2.5 rounded-full bg-amber-400 transition';
        } else {
          dSlide.classList.remove('opacity-100', 'z-10');
          dSlide.classList.add('opacity-0', 'z-0');
          mSlide.classList.remove('opacity-100', 'z-10');
          mSlide.classList.add('opacity-0', 'z-0');
          dot.className = 'w-2.5 h-2.5 rounded-full bg-white/50 transition';
        }
      }
    }

    function changeBannerSlide(step) {
      showBannerSlide(currentBannerIndex + step);
      resetBannerTimer();
    }

    function setBannerSlide(index) {
      showBannerSlide(index);
      resetBannerTimer();
    }

    function resetBannerTimer() {
      if (bannerInterval) clearInterval(bannerInterval);
      bannerInterval = setInterval(() => {
        showBannerSlide(currentBannerIndex + 1);
      }, 5000);
    }

    // Menu điện thoại
    function toggleMobileMenu() {
      const drawer = document.getElementById('mobileMenuDrawer');
      drawer.classList.toggle('hidden');
    }

    // Modal xem chi tiết sản phẩm
    function openProductModal(name, cat, driveId, oldPrice, price, discount) {
      document.getElementById('modalProdTitle').textContent = cat;
      document.getElementById('modalProdCat').textContent = cat;
      document.getElementById('modalProdName').textContent = name;
      const imgEl = document.getElementById('modalProdImg');
      imgEl.src = driveImg(driveId);
      imgEl.onerror = function() {
        this.onerror = null;
        this.src = driveFallback(driveId);
      };
      document.getElementById('modalProdOldPrice').textContent = oldPrice;
      document.getElementById('modalProdPrice').textContent = price;
      document.getElementById('modalProdSale').textContent = discount;

      const modal = document.getElementById('productModal');
      modal.classList.remove('hidden');
      modal.classList.add('flex');
    }

    function closeProductModal() {
      const modal = document.getElementById('productModal');
      modal.classList.add('hidden');
      modal.classList.remove('flex');
    }

    // Xử lý gửi Form Yêu cầu và Báo giá trang chủ
    function submitQuoteForm(e) {
      e.preventDefault();
      const name = document.getElementById('qName').value.trim();
      const phone = document.getElementById('qPhone').value.trim();
      const cat = document.getElementById('qCategory').value;
      const addr = document.getElementById('qAddress').value.trim() || 'Đà Nẵng';
      const note = document.getElementById('qNote').value.trim();

      const box = document.getElementById('quoteSuccessBox');
      box.classList.remove('hidden');
      box.innerHTML = `
        <div class="font-bold text-emerald-800 mb-1">
          <i class="fa-solid fa-circle-check mr-1"></i> Đã tiếp nhận yêu cầu báo giá của quý khách: ${name} (${phone})
        </div>
        <div>Hạng mục: <strong>${cat}</strong> - Khu vực: <strong>${addr}</strong> ${note ? `- Ghi chú: ${note}` : ''}</div>
        <div class="mt-1">Bộ phận kỹ thuật <strong>Công Ty TNHH Công Nghệ Và Dịch Vụ Kỹ Thuật An Nhiên (locnuocannhien.com)</strong> sẽ gọi tư vấn ngay qua Hotline/Zalo <strong>0777.568.919 - 0905.569.019</strong>.</div>
      `;
      document.getElementById('quoteRequestForm').reset();
    }

    // Khởi chạy khi tải trang
    window.onload = function() {
      renderAllProductSections();
      renderBlogPosts('all');
      resetBannerTimer();
    };
  </script>
</body>
</html>
