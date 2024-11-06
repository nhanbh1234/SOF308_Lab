<template>
  <div>
      <nav class="navbar navbar-expand-sm navbar-light bg-light">
          <div class="container">
              
              <a class="navbar-brand" href="#">
                  <img src="../images/logo-energy-pilates.png" alt="Logo" style="width: 150px;">
              </a>
              
              <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarContent">
                  <span class="navbar-toggler-icon"></span>
              </button>
              
              <div class="collapse navbar-collapse" id="navbarContent">
                  <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                      <li class="nav-item">
                          <a class="nav-link" href="#"><i class="fas fa-list"></i> Bài viết</a>
                      </li>
                      <li class="nav-item">
                          <a class="nav-link" href="#"><i class="fas fa-video"></i> Video</a>
                      </li>
                      <li class="nav-item">
                          <a class="nav-link" href="#"><i class="fas fa-info-circle"></i> Giới thiệu</a>
                      </li>
                      <li class="nav-item">
                          <a class="nav-link" href="#"><i class="fas fa-calendar-alt"></i> Sự kiện</a>
                      </li>
                      
                      <li class="nav-item dropdown">
                          <a class="nav-link dropdown-toggle" href="#" id="accountDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                              <i class="fas fa-user"></i> Tài khoản
                          </a>
                          <ul class="dropdown-menu" aria-labelledby="accountDropdown">
                              <li><a class="dropdown-item" href="#">Đăng nhập</a></li>
                              <li><a class="dropdown-item" href="#">Quên mật khẩu</a></li>
                              <li><a class="dropdown-item" href="#">Đăng ký thành viên</a></li>
                          </ul>
                      </li>
                  </ul>
                  
                  <ul class="navbar-nav">
                      <li class="nav-item">
                          <a class="nav-link" href="#">Tiếng Việt</a>
                      </li>
                      <li class="nav-item">
                          <a class="nav-link" href="#">Tiếng Anh</a>
                      </li>
                  </ul>
              </div>
          </div>
      </nav>
  </div>
</template>

<script>
export default {
  name: "BlogPage"
};
</script>

<style scoped>
@import "../css/bootstrap.min.css";
@import "https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css";
</style>
