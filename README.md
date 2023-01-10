-- CÀI ĐẶT WEB SERVER (Lite-Server, version 2.6.1) ---

1. Tải phần mềm NodeJS: https://nodejs.org (version: 18.13.0)

2. Tiến hành cài đặt

3. Kiểm tra phiên bản của NodeJS và NPM (Node Packages Manager)
    > node -v
    > npm -v

4. Khởi tạo dự án với NodeJS
    > npm init
   Khai báo các thông tin cấu hình cho dự án. Mọi thông tin được lưu vào package.json

5. Cài đặt Lite-Server trên project
    > npm install lite-server --save-dev

6. Tạo mới 1 file index.html thêm nội dung

7. Bổ sung command script để chỉ định web server thực thi ứng dụng
    "scripts": {
        "start": "npm run lite",
        "lite":"lite-server",
        "test": "echo \"Error: no test specified\" && exit 1"
    }

8. Chạy Lite-Server:
    > npm start

---- CÀI ĐẶT BOOTSTRAP, JQUERY, POPPER.JS VÀO Node Modules ----
1. Cài đặt Bootstrap (v4.0.0)
    > npm install bootstrap@4.0.0 --save

2. Cài đặt Jquery, Popper.js
    > npm install jquery@3.3.1 popper.js@1.12.9 --save