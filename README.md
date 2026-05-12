<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>README | VinDynamics Platform</title>
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;600;800&family=Montserrat:wght@900&display=swap" rel="stylesheet">
    <style>
        :root {
            --emerald: #006341;
            --emerald-light: #007D48;
            --gold: #D4AF37;
            --bg: #f4f7f6;
            --white: #ffffff;
            --text: #1a1a1a;
        }

        body {
            font-family: 'Plus Jakarta Sans', sans-serif;
            background-color: var(--bg);
            color: var(--text);
            line-height: 1.6;
            margin: 0;
            padding: 40px 20px;
        }

        .readme-container {
            max-width: 850px;
            margin: 0 auto;
            background: var(--white);
            padding: 50px;
            border-radius: 24px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.05);
            border: 1px solid rgba(0,99,65,0.1);
        }

        .header {
            border-bottom: 3px solid var(--emerald);
            padding-bottom: 20px;
            margin-bottom: 30px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        h1 {
            font-family: 'Montserrat', sans-serif;
            color: var(--emerald);
            font-size: 2rem;
            margin: 0;
            letter-spacing: -1px;
        }

        .version-tag {
            background: var(--emerald);
            color: var(--gold);
            padding: 4px 12px;
            border-radius: 50px;
            font-weight: 800;
            font-size: 0.8rem;
        }

        h2 {
            color: var(--emerald-light);
            font-size: 1.3rem;
            margin-top: 30px;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        h2::before {
            content: "";
            width: 8px;
            height: 20px;
            background: var(--gold);
            display: inline-block;
            border-radius: 2px;
        }

        p { margin-bottom: 15px; font-size: 1.05rem; color: #444; }

        .grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
            margin: 25px 0;
        }

        .card {
            background: #fafafa;
            padding: 20px;
            border-radius: 15px;
            border-left: 4px solid var(--emerald);
        }

        .card strong { color: var(--emerald); display: block; margin-bottom: 5px; }

        ul { list-style: none; padding: 0; }
        li { margin-bottom: 10px; padding-left: 20px; position: relative; }
        li::before {
            content: "•";
            color: var(--gold);
            font-weight: bold;
            position: absolute;
            left: 0;
        }

        .footer {
            margin-top: 40px;
            padding-top: 20px;
            border-top: 1px solid #eee;
            font-size: 0.9rem;
            color: #888;
            text-align: center;
        }
    </style>
</head>
<body>

<div class="readme-container">
    <div class="header">
        <h1>VINDYNAMICS PLATFORM</h1>
        <span class="version-tag">v1.0.0 | STRATEGY</span>
    </div>

    <p>Tài liệu này mô tả cấu trúc và mục tiêu của nền tảng <strong>VinDynamics (VDX)</strong> — hệ sinh thái tiên phong trong việc thương mại hóa dữ liệu <strong>Physical AI</strong> và giải pháp Robotics trọn gói.</p>

    <h2>1. Tổng quan Dự án</h2>
    <p>Webapp cung cấp cái nhìn chiến lược về cách VinDynamics giải quyết "nút thắt cổ chai" của ngành Robotics: <strong>Dữ liệu tương tác vật lý</strong>. Thay vì chỉ bán phần cứng, nền tảng tập trung vào mô hình <strong>Robot Skill Store</strong>.</p>

    <div class="grid">
        <div class="card">
            <strong>Mục tiêu cốt lõi</strong>
            Xây dựng "App Store cho Robot", nơi chuyển hóa SOP và kiến thức chuyên môn thành các gói kỹ năng (Skills) có thể thực thi ngay.
        </div>
        <div class="card">
            <strong>Giá trị cốt lõi</strong>
            Dựa trên hạ tầng tin cậy (Trust Infrastructure) để bảo vệ quyền sở hữu trí tuệ và chuẩn hóa dữ liệu AI.
        </div>
    </div>

    <h2>2. Cấu trúc Nội dung (Navigation)</h2>
    <ul>
        <li><strong>Phân tích thị trường:</strong> Painpoint về chi phí thu thập dữ liệu ($50k - $500k cho mỗi tác vụ đơn giản).</li>
        <li><strong>Mô hình kinh doanh:</strong> Kết hợp phần cứng, Subscription phần mềm và chia sẻ doanh thu (70/30) với Contributor.</li>
        <li><strong>Lợi thế cạnh tranh (Moats):</strong> Hiệu ứng mạng lưới dữ liệu và lợi thế nhân lực/chi phí tại Việt Nam.</li>
        <li><strong>Lộ trình (Roadmap):</strong> Từ cửa hàng kỹ năng tuyển chọn (Phase 1) đến sàn giao dịch Physical AI toàn cầu (Phase 4).</li>
    </ul>

    <h2>3. Hướng dẫn Sử dụng Web</h2>
    <ul>
        <li>Sử dụng <strong>Sidebar trái</strong> để chuyển đổi nhanh giữa 12 mục chiến lược.</li>
        <li>Các thông số quan trọng được đóng gói trong các <strong>Data Chips</strong> để dễ theo dõi.</li>
        <li>Phần <strong>Platform Function</strong> liệt kê chi tiết 20 tính năng nền tảng cần xây dựng.</li>
    </ul>

    <div class="footer">
        © 2026 VinDynamics | VDX Robotics Platform
    </div>
</div>

</body>
</html>
