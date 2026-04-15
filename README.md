# Sensor Network - LM35

## Mô tả
Dự án sử dụng Arduino để đọc nhiệt độ từ cảm biến LM35 và gửi dữ liệu qua Serial.

---

## Tính năng
- Đọc nhiệt độ từ các chân A0, A1, A2
- Chuyển đổi ADC sang độ C
- Xuất dữ liệu qua Serial

---

## Phần cứng cần thiết

| Thiết bị     | Số lượng |
|-------------|---------|
| Arduino Uno | 1       |
| LM35        | 2-3     |
| Dây nối     | Nhiều   |

---

## Cách sử dụng
1. Kết nối LM35 vào các chân A0, A1, A2  
2. Nạp code vào Arduino  
3. Mở Serial Monitor (9600 baud) để xem dữ liệu  

---

## Cấu trúc thư mục

```
project/
├── firmware/
│   └── LM35_TempReader/
│       └── LM35_TempReader.ino
└── README.md
```

---

## Thành viên nhóm

1. Nguyễn Huy Hiệu - N23DCCI024
2. Thái Gia Kỳ - N23DCCI038

---

## Tác giả

- **Nguyễn Huy Hiệu**  
  [Xem trang cá nhân](https://hamsterxt309.github.io/)