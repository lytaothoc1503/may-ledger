# Mây Ledger

Sổ quỹ tiền cọc / hoàn tiền cho **Nhà của An Homestay Tà Xùa** (dự án độc lập, không dùng chung code với website chính).

- Tiền vào → đang chờ → đã nhận; khách huỷ → hoàn tiền theo số tài khoản ngân hàng.
- Chi phí, đối soát ngày, báo cáo tháng (CSV), nhật ký thao tác.
- Phân quyền chủ / nhân viên bằng Supabase Auth + RLS (các bảng tiền tố `ml_`).

Lần đầu: đăng ký, xác nhận email, bấm "Tôi là chủ — nhận quyền quản trị" (chỉ một lần), rồi thêm email nhân viên trong "Nhân sự & cài đặt".
