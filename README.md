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
<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/15b4b24e-4b66-4a4c-b21c-748dc134a818" />
<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/dc432895-6c48-4f3c-ba99-63f566ce4dcc" />
<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/836389d4-fe89-4856-9bcf-399a135002ce" />
<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/8b46a2b1-52ef-434c-9c72-9b8f7bdc10d2" />
<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/01ec24f8-39f4-4ab7-b051-a3cf17a175c9" />
<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/4fc22fa6-c9fc-4126-a031-b192f19ac9e5" />

<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/ba9e1bb8-3dda-4306-855c-0b3d308c8eb5" />
<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/ad418101-d712-4356-a529-23191dc339e9" />
<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/0df81d17-7ed8-411a-9e0f-516f6cd3ad3d" />
<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/ca92c4ed-3590-4afc-9a7a-ce9a7851a199" />
<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/d1916dc6-772c-4656-aa60-09072c030d2b" />
<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/9f2fc9ce-215f-4337-ac53-80041558e78c" />
<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/4dd8bc27-e02f-4935-9df4-cbe469141b44" />
![Uploading image.png…]()
## Video DEMO

https://drive.google.com/drive/folders/1H-ETObOIX22Ef8hkBDMmI1q_p4Furyev?fbclid=IwY2xjawRv_aRleHRuA2FlbQIxMQBzcnRjBmFwcF9pZAEwAAEe3KO6OYsF7B9_XqAJbG3Cf98bvpIzHWvREtTT9bxAHqwmi5QZdiayp6Ldu9c_aem_T30mAM_eRe7wrK4Y2H-ADw
