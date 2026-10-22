# Website Trung tâm tiếng Anh (TTA)

Dự án website của **Trung tâm tiếng Anh TTA**, dùng để quản lý *học viên, khoá học và học phí* theo từng tháng.

## Giới thiệu

Website giúp học viên xem khoá học, đăng ký học và giúp kế toán đối chiếu học phí hằng tháng.

## Cấu trúc thư mục

| Thư mục | Nội dung |
|---------|----------|
| `data/` | Dữ liệu học viên khoá 3 và bảng học phí tháng 10 (file Excel) |
| `docs/` | Tài liệu dự án |
| `media/` | Hình ảnh, video của website |
| `logs/` | Nhật ký hoạt động |
| `archive/` | Tài liệu, dữ liệu cũ đã lưu trữ |

## Quy trình đăng ký học

1. Học viên chọn khoá học phù hợp trên website.
2. Điền phiếu đăng ký và chọn số tháng học.
3. Nộp học phí và nhận xác nhận từ trung tâm.

## Liệt kê nội dung dự án

```powershell
Get-ChildItem -Recurse -Force
```

## Công việc

- [x] Tạo cấu trúc thư mục dự án
- [x] Chuẩn hoá dữ liệu học phí tháng 10
- [ ] Hoàn thiện bảng học phí gửi kế toán

> **Lưu ý:** Không upload file `.env` lên GitHub hay bất kỳ nơi công khai nào vì chứa thông tin bí mật.
