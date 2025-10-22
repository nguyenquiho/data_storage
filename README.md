Bạn đang có **file nén đa phần (multi-part archive)** được chia bằng **WinRAR**, ví dụ:

```
Retouch_AnhCuoi_Final.part01.rar
Retouch_AnhCuoi_Final.part02.rar
Retouch_AnhCuoi_Final.part03.rar
...
Retouch_AnhCuoi_Final.part60.rar
```

Dưới đây là **cách gộp và giải nén đúng chuẩn để khôi phục file hoàn chỉnh mà không mất dữ liệu:**

---

## 🪄 CÁCH GHÉP VÀ GIẢI NÉN

### ✅ Bước 1: Đặt tất cả các file `.part01.rar` → `.part60.rar` vào **cùng một thư mục**

* Đảm bảo **đủ 60 file**, **tên không thay đổi** (phải giữ nguyên thứ tự và phần mở rộng `.partXX.rar`).
* Không đổi tên file, không thêm dấu cách, không xóa số 0.

---

### ✅ Bước 2: Giải nén **bắt đầu từ file đầu tiên**

* **Chuột phải** vào file đầu tiên:
  👉 `Retouch_AnhCuoi_Final.part01.rar`
* Chọn:

  * `Extract Here` (Giải nén tại đây) hoặc
  * `Extract to Retouch_AnhCuoi_Final\`

📦 WinRAR (hoặc 7-Zip) sẽ **tự động nhận biết** các phần `.part02`, `.part03`, … `.part60` và **ghép lại toàn bộ thành một file hoàn chỉnh**.

---

### ✅ Bước 3: Chờ WinRAR tự động gộp

WinRAR sẽ hiển thị tiến trình **Extracting from part01.rar**
→ và tự động đọc các file `.part02`, `.part03`, … nối tiếp nhau.

Sau khi hoàn tất, bạn sẽ thấy file/thư mục gốc ban đầu được giải nén ra.

---

## ⚠️ Lưu ý quan trọng

* Nếu có lỗi “**Unexpected end of archive**” hoặc “**Cannot open part02**” → nghĩa là **thiếu hoặc sai tên một file**.
  👉 Kiểm tra lại xem có **đủ 60 file**, và tên phải **giống hệt nhau** (chỉ khác phần số thứ tự).

* Nếu file nào bị lỗi tải (kích thước khác phần còn lại) → cần tải lại đúng phần đó, vì chỉ **một phần lỗi sẽ làm toàn bộ không giải nén được**.

* Bạn **chỉ cần giải nén file part01** – không cần bấm vào part02, part03,…
/* End Read me*/
