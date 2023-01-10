-- CÀI ĐẶT WEB SERVER (Lite-Server) ---

1. Tải phần mềm NodeJS: https://nodejs.org

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