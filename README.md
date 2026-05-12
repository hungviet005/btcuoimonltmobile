Xây dựng ứng dụng mua sắm quần áo online - ATH

## Tên đề tài

Xây dựng ứng dụng mua sắm quần áo online - ATH

## Giới thiệu website/hệ thống

Dự án là một hệ thống bán hàng thời trang gồm hai phần chính:
- `backend/`: API RESTful xây dựng bằng Node.js + Express cho các chức năng đăng ký, đăng nhập, sản phẩm, giỏ hàng, danh mục và đơn hàng.
- `mobile/`: ứng dụng di động React Native sử dụng Expo để hiển thị giao diện mua sắm, đăng nhập, đăng ký, tìm kiếm, chi tiết sản phẩm, giỏ hàng và thanh toán.

Hệ thống hỗ trợ:
- Đăng ký/đăng nhập người dùng
- Quản lý thông tin người dùng
- Hiển thị sản phẩm và danh mục
- Thêm/sửa/xóa sản phẩm trong giỏ hàng
- Tạo đơn hàng và xem lịch sử đơn
- Tải ảnh sản phẩm từ backend

## Danh sách thành viên

- Thành viên 1: Trần Đức Anh
- Thành viên 2: Nguyễn Mạnh Toàn
- Thành viên 3: Xa Viêt Hùng


## MSSV từng thành viên

- Thành viên 1: 23810310267
- Thành viên 2: 23810310262
- Thành viên 3: 23810310278


## Phân công nhiệm vụ cụ thể
- Trần Đức Anh : 
  - Phát triển backend API: `backend/`
  - Xây dựng các route và controller: `auth`, `product`, `cart`, `category`, `order`
  - Kết nối cơ sở dữ liệu MySQL với `backend/config/db.js`
  - Xử lý upload ảnh bằng `multer`
  - Xây dựng giao diện React Native với Expo
  - Cấu hình điều hướng màn hình bằng `@react-navigation`
  - Tích hợp API với `axios`
  - Xây dựng các màn hình: `HomeView`, `LoginView`, `OrderSuccessScreen`, `ProfileView`, `EditProfileView`

- Nguyễn Mạnh Toàn :
  - Phát triển mobile app: `mobile/`
  - Xây dựng giao diện React Native với Expo
  - Cấu hình điều hướng màn hình bằng `@react-navigation`
  - Tích hợp API với `axios`
  - Xây dựng các màn hình: `SplashView`, `RegisterView`, `SearchView`, `SearchResultView`, `OrderHistoryView`

- Xa Việt Hùng : 
  - Phát triển mobile app: `mobile/`
  - Xây dựng giao diện React Native với Expo
  - Cấu hình điều hướng màn hình bằng `@react-navigation`
  - Tích hợp API với `axios`
  - Xây dựng các màn hình: `CartView`, `CheckoutScreen`, `CustomDrawer`, `DetailView`


## Công nghệ sử dụng

 I.Backend
- Node.js
- Express
- MySQL (mysql2)
- bcryptjs
- jsonwebtoken
- multer
- cors
- dotenv

II.Mobile
- React Native
- Expo
- React Navigation
- Axios
- Async Storage
- Expo Image Picker

## Hướng dẫn cài đặt

I. Backend

1. Mở terminal và vào thư mục `backend/`:
   ```bash
   cd backend
   ```
2. Cài đặt phụ thuộc:
   ```bash
   npm install
   ```
3. Cấu hình MySQL:
   - Mở file `backend/config/db.js`
   - Đặt `host`, `user`, `password`, `database` phù hợp với môi trường của bạn.
   - Mặc định đang sử dụng:
     - host: `localhost`
     - user: `root`
     - password: `` (rỗng)
     - database: `fashion_db`
4. Tạo cơ sở dữ liệu MySQL `fashion_db` và các bảng cần thiết theo cấu trúc dự án.

 II. Mobile

1. Mở terminal và vào thư mục `mobile/`:
   ```bash
   cd mobile
   ```
2. Cài đặt phụ thuộc:
   ```bash
   npm install
   ```
3. Nếu dùng Expo CLI, cài nếu cần:
   ```bash
   npm install -g expo-cli
   ```
4. Kiểm tra file `mobile/services/api.js` để đảm bảo `baseURL` trỏ đến server backend (`http://localhost:5000/api`).

## Hướng dẫn chạy project

 I. Chạy backend

1. Trong terminal tại thư mục `backend/`:
   ```bash
   node server.js
   ```
2. Backend sẽ chạy ở `http://localhost:5000`.

II. Chạy mobile

1. Trong terminal tại thư mục `mobile/`:
   ```bash
   npm start
   ```
2. Mở ứng dụng trên thiết bị thật hoặc giả lập qua Expo.

## Tài khoản demo (nếu có)
Email : admin@gmail.com
mật khẩu : 1234
## Hình ảnh minh họa hệ thống
<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/a61de76b-01da-425a-8d2b-616140a3c9a0" />
<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/a66986d0-7e9a-4b2a-87dc-546dca6f1fec" />
<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/09e8da3a-e865-4a48-b954-825b792882e1" />
<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/a230cf58-645e-4318-a09c-b3c3549c44ca" />
<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/94c62e17-b37e-445b-a4c7-71f7770733e8" />
<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/43c2550a-d342-4d16-ae3a-4af1ec9bab8e" />
<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/f18cfb53-f68d-447a-9ae7-0a168af0cd90" />
<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/d0ba5b0d-9463-42ab-907b-b6675c62d120" />
<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/c0332940-1142-4611-9072-466c09e062a3" />
<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/8e3619f6-3280-43e2-bf20-d078db3aac85" />
<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/4b405209-658c-435a-9604-3c5366b4f2aa" />
<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/d063b960-d130-4c99-bbce-0f267381826d" />
<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/4bea8c53-5d93-4248-a004-abba33eaa0aa" />
<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/352c5308-3cab-4bf8-980b-18c50ca85998" />
<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/5583db91-576c-4c59-9eee-fedc0f5f6c8d" />

## Video DEMO

https://drive.google.com/drive/folders/1H-ETObOIX22Ef8hkBDMmI1q_p4Furyev?fbclid=IwY2xjawRv_aRleHRuA2FlbQIxMQBzcnRjBmFwcF9pZAEwAAEe3KO6OYsF7B9_XqAJbG3Cf98bvpIzHWvREtTT9bxAHqwmi5QZdiayp6Ldu9c_aem_T30mAM_eRe7wrK4Y2H-ADw
