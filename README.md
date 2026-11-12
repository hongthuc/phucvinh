<!-- Website: phucvinh.com - Phúc Vinh Mâm Quả Cưới Đà Nẵng | Cấu trúc chuẩn Flatsome UX Builder -->
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Phúc Vinh - Mâm Quả Cưới Đà Nẵng | Kết Mâm Quả & Cổng Rồng Phụng Trọn Gói</title>
    <meta name="description" content="Phúc Vinh - Mâm Quả Cưới Đà Nẵng (phucvinh.com). Chuyên: Kết Mâm Quả Cưới - Hỏi + Decor - Trang Trí Cổng Rồng Phụng Giá Rẻ Đà Nẵng Trọn Gói. Địa chỉ: 142 Bùi Tá Hán, Phường Ngũ Hành Sơn, Tp. Đà Nẵng. Hotline: 0934.153.598">

    <!-- Open Graph / Thumbnail là ảnh Logo trang web khi gửi link chia sẻ -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://phucvinh.com/">
    <meta property="og:site_name" content="phucvinh.com - Phúc Vinh Mâm Quả Cưới Đà Nẵng">
    <meta property="og:title" content="Phúc Vinh - Mâm Quả Cưới Đà Nẵng | Kết Mâm Quả & Cổng Rồng Phụng Giá Rẻ">
    <meta property="og:description" content="CHUYÊN: KẾT MÂM QUẢ CƯỚI - HỎI + DECOR - TRANG TRÍ CỔNG RỒNG PHỤNG GIÁ RẺ ĐÀ NẴNG TRỌN GÓI. Đ/c: 142 Bùi Tá Hán, P. Ngũ Hành Sơn, Đà Nẵng. ĐT: 0934.153.598">
    <meta property="og:image" content="https://drive.google.com/thumbnail?id=1xP2iyt2jNC0uVEufM3pyHIr3Mj-kDWRF&sz=w1200">
    <meta property="og:image:secure_url" content="https://drive.google.com/thumbnail?id=1xP2iyt2jNC0uVEufM3pyHIr3Mj-kDWRF&sz=w1200">
    <meta property="og:image:width" content="1200">
    <meta property="og:image:height" content="630">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="Phúc Vinh - Mâm Quả Cưới Đà Nẵng | phucvinh.com">
    <meta name="twitter:image" content="https://drive.google.com/thumbnail?id=1xP2iyt2jNC0uVEufM3pyHIr3Mj-kDWRF&sz=w1200">
    <link rel="icon" type="image/png" href="https://drive.google.com/thumbnail?id=1xP2iyt2jNC0uVEufM3pyHIr3Mj-kDWRF&sz=w200">
    <link rel="apple-touch-icon" href="https://drive.google.com/thumbnail?id=1xP2iyt2jNC0uVEufM3pyHIr3Mj-kDWRF&sz=w200">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>

    <!-- Google Fonts: Inter & Playfair Display -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Playfair+Display:ital,wght@0,600;0,700;0,800;1,600&display=swap" rel="stylesheet">

    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        pvRed: '#8B1A1A',       /* Đỏ rượu vang sang trọng theo tông logo cưới */
                        pvRedDark: '#681010',   /* Đỏ đậm */
                        pvRedLight: '#FDF2F2',  /* Hồng kem nhạt */
                        pvGold: '#C9972C',      /* Vàng hoàng gia */
                        pvGoldLight: '#F7E7C4', /* Vàng kem */
                        pvCream: '#FAF6F0',     /* Nền kem ấm */
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        serif: ['Playfair Display', 'serif'],
                    }
                }
            }
        }
    </script>

    <style>
        /* Khóa tràn viền tuyệt đối và căn chuẩn khung hình trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            margin: 0;
            padding: 0;
            width: 100%;
            max-width: 100vw;
            overflow-x: hidden;
            background-color: #FAF6F0;
            color: #262626;
            font-family: 'Inter', sans-serif;
            scroll-behavior: smooth;
        }

        /* Chiều ngang giao diện trên máy tính bằng 95% kích thước màn hình máy tính */
        .flatsome-container {
            width: 95%;
            max-width: 95%;
            margin-left: auto;
            margin-right: auto;
        }
        @media (max-width: 767px) {
            .flatsome-container {
                width: 94%;
                max-width: 94%;
            }
        }

        /* Tiêu đề Section kiểu Flatsome (Section Title) */
        .section-title-container {
            margin-bottom: 1.5rem;
        }
        .section-title-main {
            position: relative;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
        }
        .section-title-main::before,
        .section-title-main::after {
            content: "";
            flex: 1;
            height: 1px;
            background: linear-gradient(90deg, transparent, #C9972C, transparent);
            max-width: 160px;
        }

        /* Badge % giảm giá chuẩn Flatsome góc trên bên trái */
        .flatsome-onsale-badge {
            position: absolute;
            top: 8px;
            left: 8px;
            z-index: 10;
            background: #8B1A1A;
            border: 1.5px solid #F7E7C4;
            color: #ffffff;
            width: 40px;
            height: 40px;
            border-radius: 9999px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: 700;
            font-size: 11.5px;
            line-height: 1;
            box-shadow: 0 2px 6px rgba(0, 0, 0, 0.22);
        }
        @media (min-width: 768px) {
            .flatsome-onsale-badge {
                width: 44px;
                height: 44px;
                font-size: 12.5px;
                top: 10px;
                left: 10px;
            }
        }

        /* Tên danh mục viết liền trên 1 hàng, không bị ngắt chữ xuống dòng */
        .cat-pill-item {
            white-space: nowrap;
            display: inline-flex;
            align-items: center;
            justify-content: center;
            transition: all 0.2s ease;
        }

        /* Hiệu ứng nút liên hệ nổi rung nhẹ */
        @keyframes pulseRing {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(139, 26, 26, 0.6); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(139, 26, 26, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(139, 26, 26, 0); }
        }
        .float-btn-pulse {
            animation: pulseRing 2s infinite;
        }

        /* Ẩn thanh cuộn phụ nhưng vẫn giữ cuộn mượt nếu cần */
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .no-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }
    </style>
</head>
<body class="antialiased selection:bg-pvRed selection:text-white">

    <!-- =====================================================================
         FLATSOME TOP BAR (Đơn giản, không hiển thị thanh UX Builder Admin)
         ===================================================================== -->
    <div id="top-bar" class="bg-pvRedDark text-pvGoldLight text-[11px] md:text-xs py-1.5 border-b border-pvGold/30">
        <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-2 truncate">
                <i class="fa-solid fa-crown text-pvGold"></i>
                <span class="font-medium truncate">PHÚC VINH - MÂM QUẢ CƯỚI ĐÀ NẴNG | KẾT MÂM QUẢ & DECOR CỔNG RỒNG PHỤNG TRỌN GÓI</span>
            </div>
            <div class="hidden lg:flex items-center gap-4 text-[11.5px] shrink-0">
                <span><i class="fa-solid fa-location-dot text-pvGold mr-1"></i>142 Bùi Tá Hán, P. Ngũ Hành Sơn, Tp. Đà Nẵng</span>
                <span>|</span>
                <span><i class="fa-solid fa-globe text-pvGold mr-1"></i>phucvinh.com</span>
            </div>
        </div>
    </div>

    <!-- =====================================================================
         FLATSOME HEADER (Logo nhỏ gọn, danh mục viết liền trên 1 hàng, KHÔNG để nút Gọi ngay)
         ===================================================================== -->
    <header id="header" class="sticky top-0 z-40 bg-white/95 backdrop-blur-md shadow-sm border-b border-pvGold/25">
        <div class="flatsome-container py-2 md:py-2.5">
            <div class="flex items-center justify-between gap-2 md:gap-4">
                
                <!-- Nút mở Menu Điện Thoại -->
                <button onclick="toggleMobileMenu()" aria-label="Menu" class="md:hidden w-9 h-9 rounded-lg border border-pvRed/20 text-pvRed flex items-center justify-center shrink-0 hover:bg-pvRedLight">
                    <i class="fa-solid fa-bars text-base"></i>
                </button>

                <!-- Logo thu gọn nhỏ lại + Tên thương hiệu -->
                <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 group">
                    <div class="w-10 h-10 md:w-12 md:h-12 rounded-full overflow-hidden border-2 border-pvGold shadow-sm bg-pvRed flex items-center justify-center shrink-0">
                        <img src="https://drive.google.com/thumbnail?id=1xP2iyt2jNC0uVEufM3pyHIr3Mj-kDWRF&sz=w400"
                             onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1xP2iyt2jNC0uVEufM3pyHIr3Mj-kDWRF';"
                             alt="Logo Phúc Vinh - Mâm Quả Cưới Đà Nẵng"
                             class="w-full h-full object-cover">
                    </div>
                    <div class="leading-tight">
                        <span class="block font-serif font-bold text-pvRed text-sm sm:text-base md:text-lg tracking-tight">PHÚC VINH</span>
                        <span class="block text-[10px] md:text-[11px] font-semibold text-amber-800 uppercase tracking-wider">Mâm Quả Cưới Đà Nẵng</span>
                    </div>
                </a>

                <!-- Menu chính & Danh mục sản phẩm trên máy tính (Chữ nhỏ gọn, viết liền trên 1 hàng hoặc tự xuống hàng 2 nguyên cụm) -->
                <nav class="hidden md:flex flex-wrap items-center justify-center gap-x-1.5 lg:gap-x-2.5 gap-y-1 flex-1 px-2">
                    <a href="#trang-chu" class="cat-pill-item px-2.5 py-1 rounded-md text-[12.5px] font-semibold text-pvRed bg-pvRedLight hover:bg-pvRed hover:text-white">
                        Trang chủ
                    </a>
                    <a href="#gioi-thieu" class="cat-pill-item px-2.5 py-1 rounded-md text-[12.5px] font-medium text-neutral-700 hover:text-pvRed hover:bg-pvRedLight">
                        Giới thiệu
                    </a>
                    <button onclick="filterCategory('Mâm quả', true)" class="cat-pill-item px-2.5 py-1 rounded-md text-[12.5px] font-medium text-neutral-700 hover:text-pvRed hover:bg-pvRedLight">
                        Mâm quả
                    </button>
                    <button onclick="filterCategory('Cổng cưới', true)" class="cat-pill-item px-2.5 py-1 rounded-md text-[12.5px] font-medium text-neutral-700 hover:text-pvRed hover:bg-pvRedLight">
                        Cổng cưới
                    </button>
                    <button onclick="filterCategory('Gia tiên', true)" class="cat-pill-item px-2.5 py-1 rounded-md text-[12.5px] font-medium text-neutral-700 hover:text-pvRed hover:bg-pvRedLight">
                        Gia tiên
                    </button>
                    <!-- Dropdown Rồng Phụng giống web mẫu Rồng Phụng Phương Nam -->
                    <div class="relative group">
                        <button onclick="filterCategory('Rồng phụng', true)" class="cat-pill-item px-2.5 py-1 rounded-md text-[12.5px] font-medium text-neutral-700 hover:text-pvRed hover:bg-pvRedLight">
                            Rồng phụng <i class="fa-solid fa-chevron-down text-[9px] ml-1 opacity-75"></i>
                        </button>
                        <div class="absolute left-0 top-full pt-1 hidden group-hover:block z-50">
                            <div class="bg-white rounded-lg shadow-xl border border-pvGold/30 py-1.5 min-w-[230px]">
                                <button onclick="filterCategory('Rồng Phụng tạo hình từ trái cây', true)" class="w-full text-left px-3.5 py-2 text-[12.5px] text-neutral-700 hover:bg-pvRedLight hover:text-pvRed whitespace-nowrap block">
                                    Rồng Phụng tạo hình từ trái cây
                                </button>
                                <button onclick="filterCategory('Rồng Phụng xốp mỹ thuật', true)" class="w-full text-left px-3.5 py-2 text-[12.5px] text-neutral-700 hover:bg-pvRedLight hover:text-pvRed whitespace-nowrap block">
                                    Rồng Phụng xốp mỹ thuật
                                </button>
                            </div>
                        </div>
                    </div>
                    <button onclick="filterCategory('Hoa cưới', true)" class="cat-pill-item px-2.5 py-1 rounded-md text-[12.5px] font-medium text-neutral-700 hover:text-pvRed hover:bg-pvRedLight">
                        Hoa cưới
                    </button>
                    <button onclick="filterCategory('Dạm Ngõ', true)" class="cat-pill-item px-2.5 py-1 rounded-md text-[12.5px] font-medium text-neutral-700 hover:text-pvRed hover:bg-pvRedLight">
                        Dạm Ngõ
                    </button>
                    <a href="#dich-vu" class="cat-pill-item px-2.5 py-1 rounded-md text-[12.5px] font-medium text-neutral-700 hover:text-pvRed hover:bg-pvRedLight">
                        Dịch vụ
                    </a>
                    <a href="#tin-tuc" class="cat-pill-item px-2.5 py-1 rounded-md text-[12.5px] font-medium text-neutral-700 hover:text-pvRed hover:bg-pvRedLight">
                        Tin tức
                    </a>
                    <a href="#bao-gia" class="cat-pill-item px-2.5 py-1 rounded-md text-[12.5px] font-medium text-neutral-700 hover:text-pvRed hover:bg-pvRedLight">
                        Báo giá
                    </a>
                    <a href="#lien-he-map" class="cat-pill-item px-2.5 py-1 rounded-md text-[12.5px] font-medium text-neutral-700 hover:text-pvRed hover:bg-pvRedLight">
                        Liên hệ
                    </a>
                </nav>

                <!-- Công cụ tìm kiếm & Giỏ hàng nhỏ gọn (Không để nút gọi ngay để tránh tràn viền) -->
                <div class="flex items-center gap-1.5 shrink-0">
                    <button onclick="toggleSearchModal()" title="Tìm kiếm sản phẩm" class="w-9 h-9 rounded-full bg-pvCream hover:bg-pvRedLight text-pvRed flex items-center justify-center border border-pvGold/30 transition">
                        <i class="fa-solid fa-magnifying-glass text-xs"></i>
                    </button>
                    <button onclick="openQuoteScroll()" title="Giỏ báo giá" class="relative w-9 h-9 rounded-full bg-pvCream hover:bg-pvRedLight text-pvRed flex items-center justify-center border border-pvGold/30 transition">
                        <i class="fa-solid fa-bag-shopping text-xs"></i>
                        <span id="cart-count-badge" class="absolute -top-1 -right-1 w-4 h-4 rounded-full bg-pvRed text-white text-[10px] font-bold flex items-center justify-center">0</span>
                    </button>
                </div>

            </div>
        </div>

        <!-- Thanh danh mục trượt nhanh trên Điện thoại (Viết liền trên 1 dòng, chữ nhỏ gọn) -->
        <div class="md:hidden bg-pvCream border-t border-pvGold/20 py-1.5">
            <div class="flatsome-container flex items-center gap-1.5 overflow-x-auto no-scrollbar">
                <button onclick="filterCategory('all', true)" class="cat-pill-item px-2.5 py-1 rounded-full text-[11.5px] font-semibold bg-pvRed text-white shrink-0">
                    Tất cả
                </button>
                <button onclick="filterCategory('Mâm quả', true)" class="cat-pill-item px-2.5 py-1 rounded-full text-[11.5px] font-medium bg-white text-neutral-800 border border-pvGold/30 shrink-0">
                    Mâm quả
                </button>
                <button onclick="filterCategory('Cổng cưới', true)" class="cat-pill-item px-2.5 py-1 rounded-full text-[11.5px] font-medium bg-white text-neutral-800 border border-pvGold/30 shrink-0">
                    Cổng cưới
                </button>
                <button onclick="filterCategory('Gia tiên', true)" class="cat-pill-item px-2.5 py-1 rounded-full text-[11.5px] font-medium bg-white text-neutral-800 border border-pvGold/30 shrink-0">
                    Gia tiên
                </button>
                <button onclick="filterCategory('Rồng phụng', true)" class="cat-pill-item px-2.5 py-1 rounded-full text-[11.5px] font-medium bg-white text-neutral-800 border border-pvGold/30 shrink-0">
                    Rồng phụng
                </button>
                <button onclick="filterCategory('Hoa cưới', true)" class="cat-pill-item px-2.5 py-1 rounded-full text-[11.5px] font-medium bg-white text-neutral-800 border border-pvGold/30 shrink-0">
                    Hoa cưới
                </button>
                <button onclick="filterCategory('Dạm Ngõ', true)" class="cat-pill-item px-2.5 py-1 rounded-full text-[11.5px] font-medium bg-white text-neutral-800 border border-pvGold/30 shrink-0">
                    Dạm Ngõ
                </button>
            </div>
        </div>
    </header>

    <!-- Menu Drawer trên Điện thoại -->
    <div id="mobile-menu-drawer" class="fixed inset-0 z-50 hidden">
        <div onclick="toggleMobileMenu()" class="absolute inset-0 bg-black/60 backdrop-blur-xs"></div>
        <div class="relative w-72 max-w-[82vw] h-full bg-white shadow-2xl flex flex-col justify-between overflow-y-auto">
            <div>
                <div class="p-4 bg-pvRed text-white flex items-center justify-between">
                    <div class="flex items-center gap-2.5">
                        <img src="https://drive.google.com/thumbnail?id=1xP2iyt2jNC0uVEufM3pyHIr3Mj-kDWRF&sz=w200"
                             onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1xP2iyt2jNC0uVEufM3pyHIr3Mj-kDWRF';"
                             alt="Logo" class="w-9 h-9 rounded-full border border-pvGold object-cover bg-white">
                        <div>
                            <div class="font-serif font-bold text-sm">PHÚC VINH</div>
                            <div class="text-[10px] text-pvGoldLight">phucvinh.com</div>
                        </div>
                    </div>
                    <button onclick="toggleMobileMenu()" class="w-8 h-8 rounded-full bg-white/10 text-white flex items-center justify-center">
                        <i class="fa-solid fa-xmark"></i>
                    </button>
                </div>

                <div class="p-3 divide-y divide-neutral-100 text-sm">
                    <div class="py-2 px-2 font-bold text-xs uppercase text-pvRed tracking-wider">Danh mục sản phẩm</div>
                    <button onclick="filterCategory('Mâm quả', true); toggleMobileMenu();" class="w-full text-left py-2.5 px-3 hover:bg-pvRedLight rounded-lg font-medium flex items-center justify-between">
                        <span>Mâm quả</span> <i class="fa-solid fa-angle-right text-xs text-neutral-400"></i>
                    </button>
                    <button onclick="filterCategory('Cổng cưới', true); toggleMobileMenu();" class="w-full text-left py-2.5 px-3 hover:bg-pvRedLight rounded-lg font-medium flex items-center justify-between">
                        <span>Cổng cưới</span> <i class="fa-solid fa-angle-right text-xs text-neutral-400"></i>
                    </button>
                    <button onclick="filterCategory('Gia tiên', true); toggleMobileMenu();" class="w-full text-left py-2.5 px-3 hover:bg-pvRedLight rounded-lg font-medium flex items-center justify-between">
                        <span>Gia tiên</span> <i class="fa-solid fa-angle-right text-xs text-neutral-400"></i>
                    </button>
                    <button onclick="filterCategory('Rồng phụng', true); toggleMobileMenu();" class="w-full text-left py-2.5 px-3 hover:bg-pvRedLight rounded-lg font-medium flex items-center justify-between">
                        <span>Rồng phụng</span> <i class="fa-solid fa-angle-right text-xs text-neutral-400"></i>
                    </button>
                    <button onclick="filterCategory('Rồng Phụng tạo hình từ trái cây', true); toggleMobileMenu();" class="w-full text-left py-2 pl-6 pr-3 text-xs text-neutral-600 hover:bg-pvRedLight rounded-lg flex items-center justify-between">
                        <span>• Rồng Phụng tạo hình từ trái cây</span>
                    </button>
                    <button onclick="filterCategory('Rồng Phụng xốp mỹ thuật', true); toggleMobileMenu();" class="w-full text-left py-2 pl-6 pr-3 text-xs text-neutral-600 hover:bg-pvRedLight rounded-lg flex items-center justify-between">
                        <span>• Rồng Phụng xốp mỹ thuật</span>
                    </button>
                    <button onclick="filterCategory('Hoa cưới', true); toggleMobileMenu();" class="w-full text-left py-2.5 px-3 hover:bg-pvRedLight rounded-lg font-medium flex items-center justify-between">
                        <span>Hoa cưới</span> <i class="fa-solid fa-angle-right text-xs text-neutral-400"></i>
                    </button>
                    <button onclick="filterCategory('Dạm Ngõ', true); toggleMobileMenu();" class="w-full text-left py-2.5 px-3 hover:bg-pvRedLight rounded-lg font-medium flex items-center justify-between">
                        <span>Dạm Ngõ</span> <i class="fa-solid fa-angle-right text-xs text-neutral-400"></i>
                    </button>

                    <div class="py-2 px-2 pt-4 font-bold text-xs uppercase text-pvRed tracking-wider">Chuyên mục Website</div>
                    <a href="#gioi-thieu" onclick="toggleMobileMenu()" class="block py-2.5 px-3 hover:bg-pvRedLight rounded-lg font-medium">Giới thiệu Phúc Vinh</a>
                    <a href="#dich-vu" onclick="toggleMobileMenu()" class="block py-2.5 px-3 hover:bg-pvRedLight rounded-lg font-medium">Dịch vụ cưới hỏi trọn gói</a>
                    <a href="#bao-gia" onclick="toggleMobileMenu()" class="block py-2.5 px-3 hover:bg-pvRedLight rounded-lg font-medium">Yêu cầu & Nhận báo giá</a>
                    <a href="#tin-tuc" onclick="toggleMobileMenu()" class="block py-2.5 px-3 hover:bg-pvRedLight rounded-lg font-medium">Tin tức & Cẩm nang cưới</a>
                    <a href="#lien-he-map" onclick="toggleMobileMenu()" class="block py-2.5 px-3 hover:bg-pvRedLight rounded-lg font-medium">Bản đồ & Fanpage</a>
                </div>
            </div>

            <div class="p-4 bg-pvCream border-t border-pvGold/30 text-xs space-y-1.5">
                <div class="font-bold text-pvRed">PHÚC VINH - MÂM QUẢ CƯỚI ĐÀ NẴNG</div>
                <div class="text-neutral-600"><i class="fa-solid fa-location-dot text-pvRed mr-1.5"></i>142 Bùi Tá Hán, P. Ngũ Hành Sơn, Tp. Đà Nẵng</div>
                <div class="text-neutral-600"><i class="fa-solid fa-phone text-pvRed mr-1.5"></i>0934.153.598</div>
            </div>
        </div>
    </div>

    <!-- =====================================================================
         FLATSOME SLIDER SECTION: 2 ẢNH BANNER TỰ TRƯỢT KÍCH THƯỚC BẰNG NHAU
         - Thiết kế riêng 2 ảnh banner Máy Tính và 2 ảnh banner Điện Thoại
         - Chữ nhỏ gọn nằm trọn bên trong vùng an toàn của ảnh banner, không tràn viền
         ===================================================================== -->
    <section id="trang-chu" class="py-3 md:py-4">
        <div class="flatsome-container">
            <div class="relative rounded-2xl overflow-hidden shadow-lg border-2 border-pvGold/40 bg-pvRedDark">

                <!-- ================== BANNER TRÊN MÁY TÍNH (2 SLIDE KÍCH THƯỚC BẰNG NHAU 420px) ================== -->
                <div class="hidden md:block relative w-full h-[420px] overflow-hidden">
                    
                    <!-- DESKTOP SLIDE 1 -->
                    <div class="banner-slide-desktop absolute inset-0 w-full h-full transition-opacity duration-700 opacity-100 z-10">
                        <div class="w-full h-full bg-gradient-to-r from-[#590B0B] via-[#8B1A1A] to-[#4A0808] grid grid-cols-12 items-center px-10 lg:px-14">
                            <!-- Cột chữ bên trái: chỉnh chữ nhỏ gọn nằm hết trong ảnh banner -->
                            <div class="col-span-7 pr-6 text-white space-y-2.5">
                                <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-pvGold/25 border border-pvGold text-pvGoldLight text-xs font-semibold">
                                    <i class="fa-solid fa-star text-pvGold"></i> WEBSITE CHÍNH THỨC: PHUCVINH.COM
                                </div>
                                <h1 class="font-serif font-bold text-xl lg:text-2xl xl:text-[28px] leading-snug text-pvGoldLight uppercase">
                                    Phúc Vinh - Mâm Quả Cưới Đà Nẵng
                                </h1>
                                <p class="text-xs lg:text-sm font-semibold text-white/95 bg-black/25 border-l-4 border-pvGold px-3.5 py-2 rounded-r-lg leading-relaxed">
                                    CHUYÊN : KẾT MÂM QUẢ CƯỚI - HỎI + DECOR - TRANG TRÍ CỔNG RỒNG PHỤNG GIÁ RẺ ĐÀ NẴNG TRỌN GÓI
                                </p>
                                <div class="grid grid-cols-2 gap-2 pt-1 text-xs text-pvGoldLight/90">
                                    <div class="flex items-center gap-2"><i class="fa-solid fa-circle-check text-pvGold"></i> Mẫu mã truyền thống & hiện đại</div>
                                    <div class="flex items-center gap-2"><i class="fa-solid fa-circle-check text-pvGold"></i> Lễ vật tươi mới, chuẩn phong tục</div>
                                    <div class="flex items-center gap-2"><i class="fa-solid fa-location-dot text-pvGold"></i> 142 Bùi Tá Hán, Ngũ Hành Sơn</div>
                                    <div class="flex items-center gap-2"><i class="fa-solid fa-phone-volume text-pvGold"></i> Hotline/Zalo: 0934.153.598</div>
                                </div>
                                <div class="pt-2 flex items-center gap-3">
                                    <a href="#san-pham" class="px-4 py-2 rounded-lg bg-pvGold hover:bg-amber-500 text-neutral-900 font-bold text-xs uppercase tracking-wide shadow transition">
                                        Xem Mẫu Mâm Quả
                                    </a>
                                    <a href="#bao-gia" class="px-4 py-2 rounded-lg bg-white/15 hover:bg-white/25 text-white border border-white/40 font-semibold text-xs uppercase tracking-wide transition">
                                        Nhận Báo Giá Ngay
                                    </a>
                                </div>
                            </div>
                            <!-- Cột ảnh thực tế bên phải -->
                            <div class="col-span-5 grid grid-cols-2 gap-3 items-center">
                                <div class="rounded-xl overflow-hidden border-2 border-pvGold shadow-xl h-[320px]">
                                    <img src="https://drive.google.com/thumbnail?id=1wM960UqiGaU4DD0Is6PEZNbS7K8uqMnC&sz=w800"
                                         onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1wM960UqiGaU4DD0Is6PEZNbS7K8uqMnC';"
                                         alt="Mâm Quả Cưới Phúc Vinh Đà Nẵng"
                                         class="w-full h-full object-cover">
                                </div>
                                <div class="space-y-3">
                                    <div class="rounded-xl overflow-hidden border-2 border-pvGold shadow-xl h-[152px]">
                                        <img src="https://drive.google.com/thumbnail?id=1m3TYo8P2eRlqJ6iuW5Juu_qAIJDALYvm&sz=w800"
                                             onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1m3TYo8P2eRlqJ6iuW5Juu_qAIJDALYvm';"
                                             alt="Tráp Cưới Rồng Phụng"
                                             class="w-full h-full object-cover">
                                    </div>
                                    <div class="rounded-xl overflow-hidden border-2 border-pvGold shadow-xl h-[152px]">
                                        <img src="https://drive.google.com/thumbnail?id=1tvcwXRKik38P2x4hVESlQ5p0rUUV0fRD&sz=w800"
                                             onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1tvcwXRKik38P2x4hVESlQ5p0rUUV0fRD';"
                                             alt="Cổng Cưới Rồng Phụng Đà Nẵng"
                                             class="w-full h-full object-cover">
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- DESKTOP SLIDE 2 (Kích thước 420px bằng hệt Slide 1) -->
                    <div class="banner-slide-desktop absolute inset-0 w-full h-full transition-opacity duration-700 opacity-0 z-0">
                        <div class="w-full h-full bg-gradient-to-r from-[#420909] via-[#7A1515] to-[#590B0B] grid grid-cols-12 items-center px-10 lg:px-14">
                            <!-- Cột chữ bên trái: chữ nhỏ gọn nằm hết trong ảnh banner -->
                            <div class="col-span-7 pr-6 text-white space-y-2.5">
                                <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-pvGold/25 border border-pvGold text-pvGoldLight text-xs font-semibold">
                                    <i class="fa-solid fa-gem text-pvGold"></i> NGHỆ THUẬT CƯỚI HỎI TRUYỀN THỐNG & HIỆN ĐẠI
                                </div>
                                <h2 class="font-serif font-bold text-xl lg:text-2xl xl:text-[28px] leading-snug text-pvGoldLight uppercase">
                                    Cổng Cưới Rồng Phụng & Gia Tiên Độc Bản
                                </h2>
                                <p class="text-xs lg:text-sm font-semibold text-white/95 bg-black/25 border-l-4 border-pvGold px-3.5 py-2 rounded-r-lg leading-relaxed">
                                    Biến từng mâm quả cưới hỏi & không gian gia tiên thành tác phẩm nghệ thuật sang trọng, chỉn chu cho ngày trọng đại tại Đà Nẵng.
                                </p>
                                <div class="grid grid-cols-2 gap-2 pt-1 text-xs text-pvGoldLight/90">
                                    <div class="flex items-center gap-2"><i class="fa-solid fa-dragon text-pvGold"></i> Rồng Phụng trái cây & xốp mỹ thuật</div>
                                    <div class="flex items-center gap-2"><i class="fa-solid fa-archway text-pvGold"></i> Thi công cổng cưới & gia tiên tận nơi</div>
                                    <div class="flex items-center gap-2"><i class="fa-solid fa-location-dot text-pvGold"></i> 142 Bùi Tá Hán, P. Ngũ Hành Sơn</div>
                                    <div class="flex items-center gap-2"><i class="fa-solid fa-phone-volume text-pvGold"></i> Tư vấn 24/7: 0934.153.598</div>
                                </div>
                                <div class="pt-2 flex items-center gap-3">
                                    <button onclick="filterCategory('Rồng phụng', true)" class="px-4 py-2 rounded-lg bg-pvGold hover:bg-amber-500 text-neutral-900 font-bold text-xs uppercase tracking-wide shadow transition">
                                        Khám Phá Rồng Phụng
                                    </button>
                                    <a href="#lien-he-map" class="px-4 py-2 rounded-lg bg-white/15 hover:bg-white/25 text-white border border-white/40 font-semibold text-xs uppercase tracking-wide transition">
                                        Xem Bản Đồ Cửa Hàng
                                    </a>
                                </div>
                            </div>
                            <!-- Cột ảnh thực tế bên phải -->
                            <div class="col-span-5 grid grid-cols-2 gap-3 items-center">
                                <div class="rounded-xl overflow-hidden border-2 border-pvGold shadow-xl h-[320px]">
                                    <img src="https://drive.google.com/thumbnail?id=18Vgd8A-Ti51bzjEg6vPH8VaLol9NgACK&sz=w800"
                                         onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/18Vgd8A-Ti51bzjEg6vPH8VaLol9NgACK';"
                                         alt="Cổng Rồng Phụng Phúc Vinh"
                                         class="w-full h-full object-cover">
                                </div>
                                <div class="space-y-3">
                                    <div class="rounded-xl overflow-hidden border-2 border-pvGold shadow-xl h-[152px]">
                                        <img src="https://drive.google.com/thumbnail?id=1FX5nU93YLVN6e45pnB1PzEjFjqyS1pOb&sz=w800"
                                             onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1FX5nU93YLVN6e45pnB1PzEjFjqyS1pOb';"
                                             alt="Trang Trí Gia Tiên"
                                             class="w-full h-full object-cover">
                                    </div>
                                    <div class="rounded-xl overflow-hidden border-2 border-pvGold shadow-xl h-[152px]">
                                        <img src="https://drive.google.com/thumbnail?id=15kkgHhgr7jLgF5k-Kv9IAH_JfiMs6s31&sz=w800"
                                             onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/15kkgHhgr7jLgF5k-Kv9IAH_JfiMs6s31';"
                                             alt="Tráp Dạm Ngõ Đà Nẵng"
                                             class="w-full h-full object-cover">
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                </div>

                <!-- ================== BANNER TRÊN ĐIỆN THOẠI (THIẾT KẾ MỚI KHÁC VỚI MÁY TÍNH, CÙNG CHIỀU CAO 350px, CHỮ NHỎ GỌN KHÔNG TRÀN VIỀN) ================== -->
                <div class="block md:hidden relative w-full h-[350px] overflow-hidden">
                    
                    <!-- MOBILE SLIDE 1 -->
                    <div class="banner-slide-mobile absolute inset-0 w-full h-full transition-opacity duration-700 opacity-100 z-10">
                        <div class="w-full h-full bg-gradient-to-b from-[#681010] via-[#8B1A1A] to-[#4A0808] p-3.5 flex flex-col justify-between text-center text-white">
                            <!-- Khối chữ nhỏ gọn nằm trọn trong ảnh banner điện thoại -->
                            <div class="space-y-1 px-2 pt-0.5">
                                <span class="inline-block px-2.5 py-0.5 rounded-full bg-pvGold/25 border border-pvGold text-pvGoldLight text-[10px] font-bold">
                                    PHUCVINH.COM • ĐÀ NẴNG
                                </span>
                                <h2 class="font-serif font-bold text-[15px] leading-tight text-pvGoldLight uppercase">
                                    Phúc Vinh - Mâm Quả Cưới Đà Nẵng
                                </h2>
                                <p class="text-[10.5px] leading-snug text-white/95 bg-black/25 rounded-lg px-2.5 py-1.5 border border-pvGold/30">
                                    CHUYÊN: KẾT MÂM QUẢ CƯỚI - HỎI + DECOR - TRANG TRÍ CỔNG RỒNG PHỤNG GIÁ RẺ ĐÀ NẴNG TRỌN GÓI
                                </p>
                            </div>

                            <!-- 3 ảnh sản phẩm thực tế cân đối giữa banner điện thoại -->
                            <div class="grid grid-cols-3 gap-2 px-1 my-1">
                                <div class="h-28 rounded-lg overflow-hidden border border-pvGold shadow">
                                    <img src="https://drive.google.com/thumbnail?id=1wM960UqiGaU4DD0Is6PEZNbS7K8uqMnC&sz=w400"
                                         onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1wM960UqiGaU4DD0Is6PEZNbS7K8uqMnC';"
                                         alt="Mâm quả 1" class="w-full h-full object-cover">
                                </div>
                                <div class="h-28 rounded-lg overflow-hidden border border-pvGold shadow">
                                    <img src="https://drive.google.com/thumbnail?id=1m3TYo8P2eRlqJ6iuW5Juu_qAIJDALYvm&sz=w400"
                                         onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1m3TYo8P2eRlqJ6iuW5Juu_qAIJDALYvm';"
                                         alt="Mâm quả 2" class="w-full h-full object-cover">
                                </div>
                                <div class="h-28 rounded-lg overflow-hidden border border-pvGold shadow">
                                    <img src="https://drive.google.com/thumbnail?id=1tvcwXRKik38P2x4hVESlQ5p0rUUV0fRD&sz=w400"
                                         onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1tvcwXRKik38P2x4hVESlQ5p0rUUV0fRD';"
                                         alt="Mâm quả 3" class="w-full h-full object-cover">
                                </div>
                            </div>

                            <!-- Chân banner mobile gọn gàng -->
                            <div class="text-[10.5px] text-pvGoldLight pb-3">
                                <div><i class="fa-solid fa-location-dot text-pvGold mr-1"></i>142 Bùi Tá Hán, P. Ngũ Hành Sơn, Đà Nẵng</div>
                                <div class="font-bold text-white mt-0.5"><i class="fa-solid fa-phone text-pvGold mr-1"></i>Hotline/Zalo: 0934.153.598</div>
                            </div>
                        </div>
                    </div>

                    <!-- MOBILE SLIDE 2 (Kích thước 350px bằng hệt Mobile Slide 1) -->
                    <div class="banner-slide-mobile absolute inset-0 w-full h-full transition-opacity duration-700 opacity-0 z-0">
                        <div class="w-full h-full bg-gradient-to-b from-[#4A0808] via-[#7A1515] to-[#590B0B] p-3.5 flex flex-col justify-between text-center text-white">
                            <div class="space-y-1 px-2 pt-0.5">
                                <span class="inline-block px-2.5 py-0.5 rounded-full bg-pvGold/25 border border-pvGold text-pvGoldLight text-[10px] font-bold">
                                    TRỌN GÓI UY TÍN - GIÁ XƯỞNG
                                </span>
                                <h2 class="font-serif font-bold text-[15px] leading-tight text-pvGoldLight uppercase">
                                    Cổng Rồng Phụng & Trang Trí Gia Tiên
                                </h2>
                                <p class="text-[10.5px] leading-snug text-white/95 bg-black/25 rounded-lg px-2.5 py-1.5 border border-pvGold/30">
                                    Kết mâm quả rồng phụng trái cây, xốp mỹ thuật, tráp dạm ngõ & cổng hoa cưới tận nhà tại Đà Nẵng.
                                </p>
                            </div>

                            <div class="grid grid-cols-3 gap-2 px-1 my-1">
                                <div class="h-28 rounded-lg overflow-hidden border border-pvGold shadow">
                                    <img src="https://drive.google.com/thumbnail?id=18Vgd8A-Ti51bzjEg6vPH8VaLol9NgACK&sz=w400"
                                         onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/18Vgd8A-Ti51bzjEg6vPH8VaLol9NgACK';"
                                         alt="Rồng phụng 1" class="w-full h-full object-cover">
                                </div>
                                <div class="h-28 rounded-lg overflow-hidden border border-pvGold shadow">
                                    <img src="https://drive.google.com/thumbnail?id=1FX5nU93YLVN6e45pnB1PzEjFjqyS1pOb&sz=w400"
                                         onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1FX5nU93YLVN6e45pnB1PzEjFjqyS1pOb';"
                                         alt="Gia tiên 2" class="w-full h-full object-cover">
                                </div>
                                <div class="h-28 rounded-lg overflow-hidden border border-pvGold shadow">
                                    <img src="https://drive.google.com/thumbnail?id=15kkgHhgr7jLgF5k-Kv9IAH_JfiMs6s31&sz=w400"
                                         onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/15kkgHhgr7jLgF5k-Kv9IAH_JfiMs6s31';"
                                         alt="Tráp cưới 3" class="w-full h-full object-cover">
                                </div>
                            </div>

                            <div class="text-[10.5px] text-pvGoldLight pb-3">
                                <div><i class="fa-solid fa-location-dot text-pvGold mr-1"></i>142 Bùi Tá Hán, P. Ngũ Hành Sơn, Đà Nẵng</div>
                                <div class="font-bold text-white mt-0.5"><i class="fa-solid fa-phone text-pvGold mr-1"></i>Đặt lịch tư vấn: 0934.153.598</div>
                            </div>
                        </div>
                    </div>

                </div>

                <!-- Nút điều hướng 2 bên & chấm tròn chuyển Slide -->
                <button onclick="prevBannerSlide()" aria-label="Slide trước" class="absolute left-2 md:left-3 top-1/2 -translate-y-1/2 z-20 w-8 h-8 md:w-9 md:h-9 rounded-full bg-black/35 hover:bg-pvGold text-white hover:text-neutral-900 flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-left text-xs"></i>
                </button>
                <button onclick="nextBannerSlide()" aria-label="Slide tiếp" class="absolute right-2 md:right-3 top-1/2 -translate-y-1/2 z-20 w-8 h-8 md:w-9 md:h-9 rounded-full bg-black/35 hover:bg-pvGold text-white hover:text-neutral-900 flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-right text-xs"></i>
                </button>

                <div class="absolute bottom-2 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                    <button onclick="goToBannerSlide(0)" id="banner-dot-0" class="w-6 h-2 rounded-full bg-pvGold transition-all"></button>
                    <button onclick="goToBannerSlide(1)" id="banner-dot-1" class="w-2 h-2 rounded-full bg-white/50 transition-all"></button>
                </div>

            </div>
        </div>
    </section>

    <!-- =====================================================================
         FLATSOME SECTION: DANH MỤC SẢN PHẨM TRANG CHỦ (Giống Rồng Phụng Phương Nam)
         - Chữ danh mục ở trang chủ nhỏ gọn, viết liền trên 1 hàng, tối ưu trên máy tính & điện thoại
         ===================================================================== -->
    <section id="danh-muc-trang-chu" class="py-5 md:py-7">
        <div class="flatsome-container">
            <div class="section-title-container text-center">
                <div class="section-title-main">
                    <h2 class="px-4 font-serif font-bold text-lg md:text-2xl text-pvRed uppercase">
                        Danh Mục Sản Phẩm
                    </h2>
                </div>
                <p class="text-xs md:text-sm text-neutral-600 mt-1">
                    Phúc Vinh – Biến Từng Mâm Quả Thành Một Tác Phẩm Nghệ Thuật Dành Riêng Cho Bạn!
                </p>
            </div>

            <!-- Danh mục hình ảnh tròn chuẩn Flatsome UX Builder: Điện thoại 4 cột gọn đẹp, Máy tính 8 cột nằm gọn 1 hàng -->
            <div class="grid grid-cols-4 lg:grid-cols-8 gap-2 md:gap-3">
                
                <!-- 1. Mâm quả -->
                <button onclick="filterCategory('Mâm quả', true)" class="group bg-white rounded-xl p-2 md:p-2.5 border border-pvGold/30 shadow-xs hover:shadow-md hover:border-pvRed transition flex flex-col items-center text-center">
                    <div class="w-14 h-14 sm:w-16 sm:h-16 md:w-18 md:h-18 rounded-full overflow-hidden border-2 border-pvGold mb-1.5">
                        <img src="https://drive.google.com/thumbnail?id=1wM960UqiGaU4DD0Is6PEZNbS7K8uqMnC&sz=w400"
                             onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1wM960UqiGaU4DD0Is6PEZNbS7K8uqMnC';"
                             alt="Mâm quả" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <span class="cat-pill-item text-[11px] md:text-[11.5px] font-bold text-neutral-800 group-hover:text-pvRed">Mâm quả</span>
                </button>

                <!-- 2. Cổng cưới -->
                <button onclick="filterCategory('Cổng cưới', true)" class="group bg-white rounded-xl p-2 md:p-2.5 border border-pvGold/30 shadow-xs hover:shadow-md hover:border-pvRed transition flex flex-col items-center text-center">
                    <div class="w-14 h-14 sm:w-16 sm:h-16 md:w-18 md:h-18 rounded-full overflow-hidden border-2 border-pvGold mb-1.5">
                        <img src="https://drive.google.com/thumbnail?id=1tvcwXRKik38P2x4hVESlQ5p0rUUV0fRD&sz=w400"
                             onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1tvcwXRKik38P2x4hVESlQ5p0rUUV0fRD';"
                             alt="Cổng cưới" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <span class="cat-pill-item text-[11px] md:text-[11.5px] font-bold text-neutral-800 group-hover:text-pvRed">Cổng cưới</span>
                </button>

                <!-- 3. Gia tiên -->
                <button onclick="filterCategory('Gia tiên', true)" class="group bg-white rounded-xl p-2 md:p-2.5 border border-pvGold/30 shadow-xs hover:shadow-md hover:border-pvRed transition flex flex-col items-center text-center">
                    <div class="w-14 h-14 sm:w-16 sm:h-16 md:w-18 md:h-18 rounded-full overflow-hidden border-2 border-pvGold mb-1.5">
                        <img src="https://drive.google.com/thumbnail?id=1FX5nU93YLVN6e45pnB1PzEjFjqyS1pOb&sz=w400"
                             onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1FX5nU93YLVN6e45pnB1PzEjFjqyS1pOb';"
                             alt="Gia tiên" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <span class="cat-pill-item text-[11px] md:text-[11.5px] font-bold text-neutral-800 group-hover:text-pvRed">Gia tiên</span>
                </button>

                <!-- 4. Rồng phụng -->
                <button onclick="filterCategory('Rồng phụng', true)" class="group bg-white rounded-xl p-2 md:p-2.5 border border-pvGold/30 shadow-xs hover:shadow-md hover:border-pvRed transition flex flex-col items-center text-center">
                    <div class="w-14 h-14 sm:w-16 sm:h-16 md:w-18 md:h-18 rounded-full overflow-hidden border-2 border-pvGold mb-1.5">
                        <img src="https://drive.google.com/thumbnail?id=18Vgd8A-Ti51bzjEg6vPH8VaLol9NgACK&sz=w400"
                             onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/18Vgd8A-Ti51bzjEg6vPH8VaLol9NgACK';"
                             alt="Rồng phụng" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <span class="cat-pill-item text-[11px] md:text-[11.5px] font-bold text-neutral-800 group-hover:text-pvRed">Rồng phụng</span>
                </button>

                <!-- 5. Rồng Phụng tạo hình từ trái cây -->
                <button onclick="filterCategory('Rồng Phụng tạo hình từ trái cây', true)" class="group bg-white rounded-xl p-2 md:p-2.5 border border-pvGold/30 shadow-xs hover:shadow-md hover:border-pvRed transition flex flex-col items-center text-center">
                    <div class="w-14 h-14 sm:w-16 sm:h-16 md:w-18 md:h-18 rounded-full overflow-hidden border-2 border-pvGold mb-1.5">
                        <img src="https://drive.google.com/thumbnail?id=1TOIbb7pSsn_NdX83E8fQGfuz_jfWs8L9&sz=w400"
                             onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1TOIbb7pSsn_NdX83E8fQGfuz_jfWs8L9';"
                             alt="Rồng Phụng trái cây" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <span class="cat-pill-item text-[10px] md:text-[11px] font-bold text-neutral-800 group-hover:text-pvRed">Rồng Phụng trái cây</span>
                </button>

                <!-- 6. Rồng Phụng xốp mỹ thuật -->
                <button onclick="filterCategory('Rồng Phụng xốp mỹ thuật', true)" class="group bg-white rounded-xl p-2 md:p-2.5 border border-pvGold/30 shadow-xs hover:shadow-md hover:border-pvRed transition flex flex-col items-center text-center">
                    <div class="w-14 h-14 sm:w-16 sm:h-16 md:w-18 md:h-18 rounded-full overflow-hidden border-2 border-pvGold mb-1.5">
                        <img src="https://drive.google.com/thumbnail?id=15zrmu24uoBsebVAJ0rkOssuGvwGL69q8&sz=w400"
                             onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/15zrmu24uoBsebVAJ0rkOssuGvwGL69q8';"
                             alt="Rồng Phụng xốp mỹ thuật" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <span class="cat-pill-item text-[10px] md:text-[11px] font-bold text-neutral-800 group-hover:text-pvRed">Rồng Phụng xốp</span>
                </button>

                <!-- 7. Hoa cưới -->
                <button onclick="filterCategory('Hoa cưới', true)" class="group bg-white rounded-xl p-2 md:p-2.5 border border-pvGold/30 shadow-xs hover:shadow-md hover:border-pvRed transition flex flex-col items-center text-center">
                    <div class="w-14 h-14 sm:w-16 sm:h-16 md:w-18 md:h-18 rounded-full overflow-hidden border-2 border-pvGold mb-1.5">
                        <img src="https://drive.google.com/thumbnail?id=1RoYMUAnIElD5kf8TAq_1AOaxBwW3-qym&sz=w400"
                             onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1RoYMUAnIElD5kf8TAq_1AOaxBwW3-qym';"
                             alt="Hoa cưới" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <span class="cat-pill-item text-[11px] md:text-[11.5px] font-bold text-neutral-800 group-hover:text-pvRed">Hoa cưới</span>
                </button>

                <!-- 8. Dạm Ngõ -->
                <button onclick="filterCategory('Dạm Ngõ', true)" class="group bg-white rounded-xl p-2 md:p-2.5 border border-pvGold/30 shadow-xs hover:shadow-md hover:border-pvRed transition flex flex-col items-center text-center">
                    <div class="w-14 h-14 sm:w-16 sm:h-16 md:w-18 md:h-18 rounded-full overflow-hidden border-2 border-pvGold mb-1.5">
                        <img src="https://drive.google.com/thumbnail?id=1SlRjCmXVZQ-mjUyZ8MfpUZk8eKY-WTTJ&sz=w400"
                             onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1SlRjCmXVZQ-mjUyZ8MfpUZk8eKY-WTTJ';"
                             alt="Dạm Ngõ" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <span class="cat-pill-item text-[11px] md:text-[11.5px] font-bold text-neutral-800 group-hover:text-pvRed">Dạm Ngõ</span>
                </button>

            </div>
        </div>
    </section>

    <!-- =====================================================================
         FLATSOME SECTION: SẢN PHẨM & BỘ LỌC DANH MỤC (15 Ảnh Sản Phẩm Thực Tế)
         - Giá giảm + % giảm giá tròn góc trên bên trái giống Flatsome
         - Không để các nhãn dán rườm rà ở trang chủ
         - Chia 2 cột trên điện thoại, tên sản phẩm hiển thị đầy đủ không bị tràn hay mất chữ
         ===================================================================== -->
    <section id="san-pham" class="py-5 md:py-8">
        <div class="flatsome-container">
            <div class="section-title-container text-center">
                <div class="section-title-main">
                    <h2 class="px-4 font-serif font-bold text-lg md:text-2xl text-pvRed uppercase">
                        Tác Phẩm Cưới Hỏi Thực Tế Tại Phúc Vinh
                    </h2>
                </div>
                <p class="text-xs md:text-sm text-neutral-600 mt-1">
                    Chuyên: Kết Mâm Quả Cưới - Hỏi + Decor - Trang Trí Cổng Rồng Phụng Giá Rẻ Đà Nẵng Trọn Gói
                </p>
            </div>

            <!-- Thanh nút lọc danh mục trên máy tính & điện thoại (Viết liền trên 1 hàng chữ nhỏ gọn, tự xuống hàng 2 nguyên cụm, không ngắt chữ) -->
            <div id="category-filter-bar" class="flex flex-wrap items-center justify-center gap-1.5 md:gap-2 mb-5">
                <button onclick="filterCategory('all', false)" data-cat="all" class="cat-filter-btn cat-pill-item px-3 py-1.5 rounded-full text-xs font-semibold bg-pvRed text-white border border-pvRed shadow-xs">
                    Tất cả sản phẩm (15)
                </button>
                <button onclick="filterCategory('Mâm quả', false)" data-cat="Mâm quả" class="cat-filter-btn cat-pill-item px-3 py-1.5 rounded-full text-xs font-medium bg-white text-neutral-700 border border-pvGold/40 hover:border-pvRed hover:text-pvRed">
                    Mâm quả
                </button>
                <button onclick="filterCategory('Cổng cưới', false)" data-cat="Cổng cưới" class="cat-filter-btn cat-pill-item px-3 py-1.5 rounded-full text-xs font-medium bg-white text-neutral-700 border border-pvGold/40 hover:border-pvRed hover:text-pvRed">
                    Cổng cưới
                </button>
                <button onclick="filterCategory('Gia tiên', false)" data-cat="Gia tiên" class="cat-filter-btn cat-pill-item px-3 py-1.5 rounded-full text-xs font-medium bg-white text-neutral-700 border border-pvGold/40 hover:border-pvRed hover:text-pvRed">
                    Gia tiên
                </button>
                <button onclick="filterCategory('Rồng phụng', false)" data-cat="Rồng phụng" class="cat-filter-btn cat-pill-item px-3 py-1.5 rounded-full text-xs font-medium bg-white text-neutral-700 border border-pvGold/40 hover:border-pvRed hover:text-pvRed">
                    Rồng phụng
                </button>
                <button onclick="filterCategory('Rồng Phụng tạo hình từ trái cây', false)" data-cat="Rồng Phụng tạo hình từ trái cây" class="cat-filter-btn cat-pill-item px-3 py-1.5 rounded-full text-xs font-medium bg-white text-neutral-700 border border-pvGold/40 hover:border-pvRed hover:text-pvRed">
                    Rồng Phụng tạo hình từ trái cây
                </button>
                <button onclick="filterCategory('Rồng Phụng xốp mỹ thuật', false)" data-cat="Rồng Phụng xốp mỹ thuật" class="cat-filter-btn cat-pill-item px-3 py-1.5 rounded-full text-xs font-medium bg-white text-neutral-700 border border-pvGold/40 hover:border-pvRed hover:text-pvRed">
                    Rồng Phụng xốp mỹ thuật
                </button>
                <button onclick="filterCategory('Hoa cưới', false)" data-cat="Hoa cưới" class="cat-filter-btn cat-pill-item px-3 py-1.5 rounded-full text-xs font-medium bg-white text-neutral-700 border border-pvGold/40 hover:border-pvRed hover:text-pvRed">
                    Hoa cưới
                </button>
                <button onclick="filterCategory('Dạm Ngõ', false)" data-cat="Dạm Ngõ" class="cat-filter-btn cat-pill-item px-3 py-1.5 rounded-full text-xs font-medium bg-white text-neutral-700 border border-pvGold/40 hover:border-pvRed hover:text-pvRed">
                    Dạm Ngõ
                </button>
            </div>

            <!-- Grid sản phẩm Flatsome: Điện thoại 2 cột (grid-cols-2), Máy tính 4-5 cột -->
            <div id="product-grid" class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-4 xl:grid-cols-5 gap-2.5 sm:gap-3.5 md:gap-4">
                <!-- Render tự động bằng JS từ 15 ảnh Google Drive thực tế -->
            </div>
        </div>
    </section>

    <!-- =====================================================================
         FLATSOME SECTION: GIỚI THIỆU VỀ PHÚC VINH (Theo mẫu Rồng Phụng Phương Nam)
         ===================================================================== -->
    <section id="gioi-thieu" class="py-5 md:py-8">
        <div class="flatsome-container">
            <div class="bg-white rounded-2xl p-4 sm:p-6 md:p-8 border border-pvGold/35 shadow-xs grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
                
                <!-- Nội dung câu chuyện thương hiệu -->
                <div class="lg:col-span-7 space-y-3">
                    <div class="text-xs font-bold uppercase tracking-widest text-pvGold">
                        Về Chúng Tôi • phucvinh.com
                    </div>
                    <h2 class="font-serif font-bold text-xl md:text-2xl text-pvRed leading-snug">
                        Phúc Vinh – Nâng Tầm Nghệ Thuật Mâm Quả Cưới Hỏi & Cổng Rồng Phụng Tại Đà Nẵng
                    </h2>
                    <p class="text-xs sm:text-sm text-neutral-700 leading-relaxed">
                        Lễ cưới – hỏi không chỉ là nghi thức truyền thống thiêng liêng mà còn là dấu ấn mở đầu cho hành trình hạnh phúc trăm năm của đôi uyên ương. Tại <strong>Phúc Vinh - Mâm Quả Cưới Đà Nẵng</strong>, chúng tôi tự hào mang đến những bộ <strong>mâm quả cưới hỏi, tráp dạm ngõ, rồng phụng trái cây tươi, rồng phụng xốp mỹ thuật, cổng cưới và không gian gia tiên</strong> sang trọng, chuẩn phong tục miền Trung và ba miền.
                    </p>
                    <p class="text-xs sm:text-sm text-neutral-700 leading-relaxed">
                        Sự kết hợp hài hòa giữa nét truyền thống và hơi thở hiện đại giúp mỗi tác phẩm tại Phúc Vinh không chỉ chỉn chu về lễ vật mà còn mang giá trị thẩm mỹ cao, phù hợp với ngân sách của mọi gia đình tại Đà Nẵng và khu vực lân cận.
                    </p>

                    <!-- 4 Cam kết vàng -->
                    <div class="grid grid-cols-2 sm:grid-cols-4 gap-2.5 pt-2">
                        <div class="bg-pvCream rounded-xl p-3 border border-pvGold/25 text-center">
                            <div class="font-serif font-bold text-lg md:text-xl text-pvRed">10+ Năm</div>
                            <div class="text-[11px] text-neutral-600 mt-0.5">Kinh nghiệm nghệ nhân</div>
                        </div>
                        <div class="bg-pvCream rounded-xl p-3 border border-pvGold/25 text-center">
                            <div class="font-serif font-bold text-lg md:text-xl text-pvRed">1.500+</div>
                            <div class="text-[11px] text-neutral-600 mt-0.5">Lễ cưới hỏi trọn gói</div>
                        </div>
                        <div class="bg-pvCream rounded-xl p-3 border border-pvGold/25 text-center">
                            <div class="font-serif font-bold text-lg md:text-xl text-pvRed">100%</div>
                            <div class="text-[11px] text-neutral-600 mt-0.5">Hoa quả tươi loại 1</div>
                        </div>
                        <div class="bg-pvCream rounded-xl p-3 border border-pvGold/25 text-center">
                            <div class="font-serif font-bold text-lg md:text-xl text-pvRed">Đúng Giờ</div>
                            <div class="text-[11px] text-neutral-600 mt-0.5">Giao & lắp đặt tận nơi</div>
                        </div>
                    </div>
                </div>

                <!-- Khung ảnh thực tế Phúc Vinh -->
                <div class="lg:col-span-5 grid grid-cols-2 gap-3">
                    <div class="rounded-xl overflow-hidden border-2 border-pvGold shadow-sm h-48 sm:h-56">
                        <img src="https://drive.google.com/thumbnail?id=1Lxh-4OZ9C2hfNmxnJfNdBh7umBODsYzr&sz=w600"
                             onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1Lxh-4OZ9C2hfNmxnJfNdBh7umBODsYzr';"
                             alt="Nghệ thuật kết mâm quả Phúc Vinh" class="w-full h-full object-cover">
                    </div>
                    <div class="rounded-xl overflow-hidden border-2 border-pvGold shadow-sm h-48 sm:h-56">
                        <img src="https://drive.google.com/thumbnail?id=1puuNxVcDQw4Bf9P-jJEiqXLCfw1pYBO4&sz=w600"
                             onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1puuNxVcDQw4Bf9P-jJEiqXLCfw1pYBO4';"
                             alt="Cổng Rồng Phụng Đà Nẵng" class="w-full h-full object-cover">
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- =====================================================================
         FLATSOME SECTION: DỊCH VỤ CƯỚI HỎI TRỌN GÓI (UX Icon Boxes)
         ===================================================================== -->
    <section id="dich-vu" class="py-5 md:py-8">
        <div class="flatsome-container">
            <div class="section-title-container text-center">
                <div class="section-title-main">
                    <h2 class="px-4 font-serif font-bold text-lg md:text-2xl text-pvRed uppercase">
                        Dịch Vụ Cưới Hỏi Trọn Gói Phúc Vinh
                    </h2>
                </div>
                <p class="text-xs md:text-sm text-neutral-600 mt-1">
                    Giải pháp cưới hỏi đồng bộ, tiết kiệm chi phí và sang trọng bậc nhất tại Đà Nẵng
                </p>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-3.5 md:gap-4">
                <div class="bg-white rounded-xl p-4 border border-pvGold/30 shadow-xs hover:shadow-md transition">
                    <div class="w-11 h-11 rounded-xl bg-pvRed text-pvGoldLight flex items-center justify-center text-lg mb-3">
                        <i class="fa-solid fa-gift"></i>
                    </div>
                    <h3 class="font-serif font-bold text-base text-pvRed mb-1.5">Kết Mâm Quả Cưới - Hỏi</h3>
                    <p class="text-xs text-neutral-600 leading-relaxed">
                        Đa dạng gói 5, 6, 7, 9 mâm quả truyền thống và hiện đại: trầu cau, rượu trà, bánh phu thê, xôi gấc, heo quay, trái cây tươi.
                    </p>
                </div>

                <div class="bg-white rounded-xl p-4 border border-pvGold/30 shadow-xs hover:shadow-md transition">
                    <div class="w-11 h-11 rounded-xl bg-pvRed text-pvGoldLight flex items-center justify-center text-lg mb-3">
                        <i class="fa-solid fa-dragon"></i>
                    </div>
                    <h3 class="font-serif font-bold text-base text-pvRed mb-1.5">Rồng Phụng Nghệ Thuật</h3>
                    <p class="text-xs text-neutral-600 leading-relaxed">
                        Chế tác Rồng Phụng tạo hình từ trái cây tươi và Rồng Phụng xốp mỹ thuật cao cấp, đường nét sắc sảo, thần thái uy nghi.
                    </p>
                </div>

                <div class="bg-white rounded-xl p-4 border border-pvGold/30 shadow-xs hover:shadow-md transition">
                    <div class="w-11 h-11 rounded-xl bg-pvRed text-pvGoldLight flex items-center justify-center text-lg mb-3">
                        <i class="fa-solid fa-archway"></i>
                    </div>
                    <h3 class="font-serif font-bold text-base text-pvRed mb-1.5">Decor Cổng Cưới Rồng Phụng</h3>
                    <p class="text-xs text-neutral-600 leading-relaxed">
                        Thiết kế & thi công cổng cưới rồng phụng, cổng hoa lụa – hoa tươi cao cấp tận nhà với chi phí hợp lý nhất Đà Nẵng.
                    </p>
                </div>

                <div class="bg-white rounded-xl p-4 border border-pvGold/30 shadow-xs hover:shadow-md transition">
                    <div class="w-11 h-11 rounded-xl bg-pvRed text-pvGoldLight flex items-center justify-center text-lg mb-3">
                        <i class="fa-solid fa-Couch"></i>
                    </div>
                    <h3 class="font-serif font-bold text-base text-pvRed mb-1.5">Trang Trí Gia Tiên & Dạm Ngõ</h3>
                    <p class="text-xs text-neutral-600 leading-relaxed">
                        Trang trí phông bàn thờ gia tiên, bàn họ, bộ ấm tách, chữ Hỷ, tráp dạm ngõ và hoa cưới cầm tay cô dâu đồng bộ.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         FLATSOME SECTION: FORM YÊU CẦU VÀ NHẬN BÁO GIÁ TRANG CHỦ
         ===================================================================== -->
    <section id="bao-gia" class="py-5 md:py-8">
        <div class="flatsome-container">
            <div class="bg-gradient-to-br from-pvRedDark via-pvRed to-[#5A0E0E] rounded-2xl p-4 sm:p-6 md:p-8 text-white border-2 border-pvGold/50 shadow-lg">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-start">
                    
                    <!-- Cột thông tin ưu đãi & giỏ sản phẩm đã chọn -->
                    <div class="lg:col-span-5 space-y-4">
                        <div class="text-xs font-bold uppercase tracking-widest text-pvGoldLight">
                            Báo Giá Nhanh Chóng • Tận Tâm • Minh Bạch
                        </div>
                        <h2 class="font-serif font-bold text-xl md:text-2xl text-pvGoldLight leading-snug uppercase">
                            Đăng Ký Tư Vấn & Nhận Báo Giá Trọn Gói
                        </h2>
                        <p class="text-xs sm:text-sm text-white/90 leading-relaxed">
                            Quý khách để lại thông tin hoặc chọn các mẫu mâm quả, cổng rồng phụng, trang trí gia tiên yêu thích. Đội ngũ <strong>Phúc Vinh</strong> sẽ liên hệ gửi báo giá chi tiết qua Zalo/Điện thoại chỉ trong 5 phút!
                        </p>

                        <!-- Khung danh sách mẫu đã chọn vào báo giá -->
                        <div class="bg-black/25 rounded-xl p-3.5 border border-pvGold/30">
                            <div class="flex items-center justify-between mb-2">
                                <span class="text-xs font-bold text-pvGoldLight uppercase">
                                    <i class="fa-solid fa-bag-shopping mr-1.5"></i>Mẫu bạn đang quan tâm (<span id="quote-selected-count">0</span>)
                                </span>
                                <button type="button" onclick="clearQuoteItems()" class="text-[11px] text-pvGoldLight/80 hover:text-white underline">
                                    Xóa danh sách
                                </button>
                            </div>
                            <div id="quote-selected-list" class="space-y-1.5 max-h-40 overflow-y-auto text-xs text-white/90">
                                <p class="text-white/65 italic text-xs">Chưa có mẫu nào được chọn. Bạn có thể bấm nút "Chọn báo giá" ở từng sản phẩm phía trên hoặc điền trực tiếp yêu cầu bên cạnh.</p>
                            </div>
                        </div>

                        <div class="space-y-2 text-xs text-pvGoldLight/95 pt-1">
                            <div><i class="fa-solid fa-location-dot text-pvGold mr-2"></i><strong>Địa chỉ:</strong> 142 Bùi Tá Hán, Phường Ngũ Hành Sơn, Tp. Đà Nẵng</div>
                            <div><i class="fa-solid fa-phone-volume text-pvGold mr-2"></i><strong>Hotline / Zalo:</strong> 0934.153.598</div>
                            <div><i class="fa-solid fa-globe text-pvGold mr-2"></i><strong>Website:</strong> phucvinh.com</div>
                        </div>
                    </div>

                    <!-- Form Yêu Cầu & Báo Giá -->
                    <div class="lg:col-span-7 bg-white text-neutral-800 rounded-xl p-4 sm:p-6 shadow-md border border-pvGold">
                        <h3 class="font-serif font-bold text-base sm:text-lg text-pvRed mb-3 uppercase">
                            Phiếu Yêu Cầu Báo Giá Cưới Hỏi
                        </h3>
                        <form id="quote-request-form" onsubmit="submitQuoteForm(event)" class="space-y-3">
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                                <div>
                                    <label class="block text-xs font-semibold text-neutral-700 mb-1">Họ và tên Cô Dâu / Chú Rể *</label>
                                    <input type="text" id="q-name" required placeholder="Nhập họ và tên..."
                                           class="w-full px-3 py-2 rounded-lg border border-neutral-300 text-xs focus:outline-none focus:border-pvRed">
                                </div>
                                <div>
                                    <label class="block text-xs font-semibold text-neutral-700 mb-1">Số điện thoại / Zalo *</label>
                                    <input type="tel" id="q-phone" required placeholder="Ví dụ: 0934153598"
                                           class="w-full px-3 py-2 rounded-lg border border-neutral-300 text-xs focus:outline-none focus:border-pvRed">
                                </div>
                            </div>

                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                                <div>
                                    <label class="block text-xs font-semibold text-neutral-700 mb-1">Ngày tổ chức dự kiến</label>
                                    <input type="date" id="q-date"
                                           class="w-full px-3 py-2 rounded-lg border border-neutral-300 text-xs focus:outline-none focus:border-pvRed">
                                </div>
                                <div>
                                    <label class="block text-xs font-semibold text-neutral-700 mb-1">Hạng mục cần báo giá</label>
                                    <select id="q-service" class="w-full px-3 py-2 rounded-lg border border-neutral-300 text-xs focus:outline-none focus:border-pvRed bg-white">
                                        <option value="Trọn gói Mâm quả + Cổng Rồng Phụng + Gia tiên">Trọn gói Mâm quả + Cổng Rồng Phụng + Gia tiên</option>
                                        <option value="Mâm quả cưới hỏi trọn gói">Mâm quả cưới hỏi trọn gói (5 - 7 - 9 quả)</option>
                                        <option value="Cổng cưới & Rồng Phụng">Cổng cưới & Rồng Phụng nghệ thuật</option>
                                        <option value="Rồng Phụng tạo hình từ trái cây">Rồng Phụng tạo hình từ trái cây</option>
                                        <option value="Rồng Phụng xốp mỹ thuật">Rồng Phụng xốp mỹ thuật</option>
                                        <option value="Trang trí Gia tiên">Trang trí Gia tiên tại nhà</option>
                                        <option value="Tráp Dạm Ngõ & Hoa cưới">Tráp Dạm Ngõ & Hoa cưới</option>
                                    </select>
                                </div>
                            </div>

                            <div>
                                <label class="block text-xs font-semibold text-neutral-700 mb-1">Địa chỉ tổ chức & Yêu cầu chi tiết</label>
                                <textarea id="q-note" rows="3" placeholder="Nhập địa chỉ tại Đà Nẵng/Quảng Nam, số lượng mâm quả hoặc tông màu mong muốn..."
                                          class="w-full px-3 py-2 rounded-lg border border-neutral-300 text-xs focus:outline-none focus:border-pvRed"></textarea>
                            </div>

                            <div class="flex flex-wrap items-center gap-2.5 pt-1">
                                <button type="submit" class="flex-1 min-w-[180px] py-2.5 px-4 rounded-lg bg-pvRed hover:bg-pvRedDark text-white font-bold text-xs uppercase tracking-wide transition shadow">
                                    <i class="fa-solid fa-paper-plane mr-1.5"></i>Gửi Yêu Cầu Báo Giá
                                </button>
                                <a href="https://zalo.me/0934153598" target="_blank" rel="noopener noreferrer"
                                   class="py-2.5 px-4 rounded-lg bg-pvGold hover:bg-amber-500 text-neutral-900 font-bold text-xs uppercase tracking-wide transition">
                                    <i class="fa-solid fa-comments mr-1"></i>Chat Zalo Ngay
                                </a>
                            </div>

                            <!-- Thông báo gửi thành công -->
                            <div id="quote-form-feedback" class="hidden p-3 rounded-lg bg-emerald-50 border border-emerald-300 text-emerald-800 text-xs font-medium"></div>
                        </form>
                    </div>

                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         FLATSOME SECTION: DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC & CẨM NANG CƯỚI)
         ===================================================================== -->
    <section id="tin-tuc" class="py-5 md:py-8">
        <div class="flatsome-container">
            <div class="section-title-container text-center">
                <div class="section-title-main">
                    <h2 class="px-4 font-serif font-bold text-lg md:text-2xl text-pvRed uppercase">
                        Chuyên Mục Bài Viết & Cẩm Nang Cưới Hỏi
                    </h2>
                </div>
                <p class="text-xs md:text-sm text-neutral-600 mt-1">
                    Kinh nghiệm chuẩn bị lễ dạm ngõ, mâm quả cưới hỏi và trang trí cổng rồng phụng chuẩn phong tục Đà Nẵng
                </p>
            </div>

            <!-- Nút lọc danh mục bài viết trang chủ -->
            <div class="flex flex-wrap items-center justify-center gap-1.5 md:gap-2 mb-5">
                <button onclick="filterPosts('all')" data-post-cat="all" class="post-cat-btn cat-pill-item px-3 py-1.5 rounded-full text-xs font-semibold bg-pvRed text-white border border-pvRed">
                    Tất cả bài viết
                </button>
                <button onclick="filterPosts('Kinh nghiệm mâm quả')" data-post-cat="Kinh nghiệm mâm quả" class="post-cat-btn cat-pill-item px-3 py-1.5 rounded-full text-xs font-medium bg-white text-neutral-700 border border-pvGold/40 hover:border-pvRed">
                    Kinh nghiệm mâm quả
                </button>
                <button onclick="filterPosts('Nghi lễ dạm ngõ & ăn hỏi')" data-post-cat="Nghi lễ dạm ngõ & ăn hỏi" class="post-cat-btn cat-pill-item px-3 py-1.5 rounded-full text-xs font-medium bg-white text-neutral-700 border border-pvGold/40 hover:border-pvRed">
                    Nghi lễ dạm ngõ & ăn hỏi
                </button>
                <button onclick="filterPosts('Xu hướng cổng rồng phụng & gia tiên')" data-post-cat="Xu hướng cổng rồng phụng & gia tiên" class="post-cat-btn cat-pill-item px-3 py-1.5 rounded-full text-xs font-medium bg-white text-neutral-700 border border-pvGold/40 hover:border-pvRed">
                    Xu hướng cổng rồng phụng & gia tiên
                </button>
            </div>

            <!-- Danh sách bài viết (Grid 2 cột mobile hoặc 4 cột desktop) -->
            <div id="blog-grid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-3.5 md:gap-4">
                <!-- Render tự động bằng JS -->
            </div>
        </div>
    </section>

    <!-- =====================================================================
         FLATSOME SECTION: FANPAGE FACEBOOK & BẢN ĐỒ GOOGLE MAPS NGOÀI TRANG CHỦ
         - Địa chỉ: 142 Bùi Tá Hán, Phường Ngũ Hành Sơn, Tp. Đà Nẵng
         - Map link: https://share.google/ZsyPBsoC8gd3xG20L
         - Fanpage: https://www.facebook.com/mamquacuoiphucvinhdanang?locale=vi_VN
         ===================================================================== -->
    <section id="lien-he-map" class="py-5 md:py-8">
        <div class="flatsome-container">
            <div class="section-title-container text-center">
                <div class="section-title-main">
                    <h2 class="px-4 font-serif font-bold text-lg md:text-2xl text-pvRed uppercase">
                        Fanpage Chính Thức & Bản Đồ Cửa Hàng Phúc Vinh
                    </h2>
                </div>
                <p class="text-xs md:text-sm text-neutral-600 mt-1">
                    Địa chỉ: 142 Bùi Tá Hán, Phường Ngũ Hành Sơn, Tp. Đà Nẵng • Hotline/Zalo: 0934.153.598
                </p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 items-stretch">
                
                <!-- CỘT 1: FANPAGE FACEBOOK PHÚC VINH NGOÀI TRANG CHỦ -->
                <div class="lg:col-span-5 bg-white rounded-2xl p-4 sm:p-5 border border-pvGold/40 shadow-xs flex flex-col justify-between">
                    <div>
                        <div class="flex items-center justify-between gap-2 pb-3 mb-3 border-b border-neutral-100">
                            <div class="flex items-center gap-2.5">
                                <div class="w-11 h-11 rounded-full overflow-hidden border-2 border-pvGold shrink-0">
                                    <img src="https://drive.google.com/thumbnail?id=1xP2iyt2jNC0uVEufM3pyHIr3Mj-kDWRF&sz=w200"
                                         onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1xP2iyt2jNC0uVEufM3pyHIr3Mj-kDWRF';"
                                         alt="Fanpage Phúc Vinh" class="w-full h-full object-cover">
                                </div>
                                <div>
                                    <h3 class="font-bold text-sm text-pvRed leading-tight">Phúc Vinh - Mâm Quả Cưới Đà Nẵng</h3>
                                    <p class="text-[11px] text-neutral-500">facebook.com/mamquacuoiphucvinhdanang</p>
                                </div>
                            </div>
                            <a href="https://www.facebook.com/mamquacuoiphucvinhdanang?locale=vi_VN" target="_blank" rel="noopener noreferrer"
                               class="px-3 py-1.5 rounded-lg bg-[#1877F2] hover:bg-blue-700 text-white text-xs font-semibold shrink-0 flex items-center gap-1.5">
                                <i class="fa-brands fa-facebook-f"></i> Theo dõi
                            </a>
                        </div>

                        <p class="text-xs text-neutral-700 mb-3 leading-relaxed">
                            Cập nhật hình ảnh thực tế mỗi ngày các mẫu <strong>Mâm Quả Cưới Hỏi, Cổng Rồng Phụng, Rồng Phụng Trái Cây & Trang Trí Gia Tiên</strong> mới nhất tại Fanpage chính thức của Phúc Vinh.
                        </p>

                        <!-- Khung nhúng Facebook Page Plugin + Bộ ảnh thực tế Fanpage -->
                        <div class="w-full rounded-xl overflow-hidden border border-neutral-200 bg-neutral-50 mb-3">
                            <iframe
                                title="Fanpage Phúc Vinh Mâm Quả Cưới Đà Nẵng"
                                src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fmamquacuoiphucvinhdanang&tabs=timeline&width=500&height=260&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true"
                                width="100%" height="260" style="border:none;overflow:hidden" scrolling="no" frameborder="0"
                                allowfullscreen="true" allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share">
                            </iframe>
                        </div>

                        <!-- 4 ảnh hoạt động thực tế trên Fanpage -->
                        <div class="grid grid-cols-4 gap-2 mb-3">
                            <a href="https://www.facebook.com/mamquacuoiphucvinhdanang?locale=vi_VN" target="_blank" rel="noopener noreferrer" class="rounded-lg overflow-hidden h-16 border border-pvGold/40 block">
                                <img src="https://drive.google.com/thumbnail?id=1wobR6uKHQ6KFvBIIcg6lFavedqajuKgI&sz=w300"
                                     onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1wobR6uKHQ6KFvBIIcg6lFavedqajuKgI';"
                                     alt="Ảnh Fanpage 1" class="w-full h-full object-cover">
                            </a>
                            <a href="https://www.facebook.com/mamquacuoiphucvinhdanang?locale=vi_VN" target="_blank" rel="noopener noreferrer" class="rounded-lg overflow-hidden h-16 border border-pvGold/40 block">
                                <img src="https://drive.google.com/thumbnail?id=1vK8JBdPjXY2j0F6CT3tAh7zBnVDelUoA&sz=w300"
                                     onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1vK8JBdPjXY2j0F6CT3tAh7zBnVDelUoA';"
                                     alt="Ảnh Fanpage 2" class="w-full h-full object-cover">
                            </a>
                            <a href="https://www.facebook.com/mamquacuoiphucvinhdanang?locale=vi_VN" target="_blank" rel="noopener noreferrer" class="rounded-lg overflow-hidden h-16 border border-pvGold/40 block">
                                <img src="https://drive.google.com/thumbnail?id=1RoYMUAnIElD5kf8TAq_1AOaxBwW3-qym&sz=w300"
                                     onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1RoYMUAnIElD5kf8TAq_1AOaxBwW3-qym';"
                                     alt="Ảnh Fanpage 3" class="w-full h-full object-cover">
                            </a>
                            <a href="https://www.facebook.com/mamquacuoiphucvinhdanang?locale=vi_VN" target="_blank" rel="noopener noreferrer" class="rounded-lg overflow-hidden h-16 border border-pvGold/40 block">
                                <img src="https://drive.google.com/thumbnail?id=1Zuv4XQwVrYDgbnxIPcD7Y_7BOCKvOxAF&sz=w300"
                                     onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1Zuv4XQwVrYDgbnxIPcD7Y_7BOCKvOxAF';"
                                     alt="Ảnh Fanpage 4" class="w-full h-full object-cover">
                            </a>
                        </div>
                    </div>

                    <a href="https://www.facebook.com/mamquacuoiphucvinhdanang?locale=vi_VN" target="_blank" rel="noopener noreferrer"
                       class="w-full py-2.5 px-4 rounded-xl bg-[#1877F2] hover:bg-blue-700 text-white font-bold text-xs text-center uppercase tracking-wide transition block">
                        <i class="fa-brands fa-facebook mr-1.5"></i>Truy Cập Fanpage Phúc Vinh Trên Facebook
                    </a>
                </div>

                <!-- CỘT 2: HÌNH ẢNH & BẢN ĐỒ GOOGLE MAPS NGOÀI TRANG CHỦ -->
                <div class="lg:col-span-7 bg-white rounded-2xl p-4 sm:p-5 border border-pvGold/40 shadow-xs flex flex-col justify-between">
                    <div>
                        <div class="flex flex-wrap items-center justify-between gap-2 pb-3 mb-3 border-b border-neutral-100">
                            <div>
                                <h3 class="font-bold text-sm sm:text-base text-pvRed">
                                    <i class="fa-solid fa-map-location-dot text-pvGold mr-1.5"></i>Bản Đồ Google Maps - Mâm Quả Cưới Phúc Vinh
                                </h3>
                                <p class="text-xs text-neutral-600 mt-0.5">
                                    142 Bùi Tá Hán, Phường Ngũ Hành Sơn, Tp. Đà Nẵng
                                </p>
                            </div>
                            <a href="https://share.google/ZsyPBsoC8gd3xG20L" target="_blank" rel="noopener noreferrer"
                               class="px-3 py-1.5 rounded-lg bg-pvRed hover:bg-pvRedDark text-white text-xs font-semibold flex items-center gap-1.5">
                                <i class="fa-solid fa-diamond-turn-right"></i> Chỉ đường Google Maps
                            </a>
                        </div>

                        <!-- Bản đồ Google Maps trực tiếp ngoài trang chủ -->
                        <div class="w-full h-72 sm:h-80 rounded-xl overflow-hidden border-2 border-pvGold/40 shadow-inner relative bg-neutral-100">
                            <iframe
                                title="Google Map Phúc Vinh 142 Bùi Tá Hán Đà Nẵng"
                                src="https://maps.google.com/maps?q=142%20B%C3%B9i%20T%C3%A1%20H%C3%A1n,%20Ng%C5%A9%20H%C3%A0nh%20S%C6%A1n,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                                width="100%" height="100%" style="border:0;" allowfullscreen="" loading="lazy"
                                referrerpolicy="no-referrer-when-downgrade">
                            </iframe>
                        </div>

                        <!-- Thẻ thông tin địa điểm & nút mở Google Maps nhanh -->
                        <div class="mt-3 p-3 rounded-xl bg-pvCream border border-pvGold/30 flex flex-col sm:flex-row items-start sm:items-center justify-between gap-3">
                            <div class="text-xs space-y-1">
                                <div class="font-bold text-pvRed uppercase">PHÚC VINH - MÂM QUẢ CƯỚI ĐÀ NẴNG (PHUCVINH.COM)</div>
                                <div class="text-neutral-700"><i class="fa-solid fa-location-dot text-pvRed mr-1.5"></i>142 Bùi Tá Hán, Phường Ngũ Hành Sơn, Tp. Đà Nẵng</div>
                                <div class="text-neutral-700"><i class="fa-solid fa-phone text-pvRed mr-1.5"></i>Điện thoại / Zalo: <strong>0934.153.598</strong> (Mở cửa phục vụ 24/7)</div>
                            </div>
                            <a href="https://share.google/ZsyPBsoC8gd3xG20L" target="_blank" rel="noopener noreferrer"
                               class="px-3.5 py-2 rounded-lg bg-pvGold hover:bg-amber-500 text-neutral-900 font-bold text-xs whitespace-nowrap transition">
                                <i class="fa-solid fa-location-arrow mr-1"></i>Mở Bản Đồ Lớn
                            </a>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- =====================================================================
         FLATSOME FOOTER (Chân trang chuẩn cấu trúc Flatsome 4 cột)
         ===================================================================== -->
    <footer class="bg-pvRedDark text-white border-t-4 border-pvGold mt-6">
        <div class="flatsome-container py-8 md:py-10">
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-12 gap-6">
                
                <!-- Cột 1: Thương hiệu & Logo -->
                <div class="lg:col-span-4 space-y-3">
                    <div class="flex items-center gap-3">
                        <img src="https://drive.google.com/thumbnail?id=1xP2iyt2jNC0uVEufM3pyHIr3Mj-kDWRF&sz=w300"
                             onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1xP2iyt2jNC0uVEufM3pyHIr3Mj-kDWRF';"
                             alt="Logo Phúc Vinh" class="w-12 h-12 rounded-full border-2 border-pvGold object-cover bg-white shrink-0">
                        <div>
                            <div class="font-serif font-bold text-base text-pvGoldLight uppercase">Phúc Vinh - Mâm Quả Cưới Đà Nẵng</div>
                            <div class="text-xs text-white/80">Website chính thức: phucvinh.com</div>
                        </div>
                    </div>
                    <p class="text-xs text-white/85 leading-relaxed">
                        CHUYÊN : KẾT MÂM QUẢ CƯỚI - HỎI + DECOR - TRANG TRÍ CỔNG RỒNG PHỤNG GIÁ RẺ ĐÀ NẴNG TRỌN GÓI. Uy tín – Tận tâm – Chuẩn phong tục truyền thống.
                    </p>
                </div>

                <!-- Cột 2: Danh mục sản phẩm -->
                <div class="lg:col-span-3 space-y-2">
                    <h4 class="font-serif font-bold text-sm text-pvGoldLight uppercase border-b border-pvGold/30 pb-1.5">
                        Danh Mục Sản Phẩm
                    </h4>
                    <ul class="space-y-1.5 text-xs text-white/85">
                        <li><button onclick="filterCategory('Mâm quả', true)" class="hover:text-pvGoldLight">• Mâm quả cưới hỏi trọn gói</button></li>
                        <li><button onclick="filterCategory('Cổng cưới', true)" class="hover:text-pvGoldLight">• Cổng cưới Rồng Phụng & Hoa lụa</button></li>
                        <li><button onclick="filterCategory('Gia tiên', true)" class="hover:text-pvGoldLight">• Trang trí bàn thờ Gia tiên</button></li>
                        <li><button onclick="filterCategory('Rồng Phụng tạo hình từ trái cây', true)" class="hover:text-pvGoldLight">• Rồng Phụng tạo hình từ trái cây</button></li>
                        <li><button onclick="filterCategory('Rồng Phụng xốp mỹ thuật', true)" class="hover:text-pvGoldLight">• Rồng Phụng xốp mỹ thuật</button></li>
                        <li><button onclick="filterCategory('Hoa cưới', true)" class="hover:text-pvGoldLight">• Hoa cưới cầm tay cô dâu</button></li>
                        <li><button onclick="filterCategory('Dạm Ngõ', true)" class="hover:text-pvGoldLight">• Tráp lễ Dạm Ngõ</button></li>
                    </ul>
                </div>

                <!-- Cột 3: Liên kết nhanh -->
                <div class="lg:col-span-2 space-y-2">
                    <h4 class="font-serif font-bold text-sm text-pvGoldLight uppercase border-b border-pvGold/30 pb-1.5">
                        Thông Tin
                    </h4>
                    <ul class="space-y-1.5 text-xs text-white/85">
                        <li><a href="#trang-chu" class="hover:text-pvGoldLight">• Trang chủ</a></li>
                        <li><a href="#gioi-thieu" class="hover:text-pvGoldLight">• Giới thiệu Phúc Vinh</a></li>
                        <li><a href="#dich-vu" class="hover:text-pvGoldLight">• Dịch vụ cưới hỏi</a></li>
                        <li><a href="#bao-gia" class="hover:text-pvGoldLight">• Yêu cầu báo giá</a></li>
                        <li><a href="#tin-tuc" class="hover:text-pvGoldLight">• Cẩm nang cưới hỏi</a></li>
                        <li><a href="#lien-he-map" class="hover:text-pvGoldLight">• Bản đồ & Fanpage</a></li>
                    </ul>
                </div>

                <!-- Cột 4: Thông tin liên hệ -->
                <div class="lg:col-span-3 space-y-2 text-xs text-white/90">
                    <h4 class="font-serif font-bold text-sm text-pvGoldLight uppercase border-b border-pvGold/30 pb-1.5">
                        Liên Hệ Trực Tiếp
                    </h4>
                    <div><i class="fa-solid fa-location-dot text-pvGold mr-2"></i>142 Bùi Tá Hán, Phường Ngũ Hành Sơn, Tp. Đà Nẵng</div>
                    <div><i class="fa-solid fa-phone-volume text-pvGold mr-2"></i>Hotline / Zalo: <a href="tel:0934153598" class="font-bold text-pvGoldLight">0934.153.598</a></div>
                    <div><i class="fa-brands fa-facebook text-pvGold mr-2"></i><a href="https://www.facebook.com/mamquacuoiphucvinhdanang?locale=vi_VN" target="_blank" rel="noopener noreferrer" class="underline hover:text-pvGoldLight">Fanpage Phúc Vinh Đà Nẵng</a></div>
                    <div><i class="fa-solid fa-map text-pvGold mr-2"></i><a href="https://share.google/ZsyPBsoC8gd3xG20L" target="_blank" rel="noopener noreferrer" class="underline hover:text-pvGoldLight">Xem vị trí trên Google Maps</a></div>
                </div>

            </div>
        </div>

        <div class="bg-black/30 py-3 text-center text-[11px] text-white/75 border-t border-white/10">
            <div class="flatsome-container">
                © Bản quyền thuộc về <strong>phucvinh.com - Phúc Vinh Mâm Quả Cưới Đà Nẵng</strong> | Địa chỉ: 142 Bùi Tá Hán, Phường Ngũ Hành Sơn, Tp. Đà Nẵng | ĐT: 0934.153.598
            </div>
        </div>
    </footer>

    <!-- =====================================================================
         CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE) TƯƠNG THÍCH MÁY TÍNH & ĐIỆN THOẠI
         - Không gây tràn viền, hiển thị rõ ràng góc phải dưới
         ===================================================================== -->
    <div class="fixed right-3 bottom-4 z-40 flex flex-col items-end gap-2.5">
        
        <!-- Nút Facebook Fanpage -->
        <a href="https://www.facebook.com/mamquacuoiphucvinhdanang?locale=vi_VN" target="_blank" rel="noopener noreferrer"
           title="Chat Facebook Fanpage Phúc Vinh"
           class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white rounded-full p-2.5 sm:px-3.5 sm:py-2 shadow-lg border border-white/30 transition">
            <i class="fa-brands fa-facebook-messenger text-base sm:text-sm"></i>
            <span class="hidden sm:inline text-xs font-bold">Facebook</span>
        </a>

        <!-- Nút Chat Zalo -->
        <a href="https://zalo.me/0934153598" target="_blank" rel="noopener noreferrer"
           title="Chat Zalo 0934.153.598"
           class="flex items-center gap-2 bg-[#0068FF] hover:bg-blue-600 text-white rounded-full p-2.5 sm:px-3.5 sm:py-2 shadow-lg border border-white/30 transition">
            <span class="w-4 h-4 rounded-full bg-white text-[#0068FF] font-extrabold text-[10px] flex items-center justify-center">Z</span>
            <span class="hidden sm:inline text-xs font-bold">Zalo: 0934.153.598</span>
        </a>

        <!-- Nút Gọi Hotline nổi bật -->
        <a href="tel:0934153598"
           title="Gọi ngay 0934.153.598"
           class="float-btn-pulse flex items-center gap-2 bg-pvRed hover:bg-pvRedDark text-white rounded-full px-3.5 py-2.5 shadow-xl border-2 border-pvGold transition">
            <i class="fa-solid fa-phone-volume text-pvGoldLight text-sm"></i>
            <span class="text-xs font-bold tracking-wide">0934.153.598</span>
        </a>
    </div>

    <!-- =====================================================================
         MODAL XEM CHI TIẾT SẢN PHẨM (Quick View chuẩn Flatsome)
         ===================================================================== -->
    <div id="product-modal" class="fixed inset-0 z-50 hidden items-center justify-center p-3 bg-black/65 backdrop-blur-xs">
        <div class="bg-white rounded-2xl max-w-2xl w-full overflow-hidden shadow-2xl border-2 border-pvGold relative max-h-[90vh] overflow-y-auto">
            <button onclick="closeProductModal()" class="absolute top-3 right-3 z-10 w-8 h-8 rounded-full bg-black/50 text-white flex items-center justify-center hover:bg-pvRed">
                <i class="fa-solid fa-xmark"></i>
            </button>
            <div id="product-modal-body" class="p-4 sm:p-6"></div>
        </div>
    </div>

    <!-- =====================================================================
         MODAL ĐỌC BÀI VIẾT CẨM NANG CƯỚI
         ===================================================================== -->
    <div id="blog-modal" class="fixed inset-0 z-50 hidden items-center justify-center p-3 bg-black/65 backdrop-blur-xs">
        <div class="bg-white rounded-2xl max-w-2xl w-full overflow-hidden shadow-2xl border-2 border-pvGold relative max-h-[90vh] overflow-y-auto">
            <button onclick="closeBlogModal()" class="absolute top-3 right-3 z-10 w-8 h-8 rounded-full bg-black/50 text-white flex items-center justify-center hover:bg-pvRed">
                <i class="fa-solid fa-xmark"></i>
            </button>
            <div id="blog-modal-body" class="p-4 sm:p-6"></div>
        </div>
    </div>

    <!-- =====================================================================
         MODAL TÌM KIẾM NHANH SẢN PHẨM
         ===================================================================== -->
    <div id="search-modal" class="fixed inset-0 z-50 hidden items-start justify-center pt-16 p-3 bg-black/60 backdrop-blur-xs">
        <div class="bg-white rounded-2xl max-w-lg w-full p-4 shadow-2xl border border-pvGold">
            <div class="flex items-center justify-between mb-2.5">
                <span class="font-serif font-bold text-sm text-pvRed uppercase">Tìm kiếm mẫu mâm quả & cổng rồng phụng</span>
                <button onclick="toggleSearchModal()" class="w-7 h-7 rounded-full bg-neutral-100 text-neutral-700 flex items-center justify-center">
                    <i class="fa-solid fa-xmark text-xs"></i>
                </button>
            </div>
            <div class="flex gap-2">
                <input type="text" id="search-input" oninput="handleSearchInput(this.value)" placeholder="Nhập tên mâm quả, rồng phụng, cổng cưới, dạm ngõ..."
                       class="flex-1 px-3 py-2 rounded-lg border border-neutral-300 text-xs focus:outline-none focus:border-pvRed">
                <button onclick="toggleSearchModal()" class="px-3.5 py-2 rounded-lg bg-pvRed text-white text-xs font-semibold">Đóng</button>
            </div>
        </div>
    </div>

    <!-- =====================================================================
         JAVASCRIPT XỬ LÝ SLIDER, 15 SẢN PHẨM THỰC TẾ, GIỎ BÁO GIÁ & BÀI VIẾT
         ===================================================================== -->
    <script>
        /* 1. DỮ LIỆU 15 SẢN PHẨM THỰC TẾ TỪ 15 FILE GOOGLE DRIVE CỦA PHÚC VINH */
        const productsData = [
            {
                id: 1,
                driveId: "1wM960UqiGaU4DD0Is6PEZNbS7K8uqMnC",
                name: "Bộ Mâm Quả Cưới Rồng Phụng Truyền Thống Đỏ Vàng Trọn Gói",
                category: "Mâm quả",
                subCategory: "Rồng phụng",
                oldPrice: 4200000,
                price: 3500000,
                discount: 17,
                desc: "Trọn bộ mâm quả cưới hỏi truyền thống kết hợp cặp Rồng Phụng uy nghi, đầy đủ trầu cau, bánh phu thê, xôi gấc, rượu trà và trái cây tươi loại 1 tại Đà Nẵng."
            },
            {
                id: 2,
                driveId: "1m3TYo8P2eRlqJ6iuW5Juu_qAIJDALYvm",
                name: "Bộ 6 Mâm Quả Cưới Hỏi Cao Cấp Kết Hoa Tươi Sang Trọng",
                category: "Mâm quả",
                subCategory: "Mâm quả",
                oldPrice: 3800000,
                price: 3200000,
                discount: 16,
                desc: "Bộ 6 mâm quả cưới hỏi trang trí hoa tươi cao cấp, lễ vật đầy đặn chuẩn phong tục miền Trung, giao tận nhà tại Đà Nẵng."
            },
            {
                id: 3,
                driveId: "1tvcwXRKik38P2x4hVESlQ5p0rUUV0fRD",
                name: "Cổng Cưới Rồng Phụng Song Hỷ Đỏ Vàng Hoàng Gia",
                category: "Cổng cưới",
                subCategory: "Rồng phụng",
                oldPrice: 4500000,
                price: 3600000,
                discount: 20,
                desc: "Cổng cưới Rồng Phụng thiết kế nổi bật, sắc sảo từng chi tiết vảy rồng cánh phụng, mang ý nghĩa tài lộc và viên mãn cho ngày vu quy – tân hôn."
            },
            {
                id: 4,
                driveId: "1FX5nU93YLVN6e45pnB1PzEjFjqyS1pOb",
                name: "Trang Trí Không Gian Lễ Gia Tiên Đỏ Rượu Vang & Vàng Kim",
                category: "Gia tiên",
                subCategory: "Gia tiên",
                oldPrice: 5200000,
                price: 4200000,
                discount: 19,
                desc: "Gói trang trí bàn thờ gia tiên trọn gói bao gồm phông màn, chữ Hỷ, bàn để mâm quả, bàn hai họ và hoa trang trí đồng bộ."
            },
            {
                id: 5,
                driveId: "15kkgHhgr7jLgF5k-Kv9IAH_JfiMs6s31",
                name: "Bộ Mâm Quả Cưới Hỏi Kết Nơ & Hoa Lụa Hiện Đại",
                category: "Mâm quả",
                subCategory: "Mâm quả",
                oldPrice: 3200000,
                price: 2650000,
                discount: 17,
                desc: "Thiết kế mâm quả cưới hỏi hiện đại, tinh tế, phù hợp với cả không gian nhà phố và biệt thự tại Đà Nẵng."
            },
            {
                id: 6,
                driveId: "18Vgd8A-Ti51bzjEg6vPH8VaLol9NgACK",
                name: "Cặp Rồng Phụng Cưới Hỏi Nghệ Thuật Uy Nghi Độc Bản",
                category: "Rồng phụng",
                subCategory: "Rồng Phụng tạo hình từ trái cây",
                oldPrice: 2600000,
                price: 2100000,
                discount: 19,
                desc: "Cặp Rồng Phụng tạo hình tỉ mỉ bởi nghệ nhân Phúc Vinh, kết hợp trầu cau, ớt đỏ và trái cây tươi chọn lọc."
            },
            {
                id: 7,
                driveId: "1TOIbb7pSsn_NdX83E8fQGfuz_jfWs8L9",
                name: "Mâm Quả Rồng Phụng Tạo Hình Từ Trái Cây Tươi Loại 1",
                category: "Rồng Phụng tạo hình từ trái cây",
                subCategory: "Rồng phụng",
                oldPrice: 2800000,
                price: 2300000,
                discount: 18,
                desc: "Tác phẩm Rồng Phụng tạo hình hoàn toàn từ trái cây tươi ngon, giữ độ tươi suốt buổi lễ rước dâu và ăn hỏi."
            },
            {
                id: 8,
                driveId: "15zrmu24uoBsebVAJ0rkOssuGvwGL69q8",
                name: "Cặp Rồng Phụng Xốp Mỹ Thuật Chạm Khắc Tinh Xảo",
                category: "Rồng Phụng xốp mỹ thuật",
                subCategory: "Rồng phụng",
                oldPrice: 3000000,
                price: 2450000,
                discount: 18,
                desc: "Mẫu Rồng Phụng xốp mỹ thuật cao cấp, tạo hình 3D sống động, bền đẹp cho cả cổng cưới và mâm quả."
            },
            {
                id: 9,
                driveId: "1Lxh-4OZ9C2hfNmxnJfNdBh7umBODsYzr",
                name: "Trọn Bộ 7 Mâm Quả Cưới Hỏi Truyền Thống Đà Nẵng",
                category: "Mâm quả",
                subCategory: "Mâm quả",
                oldPrice: 4600000,
                price: 3850000,
                discount: 16,
                desc: "Bộ 7 mâm quả đầy đủ lễ vật: Trầu cau, Rượu thuốc trà, Bánh kem/Bánh phu thê, Xôi gấc gà, Trái cây, Heo quay, Nem chả."
            },
            {
                id: 10,
                driveId: "1puuNxVcDQw4Bf9P-jJEiqXLCfw1pYBO4",
                name: "Decor Cổng Cưới Rồng Phụng Kết Hoa Tươi Trọn Gói",
                category: "Cổng cưới",
                subCategory: "Rồng Phụng xốp mỹ thuật",
                oldPrice: 4900000,
                price: 3950000,
                discount: 19,
                desc: "Mẫu cổng cưới Rồng Phụng bề thế thi công tận nơi tại Đà Nẵng, tạo điểm nhấn chụp hình sang trọng cho hai bên gia đình."
            },
            {
                id: 11,
                driveId: "1wobR6uKHQ6KFvBIIcg6lFavedqajuKgI",
                name: "Trang Trí Lễ Gia Tiên & Bàn Quả Cưới Hỏi Tông Kem Vàng",
                category: "Gia tiên",
                subCategory: "Gia tiên",
                oldPrice: 4800000,
                price: 3900000,
                discount: 19,
                desc: "Không gian gia tiên ấm cúng, thanh lịch với tông kem vàng hoàng gia kết hợp hoa lụa cao cấp."
            },
            {
                id: 12,
                driveId: "1vK8JBdPjXY2j0F6CT3tAh7zBnVDelUoA",
                name: "Mâm Quả Trầu Cau & Trái Cây Kết Rồng Phụng Đẹp Mắt",
                category: "Rồng Phụng tạo hình từ trái cây",
                subCategory: "Mâm quả",
                oldPrice: 2500000,
                price: 2050000,
                discount: 18,
                desc: "Mâm trầu cau cánh phượng và trái cây tạo hình rồng phụng chuẩn lễ nghi truyền thống Việt Nam."
            },
            {
                id: 13,
                driveId: "1RoYMUAnIElD5kf8TAq_1AOaxBwW3-qym",
                name: "Bó Hoa Cưới Cầm Tay Cô Dâu & Hoa Cài Áo Chú Rể",
                category: "Hoa cưới",
                subCategory: "Hoa cưới",
                oldPrice: 950000,
                price: 750000,
                discount: 21,
                desc: "Hoa cưới cầm tay cô dâu kết từ hoa hồng ngoại, hoa baby và lá bạc tươi mới, tặng kèm hoa cài áo chú rể."
            },
            {
                id: 14,
                driveId: "1SlRjCmXVZQ-mjUyZ8MfpUZk8eKY-WTTJ",
                name: "Tráp Lễ Dạm Ngõ Truyền Thống Đầy Đủ Trầu Cau Rượu Trà",
                category: "Dạm Ngõ",
                subCategory: "Dạm Ngõ",
                oldPrice: 1500000,
                price: 1200000,
                discount: 20,
                desc: "Tráp dạm ngõ tinh tế gồm trầu cau tiêm cánh phượng, cặp rượu vang/rượu truyền thống, cặp trà, bánh và trái cây tươi."
            },
            {
                id: 15,
                driveId: "1Zuv4XQwVrYDgbnxIPcD7Y_7BOCKvOxAF",
                name: "Combo Mâm Quả Cưới Hỏi & Tráp Dạm Ngõ Thiết Kế Riêng",
                category: "Dạm Ngõ",
                subCategory: "Mâm quả",
                oldPrice: 3600000,
                price: 2950000,
                discount: 18,
                desc: "Combo tiết kiệm kết hợp tráp lễ dạm ngõ và bộ mâm quả ăn hỏi đồng bộ tông màu theo yêu cầu gia đình."
            }
        ];

        /* 2. DỮ LIỆU BÀI VIẾT CẨM NANG CƯỚI TRANG CHỦ */
        const blogPosts = [
            {
                id: 101,
                category: "Kinh nghiệm mâm quả",
                title: "Mâm Quả Cưới Đà Nẵng Gồm Những Lễ Vật Gì Chuẩn Phong Tục Miền Trung?",
                date: "Cẩm nang cưới Phúc Vinh",
                driveId: "1wM960UqiGaU4DD0Is6PEZNbS7K8uqMnC",
                excerpt: "Tìm hiểu chi tiết 5, 6, 7 mâm quả cưới hỏi truyền thống tại Đà Nẵng gồm trầu cau, rượu trà, bánh phu thê, xôi gấc gà, heo quay và trái cây.",
                content: "Theo phong tục cưới hỏi tại Đà Nẵng và miền Trung, nhà trai thường chuẩn bị từ 5 đến 7 hoặc 9 mâm quả. Trong đó các lễ vật cốt lõi bao gồm: 1. Mâm trầu cau (105 quả cau kèm lá trầu), 2. Mâm trà rượu và nến tơ hồng, 3. Mâm bánh phu thê hoặc bánh kem, 4. Mâm xôi gấc gà luộc hoặc heo quay, 5. Mâm trái cây ngũ quả kết rồng phụng. Tại Phúc Vinh (142 Bùi Tá Hán, Đà Nẵng), mọi lễ vật đều được chuẩn bị tươi mới trong ngày."
            },
            {
                id: 102,
                category: "Xu hướng cổng rồng phụng & gia tiên",
                title: "Ý Nghĩa Cổng Cưới Rồng Phụng & Cách Chọn Cổng Cưới Hợp Không Gian Nhà",
                date: "Xu hướng trang trí",
                driveId: "1tvcwXRKik38P2x4hVESlQ5p0rUUV0fRD",
                excerpt: "Rồng Phụng sum vầy biểu trưng cho hạnh phúc viên mãn, thịnh vượng. Khám phá các mẫu cổng rồng phụng trái cây và xốp mỹ thuật đẹp nhất.",
                content: "Cổng cưới Rồng Phụng từ lâu đã là nét đẹp văn hóa đặc trưng trong lễ cưới Việt Nam. Rồng tượng trưng cho sự mạnh mẽ, uy nghi của chú rể; Phụng tượng trưng cho nét duyên dáng, cao quý của cô dâu. Phúc Vinh cung cấp đa dạng kích thước cổng rồng phụng phù hợp từ nhà mặt phố, kiệt hẻm đến sân vườn biệt thự tại Đà Nẵng."
            },
            {
                id: 103,
                category: "Nghi lễ dạm ngõ & ăn hỏi",
                title: "Lễ Dạm Ngõ Cần Chuẩn Bị Gì? Gợi Ý Các Mẫu Tráp Dạm Ngõ Đẹp Tinh Tế",
                date: "Nghi lễ truyền thống",
                driveId: "1SlRjCmXVZQ-mjUyZ8MfpUZk8eKY-WTTJ",
                excerpt: "Lễ dạm ngõ (lễ xem mặt, bỏ trầu) là buổi gặp gỡ chính thức đầu tiên giữa hai bên gia đình. Cùng Phúc Vinh chuẩn bị tráp dạm ngõ chu đáo nhất.",
                content: "Lễ dạm ngõ không cần quá cầu kỳ nhưng đòi hỏi sự trang trọng, ấm cúng. Một tráp dạm ngõ chuẩn chỉnh tại Đà Nẵng thường có cặp trà, cặp rượu, trầu cau têm cánh phượng, bánh phu thê và hoa quả tươi được kết hoa tươi thanh lịch."
            },
            {
                id: 104,
                category: "Xu hướng cổng rồng phụng & gia tiên",
                title: "Báo Giá Trọn Gói Mâm Quả & Trang Trí Gia Tiên Giá Rẻ Tại Đà Nẵng",
                date: "Bảng giá tham khảo",
                driveId: "1FX5nU93YLVN6e45pnB1PzEjFjqyS1pOb",
                excerpt: "Kinh nghiệm đặt combo mâm quả cưới hỏi kết hợp trang trí bàn thờ gia tiên và cổng hoa cưới giúp tiết kiệm đến 20% chi phí.",
                content: "Khi đặt trọn gói Mâm quả cưới hỏi + Cổng cưới Rồng Phụng + Trang trí Gia tiên tại Phúc Vinh (142 Bùi Tá Hán, P. Ngũ Hành Sơn, Đà Nẵng - Hotline 0934.153.598), cô dâu chú rể sẽ được hưởng mức giá ưu đãi tại xưởng, miễn phí khảo sát và hỗ trợ vận chuyển tận nơi."
            }
        ];

        let selectedQuoteItems = [];
        let currentCategory = "all";

        /* Định dạng tiền tệ VNĐ */
        function formatVND(amount) {
            return amount.toLocaleString("vi-VN") + "₫";
        }

        /* 3. RENDER DANH SÁCH 15 SẢN PHẨM CHUẨN FLATSOME */
        function renderProducts(categoryFilter = "all", keyword = "") {
            const grid = document.getElementById("product-grid");
            if (!grid) return;

            const filtered = productsData.filter(item => {
                const matchCat =
                    categoryFilter === "all" ||
                    item.category.toLowerCase() === categoryFilter.toLowerCase() ||
                    item.subCategory.toLowerCase() === categoryFilter.toLowerCase() ||
                    (categoryFilter.toLowerCase() === "rồng phụng" &&
                        (item.category.toLowerCase().includes("rồng phụng") || item.subCategory.toLowerCase().includes("rồng phụng")));

                const matchKeyword =
                    !keyword ||
                    item.name.toLowerCase().includes(keyword.toLowerCase()) ||
                    item.category.toLowerCase().includes(keyword.toLowerCase());

                return matchCat && matchKeyword;
            });

            if (filtered.length === 0) {
                grid.innerHTML = `
                    <div class="col-span-full bg-white rounded-xl p-6 text-center border border-pvGold/30">
                        <p class="text-sm text-neutral-600">Không tìm thấy mẫu phù hợp. Quý khách vui lòng chọn danh mục khác hoặc gọi <strong>0934.153.598</strong> để xem thêm mẫu mới!</p>
                    </div>
                `;
                return;
            }

            grid.innerHTML = filtered.map(p => `
                <div class="bg-white rounded-xl overflow-hidden border border-pvGold/30 shadow-xs hover:shadow-md transition flex flex-col justify-between group">
                    <div>
                        <!-- Khung ảnh sản phẩm + Badge % giảm giá tròn góc trên bên trái giống Flatsome (Không để nhãn dán phụ) -->
                        <div onclick="openProductModal(${p.id})" class="relative aspect-square w-full overflow-hidden bg-neutral-100 cursor-pointer">
                            <div class="flatsome-onsale-badge">-${p.discount}%</div>
                            <img src="https://drive.google.com/thumbnail?id=${p.driveId}&sz=w700"
                                 onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/${p.driveId}';"
                                 alt="${p.name}"
                                 loading="lazy"
                                 class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                        </div>

                        <!-- Thông tin sản phẩm: Tên sản phẩm hiển thị đầy đủ, không bị cắt chữ hay tràn ra ngoài -->
                        <div class="p-2.5 sm:p-3">
                            <div class="text-[10px] sm:text-[11px] font-medium text-neutral-500 mb-1">
                                ${p.category}
                            </div>
                            <h3 onclick="openProductModal(${p.id})" class="font-semibold text-xs sm:text-[13.5px] text-neutral-800 group-hover:text-pvRed leading-snug break-words cursor-pointer">
                                ${p.name}
                            </h3>
                        </div>
                    </div>

                    <!-- Giá gốc gạch ngang + Giá giảm + Nút chọn báo giá -->
                    <div class="px-2.5 pb-2.5 sm:px-3 sm:pb-3 pt-1 border-t border-neutral-100">
                        <div class="flex flex-wrap items-baseline gap-1.5 mb-2">
                            <span class="text-[11px] text-neutral-400 line-through">${formatVND(p.oldPrice)}</span>
                            <span class="text-xs sm:text-sm font-extrabold text-pvRed">${formatVND(p.price)}</span>
                        </div>
                        <div class="grid grid-cols-2 gap-1.5">
                            <button onclick="addToQuote(${p.id})" class="py-1.5 px-2 rounded-lg bg-pvRed hover:bg-pvRedDark text-white font-semibold text-[11px] transition text-center">
                                Chọn báo giá
                            </button>
                            <button onclick="openProductModal(${p.id})" class="py-1.5 px-2 rounded-lg bg-pvCream hover:bg-pvGoldLight text-pvRed border border-pvGold/40 font-semibold text-[11px] transition text-center">
                                Xem chi tiết
                            </button>
                        </div>
                    </div>
                </div>
            `).join("");
        }

        /* 4. LỌC DANH MỤC SẢN PHẨM */
        function filterCategory(cat, shouldScroll = false) {
            currentCategory = cat;
            renderProducts(cat);

            document.querySelectorAll(".cat-filter-btn").forEach(btn => {
                if (btn.getAttribute("data-cat") === cat) {
                    btn.className = "cat-filter-btn cat-pill-item px-3 py-1.5 rounded-full text-xs font-semibold bg-pvRed text-white border border-pvRed shadow-xs";
                } else {
                    btn.className = "cat-filter-btn cat-pill-item px-3 py-1.5 rounded-full text-xs font-medium bg-white text-neutral-700 border border-pvGold/40 hover:border-pvRed hover:text-pvRed";
                }
            });

            if (shouldScroll) {
                const sec = document.getElementById("san-pham");
                if (sec) sec.scrollIntoView({ behavior: "smooth" });
            }
        }

        /* 5. QUẢN LÝ GIỎ YÊU CẦU BÁO GIÁ */
        function addToQuote(productId) {
            const product = productsData.find(p => p.id === productId);
            if (!product) return;

            if (!selectedQuoteItems.some(item => item.id === productId)) {
                selectedQuoteItems.push(product);
            }
            updateQuoteUI();
            openQuoteScroll();
        }

        function removeQuoteItem(productId) {
            selectedQuoteItems = selectedQuoteItems.filter(item => item.id !== productId);
            updateQuoteUI();
        }

        function clearQuoteItems() {
            selectedQuoteItems = [];
            updateQuoteUI();
        }

        function updateQuoteUI() {
            const badge = document.getElementById("cart-count-badge");
            const countEl = document.getElementById("quote-selected-count");
            const listEl = document.getElementById("quote-selected-list");

            if (badge) badge.textContent = selectedQuoteItems.length;
            if (countEl) countEl.textContent = selectedQuoteItems.length;

            if (!listEl) return;
            if (selectedQuoteItems.length === 0) {
                listEl.innerHTML = `<p class="text-white/65 italic text-xs">Chưa có mẫu nào được chọn. Bạn có thể bấm nút "Chọn báo giá" ở từng sản phẩm phía trên hoặc điền trực tiếp yêu cầu bên cạnh.</p>`;
                return;
            }

            listEl.innerHTML = selectedQuoteItems.map(item => `
                <div class="flex items-center justify-between gap-2 bg-white/10 rounded-lg px-2.5 py-1.5">
                    <span class="text-xs font-medium text-white break-words">${item.name} (${formatVND(item.price)})</span>
                    <button type="button" onclick="removeQuoteItem(${item.id})" class="text-pvGoldLight hover:text-red-300 text-xs shrink-0">
                        <i class="fa-solid fa-trash-can"></i>
                    </button>
                </div>
            `).join("");
        }

        function openQuoteScroll() {
            const sec = document.getElementById("bao-gia");
            if (sec) sec.scrollIntoView({ behavior: "smooth" });
        }

        function submitQuoteForm(e) {
            e.preventDefault();
            const name = document.getElementById("q-name").value.trim();
            const phone = document.getElementById("q-phone").value.trim();
            const date = document.getElementById("q-date").value;
            const service = document.getElementById("q-service").value;
            const note = document.getElementById("q-note").value.trim();
            const feedback = document.getElementById("quote-form-feedback");

            const chosenNames = selectedQuoteItems.map(i => i.name).join(", ");
            feedback.classList.remove("hidden");
            feedback.innerHTML = `
                <div class="font-bold text-emerald-900 mb-1"><i class="fa-solid fa-circle-check mr-1"></i>Đã ghi nhận yêu cầu báo giá của ${name} (${phone})!</div>
                <div>Hạng mục: <strong>${service}</strong> ${date ? `• Ngày dự kiến: <strong>${date}</strong>` : ""}</div>
                ${chosenNames ? `<div class="mt-0.5">Mẫu đã chọn: <strong>${chosenNames}</strong></div>` : ""}
                ${note ? `<div class="mt-0.5">Ghi chú: ${note}</div>` : ""}
                <div class="mt-1.5 text-pvRed font-semibold">Phúc Vinh (Hotline/Zalo: 0934.153.598) sẽ liên hệ tư vấn ngay cho bạn!</div>
            `;
        }

        /* 6. MODAL XEM CHI TIẾT SẢN PHẨM */
        function openProductModal(productId) {
            const p = productsData.find(item => item.id === productId);
            if (!p) return;
            const modal = document.getElementById("product-modal");
            const body = document.getElementById("product-modal-body");

            body.innerHTML = `
                <div class="grid grid-cols-1 md:grid-cols-2 gap-4 items-center">
                    <div class="relative rounded-xl overflow-hidden border border-pvGold">
                        <div class="flatsome-onsale-badge">-${p.discount}%</div>
                        <img src="https://drive.google.com/thumbnail?id=${p.driveId}&sz=w900"
                             onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/${p.driveId}';"
                             alt="${p.name}" class="w-full h-72 sm:h-80 object-cover">
                    </div>
                    <div class="space-y-3">
                        <span class="inline-block px-2.5 py-0.5 rounded-full bg-pvRedLight text-pvRed text-xs font-semibold">${p.category}</span>
                        <h3 class="font-serif font-bold text-lg text-neutral-900 leading-snug">${p.name}</h3>
                        <div class="flex items-baseline gap-2">
                            <span class="text-sm text-neutral-400 line-through">${formatVND(p.oldPrice)}</span>
                            <span class="text-xl font-extrabold text-pvRed">${formatVND(p.price)}</span>
                        </div>
                        <p class="text-xs text-neutral-600 leading-relaxed">${p.desc}</p>
                        <div class="p-3 rounded-lg bg-pvCream border border-pvGold/30 text-xs space-y-1">
                            <div><i class="fa-solid fa-check text-pvRed mr-1.5"></i>Thiết kế theo tông màu & ngân sách riêng</div>
                            <div><i class="fa-solid fa-location-dot text-pvRed mr-1.5"></i>142 Bùi Tá Hán, P. Ngũ Hành Sơn, Đà Nẵng</div>
                            <div><i class="fa-solid fa-phone text-pvRed mr-1.5"></i>Hotline/Zalo: <strong>0934.153.598</strong></div>
                        </div>
                        <div class="flex flex-wrap gap-2 pt-1">
                            <button onclick="addToQuote(${p.id}); closeProductModal();" class="flex-1 py-2.5 px-4 rounded-lg bg-pvRed hover:bg-pvRedDark text-white font-bold text-xs uppercase">
                                Chọn Vào Báo Giá
                            </button>
                            <a href="https://zalo.me/0934153598" target="_blank" rel="noopener noreferrer" class="py-2.5 px-4 rounded-lg bg-pvGold text-neutral-900 font-bold text-xs uppercase">
                                Tư Vấn Zalo
                            </a>
                        </div>
                    </div>
                </div>
            `;
            modal.classList.remove("hidden");
            modal.classList.add("flex");
        }

        function closeProductModal() {
            const modal = document.getElementById("product-modal");
            modal.classList.add("hidden");
            modal.classList.remove("flex");
        }

        /* 7. RENDER DANH MỤC BÀI VIẾT TRANG CHỦ */
        function renderBlogPosts(catFilter = "all") {
            const grid = document.getElementById("blog-grid");
            if (!grid) return;

            const filtered = catFilter === "all"
                ? blogPosts
                : blogPosts.filter(post => post.category === catFilter);

            grid.innerHTML = filtered.map(post => `
                <article class="bg-white rounded-xl overflow-hidden border border-pvGold/30 shadow-xs hover:shadow-md transition flex flex-col justify-between">
                    <div>
                        <div onclick="openBlogModal(${post.id})" class="aspect-video w-full overflow-hidden bg-neutral-100 cursor-pointer">
                            <img src="https://drive.google.com/thumbnail?id=${post.driveId}&sz=w600"
                                 onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/${post.driveId}';"
                                 alt="${post.title}" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                        </div>
                        <div class="p-3.5">
                            <div class="text-[11px] font-semibold text-pvGold uppercase mb-1">${post.category}</div>
                            <h3 onclick="openBlogModal(${post.id})" class="font-serif font-bold text-sm text-neutral-800 hover:text-pvRed leading-snug cursor-pointer mb-1.5">
                                ${post.title}
                            </h3>
                            <p class="text-xs text-neutral-600 leading-relaxed">${post.excerpt}</p>
                        </div>
                    </div>
                    <div class="px-3.5 pb-3.5 pt-1">
                        <button onclick="openBlogModal(${post.id})" class="text-xs font-bold text-pvRed hover:underline flex items-center gap-1">
                            Đọc chi tiết <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </button>
                    </div>
                </article>
            `).join("");
        }

        function filterPosts(cat) {
            renderBlogPosts(cat);
            document.querySelectorAll(".post-cat-btn").forEach(btn => {
                if (btn.getAttribute("data-post-cat") === cat) {
                    btn.className = "post-cat-btn cat-pill-item px-3 py-1.5 rounded-full text-xs font-semibold bg-pvRed text-white border border-pvRed";
                } else {
                    btn.className = "post-cat-btn cat-pill-item px-3 py-1.5 rounded-full text-xs font-medium bg-white text-neutral-700 border border-pvGold/40 hover:border-pvRed";
                }
            });
        }

        function openBlogModal(postId) {
            const post = blogPosts.find(p => p.id === postId);
            if (!post) return;
            const modal = document.getElementById("blog-modal");
            const body = document.getElementById("blog-modal-body");

            body.innerHTML = `
                <div class="space-y-3">
                    <span class="inline-block px-2.5 py-0.5 rounded-full bg-pvRedLight text-pvRed text-xs font-semibold">${post.category}</span>
                    <h3 class="font-serif font-bold text-lg sm:text-xl text-pvRed leading-snug">${post.title}</h3>
                    <div class="rounded-xl overflow-hidden border border-pvGold h-56 sm:h-64">
                        <img src="https://drive.google.com/thumbnail?id=${post.driveId}&sz=w800"
                             onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/${post.driveId}';"
                             alt="${post.title}" class="w-full h-full object-cover">
                    </div>
                    <p class="text-xs sm:text-sm text-neutral-700 leading-relaxed">${post.content}</p>
                    <div class="p-3 rounded-xl bg-pvCream border border-pvGold/30 text-xs">
                        <strong>Phúc Vinh - Mâm Quả Cưới Đà Nẵng (phucvinh.com)</strong><br>
                        Địa chỉ: 142 Bùi Tá Hán, Phường Ngũ Hành Sơn, Tp. Đà Nẵng • Hotline/Zalo: 0934.153.598
                    </div>
                </div>
            `;
            modal.classList.remove("hidden");
            modal.classList.add("flex");
        }

        function closeBlogModal() {
            const modal = document.getElementById("blog-modal");
            modal.classList.add("hidden");
            modal.classList.remove("flex");
        }

        /* 8. ĐIỀU KHIỂN SLIDER 2 BANNER TỰ TRƯỢT ĐỒNG BỘ MÁY TÍNH & ĐIỆN THOẠI */
        let currentSlide = 0;
        const totalSlides = 2;
        let bannerInterval = null;

        function updateBannerSlides() {
            const desktopSlides = document.querySelectorAll(".banner-slide-desktop");
            const mobileSlides = document.querySelectorAll(".banner-slide-mobile");
            const dot0 = document.getElementById("banner-dot-0");
            const dot1 = document.getElementById("banner-dot-1");

            desktopSlides.forEach((sl, idx) => {
                if (idx === currentSlide) {
                    sl.classList.remove("opacity-0", "z-0");
                    sl.classList.add("opacity-100", "z-10");
                } else {
                    sl.classList.remove("opacity-100", "z-10");
                    sl.classList.add("opacity-0", "z-0");
                }
            });

            mobileSlides.forEach((sl, idx) => {
                if (idx === currentSlide) {
                    sl.classList.remove("opacity-0", "z-0");
                    sl.classList.add("opacity-100", "z-10");
                } else {
                    sl.classList.remove("opacity-100", "z-10");
                    sl.classList.add("opacity-0", "z-0");
                }
            });

            if (dot0 && dot1) {
                if (currentSlide === 0) {
                    dot0.className = "w-6 h-2 rounded-full bg-pvGold transition-all";
                    dot1.className = "w-2 h-2 rounded-full bg-white/50 transition-all";
                } else {
                    dot0.className = "w-2 h-2 rounded-full bg-white/50 transition-all";
                    dot1.className = "w-6 h-2 rounded-full bg-pvGold transition-all";
                }
            }
        }

        function nextBannerSlide() {
            currentSlide = (currentSlide + 1) % totalSlides;
            updateBannerSlides();
        }

        function prevBannerSlide() {
            currentSlide = (currentSlide - 1 + totalSlides) % totalSlides;
            updateBannerSlides();
        }

        function goToBannerSlide(index) {
            currentSlide = index;
            updateBannerSlides();
        }

        /* 9. MENU MOBILE & TÌM KIẾM */
        function toggleMobileMenu() {
            const drawer = document.getElementById("mobile-menu-drawer");
            if (drawer) drawer.classList.toggle("hidden");
        }

        function toggleSearchModal() {
            const modal = document.getElementById("search-modal");
            if (!modal) return;
            modal.classList.toggle("hidden");
            modal.classList.toggle("flex");
            if (!modal.classList.contains("hidden")) {
                setTimeout(() => document.getElementById("search-input")?.focus(), 100);
            }
        }

        function handleSearchInput(val) {
            renderProducts("all", val);
            const sec = document.getElementById("san-pham");
            if (sec && val.length > 1) sec.scrollIntoView({ behavior: "smooth" });
        }

        /* KHỞI CHẠY TRANG WEB */
        window.addEventListener("DOMContentLoaded", () => {
            renderProducts("all");
            renderBlogPosts("all");
            bannerInterval = setInterval(nextBannerSlide, 5500);
        });
    </script>
</body>
</html>
