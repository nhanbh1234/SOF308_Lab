<template>
    <div class="container mt-5">
      <h2 class="text-center">Form Đăng Ký Thông Tin và Đăng Nhập</h2>
  
      <!-- Nav tabs -->
      <ul class="nav nav-tabs" role="tablist">
        <li class="nav-item">
          <a class="nav-link active" data-bs-toggle="tab" href="#register">Đăng ký</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" data-bs-toggle="tab" href="#login">Đăng nhập</a>
        </li>
      </ul>
  
      <!-- Tab panes -->
      <div class="tab-content">
        <div id="register" class="container tab-pane active">
          <div class="form-box">
            <h3>Form Đăng Ký Thông Tin</h3>
            <form>
              <div class="form-group">
                <label for="fullName">Họ và Tên</label>
                <input type="text" class="form-control" id="fullName" placeholder="Nhập họ và tên" />
              </div>
              <div class="form-group">
                <label for="email">Email</label>
                <input type="email" class="form-control" id="email" placeholder="Nhập email" />
              </div>
              <div class="form-group">
                <label for="phone">Số Điện Thoại</label>
                <input type="tel" class="form-control" id="phone" placeholder="Nhập số điện thoại" />
              </div>
              <div class="form-group">
                <label for="password">Mật Khẩu</label>
                <input type="password" class="form-control" id="password" placeholder="Nhập mật khẩu" />
              </div>
              <div class="form-group">
                <label for="confirmPassword">Xác Nhận Mật Khẩu</label>
                <input type="password" class="form-control" id="confirmPassword" placeholder="Xác nhận mật khẩu" />
              </div>
              <div class="form-group">
                <label>Giới Tính</label>
                <div>
                  <label class="radio-inline"><input type="radio" name="gender" value="male" /> Nam</label>
                  <label class="radio-inline"><input type="radio" name="gender" value="female" /> Nữ</label>
                </div>
              </div>
              <div class="form-group">
                <label>Ngôn Ngữ</label>
                <select class="form-control">
                  <option value="vi">Tiếng Việt</option>
                </select>
              </div>
              <div class="form-group form-check">
                <input type="checkbox" class="form-check-input" id="terms" />
                <label class="form-check-label" for="terms">Tôi đồng ý với các điều khoản và điều kiện</label>
              </div>
              <button type="submit" class="btn btn-primary">Đăng Ký</button>
            </form>
          </div>
        </div>
  
        <div id="login" class="container tab-pane fade">
          <div class="form-box">
            <h3>Form Đăng Nhập</h3>
            <form>
              <div class="form-group">
                <label for="loginEmail">Email</label>
                <input type="email" class="form-control" id="loginEmail" placeholder="Nhập email" />
              </div>
              <div class="form-group">
                <label for="loginPassword">Mật Khẩu</label>
                <input type="password" class="form-control" id="loginPassword" placeholder="Nhập mật khẩu" />
              </div>
              <button type="submit" class="btn btn-primary">Đăng Nhập</button>
            </form>
          </div>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: "Lab2Bai3"
  };
  </script>
  
  <style scoped>
  .form-box {
    max-width: 500px;
    margin: auto;
  }
  .tab-pane {
    padding-top: 20px;
  }

  @import "https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css";
@import "https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js";
@import "https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js";
  </style>
  
  <!-- Add Bootstrap JS in your main entry file (main.js) or in index.html -->
  