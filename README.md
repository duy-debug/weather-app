

# Ứng Dụng Thời Tiết với TanStack Query

Một ứng dụng thời tiết hiện đại được xây dựng bằng React và TanStack Query, cung cấp thông tin thời tiết thời gian thực và dự báo.

## Tính Năng

- 🌤️ Thông tin thời tiết hiện tại
- 📅 Dự báo thời tiết
- 🔍 Tìm kiếm địa điểm
- 📍 Định vị ngược (Reverse geocoding)
- 🌡️ Nhiệt độ theo độ C
- 🎯 Thiết kế responsive

## Công Nghệ Sử Dụng

- React
- TanStack Query (React Query)
- TypeScript
- OpenWeatherMap API
- CSS Hiện Đại

## Bắt Đầu

### Yêu Cầu

- Node.js (phiên bản 14 trở lên)
- npm hoặc yarn
- API key của OpenWeatherMap

### Cài Đặt

1. Clone repository:
```bash
git clone https://github.com/duy-debug/weather-app.git
cd weather-app
```

2. Cài đặt các dependencies:
```bash
npm install
# hoặc
yarn install
```

3. Tạo file `.env` trong thư mục gốc và thêm API key của OpenWeatherMap:
```
VITE_WEATHER_API_KEY=d051f2760596fd730c0e5da464099ee9
```

4. Khởi động server phát triển:
```bash
npm run dev
# hoặc
yarn dev
```

## Tích Hợp API

Ứng dụng sử dụng các endpoint sau của OpenWeatherMap API:
- Thời tiết hiện tại
- Dự báo thời tiết 5 ngày
- API Geocoding để tìm kiếm địa điểm
- Định vị ngược (Reverse Geocoding)

## Cấu Trúc Dự Án

```
src/
├── api/          # Tích hợp API và types
├── components/   # Các component React
├── hooks/        # Custom hooks
└── utils/        # Các hàm tiện ích
```

## Đóng Góp

Mọi đóng góp đều được hoan nghênh! Hãy thoải mái tạo Pull Request.


## Lời Cảm Ơn

- OpenWeatherMap đã cung cấp API dữ liệu thời tiết
- TanStack Query cho giải pháp lấy và lưu cache dữ liệu
## Hướng dẫn tham khảo
https://www.youtube.com/watch?v=BCp_5PoKrvI&t=26s&ab_channel=RoadsideCoder

