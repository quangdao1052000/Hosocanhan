<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Giới thiệu bản thân</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="container">
    <!-- Phần thông tin cá nhân -->
    <header class="profile">
      <div class="profile-img">
        <!-- Thay "avatar.jpg" bằng đường dẫn ảnh cá nhân của bạn -->
        <img src="avatar.jpg" alt="Hình ảnh cá nhân">
      </div>
      <h1>Nguyễn Văn A</h1>
    </header>
    
    <!-- Các ô khung chứa thông tin -->
    <section class="info-section">
      <!-- Nghề nghiệp -->
      <div class="info-box" id="professionBox">
        <div class="info-header">
          <h2>Nghề nghiệp</h2>
          <span class="toggle-indicator">+</span>
        </div>
        <div class="info-content">
          <p>Web Developer</p>
          <p class="details">
            Tôi là một nhà phát triển web với hơn 10 năm kinh nghiệm. Tôi chuyên xây dựng các ứng dụng web hiện đại, tối ưu và thân thiện với người dùng.
          </p>
        </div>
      </div>
      
      <!-- Học vấn -->
      <div class="info-box" id="educationBox">
        <div class="info-header">
          <h2>Học vấn</h2>
          <span class="toggle-indicator">+</span>
        </div>
        <div class="info-content">
          <p>Cử nhân Công nghệ Thông tin</p>
          <p class="details">
            Tôi đã tốt nghiệp Đại học Bách Khoa với chuyên ngành Công nghệ Thông tin, nơi tôi được đào tạo bài bản về lập trình, thiết kế hệ thống và phát triển phần mềm.
          </p>
        </div>
      </div>
      
      <!-- Thành tích -->
      <div class="info-box" id="achievementBox">
        <div class="info-header">
          <h2>Thành tích</h2>
          <span class="toggle-indicator">+</span>
        </div>
        <div class="info-content">
          <p>Giải thưởng Sáng tạo Công nghệ 2023</p>
          <p class="details">
            Nhờ các dự án đột phá về ứng dụng công nghệ trong kinh doanh, tôi đã được vinh danh với giải thưởng Sáng tạo Công nghệ 2023, minh chứng cho sự nỗ lực không ngừng.
          </p>
        </div>
      </div>
    </section>
  </div>

  <script src="script.js"></script>
</body>
</html>
