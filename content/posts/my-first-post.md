---
title: "My First Post"
date: 2022-06-19T04:15:59+07:00
---

Trong đó có cấu hình tên bài viết (title), ngày xuất bản (date), bản nháp hay đã sẵn sàng xuất bản (draft). Nội dung bài viết thì viết bằng cú pháp markdown, viết sau phần dấu gạch ngang ---. Bài viết nào có đánh dấu draft: true thì sẽ không được build.

Chạy thử website trên local bằng lệnh hugo server, truy cập http://localhost:1313 để xem kết quả. Đường dẫn của trang sẽ tương ứng với đường dẫn file http://localhost:1313/posts/my-first-post. Khi đã thấy ưng ý thì build ra static files (HTML CSS JS) bằng lệnh hugo. Website sẽ được build vào trong thư mục public và chỉ cần đẩy lên 1 hosting hỗ trợ static web là xong.