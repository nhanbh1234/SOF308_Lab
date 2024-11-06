<template>
    <div class="container mt-5">
      <h3 class="text-center text-danger">Bảng Thành Phần Dinh Dưỡng</h3>
      <table class="table table-bordered text-center mt-3">
        <thead>
          <tr style="background-color: #d5a209; color: white;">
            <th rowspan="2">Thành Phần</th>
            <th colspan="2">Giá Trị</th>
          </tr>
          <tr style="background-color: #FFC107; color: white;">
            <th>Khối Lượng</th>
            <th>% DV*</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>Calories</td>
            <td>200 kcal</td>
            <td>20%</td>
          </tr>
          <tr>
            <td>Chất Béo</td>
            <td>9 g</td>
            <td>14%</td>
          </tr>
          <tr>
            <td>Chất Béo Bão Hòa</td>
            <td>4 g</td>
            <td>20%</td>
          </tr>
          <tr>
            <td>Chất Đạm</td>
            <td>8 g</td>
            <td>16%</td>
          </tr>
          <tr>
            <td>Chất Xơ</td>
            <td>5 g</td>
            <td>20%</td>
          </tr>
          <tr>
            <td>Đường</td>
            <td>12 g</td>
            <td>-</td>
          </tr>
          <tr>
            <td rowspan="2">Vitamin</td>
            <td>Vitamin C</td>
            <td>25%</td>
          </tr>
          <tr>
            <td>Vitamin D</td>
            <td>10%</td>
          </tr>
        </tbody>
      </table>
    </div>
  </template>
  
  <script>
  export default {
    name: "Lab2Bai1",
  };
  </script>
  
  <style scoped>
  .table-bordered th, .table-bordered td {
    border: 1px solid #dee2e6;
  }
  .table-bordered thead th {
    background-color: #ffbf00;
    color: white;
  }
  .table thead tr:nth-child(2) th {
    background-color: #FFC107;
  }
  .text-danger {
    color: #dc3545;
  }
  </style>
  