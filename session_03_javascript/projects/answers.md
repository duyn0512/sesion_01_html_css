# JavaScript

## Exercise 0 — Hello JavaScript! (Làm quen với JavaScript)

### Bài 0.1 — Chào thế giới

#### So sánh `console.log()` và `document.write()` trong JavaScript

Hai hàm này phục vụ hai mục đích hoàn toàn khác nhau trong JavaScript: `console.log()` dùng để **kiểm tra, sửa lỗi** (debugging), còn `document.write()` dùng để **ghi trực tiếp nội dung lên trang web**.

#### Bảng so sánh nhanh

| Đặc điểm | `console.log()` | `document.write()` |
| :--- | :--- | :--- |
| **Vị trí hiển thị** | Trong tab **Console** của Công cụ nhà phát triển (F12). | Hiển thị trực tiếp trên **giao diện trang web** (DOM). |
| **Đối tượng nhìn thấy** | Lập trình viên (người dùng bình thường không thấy). | Tất cả mọi người truy cập trang web. |
| **Ảnh hưởng đến DOM** | Không làm thay đổi hay ảnh hưởng đến cấu trúc HTML. | Ghi trực tiếp vào luồng HTML, có thể can thiệp DOM. |
| **Mức độ sử dụng** | **Rất phổ biến** và là công cụ debug không thể thiếu. | **Bị hạn chế / Lỗi thời**, hầu như không dùng trong thực tế. |

#### Bài 0.2 — Khai báo biến

| Câu hỏi | `let` | `const` | `var` |
|---------|-------|---------|-------|
| Có thể thay đổi giá trị? | ✅ Có | ❌ Không | ✅ Có |
| Có thể khai báo lại? | ❌ Không | ❌ Không | ✅ Có |
| Nên dùng trong code mới? | ✅ | ✅ | ❌ Tránh |

