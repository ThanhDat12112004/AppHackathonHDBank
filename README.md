# AppHackathonHDBank
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Demo Ngân hàng Tự động</title>
    <link rel="stylesheet" href="styles.css">
</head>

<body>
    <header>
        <h1>Ngân Hàng Tự Động</h1>
        <nav>
            <ul>
                <li><a href="#home">Trang Chủ</a></li>
                <li><a href="#login">Đăng Nhập</a></li>
                <li><a href="#transactions">Lịch Sử Giao Dịch</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h2>Chào mừng đến với dịch vụ ngân hàng tự động</h2>
        <p>Quản lý tài khoản, thực hiện giao dịch, và nhiều tính năng khác chỉ với vài cú nhấp chuột!</p>
    </section>

    <section id="login">
        <h2>Đăng Nhập</h2>
        <form id="login-form">
            <input type="text" id="username" placeholder="Tên đăng nhập" required>
            <input type="password" id="password" placeholder="Mật khẩu" required>
            <button type="submit">Đăng Nhập</button>
        </form>
    </section>

    <section id="transactions">
        <h2>Lịch Sử Giao Dịch</h2>
        <table>
            <thead>
                <tr>
                    <th>Ngày</th>
                    <th>Mô Tả</th>
                    <th>Số Tiền</th>
                </tr>
            </thead>
            <tbody id="transaction-history">
                <!-- Dữ liệu giao dịch sẽ được thêm vào đây -->
            </tbody>
        </table>
    </section>

    <footer>
        <p>© 2024 Ngân Hàng Tự Động</p>
    </footer>

    <script src="app.js"></script>
</body>

</html>
