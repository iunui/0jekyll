---
layout: post
title: Hướng dẫn thêm code
author: admin
tags: ["cài đặt"]
---
Sau khi hoàn tất bước 1, ta truy cập được vào trang web, cái đường dẫn dài dài *.github.io/tenlagi
, mình sẽ hướng đẫn gắn domain sau.

Giờ tới bước thêm code 0jekyl. vì mình viết trên đt android nên hình chụp hơi khác.
app aide web. chplay để cài nhé
Trên window thì sài cái [chương trình này](https://git-scm.com/download/win)

Lệnh git thường dùng: sài riết wen ah

- git clone : tải 1 project về (dùng ít)
- git pull : đồng bộ 
- git add . : thêm file để commit, push
- git commit -am "gido" : dùng trước khi push
- git push : đẩy nội dung lên host github

Mình sai cái app nên sài giao diện.

### dzo bước 2

Tải project 0jekyll về.
> git clone https://github.com/tagiau/0jekyll

Tải project của bạn về.
> git clone https://github.com/username/gido
{% include img key='/1.png' %}
copy hết file trong 0jekyll qua project của bạn (xóa hết rồi copy củng đc)

Giờ làm việc với project của bạn. Sửa file _config.yml đổi cho giống tên project bạn
{% include img key='/2.png' %}

Tiếp thêm file dùng "git add ." > git commit -am "gido" . hình bằng app
{% include img key='/3.png' %}
{% include img key='/4.png' %}
{% include img key='/5.png' %}

Tiếp đẩy lên github dùng "git push" nó sẽ hỏi user,pass > cứ nhập từ từ mà đúng dù nó hiện ****
{% include img key='/6.png' %}
{% include img key='/7.png' %}
{% include img key='/8.png' %}
{% include img key='/9.png' %}

xong truy cập url, khác liền. 
Ở trên có chỉ cách thêm file và đẩy lên github, chú ý nhé vì sẽ dùng hoài

[Bước 3]({{site.baseurl}}/orther/hd-post)
