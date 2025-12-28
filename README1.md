# Ứng Dụng Thời Tiết với React, TanStack Query, Shadcn UI, Recharts, Tailwind và TypeScript

## Tổng quan

Một bảng điều khiển thời tiết hiện đại được xây dựng bằng React và TanStack Query, cung cấp thông tin thời tiết và dự báo thời gian thực với giao diện sạch sẽ, phản hồi tốt.

## Tính năng

- Chi tiết thời tiết hiện tại
- Dự báo thời tiết 5 ngày
- Chức năng tìm kiếm địa điểm
- Định vị ngược cho vị trí hiện tại
- Đơn vị đo lường cho nhiệt độ và tốc độ gió
- Thiết kế tương thích với mọi thiết bị
- Hỗ trợ chế độ sáng và tối

## Công nghệ sử dụng

- Frontend: React 18, Vite
- Lấy dữ liệu: TanStack Query (React Query)
- Định dạng: Tailwind CSS, Shadcn UI
- Biểu đồ: Recharts
- Ngôn ngữ: TypeScript
- API: OpenWeatherMap API

## Bắt đầu

### Điều kiện tiên quyết

- Node.js (phiên bản 14 trở lên)
- npm hoặc yarn
- Mã API OpenWeatherMap

### Cài đặt

1. Sao chép kho lưu trữ:
```bash
git clone https://github.com/duy-debug/weather-app.git
cd weather-app
```

2. Cài đặt các thư viện:
```bash
npm install
```

3. Gạo file .env trong thư mục gốc và thêm mã API OpenWeatherMap của bạn:
```
VITE_WEATHER_API_KEY=your_api_key_here
```

4. Chạy máy chủ phát triển:
```bash
npm run dev
```

## Tích hợp API

Ứng dụng tích hợp với các điểm cuối API OpenWeatherMap sau:
- Dữ liệu thời tiết hiện tại
- Dự báo 5 ngày / 3 giờ
- API Geocoding (Tìm kiếm địa điểm)
- API Geocoding ngược

## Cấu trúc dự án

```
src/
├── api/          # Tích hợp API và định nghĩa kiểu dữ liệu
├── components/   # Các thành phần giao diện có thể tái sử dụng
├── hooks/        # Các React hooks tùy chỉnh
├── pages/        # Các trang chính của ứng dụng
├── lib/          # Các tiện ích và cấu hình dùng chung
└── context/      # Các nhà cung cấp ngữ cảnh
```

## Lời cảm ơn

- Dữ liệu thời tiết được cung cấp bởi OpenWeatherMap
- Giải pháp lấy dữ liệu bởi TanStack Query
- Các thành phần giao diện bởi Shadcn UI và Radix UI
- Biểu đồ bởi Recharts

## Giấy phép

Dự án này được cấp phép theo Giấy phép MIT.
