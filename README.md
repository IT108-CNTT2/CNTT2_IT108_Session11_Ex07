# Sửa lỗi Heading và Auto TOC

## Phần 1: Phân tích

File bị lỗi mục lục vì các tiêu đề đang được định dạng thủ công như tăng cỡ chữ, in đậm, tô màu nhưng vẫn để kiểu **Normal**. Vì vậy Word không nhận ra đây là tiêu đề để đưa vào mục lục tự động.

Các cấp tiêu đề đúng là:

- `1. Thông tin chung hội nghị` → Heading 1
- `1.1. Tên hội nghị` → Heading 2
- `1.2. Thời gian & địa điểm` → Heading 2
- `2. Cơ cấu ban tổ chức` → Heading 1
- `2.1. Ban Nội dung` → Heading 2
- `2.1.1. Tiểu ban Kỹ thuật` → Heading 3
- `3. Lịch trình sự kiện` → Heading 1

## Phần 2: Sửa lỗi

- Bôi đen từng tiêu đề và gán đúng **Heading 1, Heading 2, Heading 3**.
- Có thể dùng phím tắt:
  - `Ctrl + Alt + 1` → Heading 1
  - `Ctrl + Alt + 2` → Heading 2
  - `Ctrl + Alt + 3` → Heading 3
- Các đoạn văn bình thường để **Normal**.
- Sau đó vào **References → Table of Contents → Automatic Table** để tạo lại mục lục.
- Khi thêm hoặc sửa nội dung, chọn mục lục → **Update Table → Update entire table**.

Sau khi sửa đúng cấp Heading thì mục lục sẽ hiện đầy đủ các chương và mục con.
