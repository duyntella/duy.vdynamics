<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vindynamics | Physical AI Strategy</title>
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;600;800&family=Montserrat:wght@900&display=swap" rel="stylesheet">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">
    <style>
        :root {
            --bg-main: #f8f9fa;
            --primary-green: #10b981;
            --primary-green-soft: rgba(16, 185, 129, 0.1);
            --primary-gradient: linear-gradient(135deg, #34d399 0%, #059669 100%);
            --card-bg: #ffffff;
            --card-border: rgba(0, 0, 0, 0.08);
            --text-main: #1a1a1a;
            --text-muted: #6c757d;
            --sidebar-width: 320px;
            --sidebar-bg: #064e3b;
        }

        * { margin: 0; padding: 0; box-sizing: border-box; }

        body {
            font-family: 'Plus Jakarta Sans', sans-serif;
            background-color: var(--bg-main);
            color: var(--text-main);
            height: 100vh;
            display: flex;
            overflow: hidden;
        }

        /* Sidebar */
        .sidebar {
            width: var(--sidebar-width);
            min-width: var(--sidebar-width);
            padding: 30px 15px;
            background: var(--sidebar-bg);
            border-right: 1px solid var(--card-border);
            display: flex;
            flex-direction: column;
            overflow-y: auto;
        }

        .logo {
            display: flex;
            align-items: center;
            gap: 12px;
            margin-bottom: 30px;
            font-family: 'Montserrat', sans-serif;
            font-size: 0.75rem;
            letter-spacing: 2px;
            padding-left: 10px;
            color: #fff;
        }

        .tcb-logo-box {
            width: 35px;
            height: 22px;
            background: var(--primary-gradient);
            display: flex;
            align-items: center;
            justify-content: center;
            border-radius: 2px;
        }

        .nav-btn {
            padding: 12px 18px;
            margin-bottom: 4px;
            border-radius: 10px;
            cursor: pointer;
            color: #a7f3d0;
            font-weight: 600;
            font-size: 0.8rem;
            transition: all 0.3s ease;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .nav-btn:hover { background: rgba(255,255,255,0.05); color: #fff; }
        .nav-btn.active { background: var(--primary-gradient); color: #fff; }

        /* Main Area */
        .main {
            flex-grow: 1;
            padding: 40px 5%;
            overflow-y: auto;
        }

        .header-flex { display: flex; align-items: center; margin-bottom: 30px; }
        .big-id {
            font-family: 'Montserrat', sans-serif;
            font-size: 5rem;
            color: rgba(16, 185, 129, 0.1);
            line-height: 0.8;
            margin-right: 20px;
        }

        h1 {
            font-size: 2.5rem;
            font-weight: 800;
            text-transform: uppercase;
            letter-spacing: -1px;
            color: #064e3b;
        }

        /* Formatting Toolkit */
        .hl-red {
            background: linear-gradient(to top, var(--primary-green-soft) 45%, transparent 45%);
            display: inline;
            padding: 0 2px;
            font-weight: 700;
            color: #059669;
        }

        .data-chip {
            display: inline-block;
            background: var(--primary-green-soft);
            border: 1px solid rgba(16, 185, 129, 0.2);
            padding: 1px 10px;
            border-radius: 50px;
            color: #059669;
            font-weight: 800;
            margin: 0 2px;
            font-size: 1rem;
            vertical-align: middle;
        }

        .quote-block {
            background: #fff;
            border-left: 5px solid var(--primary-green);
            padding: 20px 30px;
            margin: 25px 0;
            border-radius: 0 15px 15px 0;
            box-shadow: 0 10px 30px rgba(0,0,0,0.05);
        }

        .quote-block p {
            font-size: 1.4rem;
            font-weight: 700;
            color: #059669;
            line-height: 1.4;
            font-style: italic;
        }
        .quote-author {
            display: block;
            margin-top: 10px;
            font-weight: 600;
            color: var(--text-muted);
            font-size: 0.9rem;
        }

        .card {
            background: var(--card-bg);
            border: 1px solid var(--card-border);
            border-radius: 20px;
            padding: 35px;
            margin-bottom: 25px;
            box-shadow: 0 4px 20px rgba(0,0,0,0.02);
        }

        .section-title {
            color: #059669;
            font-weight: 800;
            font-size: 1.4rem;
            margin-bottom: 20px;
            display: block;
            text-transform: uppercase;
            border-bottom: 2px solid var(--primary-green-soft);
            padding-bottom: 10px;
        }

        p { font-size: 1.1rem; line-height: 1.6; margin-bottom: 15px; color: #333; }

        /* Table Styles */
        table { width: 100%; border-collapse: collapse; margin: 20px 0; font-size: 1rem; }
        th { background: #f1f5f9; color: #064e3b; font-weight: 700; text-align: left; padding: 12px; border: 1px solid #e2e8f0; }
        td { padding: 12px; border: 1px solid #e2e8f0; color: #444; }
        tr:nth-child(even) { background-color: #fafafa; }

        ul { list-style: none; margin-top: 15px; }
        li {
            font-size: 1.1rem;
            margin-bottom: 12px;
            padding-left: 30px;
            position: relative;
            line-height: 1.5;
        }
        li::before {
            content: "→";
            position: absolute;
            left: 0;
            color: var(--primary-green);
            font-weight: 800;
        }

        /* Flow chain */
        .flow-chain {
            display: flex;
            flex-direction: column;
            gap: 0;
            margin: 20px 0;
        }
        .flow-item {
            background: var(--primary-green-soft);
            border-left: 4px solid var(--primary-green);
            padding: 10px 20px;
            font-weight: 600;
            font-size: 1rem;
            color: #064e3b;
            border-radius: 0 8px 8px 0;
            margin-bottom: 2px;
        }
        .flow-arrow {
            color: var(--primary-green);
            font-size: 1.2rem;
            text-align: left;
            padding-left: 20px;
            line-height: 1;
            margin-bottom: 2px;
        }

        /* Trust stack */
        .trust-item {
            display: flex;
            align-items: flex-start;
            gap: 15px;
            padding: 14px 20px;
            background: #f8fffe;
            border: 1px solid rgba(16,185,129,0.15);
            border-radius: 12px;
            margin-bottom: 10px;
        }
        .trust-icon {
            font-size: 1.4rem;
            min-width: 28px;
            text-align: center;
        }
        .trust-text strong { color: #064e3b; font-size: 1rem; display: block; }
        .trust-text span { color: #555; font-size: 0.95rem; }

        /* Moat layers */
        .moat-card {
            display: flex;
            align-items: flex-start;
            gap: 18px;
            background: #fff;
            border: 1px solid var(--card-border);
            border-radius: 14px;
            padding: 22px 25px;
            margin-bottom: 15px;
            box-shadow: 0 2px 12px rgba(0,0,0,0.03);
        }
        .moat-num {
            font-family: 'Montserrat', sans-serif;
            font-size: 2.5rem;
            color: rgba(16,185,129,0.18);
            line-height: 1;
            font-weight: 900;
            min-width: 50px;
        }
        .moat-body strong { color: #064e3b; font-size: 1.05rem; display: block; margin-bottom: 4px; }
        .moat-body span { color: #555; font-size: 1rem; line-height: 1.5; }

        /* Phase cards */
        .phase-row {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 18px;
            margin-bottom: 18px;
        }
        .phase-card {
            background: #fff;
            border: 1px solid var(--card-border);
            border-radius: 14px;
            padding: 20px 22px;
            border-top: 4px solid var(--primary-green);
        }
        .phase-label {
            font-family: 'Montserrat', sans-serif;
            font-size: 0.7rem;
            letter-spacing: 2px;
            color: #059669;
            font-weight: 900;
            margin-bottom: 5px;
        }
        .phase-title { font-size: 1.1rem; font-weight: 800; color: #064e3b; margin-bottom: 10px; }
        .phase-card ul { margin-top: 0; }
        .phase-card li { font-size: 0.95rem; margin-bottom: 8px; }

        /* Revenue model */
        .rev-group { margin-bottom: 20px; }
        .rev-label {
            display: inline-flex;
            align-items: center;
            gap: 8px;
            background: var(--primary-gradient);
            color: #fff;
            font-weight: 800;
            font-size: 0.85rem;
            padding: 5px 16px;
            border-radius: 50px;
            margin-bottom: 10px;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        /* Platform function items */
        .platform-item {
            display: flex;
            align-items: flex-start;
            gap: 16px;
            padding: 16px 20px;
            background: #fafffe;
            border: 1px solid rgba(16,185,129,0.12);
            border-radius: 12px;
            margin-bottom: 10px;
        }
        .platform-num {
            background: var(--primary-gradient);
            color: #fff;
            font-weight: 900;
            font-size: 0.85rem;
            width: 30px;
            height: 30px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            min-width: 30px;
        }
        .platform-body strong { color: #064e3b; font-size: 1rem; display: block; margin-bottom: 3px; }
        .platform-body span { color: #555; font-size: 0.95rem; line-height: 1.5; }

        /* Contributor */
        .contrib-col { display: grid; grid-template-columns: 1fr 1fr; gap: 20px; margin-top: 15px; }
        .contrib-box {
            background: #fff;
            border: 1px solid var(--card-border);
            border-radius: 14px;
            padding: 20px 22px;
        }
        .contrib-box .section-title { font-size: 1.1rem; margin-bottom: 12px; }

        .tab-content { display: none; }
        .tab-content.active { display: block; animation: fadeIn 0.4s ease; }

        @keyframes fadeIn { from { opacity: 0; transform: translateY(10px); } to { opacity: 1; transform: translateY(0); } }
        ::-webkit-scrollbar { width: 6px; }
        ::-webkit-scrollbar-thumb { background: #cbd5e1; border-radius: 10px; }
    </style>
</head>
<body>

    <aside class="sidebar">
        <div class="logo">
            <div class="tcb-logo-box"></div>
            <span>VINDYNAMICS<br>VDX ROBOTICS PLATFORM</span>
        </div>
        <nav class="nav-group">
            <div class="nav-btn active" onclick="showTab(event, 'sec1', '01')">1. CHANGING WORLD</div>
            <div class="nav-btn" onclick="showTab(event, 'sec2', '02')">2. PAINPOINT</div>
            <div class="nav-btn" onclick="showTab(event, 'sec3', '03')">3. THỊ TRƯỜNG</div>
            <div class="nav-btn" onclick="showTab(event, 'sec4', '04')">4. GIẢI PHÁP</div>
            <div class="nav-btn" onclick="showTab(event, 'sec5', '05')">5. KHÁCH HÀNG MỤC TIÊU</div>
            <div class="nav-btn" onclick="showTab(event, 'sec6', '06')">6. MÔ HÌNH NỀN TẢNG</div>
            <div class="nav-btn" onclick="showTab(event, 'sec7', '07')">7. TRUST INFRASTRUCTURE</div>
            <div class="nav-btn" onclick="showTab(event, 'sec8', '08')">8. LỢI THẾ CẠNH TRANH</div>
            <div class="nav-btn" onclick="showTab(event, 'sec9', '09')">9. ROADMAP</div>
            <div class="nav-btn" onclick="showTab(event, 'sec10', '10')">10. MÔ HÌNH DOANH THU</div>
            <div class="nav-btn" onclick="showTab(event, 'sec11', '11')">11. PLATFORM FUNCTION</div>
            <div class="nav-btn" onclick="showTab(event, 'sec12', '12')">12. CONTRIBUTOR ACQUISITION</div>
        </nav>
    </aside>

    <main class="main">
        <div class="header-flex">
            <div id="project-num" class="big-id">01</div>
            <h1 id="tab-title">CHANGING WORLD</h1>
        </div>

        <!-- SECTION 1: CHANGING WORLD -->
        <div id="sec1" class="tab-content active">
            <div class="card">
                <span class="section-title">Năm làn sóng công nghệ</span>
                <p>"Mỗi robot được bán ra hôm nay đang <span class="hl-red">mù</span>. Không phải vì phần cứng tệ — mà vì không có dữ liệu để dạy nó nhìn và làm việc."</p>

                <table>
                    <thead>
                        <tr>
                            <th>Giai đoạn</th>
                            <th>Tài sản cốt lõi</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr><td>Internet</td><td>Nội dung</td></tr>
                        <tr><td>Cloud</td><td>Compute</td></tr>
                        <tr><td>LLM</td><td>Text datasets</td></tr>
                        <tr><td>Autonomous Driving</td><td>Driving data</td></tr>
                        <tr><td><strong>Robotics</strong></td><td><strong>Physical interaction data</strong></td></tr>
                    </tbody>
                </table>

                <p>Mỗi làn sóng có 1 loại dữ liệu then chốt. <span class="hl-red">Physical AI</span> cần dữ liệu tương tác thực tế — và đó là thứ <span class="hl-red">chưa ai có đủ</span>.</p>

                <div class="quote-block">
                    <p>"Bất cứ ai xây dựng được cơ sở hạ tầng để thu thập, dán nhãn và phân phối dữ liệu robot sẽ sở hữu tài sản chiến lược nhất trong lĩnh vực Trí tuệ Nhân tạo Vật lý — giống như ImageNet đã từng làm cho Computer Vision."</p>
                    <span class="quote-author">— Reddit Robotics Engineer Community</span>
                </div>
            </div>
        </div>

        <!-- SECTION 2: PAINPOINT -->
        <div id="sec2" class="tab-content">
            <div class="card">
                <span class="section-title">Bài toán dữ liệu (Painpoint)</span>
                <p>Một chuỗi khách sạn muốn tự động hóa dọn phòng. Họ mua robot. Họ thuê team AI. Sau <span class="data-chip">6 tháng</span> và <span class="data-chip">$300.000</span> — họ vẫn chưa có đủ dữ liệu để robot biết cách <span class="hl-red">gấp chăn</span>.</p>

                <p><strong>Ví dụ 1: Công việc đơn giản — Cầm &amp; Đặt</strong></p>
                <ul>
                    <li><span class="data-chip">5.000–20.000</span> demonstrations cần thiết</li>
                    <li>~<span class="data-chip">2–6 kỹ sư</span> làm việc trong <span class="data-chip">2–8 tuần</span></li>
                    <li>Chi phí: <span class="data-chip">$50.000–$500.000</span> chỉ để thu thập dữ liệu</li>
                </ul>

                <p><strong>Ví dụ 2: Để huấn luyện robot gấp chăn và làm giường:</strong></p>
                <ul>
                    <li><span class="data-chip">500 phòng</span> khác nhau</li>
                    <li><span class="data-chip">20 loại</span> ga và chăn</li>
                    <li><span class="data-chip">10.000 demonstrations</span> — Video + force + trajectory</li>
                    <li>Failure cases + Synthetic data + Benchmark tests</li>
                    <li>Chi phí thực tế lên tới <span class="hl-red">hàng trăm nghìn USD</span> trước khi đạt mức sẵn sàng thương mại</li>
                </ul>

                <p>Robot chỉ là <span class="data-chip">20–30%</span> bài toán. <span class="hl-red">70–80% nằm ở data, AI và domain expertise</span>.</p>

                <div class="quote-block">
                    <p>"Dữ liệu là nguồn tài nguyên quý giá như dầu mỏ – nhưng trong lĩnh vực robot, dữ liệu giống như nhiên liệu máy bay phản lực đã được tinh chế. Chúng ta không thể chỉ đơn giản khai thác từ lòng đất mà phải tinh chế từng giọt."</p>
                    <span class="quote-author">— Vindynamics Platform Team</span>
                </div>
            </div>
        </div>

        <!-- SECTION 3: THỊ TRƯỜNG -->
        <div id="sec3" class="tab-content">
            <div class="card">
                <span class="section-title">Tiềm năng thị trường</span>
                <ul>
                    <li><strong>Industrial Robotics:</strong> <span class="data-chip">$34B</span> → <span class="data-chip">$70.6B</span> (CAGR <span class="data-chip">13%</span>)</li>
                    <li><strong>Warehouse Automation:</strong> <span class="data-chip">$10.1B</span> → <span class="data-chip">$28.3B</span> (CAGR <span class="data-chip">17.7%</span>)</li>
                    <li><strong>Service Robots:</strong> Vượt <span class="data-chip">$168B</span> vào năm 2033</li>
                    <li><strong>Humanoid Robots:</strong> CAGR <span class="data-chip">35–40%</span></li>
                </ul>

                <p>Nhưng thị trường <span class="hl-red">THỰC SỰ</span> mà Vindynamics nhắm đến là:</p>
                <p style="font-size:1.3rem; font-weight:800; color:#064e3b; text-align:center; padding: 20px; background: var(--primary-green-soft); border-radius: 12px; margin: 15px 0;">
                    Physical AI Training Data<br>
                    <span style="font-size:1rem; font-weight:600; color:#059669;">— Nút thắt cổ chai của toàn ngành —</span>
                </p>
                <p><span class="hl-red">Chưa có công ty nào thống trị.</span> Cửa sổ cơ hội đang mở.</p>

                <div class="quote-block">
                    <p>"Trong kỷ nguyên Physical AI, Robot sẽ trở thành hàng hóa thông dụng. Dữ liệu, mô hình và hệ sinh thái sẽ là những tài sản chiến lược nhất."</p>
                    <span class="quote-author">— Vindynamics Platform Team</span>
                </div>
            </div>
        </div>

        <!-- SECTION 4: GIẢI PHÁP -->
        <div id="sec4" class="tab-content">
            <div class="card">
                <span class="section-title">Giải pháp: Robot Skill Package</span>
                <p>Chúng tôi <span class="hl-red">không bán dữ liệu thô</span> — chúng tôi bán <span class="hl-red">kết quả</span>:</p>
                <p style="text-align:center; padding: 18px; background: var(--primary-green-soft); border-radius:10px; font-size:1.2rem; font-weight:700; color:#064e3b; margin-bottom:20px;">
                    Thay vì bán: <span style="color:#888;">"8TB dữ liệu training Robot"</span><br>
                    → Bán: <span class="hl-red">"Robot biết làm công việc X"</span>
                </p>

                <p><strong>Mô hình tương tự Apple:</strong></p>
                <ul>
                    <li>iPhone = <span class="hl-red">Robot phần cứng</span></li>
                    <li>iOS = <span class="hl-red">AI software</span></li>
                    <li>App Store = <span class="hl-red">Robot Skill Store</span></li>
                    <li>App = <span class="hl-red">Robot Skill Package</span></li>
                </ul>

                <p style="margin-top:20px;"><strong>Mỗi Skill Package bao gồm:</strong></p>
                <ul>
                    <li>✓ AI model đã được luyện sẵn theo ngành</li>
                    <li>✓ SOP chuẩn ngành</li>
                    <li>✓ Hướng dẫn triển khai</li>
                    <li>✓ Benchmark kết quả</li>
                    <li>✓ Gợi ý hardware</li>
                </ul>

                <p style="margin-top:20px;"><strong>Ví dụ các kỹ năng:</strong></p>
                <ul>
                    <li>Kỹ năng lấy hàng trong kho</li>
                    <li>Kỹ năng giao hàng cho khách sạn</li>
                    <li>Kỹ năng xếp hàng lên pallet</li>
                    <li>Kỹ năng kiểm tra hàng lỗi</li>
                </ul>

                <div class="quote-block">
                    <p>"Chúng ta không bán bộ dữ liệu. Chúng ta bán những con robot đã biết cách làm việc. Sự khác biệt giống như việc bán bột mì thô so với bán một món ăn đạt chuẩn Michelin."</p>
                </div>
            </div>
        </div>

        <!-- SECTION 5: KHÁCH HÀNG MỤC TIÊU -->
        <div id="sec5" class="tab-content">
            <div class="card">
                <span class="section-title">Người bán (Supply Side)</span>
                <table>
                    <thead>
                        <tr>
                            <th>Nhóm</th>
                            <th>Khả năng tạo dữ liệu</th>
                            <th>Động lực kiếm tiền</th>
                            <th>Mức độ ưu tiên</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr><td><strong>Integrators</strong></td><td>Rất cao</td><td>Rất cao</td><td>⭐⭐⭐⭐⭐</td></tr>
                        <tr><td><strong>Enterprise users</strong></td><td>Rất cao</td><td>Cao</td><td>⭐⭐⭐⭐⭐</td></tr>
                        <tr><td>Robotics labs</td><td>Rất cao</td><td>Trung bình–Cao</td><td>⭐⭐⭐⭐</td></tr>
                        <tr><td>Universities</td><td>Cao</td><td>Trung bình</td><td>⭐⭐⭐</td></tr>
                        <tr><td>Domain consultants</td><td>Trung bình</td><td>Cao</td><td>⭐⭐⭐</td></tr>
                    </tbody>
                </table>

                <span class="section-title" style="margin-top:25px;">Người mua (Demand Side)</span>
                <table>
                    <thead>
                        <tr>
                            <th>Nhóm</th>
                            <th>Ngân sách</th>
                            <th>Nhu cầu</th>
                            <th>Tốc độ mua</th>
                            <th>Mức độ ưu tiên</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr><td><strong>Robotics startups</strong></td><td>Rất cao</td><td>Rất cao</td><td>Nhanh</td><td>⭐⭐⭐⭐⭐</td></tr>
                        <tr><td><strong>Service robot vendors</strong></td><td>Rất cao</td><td>Rất cao</td><td>Nhanh</td><td>⭐⭐⭐⭐⭐</td></tr>
                        <tr><td><strong>Warehouse automation</strong></td><td>Rất cao</td><td>Rất cao</td><td>Nhanh</td><td>⭐⭐⭐⭐⭐</td></tr>
                        <tr><td>Manufacturers</td><td>Cao</td><td>Cao</td><td>Trung bình</td><td>⭐⭐⭐⭐</td></tr>
                        <tr><td>Enterprise triển khai nội bộ</td><td>Cao</td><td>Cao</td><td>Trung bình</td><td>⭐⭐⭐⭐</td></tr>
                        <tr><td>Research institutions</td><td>Trung bình</td><td>Cao</td><td>Chậm</td><td>⭐⭐⭐</td></tr>
                    </tbody>
                </table>
            </div>
        </div>

        <!-- SECTION 6: MÔ HÌNH NỀN TẢNG -->
        <div id="sec6" class="tab-content">
            <div class="card">
                <span class="section-title">6.1. Chuỗi giá trị tổng thể</span>
                <div class="flow-chain">
                    <div class="flow-item">Kiến thức chuyên môn</div>
                    <div class="flow-arrow">↓</div>
                    <div class="flow-item">Quy trình vận hành tiêu chuẩn (SOP) / Mẫu quy trình</div>
                    <div class="flow-arrow">↓</div>
                    <div class="flow-item">Video minh họa</div>
                    <div class="flow-arrow">↓</div>
                    <div class="flow-item" style="font-weight:800; color:#059669;">Dữ liệu huấn luyện robot</div>
                    <div class="flow-arrow">↓</div>
                    <div class="flow-item">Các mô hình được tinh chỉnh</div>
                    <div class="flow-arrow">↓</div>
                    <div class="flow-item" style="font-weight:800; color:#059669;">Các gói kỹ năng / nhiệm vụ của robot</div>
                    <div class="flow-arrow">↓</div>
                    <div class="flow-item">Mẫu triển khai</div>
                    <div class="flow-arrow">↓</div>
                    <div class="flow-item">Bán hàng robot + phần mềm</div>
                    <div class="flow-arrow">↓</div>
                    <div class="flow-item">Phản hồi dữ liệu sử dụng → Cải tiến liên tục</div>
                </div>
                <p style="margin-top:15px;">Dữ liệu chỉ là nguyên liệu đầu vào; sản phẩm khách hàng sẵn sàng mua là: <span class="data-chip">Robot Skills</span> <span class="data-chip">Industry Templates</span> <span class="data-chip">AI Package</span> <span class="data-chip">Giải pháp trọn gói</span></p>
            </div>

            <div class="card">
                <span class="section-title">6.2. Customer Journey — Người bán (Contributor)</span>
                <div class="flow-chain">
                    <div class="flow-item">Sở hữu chuyên môn hoặc dữ liệu vận hành</div>
                    <div class="flow-arrow">↓</div>
                    <div class="flow-item">Tải lên SOP / video / mẫu quy trình</div>
                    <div class="flow-arrow">↓</div>
                    <div class="flow-item">Nền tảng chuẩn hóa nội dung</div>
                    <div class="flow-arrow">↓</div>
                    <div class="flow-item">Vindynamics tuyển chọn và đóng gói</div>
                    <div class="flow-arrow">↓</div>
                    <div class="flow-item">Chuyển đổi thành <strong>Kỹ năng Robot</strong></div>
                    <div class="flow-arrow">↓</div>
                    <div class="flow-item">Được xuất bản lên Cửa hàng Kỹ năng</div>
                    <div class="flow-arrow">↓</div>
                    <div class="flow-item" style="font-weight:800; color:#059669;">Giao dịch bán hàng → Contributor nhận Revenue Share</div>
                </div>
                <p style="margin-top:15px;">Vindynamics đóng vai trò: <span class="data-chip">Curator</span> <span class="data-chip">Productizer</span> <span class="data-chip">Distributor</span> <span class="data-chip">Revenue Operator</span></p>
            </div>

            <div class="card">
                <span class="section-title">6.3. Customer Journey — Người mua (Enterprise)</span>
                <div class="flow-chain">
                    <div class="flow-item">Cần trường hợp sử dụng tự động hóa</div>
                    <div class="flow-arrow">↓</div>
                    <div class="flow-item">Tìm kiếm theo ngành hoặc nhiệm vụ</div>
                    <div class="flow-arrow">↓</div>
                    <div class="flow-item">Tìm gói kỹ năng robot phù hợp</div>
                    <div class="flow-arrow">↓</div>
                    <div class="flow-item">Xem ROI và yêu cầu triển khai</div>
                    <div class="flow-arrow">↓</div>
                    <div class="flow-item">Mua Robot + Phần mềm</div>
                    <div class="flow-arrow">↓</div>
                    <div class="flow-item">Triển khai nhanh chóng</div>
                    <div class="flow-arrow">↓</div>
                    <div class="flow-item" style="font-weight:800; color:#059669;">Cung cấp dữ liệu vận hành → Gia hạn và mở rộng</div>
                </div>
                <p style="margin-top:15px;"><strong>Khách hàng mua:</strong> Kỹ năng lấy hàng trong kho · Giao hàng đến phòng · Dọn giường · Xếp hàng lên pallet</p>
            </div>
        </div>

        <!-- SECTION 7: TRUST INFRASTRUCTURE -->
        <div id="sec7" class="tab-content">
            <div class="card">
                <span class="section-title">Trust Infrastructure (Hạ tầng tin cậy)</span>
                <p>Khác biệt với marketplace thông thường: Vindynamics không chỉ kết nối người mua–bán. Vindynamics là <span class="hl-red">người kiểm định, chuẩn hóa, bảo vệ và phân phối</span>.</p>

                <p style="font-weight:700; color:#064e3b; margin: 20px 0 10px;">Trust Stack:</p>

                <div class="trust-item">
                    <div class="trust-icon">🔷</div>
                    <div class="trust-text">
                        <strong>Validation Engine</strong>
                        <span>Kiểm tra chất lượng tự động — đảm bảo mọi dataset đạt tiêu chuẩn trước khi đưa lên store</span>
                    </div>
                </div>
                <div class="trust-item">
                    <div class="trust-icon">🔷</div>
                    <div class="trust-text">
                        <strong>Human Review</strong>
                        <span>Đội ngũ chuyên gia kỹ thuật kiểm duyệt thủ công các gói kỹ năng quan trọng</span>
                    </div>
                </div>
                <div class="trust-item">
                    <div class="trust-icon">🔷</div>
                    <div class="trust-text">
                        <strong>Watermarking</strong>
                        <span>Truy vết mọi bản sao dữ liệu — bảo vệ tài sản trí tuệ của contributor</span>
                    </div>
                </div>
                <div class="trust-item">
                    <div class="trust-icon">🔷</div>
                    <div class="trust-text">
                        <strong>Escrow Payments</strong>
                        <span>Giải ngân sau nghiệm thu — đảm bảo quyền lợi cả hai phía</span>
                    </div>
                </div>
                <div class="trust-item">
                    <div class="trust-icon">🔷</div>
                    <div class="trust-text">
                        <strong>Audit Monitoring</strong>
                        <span>Theo dõi hành vi sử dụng — phát hiện vi phạm license</span>
                    </div>
                </div>
                <div class="trust-item">
                    <div class="trust-icon">🔷</div>
                    <div class="trust-text">
                        <strong>Reputation System</strong>
                        <span>Verified contributor badges — xây dựng uy tín dài hạn cho người cung cấp dữ liệu</span>
                    </div>
                </div>

                <p style="margin-top:18px; font-weight:700; color:#059669;">Kết quả: Người mua tin tưởng mua. Người bán tin tưởng bán.</p>

                <div class="quote-block">
                    <p>"Nền tảng của chúng ta là sự kết hợp giữa GitHub, App Store và AWS Data Exchange — với cơ sở hạ tầng đáng tin cậy để bảo vệ những tài sản trí tuệ quý giá nhất trong kỷ nguyên Physical AI."</p>
                </div>
            </div>
        </div>

        <!-- SECTION 8: LỢI THẾ CẠNH TRANH -->
        <div id="sec8" class="tab-content">
            <div class="card">
                <span class="section-title">Lợi thế cạnh tranh (Moats)</span>

                <div class="moat-card">
                    <div class="moat-num">L1</div>
                    <div class="moat-body">
                        <strong>🏆 DATA MOAT</strong>
                        <span>Dữ liệu tích lũy theo thời gian — AI ngày càng tốt hơn. <span class="hl-red">Không thể mua hoặc copy overnight.</span></span>
                    </div>
                </div>

                <div class="moat-card">
                    <div class="moat-num">L2</div>
                    <div class="moat-body">
                        <strong>🏆 NETWORK EFFECT</strong>
                        <span>Thêm người bán → nhiều skills hơn → nhiều khách hàng hơn → nhiều dữ liệu hơn → <span class="hl-red">vòng lặp tự tăng tốc</span>.</span>
                    </div>
                </div>

                <div class="moat-card">
                    <div class="moat-num">L3</div>
                    <div class="moat-body">
                        <strong>🏆 VIETNAM ADVANTAGE</strong>
                        <span>
                            Chi phí kỹ thuật <span class="data-chip">1/5</span> so với US/EU ·
                            Nhân tài AI hàng đầu Đông Nam Á ·
                            Cầu nối chiến lược trong chuỗi cung ứng Châu Á ·
                            <span class="hl-red">Vindynamics đã có robot và khách hàng thực tế</span>
                        </span>
                    </div>
                </div>

                <div class="quote-block">
                    <p>"Chúng ta đang xây dựng ImageNet của Physical AI — nhưng từ châu Á, dành cho toàn thế giới. Không giống như ImageNet, mô hình của chúng ta đi kèm với một mô hình kinh doanh."</p>
                </div>
            </div>
        </div>

        <!-- SECTION 9: ROADMAP -->
        <div id="sec9" class="tab-content">
            <div class="card">
                <span class="section-title">Lộ trình phát triển</span>
                <div class="phase-row">
                    <div class="phase-card">
                        <div class="phase-label">PHASE 1 · 0–6 THÁNG</div>
                        <div class="phase-title">Curated Skill Store</div>
                        <ul>
                            <li><span class="data-chip">10–20</span> Robot Skills đầu tiên</li>
                            <li><span class="data-chip">5–10</span> trusted contributors</li>
                            <li>3 ngành trọng điểm: <span class="hl-red">Hospitality, Warehouse, Manufacturing</span></li>
                            <li>Revenue sharing thủ công</li>
                        </ul>
                    </div>
                    <div class="phase-card">
                        <div class="phase-label">PHASE 2 · 6–18 THÁNG</div>
                        <div class="phase-title">Self-Service Platform</div>
                        <ul>
                            <li>Partner upload portal</li>
                            <li>Automated validation</li>
                            <li>Analytics dashboard</li>
                        </ul>
                    </div>
                </div>
                <div class="phase-row">
                    <div class="phase-card">
                        <div class="phase-label">PHASE 3 · 18–36 THÁNG</div>
                        <div class="phase-title">Enterprise Marketplace</div>
                        <ul>
                            <li>Private marketplace</li>
                            <li>Enterprise licensing</li>
                            <li>Subscription tiers</li>
                        </ul>
                    </div>
                    <div class="phase-card">
                        <div class="phase-label">PHASE 4 · 36+ THÁNG</div>
                        <div class="phase-title">Global Physical AI Exchange</div>
                        <ul>
                            <li>Open global marketplace</li>
                            <li>OEM partnerships: <span class="hl-red">Boston Dynamics, Unitree, Figure AI</span></li>
                            <li>Synthetic Data Studio</li>
                        </ul>
                    </div>
                </div>

                <div class="quote-block">
                    <p>"Chúng ta bắt đầu như Apple — được tuyển chọn, kiểm soát, chất lượng cao; mở rộng quy mô như AWS — cơ sở hạ tầng cho toàn bộ ngành."</p>
                </div>
            </div>
        </div>

        <!-- SECTION 10: MÔ HÌNH DOANH THU -->
        <div id="sec10" class="tab-content">
            <div class="card">
                <span class="section-title">Mô hình doanh thu</span>

                <div class="rev-group">
                    <div class="rev-label">💰 Hardware</div>
                    <ul><li>Bán robot (existing revenue stream)</li></ul>
                </div>

                <div class="rev-group">
                    <div class="rev-label">💰 Software Subscription</div>
                    <ul>
                        <li>Robot Skill License: <span class="data-chip">$1K–$50K</span>/skill</li>
                        <li>Maintenance &amp; Updates</li>
                        <li>Dataset Access Subscription</li>
                    </ul>
                </div>

                <div class="rev-group">
                    <div class="rev-label">💰 Services</div>
                    <ul>
                        <li>Deployment &amp; Setup fee</li>
                        <li>Custom Fine-Tuning: <span class="data-chip">$20K–$500K</span>/project</li>
                        <li>Synthetic Data Generation: <span class="data-chip">$10K–$250K</span></li>
                    </ul>
                </div>

                <div class="rev-group">
                    <div class="rev-label">💰 Platform Revenue Share</div>
                    <ul>
                        <li>Platform takes <span class="data-chip">30%</span> / Contributor gets <span class="data-chip">70%</span></li>
                    </ul>
                </div>

                <p style="font-weight:700; color:#064e3b; font-size:1.15rem; margin: 20px 0 10px;">Unit Economics</p>
                <table>
                    <thead><tr><th>Scenario</th><th>Customers</th><th>ARR</th></tr></thead>
                    <tbody>
                        <tr><td>Base</td><td><span class="data-chip">1</span> Enterprise customer</td><td><span class="data-chip">$200K/năm</span></td></tr>
                        <tr><td>Growth</td><td><span class="data-chip">100</span> customers</td><td><span class="data-chip">$20M ARR</span></td></tr>
                        <tr><td>Scale (Phase 4)</td><td><span class="data-chip">1.000</span> customers</td><td><span class="hl-red">$200M ARR</span></td></tr>
                    </tbody>
                </table>
            </div>

            <div class="card">
                <span class="section-title">Bảng giá sản phẩm — Tiered Pricing</span>
                <table>
                    <thead>
                        <tr>
                            <th>Loại sản phẩm</th>
                            <th>Giá tham khảo</th>
                            <th>Target Customer</th>
                            <th>Revenue Share</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>Dataset nhỏ (Small Skill)</td>
                            <td><span class="data-chip">$1K – $5K</span></td>
                            <td>Startup robotics, Researchers</td>
                            <td>Vindynamics 30% / Contributor 70%</td>
                        </tr>
                        <tr>
                            <td>Dataset chuyên sâu (Pro Skill)</td>
                            <td><span class="data-chip">$5K – $50K</span></td>
                            <td>Service robot vendors, SMEs</td>
                            <td>Vindynamics 30% / Contributor 70%</td>
                        </tr>
                        <tr>
                            <td>Enterprise Dataset</td>
                            <td><span class="data-chip">$50K – $500K</span></td>
                            <td>Large enterprises, Robot OEMs</td>
                            <td>Negotiate case-by-case</td>
                        </tr>
                        <tr>
                            <td>Exclusive License</td>
                            <td><span class="data-chip">$100K – $1M+</span></td>
                            <td>Global robot manufacturers</td>
                            <td>Negotiate</td>
                        </tr>
                        <tr>
                            <td>Synthetic Data Generation</td>
                            <td><span class="data-chip">$10K – $250K</span></td>
                            <td>AI labs, Startups</td>
                            <td>Service fee</td>
                        </tr>
                        <tr>
                            <td>Custom Fine-Tuning Service</td>
                            <td><span class="data-chip">$20K – $500K</span></td>
                            <td>Enterprise triển khai nội bộ</td>
                            <td>Service fee</td>
                        </tr>
                        <tr>
                            <td>Subscription (Dataset Access)</td>
                            <td><span class="data-chip">$500 – $5K/tháng</span></td>
                            <td>Research institutions, Startups</td>
                            <td>Platform fee</td>
                        </tr>
                        <tr>
                            <td>Hardware (Robot Sales)</td>
                            <td>Varies by model</td>
                            <td>All segments</td>
                            <td>N/A</td>
                        </tr>
                    </tbody>
                </table>

                <div class="quote-block">
                    <p>"Mỗi robot chúng ta bán ra đều trở thành một cỗ máy tạo dữ liệu, giúp nền tảng của chúng ta có giá trị hơn. Phần cứng thúc đẩy phần mềm. Phần mềm thúc đẩy dữ liệu. Dữ liệu thúc đẩy mọi thứ khác."</p>
                </div>
            </div>
        </div>

        <!-- SECTION 11: PLATFORM FUNCTION -->
        <div id="sec11" class="tab-content">
            <div class="card">
                <span class="section-title">Tầm nhìn kiến trúc tổng thể</span>
                <div class="phase-row" style="grid-template-columns: 1fr 1fr 1fr;">
                    <div class="phase-card">
                        <div class="phase-label">PHASE 1</div>
                        <div class="phase-title">Robot Skill Store</div>
                        <ul>
                            <li>Bán robot</li>
                            <li>Bán phần mềm AI</li>
                            <li>Thu thập dữ liệu thực tế</li>
                        </ul>
                    </div>
                    <div class="phase-card">
                        <div class="phase-label">PHASE 2</div>
                        <div class="phase-title">Private Marketplace</div>
                        <ul>
                            <li>Chia sẻ dữ liệu giữa đối tác</li>
                            <li>Enterprise licensing</li>
                        </ul>
                    </div>
                    <div class="phase-card">
                        <div class="phase-label">PHASE 3</div>
                        <div class="phase-title">Open Physical AI Exchange</div>
                        <ul>
                            <li>Nền tảng dữ liệu robotics toàn cầu</li>
                            <li>Hạ tầng Physical AI</li>
                            <li>Marketplace Robot Skills &amp; AI Datasets</li>
                        </ul>
                    </div>
                </div>
            </div>

            <div class="card">
                <span class="section-title">A. Robot Skill Store — Các tính năng cốt lõi</span>
                <p style="margin-bottom:18px;"><strong>Mục tiêu:</strong> Tăng doanh số robot và phần mềm, đồng thời thu thập dữ liệu thực tế để xây dựng lợi thế cạnh tranh lâu dài.</p>

                <div class="platform-item">
                    <div class="platform-num">1</div>
                    <div class="platform-body">
                        <strong>Contributor Portal</strong>
                        <span>Cổng dành cho chuyên gia và đối tác tải lên SOP, video, dữ liệu huấn luyện và tài liệu kỹ thuật; theo dõi trạng thái kiểm duyệt và doanh thu chia sẻ.</span>
                    </div>
                </div>
                <div class="platform-item">
                    <div class="platform-num">2</div>
                    <div class="platform-body">
                        <strong>Data Standardization Engine</strong>
                        <span>Tự động chuẩn hóa dữ liệu, kiểm tra cấu trúc, đồng bộ timestamp, phát hiện dữ liệu thiếu hoặc trùng lặp và gắn metadata tiêu chuẩn.</span>
                    </div>
                </div>
                <div class="platform-item">
                    <div class="platform-num">3</div>
                    <div class="platform-body">
                        <strong>AI Training &amp; MLOps Platform</strong>
                        <span>Quản lý toàn bộ quá trình huấn luyện, fine-tuning, benchmark và quản lý phiên bản dataset/model.</span>
                    </div>
                </div>
                <div class="platform-item">
                    <div class="platform-num">4</div>
                    <div class="platform-body">
                        <strong>Robot Skill Packaging Engine</strong>
                        <span>Đóng gói mô hình AI thành <strong>Robot Skill Packages</strong> gồm model, cấu hình, SOP, hướng dẫn triển khai, benchmark và license.</span>
                    </div>
                </div>
                <div class="platform-item">
                    <div class="platform-num">5</div>
                    <div class="platform-body">
                        <strong>Robot Skill Store</strong>
                        <span>"App Store cho Robot" — khách hàng tìm kiếm, đánh giá ROI và mua các kỹ năng AI theo từng ngành và tác vụ.</span>
                    </div>
                </div>
                <div class="platform-item">
                    <div class="platform-num">6</div>
                    <div class="platform-body">
                        <strong>Deployment &amp; Fleet Management</strong>
                        <span>Triển khai robot tại doanh nghiệp, cấu hình từ xa, cập nhật OTA, giám sát hoạt động và phân tích mức độ sử dụng.</span>
                    </div>
                </div>
                <div class="platform-item">
                    <div class="platform-num">7</div>
                    <div class="platform-body">
                        <strong>Operational Data Collection</strong>
                        <span>Thu thập video, sensor logs, failure cases và dữ liệu can thiệp của con người để cải thiện mô hình AI liên tục.</span>
                    </div>
                </div>
                <div class="platform-item">
                    <div class="platform-num">8</div>
                    <div class="platform-body">
                        <strong>ROI Analytics Dashboard</strong>
                        <span>Hiển thị hiệu quả đầu tư: năng suất tăng, lỗi giảm, thời gian tiết kiệm và ROI thực tế.</span>
                    </div>
                </div>
                <div class="platform-item">
                    <div class="platform-num">9</div>
                    <div class="platform-body">
                        <strong>Revenue Sharing System</strong>
                        <span>Tự động tính toán và phân bổ doanh thu cho contributors và đối tác.</span>
                    </div>
                </div>
                <div class="platform-item">
                    <div class="platform-num">10</div>
                    <div class="platform-body">
                        <strong>Trust &amp; Governance Layer</strong>
                        <span>Quản lý xác minh đối tác, license, watermark, audit logs, reputation score và các cơ chế bảo vệ tài sản trí tuệ.</span>
                    </div>
                </div>
            </div>

            <div class="card">
                <span class="section-title">B. Giai đoạn 2 — Physical AI Data Exchange</span>
                <p style="margin-bottom:18px;"><strong>Mục tiêu:</strong> Mở rộng thành nền tảng giao dịch dữ liệu AI cho robot trên quy mô khu vực và quốc tế.</p>

                <div class="platform-item">
                    <div class="platform-num">11</div>
                    <div class="platform-body">
                        <strong>Dataset Marketplace</strong>
                        <span>Cho phép đăng tải, tìm kiếm, so sánh benchmark và mua bán các bộ dữ liệu robotics.</span>
                    </div>
                </div>
                <div class="platform-item">
                    <div class="platform-num">12</div>
                    <div class="platform-body">
                        <strong>Synthetic Data Studio</strong>
                        <span>Tạo dữ liệu mô phỏng, tình huống hiếm và tự động gán nhãn để bổ sung dữ liệu thực.</span>
                    </div>
                </div>
                <div class="platform-item">
                    <div class="platform-num">13</div>
                    <div class="platform-body">
                        <strong>Data Request Marketplace</strong>
                        <span>Doanh nghiệp đăng nhu cầu dữ liệu; contributors báo giá và cung cấp theo yêu cầu.</span>
                    </div>
                </div>
                <div class="platform-item">
                    <div class="platform-num">14</div>
                    <div class="platform-body">
                        <strong>Private Marketplace for Enterprise</strong>
                        <span>Marketplace riêng cho doanh nghiệp lớn để chia sẻ và quản lý dữ liệu nội bộ một cách an toàn.</span>
                    </div>
                </div>
                <div class="platform-item">
                    <div class="platform-num">15</div>
                    <div class="platform-body">
                        <strong>API &amp; SDK Platform</strong>
                        <span>Cung cấp Robot SDK, Dataset APIs, Skill APIs và Model APIs để bên thứ ba tích hợp vào hệ sinh thái.</span>
                    </div>
                </div>
            </div>

            <div class="card">
                <span class="section-title">C. Hệ thống nền tảng dùng chung</span>

                <div class="platform-item">
                    <div class="platform-num">16</div>
                    <div class="platform-body">
                        <strong>Identity &amp; Access Management</strong>
                        <span>Quản lý tài khoản, phân quyền, multi-tenant và Single Sign-On.</span>
                    </div>
                </div>
                <div class="platform-item">
                    <div class="platform-num">17</div>
                    <div class="platform-body">
                        <strong>Large-Scale Data Storage</strong>
                        <span>Hạ tầng lưu trữ phân tán cho dữ liệu robotics dung lượng lớn, hỗ trợ upload/download tốc độ cao.</span>
                    </div>
                </div>
                <div class="platform-item">
                    <div class="platform-num">18</div>
                    <div class="platform-body">
                        <strong>Billing &amp; Subscription</strong>
                        <span>Quản lý subscription, usage-based pricing, enterprise invoicing, revenue sharing và escrow.</span>
                    </div>
                </div>
                <div class="platform-item">
                    <div class="platform-num">19</div>
                    <div class="platform-body">
                        <strong>AI/MLOps Infrastructure</strong>
                        <span>Model registry, experiment tracking, CI/CD cho AI, monitoring và drift detection.</span>
                    </div>
                </div>
                <div class="platform-item">
                    <div class="platform-num">20</div>
                    <div class="platform-body">
                        <strong>Security &amp; Compliance</strong>
                        <span>Mã hóa dữ liệu, audit logs, backup, disaster recovery và bảo vệ tài sản trí tuệ.</span>
                    </div>
                </div>
            </div>
        </div>

        <!-- SECTION 12: CONTRIBUTOR ACQUISITION -->
        <div id="sec12" class="tab-content">
            <div class="card">
                <span class="section-title">Contributor Acquisition</span>

                <div class="contrib-col">
                    <div class="contrib-box">
                        <span class="section-title">A. Revenue Sharing</span>
                        <p style="text-align:center; padding: 20px; background: var(--primary-green-soft); border-radius: 12px;">
                            <span style="font-size:2rem; font-weight:900; color:#059669; display:block;">70%</span>
                            <span style="font-size:0.9rem; color:#555;">Contributor</span>
                        </p>
                        <p style="text-align:center; padding: 10px; background: #f1f5f9; border-radius: 12px; margin-top:10px;">
                            <span style="font-size:1.5rem; font-weight:900; color:#064e3b; display:block;">30%</span>
                            <span style="font-size:0.9rem; color:#555;">Vindynamics</span>
                        </p>
                    </div>

                    <div class="contrib-box">
                        <span class="section-title">B. Biến chuyên môn thành thu nhập</span>
                        <p><strong>Ví dụ đầu vào:</strong></p>
                        <ul>
                            <li>Một SOP warehouse tốt</li>
                            <li>Một quy trình inspection chuẩn</li>
                            <li>Một video thao tác robot</li>
                        </ul>
                        <p style="margin-top:12px;"><strong>Có thể trở thành:</strong></p>
                        <ul>
                            <li><span class="data-chip">Robot Skill</span></li>
                            <li><span class="data-chip">AI Package</span></li>
                            <li><span class="data-chip">Dataset thương mại</span></li>
                        </ul>
                    </div>
                </div>
            </div>

            <div class="card">
                <span class="section-title">C. Contributor không cần xử lý kỹ thuật phức tạp</span>
                <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 20px; margin-top: 10px;">
                    <div>
                        <p style="font-weight:800; color:#064e3b; margin-bottom:12px;">Vindynamics làm:</p>
                        <ul>
                            <li>Chuẩn hóa dữ liệu</li>
                            <li>Fine-tuning model</li>
                            <li>Packaging sản phẩm</li>
                            <li>Sales &amp; Marketing</li>
                            <li>License management</li>
                            <li>Customer support</li>
                        </ul>
                    </div>
                    <div>
                        <p style="font-weight:800; color:#059669; margin-bottom:12px;">Contributor chỉ cần:</p>
                        <div style="background: var(--primary-green-soft); border: 2px solid var(--primary-green); border-radius: 14px; padding: 30px; text-align: center;">
                            <span style="font-size: 1.5rem; font-weight: 900; color: #064e3b;">Chia sẻ Expertise</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>

    </main>

    <script>
        function showTab(event, tabId, sectionNum) {
            const contents = document.querySelectorAll('.tab-content');
            contents.forEach(content => content.classList.remove('active'));

            const buttons = document.querySelectorAll('.nav-btn');
            buttons.forEach(btn => btn.classList.remove('active'));

            document.getElementById(tabId).classList.add('active');
            event.currentTarget.classList.add('active');

            document.getElementById('tab-title').innerText = event.currentTarget.innerText.replace(/^\d+\.\s/, '');
            document.getElementById('project-num').innerText = sectionNum;

            document.querySelector('.main').scrollTop = 0;
        }
    </script>
</body>
</html>
