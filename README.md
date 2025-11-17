# ESP8266 - Module Wifi

## 1. Linh kiện cần có

| Linh kiện                | Mô tả                         |
| ------------------------ | ----------------------------- |
| **ESP8266 (NodeMCU)**    | Vi điều khiển chính của dự án |
| **Cáp USB Micro**        | Dùng để nạp code và cấp nguồn |
| **LED**                  | Hiển thị tín hiệu             |
| **Động cơ DC**           | Điều khiển chuyển động        |
| **Cảm biến dò line**     | Phát hiện đường line          |
| **Dây cắm / Breadboard** | Dùng để đấu nối               |

> **Ghi chú:** Một số board dùng chip nạp **CH340** hoặc **CP2102**, cần cài driver để máy tính nhận cổng COM.

---

## 2. Cài đặt board ESP8266 trên Arduino IDE

1. Mở **Arduino IDE**
2. Vào **Tools → Board → Boards Manager**
3. Tìm: **"ESP8266"**
4. Nhấn **Install**

---

## 3. Chọn board và cổng COM

* **Board:** NodeMCU 1.0 (ESP-12E Module)
* **Port:** COM3, COM4,... tùy máy nhận được

---

## 4. Cài đặt thư viện

Các thư viện cần thiết:

* **ESPAsyncTCP**
* **ESPAsyncWebServer**

Cách cài:

1. Vào **Sketch → Include Library → Manage Libraries…**
2. Nhập tên thư viện
3. Chọn **Install**
