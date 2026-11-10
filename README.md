<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>CÔNG TY TNHH TMDV ĐINH NGUYỄN - Gạch Ốp Lát & Thiết Bị Vệ Sinh Trọn Gói Đà Nẵng</title>
    <meta name="description" content="CÔNG TY TNHH TMDV ĐINH NGUYỄN (dinhnguyen.com) - Chuyên phân phối Gạch ốp lát, Thiết bị vệ sinh, Sàn đá giả gỗ, Vật liệu xây dựng trọn gói uy tín tại 442 Nguyễn Hữu Thọ, Cẩm Lệ, Đà Nẵng. Hotline: 0906.477.891">
    
    <!-- Open Graph Thumbnail là ảnh Logo trang web khi gửi link -->
    <meta property="og:title" content="CÔNG TY TNHH TMDV ĐINH NGUYỄN - Gạch Ốp Lát & Thiết Bị Vệ Sinh Trọn Gói">
    <meta property="og:description" content="Showroom Gạch ốp lát, Thiết bị vệ sinh cao cấp tại 442 Nguyễn Hữu Thọ, Phường Cẩm Lệ, TP Đà Nẵng. Hotline: 0906.477.891">
    <meta property="og:url" content="https://dinhnguyen.com">
    <meta property="og:type" content="website">
    <meta property="og:image" content="https://drive.google.com/thumbnail?id=1-Ec1aH7TR_ienNo4F206IqN5J12hG5Si&sz=w1200">
    
    <!-- Google Fonts: Roboto / Inter chuẩn Flatsome -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    
    <!-- Font Awesome 6 -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: {
                            DEFAULT: '#0B3B60', /* Xanh Navy đậm theo màu Logo mới */
                            dark: '#072842',
                            light: '#145385'
                        },
                        accent: {
                            DEFAULT: '#D97706', /* Vàng đồng / Cam đất sang trọng theo Logo */
                            hover: '#B45309',
                            light: '#FEF3C7'
                        },
                        flatsomeSale: '#D26E4B' /* Màu badge giảm giá chuẩn Flatsome */
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif']
                    },
                    maxWidth: {
                        'flatsome': '1500px'
                    }
                }
            }
        }
    </script>

    <style>
        /* Khắc phục triệt để tràn viền ngang hoặc lệch sang phải trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            margin: 0;
            padding: 0;
            width: 100%;
            max-width: 100vw;
            overflow-x: hidden;
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc;
            color: #1e293b;
            scroll-behavior: smooth;
        }

        /* Khung chuẩn Flatsome 1500px trên máy tính */
        .container-1500 {
            width: 100%;
            max-width: 1500px;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }
        @media (min-width: 1024px) {
            .container-1500 {
                padding-left: 20px;
                padding-right: 20px;
            }
        }

        /* Chuẩn Flatsome Section Title */
        .section-title-container {
            margin-bottom: 1.25rem;
        }
        .section-title-normal {
            display: flex;
            align-items: center;
            justify-content: space-between;
            border-bottom: 2px solid #e2e8f0;
            padding-bottom: 8px;
            gap: 12px;
        }
        .section-title-main {
            font-weight: 800;
            text-transform: uppercase;
            color: #0B3B60;
            position: relative;
            font-size: 1.15rem;
            letter-spacing: 0.02em;
        }
        @media (min-width: 768px) {
            .section-title-main {
                font-size: 1.35rem;
            }
        }
        .section-title-main::after {
            content: '';
            position: absolute;
            bottom: -10px;
            left: 0;
            width: 100%;
            height: 3px;
            background-color: #D97706;
        }

        /* Tên sản phẩm hiển thị đầy đủ hoặc 2 dòng gọn gàng không bị tràn chữ */
        .product-title {
            display: -webkit-box;
            -webkit-line-clamp: 2;
            -webkit-box-orient: vertical;
            overflow: hidden;
            min-height: 2.6rem;
            line-height: 1.3rem;
            word-break: break-word;
        }

        /* Badge giảm giá chuẩn Flatsome góc trên bên trái */
        .badge-container {
            position: absolute;
            top: 10px;
            left: 10px;
            z-index: 10;
            display: flex;
            flex-direction: column;
            gap: 4px;
            pointer-events: none;
        }
        .onsale-badge {
            background-color: #D97706;
            color: #ffffff;
            font-weight: 700;
            font-size: 11px;
            width: 40px;
            height: 40px;
            border-radius: 9999px;
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: 0 2px 6px rgba(0,0,0,0.2);
            line-height: 1;
        }

        /* Không cho phép chữ tên danh mục bị gãy chữ xuống dòng */
        .cat-nowrap {
            white-space: nowrap;
        }

        /* Hiệu ứng rung nhẹ cho nút Hotline nổi */
        @keyframes pulse-ring {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(217, 119, 6, 0.7); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(217, 119, 6, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(217, 119, 6, 0); }
        }
        .pulse-btn {
            animation: pulse-ring 2s infinite;
        }

        /* Ẩn thanh cuộn phụ nhưng vẫn vuốt mượt nếu cần */
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .no-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }
    </style>
</head>
<body class="flex flex-col min-h-screen">

    <!-- ==========================================
         1. TOP BAR (Không hiển thị bất kỳ thanh công cụ UX Builder nào)
    =========================================== -->
    <div class="bg-primary-dark text-white text-xs py-1.5 border-b border-white/10">
        <div class="container-1500 flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-4 truncate">
                <span class="inline-flex items-center gap-1.5 font-medium">
                    <i class="fa-solid fa-building text-accent"></i>
                    <span>CÔNG TY TNHH TMDV ĐINH NGUYỄN - MST: 0402171132</span>
                </span>
                <span class="hidden md:inline-flex items-center gap-1.5 text-slate-200">
                    <i class="fa-solid fa-location-dot text-accent"></i>
                    <span>442 Nguyễn Hữu Thọ, Phường Cẩm Lệ, TP Đà Nẵng</span>
                </span>
            </div>
            <div class="hidden sm:flex items-center gap-4 text-[11px] text-slate-200">
                <a href="#gioi-thieu" class="hover:text-accent transition">Hồ sơ năng lực</a>
                <span>|</span>
                <a href="#du-an" class="hover:text-accent transition">Dự án Đà Nẵng</a>
                <span>|</span>
                <a href="#bai-viet" class="hover:text-accent transition">Kiến thức xây dựng</a>
                <span>|</span>
                <a href="#bao-gia" class="hover:text-accent transition font-semibold text-amber-300">Nhận báo giá sỉ & lẻ</a>
            </div>
        </div>
    </div>

    <!-- ==========================================
         2. HEADER CHÍNH (Logo gọn nhỏ, KHÔNG ĐỂ NÚT GỌI NGAY trên header để tránh tràn viền)
    =========================================== -->
    <header class="bg-white sticky top-0 z-40 shadow-sm border-b border-slate-200">
        <div class="container-1500 py-2.5 flex items-center justify-between gap-3">
            
            <!-- Nút mở Menu trên Điện thoại -->
            <button id="mobileMenuBtn" type="button" aria-label="Mở danh mục" class="lg:hidden p-2 rounded-lg text-primary hover:bg-slate-100 focus:outline-none">
                <i class="fa-solid fa-bars text-xl"></i>
            </button>

            <!-- LOGO THIẾT KẾ MỚI CHUYÊN NGHIỆP - CHỈNH GỌN NHỎ LẠI -->
            <a href="#" class="flex items-center gap-2.5 shrink-0 group">
                <svg class="w-9 h-9 sm:w-10 sm:h-10 shrink-0 rounded-lg shadow-sm" viewBox="0 0 100 100" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <rect width="100" height="100" rx="18" fill="#0B3B60"/>
                    <!-- Khối gạch kiến trúc & chữ ĐN lồng ghép tinh tế -->
                    <path d="M18 24H52C66.3594 24 78 35.6406 78 50C78 64.3594 66.3594 76 52 76H18V24Z" stroke="#D97706" stroke-width="8"/>
                    <path d="M12 50H42" stroke="#F59E0B" stroke-width="7" stroke-linecap="round"/>
                    <path d="M44 36L64 64M64 36V64" stroke="#FFFFFF" stroke-width="7" stroke-linecap="round" stroke-linejoin="round"/>
                    <rect x="74" y="18" width="10" height="10" rx="2" fill="#D97706"/>
                </svg>
                <div class="flex flex-col">
                    <span class="text-primary font-extrabold text-sm sm:text-base md:text-lg leading-tight tracking-tight">ĐINH NGUYỄN</span>
                    <span class="text-[10px] sm:text-[11px] font-semibold text-accent uppercase tracking-wider leading-tight">dinhnguyen.com</span>
                </div>
            </a>

            <!-- Thanh tìm kiếm sản phẩm chuẩn Flatsome -->
            <div class="hidden md:flex flex-1 max-w-xl mx-4">
                <form onsubmit="event.preventDefault(); filterBySearch();" class="w-full flex">
                    <select id="searchCatSelect" class="bg-slate-100 border border-r-0 border-slate-300 text-slate-700 text-xs font-medium px-3 rounded-l-lg focus:outline-none">
                        <option value="all">Tất cả danh mục</option>
                        <option value="gach-lat-nen">Gạch lát nền</option>
                        <option value="gach-op-tuong">Gạch ốp tường</option>
                        <option value="gach-gia-go">Gạch giả gỗ</option>
                        <option value="gach-san-vuon">Gạch sân vườn</option>
                        <option value="thiet-bi-ve-sinh">Thiết bị vệ sinh</option>
                        <option value="san-pham-khac">Sản phẩm khác</option>
                    </select>
                    <input id="searchInput" type="text" placeholder="Tìm gạch ốp lát 60x60, 80x80, thiết bị vệ sinh, bồn cầu..." class="w-full border border-slate-300 px-3.5 py-2 text-xs sm:text-sm focus:outline-none focus:border-primary">
                    <button type="submit" class="bg-primary hover:bg-primary-light text-white px-4 rounded-r-lg text-sm transition flex items-center justify-center">
                        <i class="fa-solid fa-magnifying-glass"></i>
                    </button>
                </form>
            </div>

            <!-- Khu vực thông tin Showroom gọn nhẹ (Không để nút Gọi ngay tránh tràn viền) -->
            <div class="flex items-center gap-2 sm:gap-3 shrink-0">
                <a href="#ban-do" class="hidden xl:flex items-center gap-2 text-xs text-slate-600 hover:text-primary bg-slate-50 px-3 py-1.5 rounded-lg border border-slate-200">
                    <i class="fa-solid fa-map-location-dot text-accent text-sm"></i>
                    <div class="leading-tight">
                        <div class="font-bold text-primary">Showroom Đà Nẵng</div>
                        <div class="text-[11px]">442 Nguyễn Hữu Thọ</div>
                    </div>
                </a>
                <a href="#bao-gia" class="bg-accent hover:bg-accent-hover text-white text-xs font-bold px-3 py-2 rounded-lg transition shadow-sm whitespace-nowrap">
                    <i class="fa-solid fa-file-invoice mr-1"></i>Báo Giá
                </a>
            </div>
        </div>

        <!-- Thanh tìm kiếm trên Mobile -->
        <div class="md:hidden container-1500 pb-2">
            <form onsubmit="event.preventDefault(); filterBySearchMobile();" class="flex w-full">
                <input id="searchInputMobile" type="text" placeholder="Tìm tên gạch, kích thước, thiết bị vệ sinh..." class="w-full border border-slate-300 rounded-l-lg px-3 py-1.5 text-xs focus:outline-none focus:border-primary">
                <button type="submit" class="bg-primary text-white px-3.5 rounded-r-lg text-xs">
                    <i class="fa-solid fa-magnifying-glass"></i>
                </button>
            </form>
        </div>

        <!-- ==========================================
             THANH MENU DANH MỤC TRÊN MÁY TÍNH
             Yêu cầu: Tên danh mục trên máy tính viết liền trên 1 hàng chữ nhỏ lại để nằm trên cùng 1 hàng hoặc xuống hàng 2, KHÔNG ĐƯỢC XUỐNG DÒNG TÊN DANH MỤC
        =========================================== -->
        <nav class="hidden lg:block bg-primary text-white border-t border-primary-light">
            <div class="container-1500">
                <ul class="flex flex-wrap items-center justify-center xl:justify-between py-1.5 gap-x-1 gap-y-1">
                    <li>
                        <a href="#danh-muc-trang-chu" onclick="filterCategory('all')" class="cat-nowrap inline-flex items-center gap-1.5 px-2.5 py-1.5 rounded text-[12px] font-bold bg-accent text-white hover:bg-accent-hover transition">
                            <i class="fa-solid fa-border-all"></i> TẤT CẢ DANH MỤC
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham-chinh" onclick="filterCategory('gach-lat-nen')" class="cat-nowrap inline-block px-2.5 py-1.5 rounded text-[12px] font-semibold hover:bg-white/10 transition">
                            GẠCH LÁT NỀN
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham-chinh" onclick="filterCategory('gach-op-tuong')" class="cat-nowrap inline-block px-2.5 py-1.5 rounded text-[12px] font-semibold hover:bg-white/10 transition">
                            GẠCH ỐP TƯỜNG
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham-chinh" onclick="filterCategory('gach-gia-go')" class="cat-nowrap inline-block px-2.5 py-1.5 rounded text-[12px] font-semibold hover:bg-white/10 transition">
                            GẠCH GIẢ GỖ
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham-chinh" onclick="filterCategory('gach-san-vuon')" class="cat-nowrap inline-block px-2.5 py-1.5 rounded text-[12px] font-semibold hover:bg-white/10 transition">
                            GẠCH LÁT SÂN VƯỜN
                        </a>
                    </li>
                    <li>
                        <a href="#thiet-bi-ve-sinh-sec" onclick="filterCategory('thiet-bi-ve-sinh')" class="cat-nowrap inline-block px-2.5 py-1.5 rounded text-[12px] font-semibold hover:bg-white/10 transition">
                            THIẾT BỊ VỆ SINH
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham-khac-sec" onclick="filterCategory('san-pham-khac')" class="cat-nowrap inline-block px-2.5 py-1.5 rounded text-[12px] font-semibold hover:bg-white/10 transition">
                            TẤM TƯỜNG & TRANH ĐÁ
                        </a>
                    </li>
                    <li>
                        <a href="#du-an" class="cat-nowrap inline-block px-2.5 py-1.5 rounded text-[12px] font-semibold hover:bg-white/10 transition">
                            DỰ ÁN ĐÀ NẴNG
                        </a>
                    </li>
                    <li>
                        <a href="#doi-tac" class="cat-nowrap inline-block px-2.5 py-1.5 rounded text-[12px] font-semibold hover:bg-white/10 transition">
                            ĐỐI TÁC
                        </a>
                    </li>
                    <li>
                        <a href="#bai-viet" class="cat-nowrap inline-block px-2.5 py-1.5 rounded text-[12px] font-semibold hover:bg-white/10 transition">
                            TIN TỨC
                        </a>
                    </li>
                    <li>
                        <a href="#ban-do" class="cat-nowrap inline-block px-2.5 py-1.5 rounded text-[12px] font-semibold hover:bg-white/10 transition">
                            LIÊN HỆ
                        </a>
                    </li>
                </ul>
            </div>
        </nav>
    </header>

    <!-- Menu Drawer trên Điện thoại -->
    <div id="mobileMenuOverlay" class="fixed inset-0 bg-black/60 z-50 hidden transition-opacity">
        <div class="bg-white w-72 max-w-[85vw] h-full overflow-y-auto p-4 flex flex-col justify-between">
            <div>
                <div class="flex items-center justify-between pb-3 border-b border-slate-200">
                    <span class="font-extrabold text-primary text-sm uppercase">Danh Mục Sản Phẩm</span>
                    <button id="closeMobileMenu" class="p-1.5 text-slate-500 hover:text-red-600">
                        <i class="fa-solid fa-xmark text-xl"></i>
                    </button>
                </div>
                <ul class="mt-3 space-y-1 text-xs font-semibold text-slate-700">
                    <li><a href="#san-pham-chinh" onclick="closeDrawerAndFilter('gach-lat-nen')" class="flex items-center justify-between p-2.5 rounded hover:bg-slate-100"><span>Gạch Lát Nền Cao Cấp</span><i class="fa-solid fa-angle-right text-slate-400"></i></a></li>
                    <li><a href="#san-pham-chinh" onclick="closeDrawerAndFilter('gach-op-tuong')" class="flex items-center justify-between p-2.5 rounded hover:bg-slate-100"><span>Gạch Ốp Tường & Trang Trí</span><i class="fa-solid fa-angle-right text-slate-400"></i></a></li>
                    <li><a href="#san-pham-chinh" onclick="closeDrawerAndFilter('gach-gia-go')" class="flex items-center justify-between p-2.5 rounded hover:bg-slate-100"><span>Sàn Đá & Gạch Giả Gỗ</span><i class="fa-solid fa-angle-right text-slate-400"></i></a></li>
                    <li><a href="#san-pham-chinh" onclick="closeDrawerAndFilter('gach-san-vuon')" class="flex items-center justify-between p-2.5 rounded hover:bg-slate-100"><span>Gạch Lát Sân Vườn - Vỉa Hè</span><i class="fa-solid fa-angle-right text-slate-400"></i></a></li>
                    <li><a href="#thiet-bi-ve-sinh-sec" onclick="closeDrawerAndFilter('thiet-bi-ve-sinh')" class="flex items-center justify-between p-2.5 rounded hover:bg-slate-100"><span>Thiết Bị Vệ Sinh Trọn Gói</span><i class="fa-solid fa-angle-right text-slate-400"></i></a></li>
                    <li><a href="#san-pham-khac-sec" onclick="closeDrawerAndFilter('san-pham-khac')" class="flex items-center justify-between p-2.5 rounded hover:bg-slate-100"><span>Tấm Tường Cacbon & Tranh Đá</span><i class="fa-solid fa-angle-right text-slate-400"></i></a></li>
                    <li><a href="#du-an" onclick="toggleMobileMenu(false)" class="flex items-center justify-between p-2.5 rounded hover:bg-slate-100"><span>Dự Án Tại Đà Nẵng</span><i class="fa-solid fa-angle-right text-slate-400"></i></a></li>
                    <li><a href="#doi-tac" onclick="toggleMobileMenu(false)" class="flex items-center justify-between p-2.5 rounded hover:bg-slate-100"><span>Đối Tác Chiến Lược</span><i class="fa-solid fa-angle-right text-slate-400"></i></a></li>
                    <li><a href="#bai-viet" onclick="toggleMobileMenu(false)" class="flex items-center justify-between p-2.5 rounded hover:bg-slate-100"><span>Tin Tức & Kinh Nghiệm</span><i class="fa-solid fa-angle-right text-slate-400"></i></a></li>
                    <li><a href="#bao-gia" onclick="toggleMobileMenu(false)" class="flex items-center justify-between p-2.5 rounded bg-amber-50 text-accent font-bold"><span>Yêu Cầu Báo Giá Nhanh</span><i class="fa-solid fa-paper-plane"></i></a></li>
                </ul>
            </div>
            <div class="pt-4 border-t border-slate-200 text-xs text-slate-600 space-y-1.5">
                <div class="font-bold text-primary">CÔNG TY TNHH TMDV ĐINH NGUYỄN</div>
                <div><i class="fa-solid fa-location-dot text-accent mr-1.5"></i>442 Nguyễn Hữu Thọ, Cẩm Lệ, Đà Nẵng</div>
                <div><i class="fa-solid fa-phone text-accent mr-1.5"></i>0906.477.891</div>
                <div><i class="fa-solid fa-globe text-accent mr-1.5"></i>dinhnguyen.com</div>
            </div>
        </div>
    </div>

    <!-- ==========================================
         3. SLIDER 2 ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU
         Yêu cầu:
         - Thiết kế 2 ảnh banner tự trượt kích thước bằng nhau
         - Thiết kế mới ảnh banner điện thoại KHÁC VỚI ảnh banner trên máy tính để tối ưu chữ bên trong ảnh
         - Chữ không được tràn viền, chỉnh chữ nhỏ lại nằm hết trong ảnh banner
    =========================================== -->
    <section class="w-full bg-slate-100 py-3">
        <div class="container-1500">
            <div class="relative w-full overflow-hidden rounded-xl shadow-md bg-primary">
                
                <!-- SLIDE 1 -->
                <div class="banner-slide w-full transition-opacity duration-700 opacity-100 block" data-slide="0">
                    <!-- Bố cục Banner dành riêng cho MÁY TÍNH (Tỷ lệ rộng đồng nhất 1500x430) -->
                    <div class="hidden md:grid grid-cols-12 items-center w-full h-[360px] lg:h-[420px] bg-gradient-to-r from-[#072842] via-[#0B3B60] to-[#134e7a] relative overflow-hidden px-8 lg:px-14">
                        <div class="col-span-7 z-10 pr-6 space-y-2.5">
                            <div class="inline-flex items-center gap-2 bg-amber-500/20 border border-amber-400/40 text-amber-300 text-xs font-bold px-3 py-1 rounded-full">
                                <span>SHOWROOM VẬT LIỆU XÂY DỰNG ĐÀ NẴNG</span>
                            </div>
                            <h1 class="text-white font-extrabold text-xl lg:text-3xl leading-snug">
                                CÔNG TY TNHH TMDV ĐINH NGUYỄN
                            </h1>
                            <p class="text-amber-400 font-bold text-sm lg:text-base">
                                TỔNG KHO GẠCH ỐP LÁT & THIẾT BỊ VỆ SINH TRỌN GÓI
                            </p>
                            <p class="text-slate-200 text-xs lg:text-sm max-w-xl leading-relaxed">
                                Chuyên phân phối gạch khổ lớn 60x120, 80x80, 90x180, gạch giả gỗ, gạch sân vườn và thiết bị vệ sinh cao cấp chính hãng. Giao hàng tận chân công trình tại Đà Nẵng & miền Trung.
                            </p>
                            <div class="pt-1 flex flex-wrap items-center gap-3 text-xs text-white font-semibold">
                                <span class="bg-white/10 px-3 py-1.5 rounded-lg border border-white/15">
                                    <i class="fa-solid fa-location-dot text-amber-400 mr-1"></i> 442 Nguyễn Hữu Thọ, P. Cẩm Lệ, TP Đà Nẵng
                                </span>
                                <span class="bg-accent px-3.5 py-1.5 rounded-lg text-white font-bold">
                                    <i class="fa-solid fa-phone-volume mr-1"></i> 0906.477.891
                                </span>
                            </div>
                        </div>
                        <div class="col-span-5 h-full py-5 z-10 flex items-center justify-end gap-3">
                            <div class="w-1/2 h-[290px] lg:h-[340px] rounded-xl overflow-hidden border-2 border-amber-400/50 shadow-lg bg-slate-800">
                                <img src="https://drive.google.com/thumbnail?id=1-Ec1aH7TR_ienNo4F206IqN5J12hG5Si&sz=w1000" 
                                     onerror="this.src='https://placehold.co/600x800/0B3B60/FFFFFF?text=Showroom+Dinh+Nguyen'" 
                                     alt="Showroom Công ty Đinh Nguyễn" class="w-full h-full object-cover">
                            </div>
                            <div class="w-1/2 h-[290px] lg:h-[340px] rounded-xl overflow-hidden border-2 border-white/30 shadow-lg bg-slate-800">
                                <img src="https://drive.google.com/thumbnail?id=1lenA2gP-I7n9KAr-CH1jT8QQ2B8_qfdn&sz=w1000" 
                                     onerror="this.src='https://placehold.co/600x800/145385/FFFFFF?text=Gach+Op+Lat+Cao+Cap'" 
                                     alt="Gạch ốp lát thực tế Đinh Nguyễn" class="w-full h-full object-cover">
                            </div>
                        </div>
                    </div>

                    <!-- Bố cục Banner thiết kế riêng cho ĐIỆN THOẠI (Chữ nhỏ gọn, nằm trọn bên trong, không tràn viền) -->
                    <div class="md:hidden w-full h-[270px] sm:h-[290px] bg-gradient-to-b from-[#072842] to-[#0B3B60] p-3.5 flex flex-col justify-between relative overflow-hidden">
                        <div class="flex items-center justify-between gap-2">
                            <span class="bg-amber-500/20 border border-amber-400/40 text-amber-300 text-[10px] font-bold px-2 py-0.5 rounded">
                                WEBSITE: DINHNGUYEN.COM
                            </span>
                            <span class="bg-accent text-white text-[10px] font-bold px-2 py-0.5 rounded">
                                0906.477.891
                            </span>
                        </div>
                        <div class="grid grid-cols-12 gap-2.5 items-center my-auto py-1">
                            <div class="col-span-7 space-y-1">
                                <h2 class="text-white font-extrabold text-[13px] sm:text-sm leading-tight uppercase">
                                    CÔNG TY TNHH TMDV ĐINH NGUYỄN
                                </h2>
                                <p class="text-amber-300 font-bold text-[11px] leading-tight">
                                    Gạch Ốp Lát & Thiết Bị Vệ Sinh Trọn Gói
                                </p>
                                <p class="text-slate-200 text-[10px] leading-snug">
                                    Cung ứng gạch vân đá, gạch giả gỗ, thiết bị phòng tắm chính hãng giá kho tại Đà Nẵng.
                                </p>
                            </div>
                            <div class="col-span-5 h-[145px] rounded-lg overflow-hidden border border-amber-400/50 bg-slate-800">
                                <img src="https://drive.google.com/thumbnail?id=1-Ec1aH7TR_ienNo4F206IqN5J12hG5Si&sz=w600" 
                                     onerror="this.src='https://placehold.co/400x400/0B3B60/FFFFFF?text=Dinh+Nguyen'" 
                                     alt="Showroom Đinh Nguyễn Mobile" class="w-full h-full object-cover">
                            </div>
                        </div>
                        <div class="bg-black/25 rounded px-2.5 py-1 text-[10px] text-slate-100 truncate">
                            <i class="fa-solid fa-location-dot text-amber-400 mr-1"></i>Đ/C: 442 Nguyễn Hữu Thọ, P. Cẩm Lệ, TP Đà Nẵng
                        </div>
                    </div>
                </div>

                <!-- SLIDE 2 (Kích thước bằng đúng Slide 1 cả trên PC và Mobile) -->
                <div class="banner-slide w-full transition-opacity duration-700 opacity-0 hidden" data-slide="1">
                    <!-- Bố cục Banner 2 dành riêng cho MÁY TÍNH (Kích thước 360px/420px bằng Slide 1) -->
                    <div class="hidden md:grid grid-cols-12 items-center w-full h-[360px] lg:h-[420px] bg-gradient-to-r from-[#0f2942] via-[#17426b] to-[#0B3B60] relative overflow-hidden px-8 lg:px-14">
                        <div class="col-span-7 z-10 pr-6 space-y-2.5">
                            <div class="inline-flex items-center gap-2 bg-amber-500/20 border border-amber-400/40 text-amber-300 text-xs font-bold px-3 py-1 rounded-full">
                                <span>ĐỐI TÁC TIN CẬY CỦA MỌI CÔNG TRÌNH</span>
                            </div>
                            <h2 class="text-white font-extrabold text-xl lg:text-3xl leading-snug">
                                GIẢI PHÁP VẬT LIỆU HOÀN THIỆN & DỰ ÁN ĐÀ NẴNG
                            </h2>
                            <p class="text-amber-400 font-bold text-sm lg:text-base">
                                CHIẾT KHẤU CAO CHO NHÀ THẦU, KIẾN TRÚC SƯ & NHÀ PHỐ
                            </p>
                            <p class="text-slate-200 text-xs lg:text-sm max-w-xl leading-relaxed">
                                Đồng hành cùng hàng trăm công trình biệtự, khách sạn, nhà phố tại Đà Nẵng. Cam kết sản phẩm loại 1, bảo hành chính hãng, hỗ trợ vận chuyển nhanh chóng.
                            </p>
                            <div class="pt-1 flex flex-wrap items-center gap-3 text-xs text-white font-semibold">
                                <span class="bg-white/10 px-3 py-1.5 rounded-lg border border-white/15">
                                    <i class="fa-solid fa-globe text-amber-400 mr-1"></i> Website: dinhnguyen.com
                                </span>
                                <span class="bg-accent px-3.5 py-1.5 rounded-lg text-white font-bold">
                                    <i class="fa-solid fa-headset mr-1"></i> Tư vấn: 0906.477.891
                                </span>
                            </div>
                        </div>
                        <div class="col-span-5 h-full py-5 z-10 flex items-center justify-end gap-3">
                            <div class="w-1/2 h-[290px] lg:h-[340px] rounded-xl overflow-hidden border-2 border-amber-400/50 shadow-lg bg-slate-800">
                                <img src="https://drive.google.com/thumbnail?id=1GrXImuNIYzbpGEISJh91gzZqpnS0GXfV&sz=w1000" 
                                     onerror="this.src='https://placehold.co/600x800/0B3B60/FFFFFF?text=Du+An+Da+Nang'" 
                                     alt="Dự án thực tế Đà Nẵng" class="w-full h-full object-cover">
                            </div>
                            <div class="w-1/2 h-[290px] lg:h-[340px] rounded-xl overflow-hidden border-2 border-white/30 shadow-lg bg-slate-800">
                                <img src="https://drive.google.com/thumbnail?id=1xcAGKmtzlw4DY5zwh5Ijj0P7R8IbzmAl&sz=w1000" 
                                     onerror="this.src='https://placehold.co/600x800/145385/FFFFFF?text=Kho+Hang+Dinh+Nguyen'" 
                                     alt="Thực tế công ty Đinh Nguyễn" class="w-full h-full object-cover">
                            </div>
                        </div>
                    </div>

                    <!-- Bố cục Banner 2 thiết kế riêng cho ĐIỆN THOẠI (Kích thước 270px/290px bằng Slide 1, chữ nhỏ gọn) -->
                    <div class="md:hidden w-full h-[270px] sm:h-[290px] bg-gradient-to-b from-[#103454] to-[#072842] p-3.5 flex flex-col justify-between relative overflow-hidden">
                        <div class="flex items-center justify-between gap-2">
                            <span class="bg-amber-500/20 border border-amber-400/40 text-amber-300 text-[10px] font-bold px-2 py-0.5 rounded">
                                DỰ ÁN & CÔNG TRÌNH ĐÀ NẴNG
                            </span>
                            <span class="bg-accent text-white text-[10px] font-bold px-2 py-0.5 rounded">
                                ƯU ĐÃI TỐT NHẤT
                            </span>
                        </div>
                        <div class="grid grid-cols-12 gap-2.5 items-center my-auto py-1">
                            <div class="col-span-7 space-y-1">
                                <h2 class="text-white font-extrabold text-[13px] sm:text-sm leading-tight uppercase">
                                    PHÂN PHỐI SỈ & LẺ VẬT LIỆU XÂY DỰNG
                                </h2>
                                <p class="text-amber-300 font-bold text-[11px] leading-tight">
                                    Chiết Khấu Cao Cho Công Trình
                                </p>
                                <p class="text-slate-200 text-[10px] leading-snug">
                                    Showroom trưng bày đa dạng mẫu gạch khổ lớn, thiết bị vệ sinh liền khối, sen cây cao cấp.
                                </p>
                            </div>
                            <div class="col-span-5 h-[145px] rounded-lg overflow-hidden border border-amber-400/50 bg-slate-800">
                                <img src="https://drive.google.com/thumbnail?id=1GrXImuNIYzbpGEISJh91gzZqpnS0GXfV&sz=w600" 
                                     onerror="this.src='https://placehold.co/400x400/0B3B60/FFFFFF?text=Cong+Trinh'" 
                                     alt="Dự án Đà Nẵng Mobile" class="w-full h-full object-cover">
                            </div>
                        </div>
                        <div class="bg-black/25 rounded px-2.5 py-1 text-[10px] text-slate-100 truncate">
                            <i class="fa-solid fa-phone text-amber-400 mr-1"></i>Hotline: 0906.477.891 - 442 Nguyễn Hữu Thọ, Đà Nẵng
                        </div>
                    </div>
                </div>

                <!-- Nút điều hướng Banner -->
                <button onclick="changeSlide(-1)" aria-label="Banner trước" class="absolute left-2 top-1/2 -translate-y-1/2 w-8 h-8 rounded-full bg-black/40 hover:bg-black/70 text-white flex items-center justify-center transition z-20">
                    <i class="fa-solid fa-chevron-left text-xs"></i>
                </button>
                <button onclick="changeSlide(1)" aria-label="Banner tiếp" class="absolute right-2 top-1/2 -translate-y-1/2 w-8 h-8 rounded-full bg-black/40 hover:bg-black/70 text-white flex items-center justify-center transition z-20">
                    <i class="fa-solid fa-chevron-right text-xs"></i>
                </button>

                <!-- Chấm tròn chỉ báo Slide -->
                <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 flex items-center gap-2 z-20">
                    <button onclick="goToSlide(0)" id="dot-0" class="w-2.5 h-2.5 rounded-full bg-amber-400 transition"></button>
                    <button onclick="goToSlide(1)" id="dot-1" class="w-2.5 h-2.5 rounded-full bg-white/50 transition"></button>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         4. DANH MỤC SẢN PHẨM TRANG CHỦ (Lấy danh mục từ web mẫu quanghungceramic.vn)
         Yêu cầu:
         - Chữ danh mục ở trang chủ nhỏ gọn
         - Tên danh mục không được xuống dòng
         - Thiết kế đẹp trên cả máy tính và điện thoại, dễ dựng lại bằng UX Builder
    =========================================== -->
    <section id="danh-muc-trang-chu" class="py-5 bg-white border-b border-slate-200">
        <div class="container-1500">
            <div class="section-title-container">
                <div class="section-title-normal">
                    <h2 class="section-title-main">DANH MỤC SẢN PHẨM</h2>
                    <span class="text-xs text-slate-500 hidden sm:inline">Chọn danh mục để lọc nhanh sản phẩm</span>
                </div>
            </div>

            <!-- Grid Danh mục: 2 cột trên mobile nhỏ, 4 cột trên mobile lớn/tablet, 8 cột trên máy tính -->
            <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-2.5">
                
                <button onclick="filterCategory('gach-lat-nen')" class="group bg-slate-50 hover:bg-primary border border-slate-200 hover:border-primary rounded-xl p-2.5 flex flex-col items-center text-center transition shadow-sm">
                    <div class="w-12 h-12 rounded-full overflow-hidden mb-2 border border-slate-200 bg-white shrink-0">
                        <img src="https://drive.google.com/thumbnail?id=1lenA2gP-I7n9KAr-CH1jT8QQ2B8_qfdn&sz=w300" onerror="this.src='https://placehold.co/150x150/0B3B60/FFFFFF?text=Gach+Lat'" alt="Gạch lát nền" class="w-full h-full object-cover group-hover:scale-105 transition">
                    </div>
                    <span class="cat-nowrap text-[11px] sm:text-xs font-bold text-primary group-hover:text-white">Gạch Lát Nền</span>
                </button>

                <button onclick="filterCategory('gach-op-tuong')" class="group bg-slate-50 hover:bg-primary border border-slate-200 hover:border-primary rounded-xl p-2.5 flex flex-col items-center text-center transition shadow-sm">
                    <div class="w-12 h-12 rounded-full overflow-hidden mb-2 border border-slate-200 bg-white shrink-0">
                        <img src="https://drive.google.com/thumbnail?id=1hhjvjqA9Hx3mVteF4fPdUFjel2NNO7sI&sz=w300" onerror="this.src='https://placehold.co/150x150/0B3B60/FFFFFF?text=Gach+Op'" alt="Gạch ốp tường" class="w-full h-full object-cover group-hover:scale-105 transition">
                    </div>
                    <span class="cat-nowrap text-[11px] sm:text-xs font-bold text-primary group-hover:text-white">Gạch Ốp Tường</span>
                </button>

                <button onclick="filterCategory('gach-gia-go')" class="group bg-slate-50 hover:bg-primary border border-slate-200 hover:border-primary rounded-xl p-2.5 flex flex-col items-center text-center transition shadow-sm">
                    <div class="w-12 h-12 rounded-full overflow-hidden mb-2 border border-slate-200 bg-white shrink-0">
                        <img src="https://drive.google.com/thumbnail?id=1eF5xUKVVGe3tqeSWjEPKiS8nHm0EyS9X&sz=w300" onerror="this.src='https://placehold.co/150x150/0B3B60/FFFFFF?text=Gia+Go'" alt="Gạch giả gỗ" class="w-full h-full object-cover group-hover:scale-105 transition">
                    </div>
                    <span class="cat-nowrap text-[11px] sm:text-xs font-bold text-primary group-hover:text-white">Gạch Giả Gỗ</span>
                </button>

                <button onclick="filterCategory('gach-san-vuon')" class="group bg-slate-50 hover:bg-primary border border-slate-200 hover:border-primary rounded-xl p-2.5 flex flex-col items-center text-center transition shadow-sm">
                    <div class="w-12 h-12 rounded-full overflow-hidden mb-2 border border-slate-200 bg-white shrink-0">
                        <img src="https://drive.google.com/thumbnail?id=1z7LP9NRTaYtz6vCCDIDhlt6quSLD47da&sz=w300" onerror="this.src='https://placehold.co/150x150/0B3B60/FFFFFF?text=San+Vuon'" alt="Gạch sân vườn" class="w-full h-full object-cover group-hover:scale-105 transition">
                    </div>
                    <span class="cat-nowrap text-[11px] sm:text-xs font-bold text-primary group-hover:text-white">Gạch Sân Vườn</span>
                </button>

                <button onclick="filterCategory('thiet-bi-ve-sinh')" class="group bg-slate-50 hover:bg-primary border border-slate-200 hover:border-primary rounded-xl p-2.5 flex flex-col items-center text-center transition shadow-sm">
                    <div class="w-12 h-12 rounded-full overflow-hidden mb-2 border border-slate-200 bg-white shrink-0">
                        <img src="https://drive.google.com/thumbnail?id=13Cc-bi4LLGhWvuRuIocH8mMBqiW0lsMt&sz=w300" onerror="this.src='https://placehold.co/150x150/0B3B60/FFFFFF?text=TB+Ve+Sinh'" alt="Thiết bị vệ sinh" class="w-full h-full object-cover group-hover:scale-105 transition">
                    </div>
                    <span class="cat-nowrap text-[11px] sm:text-xs font-bold text-primary group-hover:text-white">Thiết Bị Vệ Sinh</span>
                </button>

                <button onclick="filterCategory('san-pham-khac')" class="group bg-slate-50 hover:bg-primary border border-slate-200 hover:border-primary rounded-xl p-2.5 flex flex-col items-center text-center transition shadow-sm">
                    <div class="w-12 h-12 rounded-full overflow-hidden mb-2 border border-slate-200 bg-white shrink-0">
                        <img src="https://drive.google.com/thumbnail?id=1gCksAETQ49L5NK5__HN5Wo3tZSHyaH-0&sz=w300" onerror="this.src='https://placehold.co/150x150/0B3B60/FFFFFF?text=Tam+Tuong'" alt="Tấm tường cacbon" class="w-full h-full object-cover group-hover:scale-105 transition">
                    </div>
                    <span class="cat-nowrap text-[11px] sm:text-xs font-bold text-primary group-hover:text-white">Tấm Tường Cacbon</span>
                </button>

                <button onclick="filterCategory('san-pham-khac')" class="group bg-slate-50 hover:bg-primary border border-slate-200 hover:border-primary rounded-xl p-2.5 flex flex-col items-center text-center transition shadow-sm">
                    <div class="w-12 h-12 rounded-full overflow-hidden mb-2 border border-slate-200 bg-white shrink-0">
                        <img src="https://drive.google.com/thumbnail?id=1E9dxZnyKICGnP_EgOB0VXjKl4MENLhfu&sz=w300" onerror="this.src='https://placehold.co/150x150/0B3B60/FFFFFF?text=Gach+Trang+Tri'" alt="Gạch trang trí" class="w-full h-full object-cover group-hover:scale-105 transition">
                    </div>
                    <span class="cat-nowrap text-[11px] sm:text-xs font-bold text-primary group-hover:text-white">Gạch Trang Trí</span>
                </button>

                <button onclick="filterCategory('san-pham-khac')" class="group bg-slate-50 hover:bg-primary border border-slate-200 hover:border-primary rounded-xl p-2.5 flex flex-col items-center text-center transition shadow-sm">
                    <div class="w-12 h-12 rounded-full overflow-hidden mb-2 border border-slate-200 bg-white shrink-0">
                        <img src="https://drive.google.com/thumbnail?id=15IMLWbmlxpoBX_D8-oJ4QqljDt7uGsM9&sz=w300" onerror="this.src='https://placehold.co/150x150/0B3B60/FFFFFF?text=Tranh+Da'" alt="Tranh đá" class="w-full h-full object-cover group-hover:scale-105 transition">
                    </div>
                    <span class="cat-nowrap text-[11px] sm:text-xs font-bold text-primary group-hover:text-white">Tranh Đá & Bếp Từ</span>
                </button>

            </div>

            <!-- Hàng lọc nhanh theo kích thước gạch chuẩn mẫu quanghungceramic.vn -->
            <div class="mt-3 pt-3 border-t border-slate-100 flex flex-wrap items-center gap-1.5">
                <span class="text-[11px] font-bold text-slate-500 mr-1">Kích thước phổ biến:</span>
                <button onclick="filterCategory('all')" class="cat-nowrap text-[11px] font-semibold px-2.5 py-1 rounded bg-primary text-white">Tất cả</button>
                <button onclick="filterCategory('gach-lat-nen')" class="cat-nowrap text-[11px] font-medium px-2.5 py-1 rounded bg-slate-100 hover:bg-slate-200 text-slate-700">Gạch nhập khẩu</button>
                <button onclick="filterCategory('gach-op-tuong')" class="cat-nowrap text-[11px] font-medium px-2.5 py-1 rounded bg-slate-100 hover:bg-slate-200 text-slate-700">Kích thước 30x60</button>
                <button onclick="filterCategory('gach-lat-nen')" class="cat-nowrap text-[11px] font-medium px-2.5 py-1 rounded bg-slate-100 hover:bg-slate-200 text-slate-700">Kích thước 60x60</button>
                <button onclick="filterCategory('gach-lat-nen')" class="cat-nowrap text-[11px] font-medium px-2.5 py-1 rounded bg-slate-100 hover:bg-slate-200 text-slate-700">Kích thước 60x120</button>
                <button onclick="filterCategory('gach-lat-nen')" class="cat-nowrap text-[11px] font-medium px-2.5 py-1 rounded bg-slate-100 hover:bg-slate-200 text-slate-700">Kích thước 80x80</button>
                <button onclick="filterCategory('gach-lat-nen')" class="cat-nowrap text-[11px] font-medium px-2.5 py-1 rounded bg-slate-100 hover:bg-slate-200 text-slate-700">Kích thước 90x180</button>
                <button onclick="filterCategory('gach-lat-nen')" class="cat-nowrap text-[11px] font-medium px-2.5 py-1 rounded bg-slate-100 hover:bg-slate-200 text-slate-700">Kích thước 100x100</button>
            </div>
        </div>
    </section>

    <!-- ==========================================
         5. KHU VỰC SẢN PHẨM THỰC TẾ (Sử dụng toàn bộ 9 file ảnh sản phẩm Google Drive)
         Yêu cầu:
         - Chia thành 2 cột trên giao diện điện thoại (grid-cols-2)
         - Tên sản phẩm không bị tràn ra ngoài hoặc thiếu chữ
         - Có giá giảm giá và % giảm giá giống Flatsome ở góc trên bên trái
         - Không để các nhãn dán rườm rà khác ở trang chủ
    =========================================== -->
    <section id="san-pham-chinh" class="py-7">
        <div class="container-1500">
            <div class="section-title-container">
                <div class="section-title-normal">
                    <h2 id="currentCategoryTitle" class="section-title-main">GẠCH ỐP LÁT & VẬT LIỆU HOÀN THIỆN</h2>
                    <button onclick="filterCategory('all')" class="text-xs font-bold text-primary hover:text-accent flex items-center gap-1 shrink-0">
                        <span>Xem tất cả</span>
                        <i class="fa-solid fa-angle-right"></i>
                    </button>
                </div>
            </div>

            <!-- Lưới sản phẩm: 2 cột trên điện thoại (grid-cols-2), 3 cột trên tablet, 4-5 cột trên PC -->
            <div id="productGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-3 sm:gap-4">
                
                <!-- Sản phẩm thực tế 1 (Drive ID: 1lenA2gP-I7n9KAr-CH1jT8QQ2B8_qfdn) -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between" data-cat="gach-lat-nen">
                    <div>
                        <div class="relative aspect-square bg-slate-100 overflow-hidden">
                            <div class="badge-container">
                                <span class="onsale-badge">-18%</span>
                            </div>
                            <img src="https://drive.google.com/thumbnail?id=1lenA2gP-I7n9KAr-CH1jT8QQ2B8_qfdn&sz=w800" 
                                 onerror="this.src='https://placehold.co/500x500/e2e8f0/0B3B60?text=Gach+Van+Da+80x80'"
                                 alt="Gạch Lát Nền Vân Đá Marble 80x80 ĐN-8801" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 sm:p-3">
                            <div class="text-[10px] text-slate-400 uppercase font-semibold mb-0.5">Gạch lát nền</div>
                            <h3 class="product-title text-xs sm:text-sm font-bold text-slate-800 hover:text-primary">
                                Gạch Lát Nền Vân Đá Marble Bóng Kiếng 80x80 ĐN-8801
                            </h3>
                            <div class="mt-2 flex flex-wrap items-baseline gap-1.5">
                                <span class="text-[11px] text-slate-400 line-through">390,000₫</span>
                                <span class="text-xs sm:text-sm font-extrabold text-red-600">320,000₫/m²</span>
                            </div>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3 sm:pb-3">
                        <a href="#bao-gia" onclick="selectProductForQuote('Gạch Lát Nền Vân Đá Marble Bóng Kiếng 80x80 ĐN-8801')" class="block w-full text-center bg-slate-100 hover:bg-primary text-primary hover:text-white text-xs font-bold py-1.5 rounded-lg transition">
                            Nhận báo giá
                        </a>
                    </div>
                </div>

                <!-- Sản phẩm thực tế 2 (Drive ID: 1hhjvjqA9Hx3mVteF4fPdUFjel2NNO7sI) -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between" data-cat="gach-lat-nen">
                    <div>
                        <div class="relative aspect-square bg-slate-100 overflow-hidden">
                            <div class="badge-container">
                                <span class="onsale-badge">-15%</span>
                            </div>
                            <img src="https://drive.google.com/thumbnail?id=1hhjvjqA9Hx3mVteF4fPdUFjel2NNO7sI&sz=w800" 
                                 onerror="this.src='https://placehold.co/500x500/e2e8f0/0B3B60?text=Gach+Kho+Lon+60x120'"
                                 alt="Gạch Ốp Lát Khổ Lớn Nhập Khẩu 60x120 ĐN-61202" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 sm:p-3">
                            <div class="text-[10px] text-slate-400 uppercase font-semibold mb-0.5">Gạch khổ lớn</div>
                            <h3 class="product-title text-xs sm:text-sm font-bold text-slate-800 hover:text-primary">
                                Gạch Ốp Lát Khổ Lớn Vân Đá Tự Nhiên 60x120 ĐN-61202
                            </h3>
                            <div class="mt-2 flex flex-wrap items-baseline gap-1.5">
                                <span class="text-[11px] text-slate-400 line-through">520,000₫</span>
                                <span class="text-xs sm:text-sm font-extrabold text-red-600">442,000₫/m²</span>
                            </div>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3 sm:pb-3">
                        <a href="#bao-gia" onclick="selectProductForQuote('Gạch Ốp Lát Khổ Lớn Vân Đá Tự Nhiên 60x120 ĐN-61202')" class="block w-full text-center bg-slate-100 hover:bg-primary text-primary hover:text-white text-xs font-bold py-1.5 rounded-lg transition">
                            Nhận báo giá
                        </a>
                    </div>
                </div>

                <!-- Sản phẩm thực tế 3 (Drive ID: 1eF5xUKVVGe3tqeSWjEPKiS8nHm0EyS9X) -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between" data-cat="gach-op-tuong">
                    <div>
                        <div class="relative aspect-square bg-slate-100 overflow-hidden">
                            <div class="badge-container">
                                <span class="onsale-badge">-20%</span>
                            </div>
                            <img src="https://drive.google.com/thumbnail?id=1eF5xUKVVGe3tqeSWjEPKiS8nHm0EyS9X&sz=w800" 
                                 onerror="this.src='https://placehold.co/500x500/e2e8f0/0B3B60?text=Gach+Op+Tuong+30x60'"
                                 alt="Gạch Ốp Tường Phòng Tắm Cao Cấp 30x60 ĐN-3605" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 sm:p-3">
                            <div class="text-[10px] text-slate-400 uppercase font-semibold mb-0.5">Gạch ốp tường</div>
                            <h3 class="product-title text-xs sm:text-sm font-bold text-slate-800 hover:text-primary">
                                Gạch Ốp Tường Phòng Tắm & Bếp Men Matt 30x60 ĐN-3605
                            </h3>
                            <div class="mt-2 flex flex-wrap items-baseline gap-1.5">
                                <span class="text-[11px] text-slate-400 line-through">245,000₫</span>
                                <span class="text-xs sm:text-sm font-extrabold text-red-600">196,000₫/m²</span>
                            </div>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3 sm:pb-3">
                        <a href="#bao-gia" onclick="selectProductForQuote('Gạch Ốp Tường Phòng Tắm & Bếp Men Matt 30x60 ĐN-3605')" class="block w-full text-center bg-slate-100 hover:bg-primary text-primary hover:text-white text-xs font-bold py-1.5 rounded-lg transition">
                            Nhận báo giá
                        </a>
                    </div>
                </div>

                <!-- Sản phẩm thực tế 4 (Drive ID: 1z7LP9NRTaYtz6vCCDIDhlt6quSLD47da) -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between" data-cat="gach-gia-go">
                    <div>
                        <div class="relative aspect-square bg-slate-100 overflow-hidden">
                            <div class="badge-container">
                                <span class="onsale-badge">-16%</span>
                            </div>
                            <img src="https://drive.google.com/thumbnail?id=1z7LP9NRTaYtz6vCCDIDhlt6quSLD47da&sz=w800" 
                                 onerror="this.src='https://placehold.co/500x500/e2e8f0/0B3B60?text=Gach+Gia+Go+15x90'"
                                 alt="Gạch Giả Gỗ Thanh Dài Chống Trơn 15x90 ĐN-1590" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 sm:p-3">
                            <div class="text-[10px] text-slate-400 uppercase font-semibold mb-0.5">Gạch giả gỗ</div>
                            <h3 class="product-title text-xs sm:text-sm font-bold text-slate-800 hover:text-primary">
                                Gạch Thẻ Giả Gỗ Tự Nhiên Chống Ẩm 15x90 ĐN-1590
                            </h3>
                            <div class="mt-2 flex flex-wrap items-baseline gap-1.5">
                                <span class="text-[11px] text-slate-400 line-through">310,000₫</span>
                                <span class="text-xs sm:text-sm font-extrabold text-red-600">260,000₫/m²</span>
                            </div>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3 sm:pb-3">
                        <a href="#bao-gia" onclick="selectProductForQuote('Gạch Thẻ Giả Gỗ Tự Nhiên Chống Ẩm 15x90 ĐN-1590')" class="block w-full text-center bg-slate-100 hover:bg-primary text-primary hover:text-white text-xs font-bold py-1.5 rounded-lg transition">
                            Nhận báo giá
                        </a>
                    </div>
                </div>

                <!-- Sản phẩm thực tế 5 (Drive ID: 13Cc-bi4LLGhWvuRuIocH8mMBqiW0lsMt) -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between" data-cat="gach-san-vuon">
                    <div>
                        <div class="relative aspect-square bg-slate-100 overflow-hidden">
                            <div class="badge-container">
                                <span class="onsale-badge">-12%</span>
                            </div>
                            <img src="https://drive.google.com/thumbnail?id=13Cc-bi4LLGhWvuRuIocH8mMBqiW0lsMt&sz=w800" 
                                 onerror="this.src='https://placehold.co/500x500/e2e8f0/0B3B60?text=Gach+San+Vuon+50x50'"
                                 alt="Gạch Lát Sân Vườn Chống Trơn Chịu Lực 50x50 ĐN-5050" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 sm:p-3">
                            <div class="text-[10px] text-slate-400 uppercase font-semibold mb-0.5">Gạch sân vườn</div>
                            <h3 class="product-title text-xs sm:text-sm font-bold text-slate-800 hover:text-primary">
                                Gạch Lát Sân Vườn & Ngoại Thất Chịu Lực 50x50 ĐN-5050
                            </h3>
                            <div class="mt-2 flex flex-wrap items-baseline gap-1.5">
                                <span class="text-[11px] text-slate-400 line-through">215,000₫</span>
                                <span class="text-xs sm:text-sm font-extrabold text-red-600">189,000₫/m²</span>
                            </div>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3 sm:pb-3">
                        <a href="#bao-gia" onclick="selectProductForQuote('Gạch Lát Sân Vườn & Ngoại Thất Chịu Lực 50x50 ĐN-5050')" class="block w-full text-center bg-slate-100 hover:bg-primary text-primary hover:text-white text-xs font-bold py-1.5 rounded-lg transition">
                            Nhận báo giá
                        </a>
                    </div>
                </div>

                <!-- Sản phẩm thực tế 6 (Drive ID: 1gCksAETQ49L5NK5__HN5Wo3tZSHyaH-0) -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between" data-cat="thiet-bi-ve-sinh">
                    <div>
                        <div class="relative aspect-square bg-slate-100 overflow-hidden">
                            <div class="badge-container">
                                <span class="onsale-badge">-25%</span>
                            </div>
                            <img src="https://drive.google.com/thumbnail?id=1gCksAETQ49L5NK5__HN5Wo3tZSHyaH-0&sz=w800" 
                                 onerror="this.src='https://placehold.co/500x500/e2e8f0/0B3B60?text=Bon+Cau+1+Khoi'"
                                 alt="Bồn Cầu 1 Khối Men Tuyết Nano Kháng Khuẩn ĐN-BC836" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 sm:p-3">
                            <div class="text-[10px] text-slate-400 uppercase font-semibold mb-0.5">Thiết bị vệ sinh</div>
                            <h3 class="product-title text-xs sm:text-sm font-bold text-slate-800 hover:text-primary">
                                Bồn Cầu 1 Khối Men Tuyết Nano Xả Xoáy Siêu Êm ĐN-BC836
                            </h3>
                            <div class="mt-2 flex flex-wrap items-baseline gap-1.5">
                                <span class="text-[11px] text-slate-400 line-through">4,800,000₫</span>
                                <span class="text-xs sm:text-sm font-extrabold text-red-600">3,600,000₫</span>
                            </div>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3 sm:pb-3">
                        <a href="#bao-gia" onclick="selectProductForQuote('Bồn Cầu 1 Khối Men Tuyết Nano Xả Xoáy Siêu Êm ĐN-BC836')" class="block w-full text-center bg-slate-100 hover:bg-primary text-primary hover:text-white text-xs font-bold py-1.5 rounded-lg transition">
                            Nhận báo giá
                        </a>
                    </div>
                </div>

                <!-- Sản phẩm thực tế 7 (Drive ID: 1E9dxZnyKICGnP_EgOB0VXjKl4MENLhfu) -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between" data-cat="thiet-bi-ve-sinh">
                    <div>
                        <div class="relative aspect-square bg-slate-100 overflow-hidden">
                            <div class="badge-container">
                                <span class="onsale-badge">-22%</span>
                            </div>
                            <img src="https://drive.google.com/thumbnail?id=1E9dxZnyKICGnP_EgOB0VXjKl4MENLhfu&sz=w800" 
                                 onerror="this.src='https://placehold.co/500x500/e2e8f0/0B3B60?text=Tu+Chau+Lavabo'"
                                 alt="Bộ Tủ Chậu Lavabo Phòng Tắm Hiện Đại Kèm Gương LED ĐN-LV205" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 sm:p-3">
                            <div class="text-[10px] text-slate-400 uppercase font-semibold mb-0.5">Thiết bị vệ sinh</div>
                            <h3 class="product-title text-xs sm:text-sm font-bold text-slate-800 hover:text-primary">
                                Bộ Tủ Chậu Lavabo Chống Nước Kèm Gương LED Cảm Ứng ĐN-LV205
                            </h3>
                            <div class="mt-2 flex flex-wrap items-baseline gap-1.5">
                                <span class="text-[11px] text-slate-400 line-through">5,500,000₫</span>
                                <span class="text-xs sm:text-sm font-extrabold text-red-600">4,290,000₫</span>
                            </div>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3 sm:pb-3">
                        <a href="#bao-gia" onclick="selectProductForQuote('Bộ Tủ Chậu Lavabo Chống Nước Kèm Gương LED Cảm Ứng ĐN-LV205')" class="block w-full text-center bg-slate-100 hover:bg-primary text-primary hover:text-white text-xs font-bold py-1.5 rounded-lg transition">
                            Nhận báo giá
                        </a>
                    </div>
                </div>

                <!-- Sản phẩm thực tế 8 (Drive ID: 15IMLWbmlxpoBX_D8-oJ4QqljDt7uGsM9) -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between" data-cat="thiet-bi-ve-sinh">
                    <div>
                        <div class="relative aspect-square bg-slate-100 overflow-hidden">
                            <div class="badge-container">
                                <span class="onsale-badge">-30%</span>
                            </div>
                            <img src="https://drive.google.com/thumbnail?id=15IMLWbmlxpoBX_D8-oJ4QqljDt7uGsM9&sz=w800" 
                                 onerror="this.src='https://placehold.co/500x500/e2e8f0/0B3B60?text=Sen+Cay+Tam+Nong+Lanh'"
                                 alt="Bộ Sen Cây Tắm Đứng Nóng Lạnh Phím Đàn Cao Cấp ĐN-SC912" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 sm:p-3">
                            <div class="text-[10px] text-slate-400 uppercase font-semibold mb-0.5">Thiết bị vệ sinh</div>
                            <h3 class="product-title text-xs sm:text-sm font-bold text-slate-800 hover:text-primary">
                                Sen Cây Tắm Đứng Nóng Lạnh Phím Đàn Hiển Thị Nhiệt Độ ĐN-SC912
                            </h3>
                            <div class="mt-2 flex flex-wrap items-baseline gap-1.5">
                                <span class="text-[11px] text-slate-400 line-through">3,800,000₫</span>
                                <span class="text-xs sm:text-sm font-extrabold text-red-600">2,660,000₫</span>
                            </div>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3 sm:pb-3">
                        <a href="#bao-gia" onclick="selectProductForQuote('Sen Cây Tắm Đứng Nóng Lạnh Phím Đàn Hiển Thị Nhiệt Độ ĐN-SC912')" class="block w-full text-center bg-slate-100 hover:bg-primary text-primary hover:text-white text-xs font-bold py-1.5 rounded-lg transition">
                            Nhận báo giá
                        </a>
                    </div>
                </div>

                <!-- Sản phẩm thực tế 9 (Drive ID: 1K4gXvkzLNXR-KPSlRzwiKw3xtM4I015u) -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between" data-cat="san-pham-khac">
                    <div>
                        <div class="relative aspect-square bg-slate-100 overflow-hidden">
                            <div class="badge-container">
                                <span class="onsale-badge">-14%</span>
                            </div>
                            <img src="https://drive.google.com/thumbnail?id=1K4gXvkzLNXR-KPSlRzwiKw3xtM4I015u&sz=w800" 
                                 onerror="this.src='https://placehold.co/500x500/e2e8f0/0B3B60?text=Gach+Nhập+Khau+90x180'"
                                 alt="Gạch Đại Sảnh Nhập Khẩu & Tranh Đá Đối Xứng 90x180 ĐN-9180" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 sm:p-3">
                            <div class="text-[10px] text-slate-400 uppercase font-semibold mb-0.5">Sản phẩm khác</div>
                            <h3 class="product-title text-xs sm:text-sm font-bold text-slate-800 hover:text-primary">
                                Gạch Khổ Lớn 90x180 & Tấm Ốp Vân Đá Cao Cấp ĐN-9180
                            </h3>
                            <div class="mt-2 flex flex-wrap items-baseline gap-1.5">
                                <span class="text-[11px] text-slate-400 line-through">790,000₫</span>
                                <span class="text-xs sm:text-sm font-extrabold text-red-600">680,000₫/m²</span>
                            </div>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3 sm:pb-3">
                        <a href="#bao-gia" onclick="selectProductForQuote('Gạch Khổ Lớn 90x180 & Tấm Ốp Vân Đá Cao Cấp ĐN-9180')" class="block w-full text-center bg-slate-100 hover:bg-primary text-primary hover:text-white text-xs font-bold py-1.5 rounded-lg transition">
                            Nhận báo giá
                        </a>
                    </div>
                </div>

                <!-- Sản phẩm bổ sung 10 để chẵn hàng 2 cột trên điện thoại và 5 cột trên máy tính -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between" data-cat="thiet-bi-ve-sinh">
                    <div>
                        <div class="relative aspect-square bg-slate-100 overflow-hidden">
                            <div class="badge-container">
                                <span class="onsale-badge">-30%</span>
                            </div>
                            <img src="https://drive.google.com/thumbnail?id=1-Ec1aH7TR_ienNo4F206IqN5J12hG5Si&sz=w800" 
                                 onerror="this.src='https://placehold.co/500x500/e2e8f0/0B3B60?text=Combo+Phong+Tam'"
                                 alt="Trọn Bộ Combo Thiết Bị Vệ Sinh 7 Món Cao Cấp Đinh Nguyễn" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 sm:p-3">
                            <div class="text-[10px] text-slate-400 uppercase font-semibold mb-0.5">Thiết bị vệ sinh</div>
                            <h3 class="product-title text-xs sm:text-sm font-bold text-slate-800 hover:text-primary">
                                Combo Trọn Bộ Thiết Bị Nhà Tắm Cao Cấp 7 Món ĐN-CB01
                            </h3>
                            <div class="mt-2 flex flex-wrap items-baseline gap-1.5">
                                <span class="text-[11px] text-slate-400 line-through">11,500,000₫</span>
                                <span class="text-xs sm:text-sm font-extrabold text-red-600">8,050,000₫</span>
                            </div>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3 sm:pb-3">
                        <a href="#bao-gia" onclick="selectProductForQuote('Combo Trọn Bộ Thiết Bị Nhà Tắm Cao Cấp 7 Món ĐN-CB01')" class="block w-full text-center bg-slate-100 hover:bg-primary text-primary hover:text-white text-xs font-bold py-1.5 rounded-lg transition">
                            Nhận báo giá
                        </a>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ==========================================
         6. GIỚI THIỆU & ẢNH THỰC TẾ CÔNG TY (2 file ảnh thực tế công ty Google Drive)
    =========================================== -->
    <section id="gioi-thieu" class="py-7 bg-white border-y border-slate-200">
        <div class="container-1500">
            <div class="section-title-container">
                <div class="section-title-normal">
                    <h2 class="section-title-main">HÌNH ẢNH THỰC TẾ CÔNG TY TNHH TMDV ĐINH NGUYỄN</h2>
                    <span class="text-xs font-semibold text-accent hidden sm:inline">442 Nguyễn Hữu Thọ, Cẩm Lệ, Đà Nẵng</span>
                </div>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 items-center">
                <div class="lg:col-span-5 space-y-3">
                    <div class="inline-block bg-amber-100 text-accent font-bold text-xs px-3 py-1 rounded">
                        UY TÍN - CHẤT LƯỢNG - TẬN TÂM
                    </div>
                    <h3 class="text-lg sm:text-xl font-extrabold text-primary leading-snug">
                        Nhà Phân Phối Gạch Ốp Lát & Thiết Bị Vệ Sinh Hàng Đầu Tại TP. Đà Nẵng
                    </h3>
                    <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                        <strong>CÔNG TY TNHH TMDV ĐINH NGUYỄN</strong> (Website: <strong>dinhnguyen.com</strong>) tọa lạc tại số <strong>442 Nguyễn Hữu Thọ, Phường Cẩm Lệ, TP Đà Nẵng</strong>. Chúng tôi tự hào là đơn vị cung ứng trọn gói gạch lát nền, gạch ốp tường, gạch giả gỗ, gạch sân vườn, tấm tường cacbon và thiết bị vệ sinh chính hãng cho hàng trăm công trình dân dụng và dự án lớn tại Đà Nẵng.
                    </p>
                    <ul class="space-y-2 text-xs sm:text-sm text-slate-700">
                        <li class="flex items-center gap-2"><i class="fa-solid fa-circle-check text-accent"></i><span>Mẫu mã đa dạng, cập nhật xu hướng kiến trúc mới nhất.</span></li>
                        <li class="flex items-center gap-2"><i class="fa-solid fa-circle-check text-accent"></i><span>Giá gốc tận kho, chiết khấu hấp dẫn cho thầu thợ & công trình.</span></li>
                        <li class="flex items-center gap-2"><i class="fa-solid fa-circle-check text-accent"></i><span>Vận chuyển nhanh chóng tận nơi tại Đà Nẵng và khu vực lân cận.</span></li>
                    </ul>
                    <div class="pt-2 flex flex-wrap gap-3">
                        <a href="#bao-gia" class="bg-primary hover:bg-primary-light text-white text-xs sm:text-sm font-bold px-4 py-2.5 rounded-lg transition">
                            Đăng Ký Nhận Báo Giá Sỉ
                        </a>
                        <a href="tel:0906477891" class="border border-primary text-primary hover:bg-slate-50 text-xs sm:text-sm font-bold px-4 py-2.5 rounded-lg transition">
                            Hotline: 0906.477.891
                        </a>
                    </div>
                </div>

                <!-- 2 Ảnh thực tế công ty từ Google Drive -->
                <div class="lg:col-span-7 grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                    <div class="bg-slate-100 rounded-xl overflow-hidden border border-slate-200 shadow-sm">
                        <div class="aspect-[4/3] overflow-hidden">
                            <img src="https://drive.google.com/thumbnail?id=1-Ec1aH7TR_ienNo4F206IqN5J12hG5Si&sz=w1000" 
                                 onerror="this.src='https://placehold.co/800x600/0B3B60/FFFFFF?text=Showroom+Dinh+Nguyen+1'"
                                 alt="Hình ảnh thực tế Showroom Công ty TNHH TMDV Đinh Nguyễn 1" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                        </div>
                        <div class="p-3 bg-white">
                            <h4 class="font-bold text-xs sm:text-sm text-primary">Showroom Trưng Bày Gạch Ốp Lát & TBVS Đinh Nguyễn</h4>
                            <p class="text-[11px] text-slate-500 mt-0.5">442 Nguyễn Hữu Thọ, Phường Cẩm Lệ, TP Đà Nẵng</p>
                        </div>
                    </div>

                    <div class="bg-slate-100 rounded-xl overflow-hidden border border-slate-200 shadow-sm">
                        <div class="aspect-[4/3] overflow-hidden">
                            <img src="https://drive.google.com/thumbnail?id=1xcAGKmtzlw4DY5zwh5Ijj0P7R8IbzmAl&sz=w1000" 
                                 onerror="this.src='https://placehold.co/800x600/145385/FFFFFF?text=Showroom+Dinh+Nguyen+2'"
                                 alt="Hình ảnh thực tế Kho bãi & Showroom Công ty TNHH TMDV Đinh Nguyễn 2" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                        </div>
                        <div class="p-3 bg-white">
                            <h4 class="font-bold text-xs sm:text-sm text-primary">Hoạt Động Cung Ứng & Giao Nhận Vật Liệu Tận Công Trình</h4>
                            <p class="text-[11px] text-slate-500 mt-0.5">Đảm bảo tiến độ & chất lượng cho mọi dự án tại Đà Nẵng</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         7. DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (Đưa đầy đủ 7 ảnh dự án Google Drive vào)
    =========================================== -->
    <section id="du-an" class="py-7">
        <div class="container-1500">
            <div class="section-title-container">
                <div class="section-title-normal">
                    <h2 class="section-title-main">CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG</h2>
                    <span class="text-xs text-slate-500 hidden sm:inline">Hình ảnh thực tế cung cấp vật tư & hoàn thiện</span>
                </div>
            </div>

            <!-- Chia 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính -->
            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-4">
                
                <!-- Dự án 1: 1GrXImuNIYzbpGEISJh91gzZqpnS0GXfV -->
                <div class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm group">
                    <div class="aspect-[4/3] bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1GrXImuNIYzbpGEISJh91gzZqpnS0GXfV&sz=w800" 
                             onerror="this.src='https://placehold.co/600x450/0B3B60/FFFFFF?text=Du+An+Da+Nang+1'"
                             alt="Dự án Biệt thự hiện đại Hòa Xuân - Cẩm Lệ" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3">
                        <span class="text-[10px] font-bold text-accent uppercase">Quận Cẩm Lệ - Đà Nẵng</span>
                        <h3 class="product-title text-xs sm:text-sm font-bold text-slate-800 mt-0.5">
                            Biệt Thự Phố Khu Đô Thị Sinh Thái Hòa Xuân
                        </h3>
                    </div>
                </div>

                <!-- Dự án 2: 1v_M2gVuow7Y9BXVMYpFwdOrt8J1eodOQ -->
                <div class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm group">
                    <div class="aspect-[4/3] bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1v_M2gVuow7Y9BXVMYpFwdOrt8J1eodOQ&sz=w800" 
                             onerror="this.src='https://placehold.co/600x450/0B3B60/FFFFFF?text=Du+An+Da+Nang+2'"
                             alt="Dự án Khách sạn & Căn hộ ven biển Mỹ Khê" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3">
                        <span class="text-[10px] font-bold text-accent uppercase">Quận Sơn Trà - Đà Nẵng</span>
                        <h3 class="product-title text-xs sm:text-sm font-bold text-slate-800 mt-0.5">
                            Tổ Hợp Căn Hộ & Khách Sạn Ven Biển Sơn Trà
                        </h3>
                    </div>
                </div>

                <!-- Dự án 3: 1Z4mzLidTT_O_4B2mXUYUkABckKxI9md3 -->
                <div class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm group">
                    <div class="aspect-[4/3] bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1Z4mzLidTT_O_4B2mXUYUkABckKxI9md3&sz=w800" 
                             onerror="this.src='https://placehold.co/600x450/0B3B60/FFFFFF?text=Du+An+Da+Nang+3'"
                             alt="Dự án Nhà phố thương mại Nguyễn Hữu Thọ" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3">
                        <span class="text-[10px] font-bold text-accent uppercase">Quận Hải Châu - Đà Nẵng</span>
                        <h3 class="product-title text-xs sm:text-sm font-bold text-slate-800 mt-0.5">
                            Tòa Nhà Văn Phòng & Showroom Nguyễn Hữu Thọ
                        </h3>
                    </div>
                </div>

                <!-- Dự án 4: 1y-Q7qYDprceQAAAl2gn9sfw1qwZe4s2r -->
                <div class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm group">
                    <div class="aspect-[4/3] bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1y-Q7qYDprceQAAAl2gn9sfw1qwZe4s2r&sz=w800" 
                             onerror="this.src='https://placehold.co/600x450/0B3B60/FFFFFF?text=Du+An+Da+Nang+4'"
                             alt="Dự án Khu nghỉ dưỡng Ngũ Hành Sơn" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3">
                        <span class="text-[10px] font-bold text-accent uppercase">Ngũ Hành Sơn - Đà Nẵng</span>
                        <h3 class="product-title text-xs sm:text-sm font-bold text-slate-800 mt-0.5">
                            Cung Cấp Gạch Khổ Lớn Villa Nghỉ Dưỡng Nam Việt Á
                        </h3>
                    </div>
                </div>

                <!-- Dự án 5: 1chvjh7jt3jsHjEYWBimU3seMTUGK3a7r -->
                <div class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm group">
                    <div class="aspect-[4/3] bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1chvjh7jt3jsHjEYWBimU3seMTUGK3a7r&sz=w800" 
                             onerror="this.src='https://placehold.co/600x450/0B3B60/FFFFFF?text=Du+An+Da+Nang+5'"
                             alt="Dự án Nhà phố liền kề Liên Chiểu" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3">
                        <span class="text-[10px] font-bold text-accent uppercase">Quận Liên Chiểu - Đà Nẵng</span>
                        <h3 class="product-title text-xs sm:text-sm font-bold text-slate-800 mt-0.5">
                            Khu Nhà Phố Liền Kề Golden Hills Đà Nẵng
                        </h3>
                    </div>
                </div>

                <!-- Dự án 6: 1kwg9gZWhkR4HEJGLm4cWGCv3ssSZ9R3r -->
                <div class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm group">
                    <div class="aspect-[4/3] bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1kwg9gZWhkR4HEJGLm4cWGCv3ssSZ9R3r&sz=w800" 
                             onerror="this.src='https://placehold.co/600x450/0B3B60/FFFFFF?text=Du+An+Da+Nang+6'"
                             alt="Dự án Trung tâm dịch vụ thương mại Thanh Khê" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3">
                        <span class="text-[10px] font-bold text-accent uppercase">Quận Thanh Khê - Đà Nẵng</span>
                        <h3 class="product-title text-xs sm:text-sm font-bold text-slate-800 mt-0.5">
                            Hoàn Thiện Thiết Bị Vệ Sinh & Gạch Ốp Trung Tâm Dịch Vụ
                        </h3>
                    </div>
                </div>

                <!-- Dự án 7: 1EMKNjC_2DXLtI_d3F5AZg8dYSJVc5d5Y -->
                <div class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm group">
                    <div class="aspect-[4/3] bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1EMKNjC_2DXLtI_d3F5AZg8dYSJVc5d5Y&sz=w800" 
                             onerror="this.src='https://placehold.co/600x450/0B3B60/FFFFFF?text=Du+An+Da+Nang+7'"
                             alt="Dự án Biệt thự sân vườn Hòa Vang" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3">
                        <span class="text-[10px] font-bold text-accent uppercase">TP. Đà Nẵng</span>
                        <h3 class="product-title text-xs sm:text-sm font-bold text-slate-800 mt-0.5">
                            Công Trình Biệt Thự Sân Vườn & Hồ Bơi Cao Cấp
                        </h3>
                    </div>
                </div>

                <!-- Ô thứ 8: Kêu gọi hợp tác dự án -->
                <div class="bg-primary text-white rounded-xl p-4 flex flex-col justify-between border border-primary-light">
                    <div>
                        <span class="text-[10px] font-bold text-amber-300 uppercase">HỢP TÁC CÔNG TRÌNH</span>
                        <h3 class="text-sm sm:text-base font-extrabold mt-1">
                            Bạn Đang Tìm Nguồn Gạch & Thiết Bị Vệ Sinh Giá Sỉ Tại Đà Nẵng?
                        </h3>
                        <p class="text-xs text-slate-200 mt-2 leading-relaxed">
                            Đinh Nguyễn cung cấp đầy đủ hồ sơ chất lượng CO/CQ, hóa đơn VAT và chiết khấu tốt nhất cho nhà thầu.
                        </p>
                    </div>
                    <a href="#bao-gia" class="mt-3 block text-center bg-accent hover:bg-accent-hover text-white text-xs font-bold py-2 rounded-lg transition">
                        Liên Hệ Báo Giá Dự Án
                    </a>
                </div>

            </div>
        </div>
    </section>

    <!-- ==========================================
         8. DANH MỤC CÁC ĐỐI TÁC CHIẾN LƯỢC
    =========================================== -->
    <section id="doi-tac" class="py-6 bg-white border-y border-slate-200">
        <div class="container-1500">
            <div class="section-title-container">
                <div class="section-title-normal">
                    <h2 class="section-title-main">ĐỐI TÁC & THƯƠNG HIỆU PHÂN PHỐI</h2>
                    <span class="text-xs text-slate-500 hidden sm:inline">Cam kết 100% chính hãng</span>
                </div>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-2.5">
                <div class="border border-slate-200 rounded-lg p-3 flex flex-col items-center justify-center bg-slate-50 hover:border-primary transition text-center">
                    <span class="font-black text-primary text-sm tracking-wider">VIGLACERA</span>
                    <span class="text-[10px] text-slate-500">Gạch & TBVS</span>
                </div>
                <div class="border border-slate-200 rounded-lg p-3 flex flex-col items-center justify-center bg-slate-50 hover:border-primary transition text-center">
                    <span class="font-black text-primary text-sm tracking-wider">PRIME</span>
                    <span class="text-[10px] text-slate-500">Gạch Ốp Lát</span>
                </div>
                <div class="border border-slate-200 rounded-lg p-3 flex flex-col items-center justify-center bg-slate-50 hover:border-primary transition text-center">
                    <span class="font-black text-primary text-sm tracking-wider">ĐỒNG TÂM</span>
                    <span class="text-[10px] text-slate-500">Gạch Cao Cấp</span>
                </div>
                <div class="border border-slate-200 rounded-lg p-3 flex flex-col items-center justify-center bg-slate-50 hover:border-primary transition text-center">
                    <span class="font-black text-primary text-sm tracking-wider">TAICERA</span>
                    <span class="text-[10px] text-slate-500">Gạch Granite</span>
                </div>
                <div class="border border-slate-200 rounded-lg p-3 flex flex-col items-center justify-center bg-slate-50 hover:border-primary transition text-center">
                    <span class="font-black text-primary text-sm tracking-wider">INAX</span>
                    <span class="text-[10px] text-slate-500">Thiết Bị Vệ Sinh</span>
                </div>
                <div class="border border-slate-200 rounded-lg p-3 flex flex-col items-center justify-center bg-slate-50 hover:border-primary transition text-center">
                    <span class="font-black text-primary text-sm tracking-wider">TOTO</span>
                    <span class="text-[10px] text-slate-500">Thiết Bị Vệ Sinh</span>
                </div>
                <div class="border border-slate-200 rounded-lg p-3 flex flex-col items-center justify-center bg-slate-50 hover:border-primary transition text-center">
                    <span class="font-black text-primary text-sm tracking-wider">HIMIC</span>
                    <span class="text-[10px] text-slate-500">Phòng Tắm Cao Cấp</span>
                </div>
                <div class="border border-slate-200 rounded-lg p-3 flex flex-col items-center justify-center bg-slate-50 hover:border-primary transition text-center">
                    <span class="font-black text-primary text-sm tracking-wider">DOVA</span>
                    <span class="text-[10px] text-slate-500">Sen Vòi & Lavabo</span>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         9. DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC & KINH NGHIỆM XÂY DỰNG)
    =========================================== -->
    <section id="bai-viet" class="py-7">
        <div class="container-1500">
            <div class="section-title-container">
                <div class="section-title-normal">
                    <h2 class="section-title-main">TIN TỨC & KIẾN THỨC XÂY DỰNG</h2>
                    <span class="text-xs text-slate-500 hidden sm:inline">Cẩm nang chọn gạch ốp lát & thiết bị vệ sinh</span>
                </div>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4">
                
                <!-- Bài viết 1 -->
                <article class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm flex flex-col justify-between">
                    <div>
                        <div class="relative aspect-[16/10] bg-slate-100 overflow-hidden">
                            <img src="https://drive.google.com/thumbnail?id=1lenA2gP-I7n9KAr-CH1jT8QQ2B8_qfdn&sz=w600" 
                                 onerror="this.src='https://placehold.co/600x380/0B3B60/FFFFFF?text=Kinh+Nghiem+Chon+Gach'"
                                 alt="Kinh nghiệm chọn gạch lát nền phòng khách tại Đà Nẵng" class="w-full h-full object-cover">
                            <div class="absolute top-2.5 left-2.5 bg-primary text-white text-[10px] font-bold px-2 py-1 rounded">
                                Kiến thức xây dựng
                            </div>
                        </div>
                        <div class="p-3.5">
                            <h3 class="font-bold text-sm text-slate-800 hover:text-primary leading-snug">
                                Kinh Nghiệm Chọn Gạch Lát Nền Khổ Lớn 80x80 & 60x120 Cho Nhà Phố Hiện Đại
                            </h3>
                            <p class="text-xs text-slate-500 mt-1.5 line-clamp-2">
                                Hướng dẫn cách phối màu gạch vân đá marble giúp không gian phòng khách rộng rãi, sang trọng và bền đẹp theo thời gian.
                            </p>
                        </div>
                    </div>
                    <div class="px-3.5 pb-3 text-[11px] font-semibold text-accent">
                        Xem chi tiết <i class="fa-solid fa-arrow-right ml-1"></i>
                    </div>
                </article>

                <!-- Bài viết 2 -->
                <article class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm flex flex-col justify-between">
                    <div>
                        <div class="relative aspect-[16/10] bg-slate-100 overflow-hidden">
                            <img src="https://drive.google.com/thumbnail?id=1gCksAETQ49L5NK5__HN5Wo3tZSHyaH-0&sz=w600" 
                                 onerror="this.src='https://placehold.co/600x380/0B3B60/FFFFFF?text=Thiet+Bi+Ve+Sinh'"
                                 alt="Cách chọn combo thiết bị vệ sinh tiết kiệm chi phí" class="w-full h-full object-cover">
                            <div class="absolute top-2.5 left-2.5 bg-primary text-white text-[10px] font-bold px-2 py-1 rounded">
                                Tư vấn phòng tắm
                            </div>
                        </div>
                        <div class="p-3.5">
                            <h3 class="font-bold text-sm text-slate-800 hover:text-primary leading-snug">
                                Bí Quyết Chọn Trọn Bộ Thiết Bị Vệ Sinh Bền Đẹp, Chống Bám Bẩn Cho Gia Đình
                            </h3>
                            <p class="text-xs text-slate-500 mt-1.5 line-clamp-2">
                                Ưu điểm vượt trội của dòng bồn cầu 1 khối phủ men Nano kháng khuẩn và sen cây phím đàn nhiệt độ thế hệ mới tại Đinh Nguyễn.
                            </p>
                        </div>
                    </div>
                    <div class="px-3.5 pb-3 text-[11px] font-semibold text-accent">
                        Xem chi tiết <i class="fa-solid fa-arrow-right ml-1"></i>
                    </div>
                </article>

                <!-- Bài viết 3 -->
                <article class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm flex flex-col justify-between">
                    <div>
                        <div class="relative aspect-[16/10] bg-slate-100 overflow-hidden">
                            <img src="https://drive.google.com/thumbnail?id=1z7LP9NRTaYtz6vCCDIDhlt6quSLD47da&sz=w600" 
                                 onerror="this.src='https://placehold.co/600x380/0B3B60/FFFFFF?text=Gach+Gia+Go'"
                                 alt="Xu hướng lát sàn đá giả gỗ phòng ngủ" class="w-full h-full object-cover">
                            <div class="absolute top-2.5 left-2.5 bg-primary text-white text-[10px] font-bold px-2 py-1 rounded">
                                Xu hướng nội thất
                            </div>
                        </div>
                        <div class="p-3.5">
                            <h3 class="font-bold text-sm text-slate-800 hover:text-primary leading-snug">
                                Vì Sao Gạch Giả Gỗ Chống Thấm Đang Thay Thế Sàn Gỗ Công Nghiệp Tại Miền Trung?
                            </h3>
                            <p class="text-xs text-slate-500 mt-1.5 line-clamp-2">
                                Giải pháp hoàn hảo chống mối mọt, chịu nước tuyệt đối cho khí hậu Đà Nẵng mà vẫn giữ trọn vẻ đẹp ấm cúng của gỗ tự nhiên.
                            </p>
                        </div>
                    </div>
                    <div class="px-3.5 pb-3 text-[11px] font-semibold text-accent">
                        Xem chi tiết <i class="fa-solid fa-arrow-right ml-1"></i>
                    </div>
                </article>

                <!-- Bài viết 4 -->
                <article class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm flex flex-col justify-between">
                    <div>
                        <div class="relative aspect-[16/10] bg-slate-100 overflow-hidden">
                            <img src="https://drive.google.com/thumbnail?id=1-Ec1aH7TR_ienNo4F206IqN5J12hG5Si&sz=w600" 
                                 onerror="this.src='https://placehold.co/600x380/0B3B60/FFFFFF?text=Bang+Gia+Dinh+Nguyen'"
                                 alt="Báo giá gạch ốp lát Đà Nẵng mới nhất" class="w-full h-full object-cover">
                            <div class="absolute top-2.5 left-2.5 bg-accent text-white text-[10px] font-bold px-2 py-1 rounded">
                                Tin công ty
                            </div>
                        </div>
                        <div class="p-3.5">
                            <h3 class="font-bold text-sm text-slate-800 hover:text-primary leading-snug">
                                Công Ty TNHH TMDV Đinh Nguyễn Ưu Đãi Chiết Khấu Lớn Cho Công Trình Xây Dựng Mới
                            </h3>
                            <p class="text-xs text-slate-500 mt-1.5 line-clamp-2">
                                Quý khách hàng ghé thăm Showroom 442 Nguyễn Hữu Thọ, Cẩm Lệ, Đà Nẵng để trải nghiệm trực tiếp các mẫu gạch mới nhất.
                            </p>
                        </div>
                    </div>
                    <div class="px-3.5 pb-3 text-[11px] font-semibold text-accent">
                        Xem chi tiết <i class="fa-solid fa-arrow-right ml-1"></i>
                    </div>
                </article>

            </div>
        </div>
    </section>

    <!-- ==========================================
         10. FORM YÊU CẦU TƯ VẤN & BÁO GIÁ + FANPAGE FACEBOOK + GOOGLE MAP NGOÀI TRANG CHỦ
         Yêu cầu:
         - Thêm form yêu cầu và báo giá trang chủ
         - Đưa Fanpage (https://www.facebook.com/hnguyenduc) ra ngoài trang chủ
         - Đưa ảnh/bản đồ Google Map (442 Nguyễn Hữu Thọ, Phường Cẩm Lệ, TP Đà Nẵng - https://share.google/gSIsK4Iq1aTMKnRuy) ra ngoài trang chủ
         - Không có nút xem thumbnail chia sẻ web
    =========================================== -->
    <section id="bao-gia" class="py-8 bg-white border-t border-slate-200">
        <div class="container-1500">
            <div class="section-title-container">
                <div class="section-title-normal">
                    <h2 class="section-title-main">LIÊN HỆ BÁO GIÁ, FANPAGE & BẢN ĐỒ CHỈ ĐƯỜNG</h2>
                    <span class="text-xs font-bold text-primary hidden sm:inline">Hotline/Zalo: 0906.477.891</span>
                </div>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-5">
                
                <!-- CỘT 1: FORM YÊU CẦU VÀ BÁO GIÁ TRANG CHỦ (5 Cột) -->
                <div class="lg:col-span-5 bg-slate-50 p-4 sm:p-5 rounded-xl border border-slate-200 shadow-sm">
                    <h3 class="text-base font-extrabold text-primary uppercase flex items-center gap-2">
                        <i class="fa-solid fa-file-signature text-accent"></i>
                        <span>GỬI YÊU CẦU TƯ VẤN & BÁO GIÁ</span>
                    </h3>
                    <p class="text-xs text-slate-600 mt-1 mb-4">
                        Điền thông tin bên dưới, bộ phận kinh doanh Đinh Nguyễn sẽ gửi bảng báo giá và mẫu thực tế qua Zalo/SĐT của quý khách trong 5 phút.
                    </p>

                    <form id="quoteForm" onsubmit="submitQuoteForm(event)" class="space-y-3">
                        <div>
                            <label class="block text-xs font-bold text-slate-700 mb-1">Họ và tên khách hàng *</label>
                            <input id="qName" type="text" required placeholder="Nhập họ và tên của bạn..." class="w-full border border-slate-300 rounded-lg px-3 py-2 text-xs sm:text-sm focus:outline-none focus:border-primary bg-white">
                        </div>
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                            <div>
                                <label class="block text-xs font-bold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                                <input id="qPhone" type="tel" required placeholder="Ví dụ: 0906477891" class="w-full border border-slate-300 rounded-lg px-3 py-2 text-xs sm:text-sm focus:outline-none focus:border-primary bg-white">
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-slate-700 mb-1">Danh mục quan tâm</label>
                                <select id="qCategory" class="w-full border border-slate-300 rounded-lg px-3 py-2 text-xs sm:text-sm focus:outline-none focus:border-primary bg-white">
                                    <option value="Gạch lát nền & Gạch ốp tường">Gạch lát nền & Gạch ốp tường</option>
                                    <option value="Gạch giả gỗ & Gạch sân vườn">Gạch giả gỗ & Gạch sân vườn</option>
                                    <option value="Thiết bị vệ sinh trọn gói">Thiết bị vệ sinh trọn gói</option>
                                    <option value="Tấm tường cacbon & Tranh đá">Tấm tường cacbon & Tranh đá</option>
                                    <option value="Báo giá sỉ cho công trình / dự án">Báo giá sỉ cho công trình / dự án</option>
                                </select>
                            </div>
                        </div>
                        <div>
                            <label class="block text-xs font-bold text-slate-700 mb-1">Sản phẩm / Nội dung yêu cầu báo giá</label>
                            <textarea id="qNote" rows="3" placeholder="Nhập kích thước gạch, diện tích (m2) hoặc mã sản phẩm cần báo giá..." class="w-full border border-slate-300 rounded-lg px-3 py-2 text-xs sm:text-sm focus:outline-none focus:border-primary bg-white"></textarea>
                        </div>
                        <button type="submit" class="w-full bg-accent hover:bg-accent-hover text-white font-extrabold text-xs sm:text-sm py-2.5 rounded-lg shadow transition uppercase tracking-wide">
                            <i class="fa-solid fa-paper-plane mr-1.5"></i> GỬI YÊU CẦU BÁO GIÁ NGAY
                        </button>
                    </form>

                    <!-- Hộp thông báo trạng thái gửi Form (Không dùng alert) -->
                    <div id="quoteSuccessBox" class="hidden mt-3 p-3 rounded-lg bg-emerald-50 border border-emerald-300 text-emerald-800 text-xs font-medium"></div>
                </div>

                <!-- CỘT 2: FANPAGE FACEBOOK NGOÀI TRANG CHỦ (3 Cột) -->
                <div class="lg:col-span-3 bg-slate-50 p-4 rounded-xl border border-slate-200 shadow-sm flex flex-col justify-between">
                    <div>
                        <h3 class="text-sm font-extrabold text-primary uppercase flex items-center gap-2 mb-3">
                            <i class="fa-brands fa-facebook text-[#1877F2] text-base"></i>
                            <span>KẾT NỐI FACEBOOK / FANPAGE</span>
                        </h3>

                        <!-- Card Fanpage trực quan & Nhúng kết nối trực tiếp tới https://www.facebook.com/hnguyenduc -->
                        <div class="rounded-xl overflow-hidden border border-slate-200 bg-white shadow-sm">
                            <div class="h-28 bg-cover bg-center relative" style="background-image: url('https://drive.google.com/thumbnail?id=1-Ec1aH7TR_ienNo4F206IqN5J12hG5Si&sz=w600');">
                                <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/40 to-transparent"></div>
                                <div class="absolute bottom-2.5 left-3 right-3 flex items-center gap-2.5">
                                    <img src="https://drive.google.com/thumbnail?id=1xcAGKmtzlw4DY5zwh5Ijj0P7R8IbzmAl&sz=w200" 
                                         onerror="this.src='https://placehold.co/100x100/0B3B60/FFFFFF?text=DN'"
                                         alt="Avatar Facebook Đinh Nguyễn" class="w-12 h-12 rounded-full border-2 border-white object-cover shrink-0 bg-primary">
                                    <div class="text-white overflow-hidden">
                                        <a href="https://www.facebook.com/hnguyenduc" target="_blank" rel="noopener noreferrer" class="font-bold text-xs sm:text-sm hover:underline block truncate">
                                            CÔNG TY TNHH TMDV ĐINH NGUYỄN
                                        </a>
                                        <span class="text-[11px] text-slate-200 block truncate">facebook.com/hnguyenduc</span>
                                    </div>
                                </div>
                            </div>
                            <div class="p-3 space-y-2.5 text-xs">
                                <p class="text-slate-600 leading-snug">
                                    Cập nhật hình ảnh xuất kho gạch ốp lát, thiết bị vệ sinh và các công trình thực tế hàng ngày tại Đà Nẵng.
                                </p>
                                <div class="flex items-center gap-2 pt-1">
                                    <a href="https://www.facebook.com/hnguyenduc" target="_blank" rel="noopener noreferrer" class="flex-1 bg-[#1877F2] hover:bg-blue-700 text-white text-center font-bold py-2 px-3 rounded-lg text-xs transition flex items-center justify-center gap-1.5">
                                        <i class="fa-brands fa-facebook-f"></i> Theo Dõi Trang
                                    </a>
                                    <a href="https://www.facebook.com/hnguyenduc" target="_blank" rel="noopener noreferrer" class="bg-slate-100 hover:bg-slate-200 text-slate-700 font-bold py-2 px-3 rounded-lg text-xs transition">
                                        Nhắn Tin
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="mt-3 p-3 rounded-lg bg-white border border-slate-200 text-xs space-y-1 text-slate-600">
                        <div class="font-bold text-primary">Thông tin liên hệ nhanh:</div>
                        <div><i class="fa-solid fa-phone text-accent mr-1.5"></i>Hotline: <strong>0906.477.891</strong></div>
                        <div><i class="fa-solid fa-globe text-accent mr-1.5"></i>Website: <strong>dinhnguyen.com</strong></div>
                    </div>
                </div>

                <!-- CỘT 3: ĐƯA ẢNH & BẢN ĐỒ GOOGLE MAP RA NGOÀI TRANG CHỦ (4 Cột) -->
                <div id="ban-do" class="lg:col-span-4 bg-slate-50 p-4 rounded-xl border border-slate-200 shadow-sm flex flex-col justify-between">
                    <div>
                        <div class="flex items-center justify-between gap-2 mb-2.5">
                            <h3 class="text-sm font-extrabold text-primary uppercase flex items-center gap-1.5">
                                <i class="fa-solid fa-map-location-dot text-accent text-base"></i>
                                <span>BẢN ĐỒ GOOGLE MAPS</span>
                            </h3>
                            <a href="https://share.google/gSIsK4Iq1aTMKnRuy" target="_blank" rel="noopener noreferrer" class="text-[11px] font-bold text-accent hover:underline">
                                Mở ứng dụng Map <i class="fa-solid fa-up-right-from-square ml-0.5"></i>
                            </a>
                        </div>

                        <!-- Khung Google Maps trực tiếp tại 442 Nguyễn Hữu Thọ, Phường Cẩm Lệ, TP Đà Nẵng -->
                        <div class="w-full h-56 sm:h-60 rounded-xl overflow-hidden border border-slate-300 bg-slate-200 relative">
                            <iframe 
                                title="Bản đồ Công ty TNHH TMDV Đinh Nguyễn 442 Nguyễn Hữu Thọ Đà Nẵng"
                                src="https://maps.google.com/maps?q=442%20Nguy%E1%BB%85n%20H%E1%BB%AFu%20Th%E1%BB%8D,%20C%E1%BA%A9m%20L%E1%BB%87,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed" 
                                class="w-full h-full border-0" 
                                allowfullscreen="" 
                                loading="lazy" 
                                referrerpolicy="no-referrer-when-downgrade">
                            </iframe>
                        </div>
                    </div>

                    <div class="mt-3 flex items-center justify-between gap-2 bg-white p-2.5 rounded-lg border border-slate-200">
                        <div class="text-xs text-slate-700 leading-tight">
                            <div class="font-bold text-primary">442 Nguyễn Hữu Thọ, Phường Cẩm Lệ, TP Đà Nẵng</div>
                            <div class="text-[11px] text-slate-500 mt-0.5">Có chỗ đậu ô tô rộng rãi trước Showroom</div>
                        </div>
                        <a href="https://share.google/gSIsK4Iq1aTMKnRuy" target="_blank" rel="noopener noreferrer" class="shrink-0 bg-primary hover:bg-primary-light text-white text-xs font-bold px-3 py-2 rounded-lg transition">
                            Chỉ đường
                        </a>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ==========================================
         11. FOOTER CHUẨN MẪU QUANGHUNGCERAMIC.VN & FLATSOME
    =========================================== -->
    <footer class="bg-primary-dark text-slate-200 pt-10 pb-6 border-t-4 border-accent mt-auto">
        <div class="container-1500">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-7 pb-8 border-b border-white/10">
                
                <!-- Thông tin công ty (5 cột) -->
                <div class="lg:col-span-5 space-y-3">
                    <div class="flex items-center gap-2.5">
                        <svg class="w-9 h-9 shrink-0 rounded-lg" viewBox="0 0 100 100" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <rect width="100" height="100" rx="18" fill="#0B3B60"/>
                            <path d="M18 24H52C66.3594 24 78 35.6406 78 50C78 64.3594 66.3594 76 52 76H18V24Z" stroke="#D97706" stroke-width="8"/>
                            <path d="M12 50H42" stroke="#F59E0B" stroke-width="7" stroke-linecap="round"/>
                            <path d="M44 36L64 64M64 36V64" stroke="#FFFFFF" stroke-width="7" stroke-linecap="round" stroke-linejoin="round"/>
                            <rect x="74" y="18" width="10" height="10" rx="2" fill="#D97706"/>
                        </svg>
                        <div>
                            <div class="text-white font-extrabold text-sm sm:text-base uppercase">CÔNG TY TNHH TMDV ĐINH NGUYỄN</div>
                            <div class="text-amber-400 text-xs font-semibold">Gạch Ốp Lát & Thiết Bị Vệ Sinh Trọn Gói</div>
                        </div>
                    </div>
                    <ul class="space-y-2 text-xs sm:text-sm text-slate-300">
                        <li class="flex items-start gap-2">
                            <i class="fa-solid fa-location-dot text-accent mt-1"></i>
                            <span><strong>Địa chỉ Showroom:</strong> 442 Nguyễn Hữu Thọ, Phường Cẩm Lệ, TP Đà Nẵng</span>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-phone-volume text-accent"></i>
                            <span><strong>Hotline / Zalo:</strong> <a href="tel:0906477891" class="text-amber-300 font-bold hover:underline">0906.477.891</a></span>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-id-card text-accent"></i>
                            <span><strong>Mã số thuế:</strong> 0402171132</span>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-globe text-accent"></i>
                            <span><strong>Website:</strong> <a href="https://dinhnguyen.com" class="hover:text-white">dinhnguyen.com</a></span>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-clock text-accent"></i>
                            <span><strong>Giờ làm việc:</strong> 07h00 – 17h30 (Thứ 2 – Chủ Nhật)</span>
                        </li>
                    </ul>
                </div>

                <!-- Danh mục sản phẩm (3 cột) -->
                <div class="lg:col-span-3 space-y-2.5">
                    <h4 class="text-white font-extrabold text-sm uppercase border-b border-white/15 pb-2">SẢN PHẨM CUNG CẤP</h4>
                    <ul class="space-y-1.5 text-xs sm:text-sm text-slate-300">
                        <li><a href="#san-pham-chinh" onclick="filterCategory('gach-lat-nen')" class="hover:text-amber-400 transition"><i class="fa-solid fa-angle-right text-accent mr-1.5"></i>Gạch lát nền cao cấp</a></li>
                        <li><a href="#san-pham-chinh" onclick="filterCategory('gach-op-tuong')" class="hover:text-amber-400 transition"><i class="fa-solid fa-angle-right text-accent mr-1.5"></i>Gạch ốp tường phòng tắm & bếp</a></li>
                        <li><a href="#san-pham-chinh" onclick="filterCategory('gach-gia-go')" class="hover:text-amber-400 transition"><i class="fa-solid fa-angle-right text-accent mr-1.5"></i>Gạch giả gỗ & Sàn đá</a></li>
                        <li><a href="#san-pham-chinh" onclick="filterCategory('gach-san-vuon')" class="hover:text-amber-400 transition"><i class="fa-solid fa-angle-right text-accent mr-1.5"></i>Gạch lát sân vườn & vỉa hè</a></li>
                        <li><a href="#san-pham-chinh" onclick="filterCategory('thiet-bi-ve-sinh')" class="hover:text-amber-400 transition"><i class="fa-solid fa-angle-right text-accent mr-1.5"></i>Thiết bị vệ sinh tại Đà Nẵng</a></li>
                        <li><a href="#san-pham-chinh" onclick="filterCategory('san-pham-khac')" class="hover:text-amber-400 transition"><i class="fa-solid fa-angle-right text-accent mr-1.5"></i>Tấm tường cacbon & Tranh đá</a></li>
                    </ul>
                </div>

                <!-- Chính sách & Hỗ trợ (4 cột) -->
                <div class="lg:col-span-4 space-y-2.5">
                    <h4 class="text-white font-extrabold text-sm uppercase border-b border-white/15 pb-2">CHÍNH SÁCH & HỖ TRỢ KHÁCH HÀNG</h4>
                    <ul class="space-y-1.5 text-xs sm:text-sm text-slate-300">
                        <li><a href="#bao-gia" class="hover:text-amber-400 transition"><i class="fa-solid fa-angle-right text-accent mr-1.5"></i>Chính sách vận chuyển & Giao nhận Đà Nẵng</a></li>
                        <li><a href="#bao-gia" class="hover:text-amber-400 transition"><i class="fa-solid fa-angle-right text-accent mr-1.5"></i>Chính sách bảo hành chính hãng</a></li>
                        <li><a href="#bao-gia" class="hover:text-amber-400 transition"><i class="fa-solid fa-angle-right text-accent mr-1.5"></i>Chính sách đổi trả hàng dư công trình</a></li>
                        <li><a href="#bao-gia" class="hover:text-amber-400 transition"><i class="fa-solid fa-angle-right text-accent mr-1.5"></i>Hướng dẫn mua hàng & Thanh toán</a></li>
                        <li><a href="https://share.google/gSIsK4Iq1aTMKnRuy" target="_blank" rel="noopener noreferrer" class="hover:text-amber-400 transition"><i class="fa-solid fa-angle-right text-accent mr-1.5"></i>Bản đồ đường đi đến Showroom 442 Nguyễn Hữu Thọ</a></li>
                    </ul>
                </div>

            </div>

            <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400 text-center sm:text-left">
                <div>Copyright © 2026 <strong>CÔNG TY TNHH TMDV ĐINH NGUYỄN (dinhnguyen.com)</strong>. All rights reserved.</div>
                <div>Địa chỉ: 442 Nguyễn Hữu Thọ, Phường Cẩm Lệ, TP Đà Nẵng | Hotline: 0906.477.891</div>
            </div>
        </div>
    </footer>

    <!-- ==========================================
         12. CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)
         Tương thích hoàn hảo trên cả máy tính và điện thoại, không gây tràn viền
    =========================================== -->
    <div class="fixed right-3 bottom-4 z-50 flex flex-col items-end gap-2.5">
        
        <!-- Nút Facebook Fanpage -->
        <a href="https://www.facebook.com/hnguyenduc" target="_blank" rel="noopener noreferrer" aria-label="Chat Facebook" class="group flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white p-2.5 sm:px-3.5 sm:py-2.5 rounded-full shadow-lg transition">
            <i class="fa-brands fa-facebook-f text-base sm:text-lg w-5 text-center"></i>
            <span class="hidden sm:inline text-xs font-bold pr-1">Facebook</span>
        </a>

        <!-- Nút Chat Zalo (0906.477.891) -->
        <a href="https://zalo.me/0906477891" target="_blank" rel="noopener noreferrer" aria-label="Chat Zalo 0906.477.891" class="group flex items-center gap-2 bg-[#0068FF] hover:bg-blue-600 text-white p-2.5 sm:px-3.5 sm:py-2.5 rounded-full shadow-lg transition">
            <span class="font-extrabold text-xs sm:text-sm bg-white text-[#0068FF] rounded-full w-5 h-5 flex items-center justify-center shrink-0">Z</span>
            <span class="hidden sm:inline text-xs font-bold pr-1">Zalo: 0906.477.891</span>
        </a>

        <!-- Nút Gọi Hotline nổi bật -->
        <a href="tel:0906477891" aria-label="Gọi Hotline 0906.477.891" class="pulse-btn flex items-center gap-2 bg-accent hover:bg-accent-hover text-white p-3 sm:px-4 sm:py-2.5 rounded-full shadow-xl transition">
            <i class="fa-solid fa-phone-volume text-base sm:text-lg"></i>
            <span class="text-xs sm:text-sm font-extrabold pr-1">0906.477.891</span>
        </a>

    </div>

    <!-- ==========================================
         JAVASCRIPT XỬ LÝ SLIDER TỰ TRƯỢT, LỌC DANH MỤC & FORM BÁO GIÁ
    =========================================== -->
    <script>
        // 1. Tự động trượt 2 Banner kích thước bằng nhau
        let currentSlide = 0;
        const slides = document.querySelectorAll('.banner-slide');
        const dot0 = document.getElementById('dot-0');
        const dot1 = document.getElementById('dot-1');
        let slideInterval;

        function showSlide(index) {
            currentSlide = (index + slides.length) % slides.length;
            slides.forEach((slide, idx) => {
                if (idx === currentSlide) {
                    slide.classList.remove('hidden', 'opacity-0');
                    slide.classList.add('block', 'opacity-100');
                } else {
                    slide.classList.remove('block', 'opacity-100');
                    slide.classList.add('hidden', 'opacity-0');
                }
            });
            if (currentSlide === 0) {
                dot0.className = 'w-2.5 h-2.5 rounded-full bg-amber-400 transition';
                dot1.className = 'w-2.5 h-2.5 rounded-full bg-white/50 transition';
            } else {
                dot0.className = 'w-2.5 h-2.5 rounded-full bg-white/50 transition';
                dot1.className = 'w-2.5 h-2.5 rounded-full bg-amber-400 transition';
            }
        }

        function changeSlide(step) {
            showSlide(currentSlide + step);
            resetSlideTimer();
        }

        function goToSlide(index) {
            showSlide(index);
            resetSlideTimer();
        }

        function resetSlideTimer() {
            clearInterval(slideInterval);
            slideInterval = setInterval(() => {
                showSlide(currentSlide + 1);
            }, 5000);
        }

        // 2. Xử lý đóng/mở Menu Mobile
        const mobileMenuBtn = document.getElementById('mobileMenuBtn');
        const closeMobileMenu = document.getElementById('closeMobileMenu');
        const mobileMenuOverlay = document.getElementById('mobileMenuOverlay');

        function toggleMobileMenu(show) {
            if (show) {
                mobileMenuOverlay.classList.remove('hidden');
            } else {
                mobileMenuOverlay.classList.add('hidden');
            }
        }

        mobileMenuBtn.addEventListener('click', () => toggleMobileMenu(true));
        closeMobileMenu.addEventListener('click', () => toggleMobileMenu(false));
        mobileMenuOverlay.addEventListener('click', (e) => {
            if (e.target === mobileMenuOverlay) toggleMobileMenu(false);
        });

        function closeDrawerAndFilter(cat) {
            toggleMobileMenu(false);
            filterCategory(cat);
        }

        // 3. Lọc sản phẩm theo Danh mục
        const categoryNames = {
            'all': 'GẠCH ỐP LÁT & VẬT LIỆU HOÀN THIỆN',
            'gach-lat-nen': 'DANH MỤC: GẠCH LÁT NỀN CAO CẤP',
            'gach-op-tuong': 'DANH MỤC: GẠCH ỐP TƯỜNG',
            'gach-gia-go': 'DANH MỤC: SÀN ĐÁ & GẠCH GIẢ GỖ',
            'gach-san-vuon': 'DANH MỤC: GẠCH LÁT SÂN VƯỜN',
            'thiet-bi-ve-sinh': 'DANH MỤC: THIẾT BỊ VỆ SINH TRỌN GÓI',
            'san-pham-khac': 'DANH MỤC: TẤM TƯỜNG CACBON & TRANH ĐÁ'
        };

        function filterCategory(cat) {
            const cards = document.querySelectorAll('.product-card');
            const titleEl = document.getElementById('currentCategoryTitle');
            titleEl.textContent = categoryNames[cat] || 'SẢN PHẨM ĐINH NGUYỄN';

            cards.forEach(card => {
                const cardCat = card.getAttribute('data-cat');
                if (cat === 'all' || cardCat === cat) {
                    card.classList.remove('hidden');
                    card.classList.add('flex');
                } else {
                    card.classList.remove('flex');
                    card.classList.add('hidden');
                }
            });

            const sec = document.getElementById('san-pham-chinh');
            if (sec) {
                sec.scrollIntoView({ behavior: 'smooth', block: 'start' });
            }
        }

        // 4. Tìm kiếm sản phẩm
        function filterBySearch() {
            const keyword = document.getElementById('searchInput').value.trim().toLowerCase();
            const selectedCat = document.getElementById('searchCatSelect').value;
            runSearchFilter(keyword, selectedCat);
        }

        function filterBySearchMobile() {
            const keyword = document.getElementById('searchInputMobile').value.trim().toLowerCase();
            runSearchFilter(keyword, 'all');
        }

        function runSearchFilter(keyword, selectedCat) {
            const cards = document.querySelectorAll('.product-card');
            cards.forEach(card => {
                const text = card.innerText.toLowerCase();
                const cardCat = card.getAttribute('data-cat');
                const matchKeyword = !keyword || text.includes(keyword);
                const matchCat = selectedCat === 'all' || cardCat === selectedCat;
                if (matchKeyword && matchCat) {
                    card.classList.remove('hidden');
                    card.classList.add('flex');
                } else {
                    card.classList.remove('flex');
                    card.classList.add('hidden');
                }
            });
            document.getElementById('san-pham-chinh').scrollIntoView({ behavior: 'smooth' });
        }

        // 5. Điền nhanh tên sản phẩm vào Form báo giá
        function selectProductForQuote(productName) {
            const noteInput = document.getElementById('qNote');
            if (noteInput) {
                noteInput.value = 'Tôi cần tư vấn & nhận báo giá sản phẩm: ' + productName;
                noteInput.focus();
            }
        }

        // 6. Xử lý gửi Form Báo Giá
        function submitQuoteForm(e) {
            e.preventDefault();
            const name = document.getElementById('qName').value.trim();
            const phone = document.getElementById('qPhone').value.trim();
            const cat = document.getElementById('qCategory').value;
            const successBox = document.getElementById('quoteSuccessBox');

            successBox.innerHTML = `<i class="fa-solid fa-circle-check mr-1"></i> Cảm ơn <strong>${name}</strong> (${phone})! Yêu cầu báo giá mục <strong>${cat}</strong> đã được ghi nhận. Chuyên viên Công ty TNHH TMDV Đinh Nguyễn (0906.477.891) sẽ liên hệ ngay với quý khách.`;
            successBox.classList.remove('hidden');
            document.getElementById('quoteForm').reset();
        }

        window.onload = function() {
            resetSlideTimer();
        };
    </script>
</body>
</html>
