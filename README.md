<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Giới thiệu bản thân</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="container">
    <header>
      <h1>Chào mừng đến với trang web của tôi!</h1>
      <p>Xin chào, tôi là <input type="text" id="fullName" placeholder="Nhập tên của bạn"></p>
      <p>Nghề nghiệp: <input type="text" id="occupation" placeholder="Nhập nghề nghiệp của bạn"></p>
    </header>

    <section id="achievements">
      <h2>Thành tích</h2>
      <div class="achievement" id="achievement1">
        <h3>Thành tích 1</h3>
        <p class="details">[Thông tin chi tiết về thành tích 1]</p>
      </div>
      <div class="achievement" id="achievement2">
        <h3>Thành tích 2</h3>
        <p class="details">[Thông tin chi tiết về thành tích 2]</p>
      </div>
      <div class="achievement" id="achievement3">
        <h3>Thành tích 3</h3>
        <p class="details">[Thông tin chi tiết về thành tích 3]</p>
      </div>
    </section>
    
    <section id="moreInfo">
      <h2>Thông tin khác</h2>
      <textarea id="bio" placeholder="Nhập thông tin giới thiệu bản thân..."></textarea>
    </section>
  </div>

  <script src="script.js"></script>
</body>
</html>
