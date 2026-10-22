- **Họ tên:** Nguyễn Trung Thành
- **Lớp:** CNTT 3
- **Link repository:**
- **Hệ điều hành (Windows/macOS):** Windows

## Bài 1. README.md

> README.md được chấm trực tiếp trên file `README.md` ở thư mục gốc. Đánh dấu `[x]` vào các mục đã làm để tự kiểm tra.

- [x] Heading 1: tên dự án
- [x] Ít nhất 2 heading cấp 2
- [x] Mô tả ngắn có cả **in đậm** và *in nghiêng*
- [x] Bảng `Thư mục | Nội dung`, ít nhất 3 dòng dữ liệu
- [x] Danh sách đánh số ít nhất 3 bước
- [x] Code block chứa lệnh PowerShell/Terminal liệt kê nội dung dự án
- [x] Task list ít nhất 2 công việc, có ít nhất 1 mục đã hoàn thành
- [x] Blockquote nhắc không upload `.env`

## Bài 2. Excel

> Công thức được chấm trực tiếp trên file `data/hoc_phi_thang_10.xlsx`.

- **Số dòng còn hiển thị sau khi lọc (câu d):** (điền sau khi lọc xong)
- **Câu e - Vì sao vùng tra cứu cần dấu $:** Dấu `$` khoá vùng tra cứu `KhoaHoc!$A$2:$C$8` (tham chiếu tuyệt đối), nên khi kéo công thức xuống, vùng tra luôn cố định ở A2:C8 và dòng nào cũng tra đúng bảng 7 khoá học. Nếu bỏ `$` rồi kéo xuống, vùng tra sẽ trượt theo từng dòng (dòng 3 thành A3:C9, dòng 4 thành A4:C10...). Các khoá ở đầu bảng rơi ra ngoài vùng tra, VLOOKUP trả về `#N/A`, kéo càng xa kết quả càng sai.

## Tự chấm (điền sau khi có đáp án)

- **Điểm tự chấm:** ..../100
- **Lỗi mình đã mắc và cách sửa:**