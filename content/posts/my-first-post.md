---
title: "My First Post"
date: 2022-06-19T04:15:59+07:00
featured_image: '/images/123.png'
params:
ananke_socials:
- name: twitter
  url: https://twitter.com/theNewDynamic
- name: github
  url: https://github.com/theNewDynamic
---

[//]: # ({{< form-contact action="https://formspree.io/lephung8399@gmail.com" >}})

Trong đó có cấu hình tên bài viết (t1itle), ngày xuất bản (date), bản nháp hay đã sẵn sàng xuất bản (draft). Nội dung bài viết thì viết bằng cú pháp markdown, viết sau phần dấu gạch ngang ---. Bài viết nào có đánh dấu draft: true thì sẽ không được build.

Chạy thử website trên local bằng lệnh hugo server, truy cập http://localhost:1313 để xem kết quả. Đường dẫn của trang sẽ tương ứng với đường dẫn file http://localhost:1313/posts/my-first-post. Khi đã thấy ưng ý thì build ra static files (HTML CSS JS) bằng lệnh hugo. Website sẽ được build vào trong thư mục public và chỉ cần đẩy lên 1 hosting hỗ trợ static web là xong.