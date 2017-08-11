---
layout: post
title: Hướng dẫn sơ
author: admin
tags: [ghim]
thumb: logo.png
---
Đây là bài gửi được viết từ github new file.

### Phần gửi bài
- Muốn tạo bài thì bạn tạo 2016-8-19-filename.md vào thư mục _posts trong (work) là một chuyên mục
- Bạn hãy tham khảo nội dung 1 bài mẩu nào đó.
- Hình thu nhỏ (thumbnail) của bài viết được lấy tự động trong nội dung hoặc tự khai báo trong bài viết (thumb: tenhinh.jpg)
- Lưu ý là thumb nếu là link có http thì tự code sẽ hiển thị hình luôn còn ko là dạng tenhinh.jpg, bạn hãy tải lên thư mục assets/tenhinh.jpg

### Thêm vào bài viết
- Hình là liên kết
```
{ % include img key="//tenmien.xyz/tenhinh.jpg" % }
{ % include img key="http://tenmien.xyz/tenhinh.jpg" % }
{ % include img key="https://tenmien.xyz/tenhinh.jpg" % }
```
- Hình thu muc page-id trong assets
```
{ % include img key="/tenhinh.jpg" % }
```
- Hình la page-id.jpg trong assets
```
{ % include img % }
```
- Kiểu album
```
{ % include album key="tenthumuc" % }
```
- Kiểu video youtube
```
{ % include video_yt key="youtubeid" % }
```
- Kiểu slider
```
{ % include carousel key="tenthumuc" % }
```

### Phần skin
- Skin là thư mục nằm trong _include/{skin-name}.
- Làm skin để dùng chung data _posts
- Bạn muốn thay đổi skin thì vào _config.yml > skin , đổi giống tên thư mục trong _include
- Bạn hãy tạo dùm vài skin và gửi mình nhé. Bằng cách nhân bản 1 skin nào đó và tùy chỉnh.

### Phần chuyên mục (cat)
- Bộ code này hổ trợ cat bằng thư mục ngang _config.yml. Bên trong gồm 1 file index.html và thư mục _posts
- Để tạo 1 cat bạn hãy nhân bản thư mục work (cat), và có thể tạo bài trong _posts

### Phần nhãn (tag)
- Trong jekyll tag khác cat và đôi lúc chúng cũng giống nhau, nên phần tag mình chỉ dùng làm nhãn cho bài và ko có phân url

### Phần comment
- Trong bộ cod này có sẵn phần comment bằng firebase nhưng bạn sẽ ko sài được vì crossdomain
- Bạn hãy vào _include/comment đọc và thay đổi cái url firebase.
- Nếu thích thì mình làm thêm phần comment bằng facebook.
