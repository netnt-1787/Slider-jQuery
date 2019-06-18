# ⚡️ Plugin Slider jQuery

Là một plugin jQuery tạo slide đơn giản, dễ dùng, nhiều options. Các bạn có thể tạo slideshow ảnh, tạo slide bài tin,... với các tuỳ biến phong phú.

## 🛠 Cài Đặt

### 🔥 jQuery

Đầu tiên, không thể thiếu được jQuery, bạn có thể tải file trực tiếp từ Trang chủ jQuery hoặc CDN

#### Import JS và CSS của Plugin

Đây là một plugin đã được viết sẳn nên để sử dụng nó bạn cần import nó vào website của mình trước khi dùng

```
<!-- Important stylesheet -->
<link rel="stylesheet" href="slider.css">
 
<!--  jQuery -->
<script src="jquery-3.4.1.min.js"></script>
 
<!-- Include js plugin -->
<script src="assets/slider.js"></script>
```

#### Thiết lập cấu trúc HTML

Plugin được tạo sẳn và tất nhiên là cấu trúc html cũng cần tuần theo quy định của Plugins

```
<div class= "slider-carousel" data-pagi= "true" data-navi = "true" >
  <div class= "slider-stage">
    <div clas= "slider-stage__item active slide-0"
      Your Content
    </div>
    <div clas= "slider-stage__item slide-1"
      Your Content
    </div>
    <div clas= "slider-stage__item slide-2"
      Your Content
    </div>
    <div clas= "slider-stage__item slide-3"
      Your Content
    </div>
  </div>
```

### Thiết lập gọi sử dụng Plugin

Bước này là bước cuối cùng để thêm Slider vào website. 

Ở bước này dùng khai báo đối tượng nào được áp dụng

```
$(document).ready(function() {
  $(".slider-carousel).slider_plugin();
});
```

Ngoài ra, Slider có rất nhiều options cho chúng ta lựa chọn để xây dựng Slider thích hợp

