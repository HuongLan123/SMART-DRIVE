# Hướng dẫn cài đặt và chạy dự án

## Công nghệ sử dụng
- Ngôn ngữ: TypeScript, JavaScript, Python, HTML, CSS
- Framework/Libraries: ReactJS

## Yêu cầu cài đặt công cụ
Trước khi bắt đầu, bạn cần cài đặt các công cụ sau:
- IDE: Visual Studio Code (hoặc IDE bạn yêu thích)
- Node.js (phiên bản mới nhất được khuyến nghị)
- Python (phiên bản mới nhất được khuyến nghị)

## Các bước thực hiện

### 1. Tải mã nguồn về máy
Mở terminal và chạy lệnh sau để tải mã nguồn từ GitHub:

```bash
git clone https://github.com/HuongLan123/SMART-DRIVE.git
cd SMART-DRIVE
```
### 2. Kiểm tra cấu hình môi trường
Kiểm tra xem Node.js và npm đã được cài đặt đúng chưa:
```bash
node -v
npm -v
```
Nếu chưa có hoặc phiên bản quá cũ, vui lòng cài đặt hoặc cập nhật Node.js tại https://nodejs.org.
### 3. Cài đặt các package
Chạy lệnh sau để cài đặt các thư viện cần thiết:
```bash
npm install
```
### 4. Chạy server backend
Mở một terminal mới, chạy lệnh:
```bash
node server.js
```
### 5. Chạy frontend development server
Mở một terminal khác, chạy lệnh:
```bash
npm run dev
```
