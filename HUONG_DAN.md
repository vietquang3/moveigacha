# Movie Gacha -> IPA (không cần Mac)

1. Tạo repo GitHub mới (private cũng được), upload toàn bộ thư mục này (nhớ cả thư mục .github).
2. Vào tab Actions -> "Build IPA" -> Run workflow. Đợi ~5-10 phút.
3. Tải artifact "MovieGacha-ipa" -> giải nén ra MovieGacha.ipa (chưa ký).
4. Cài lên iPhone bằng Sideloadly (Windows/Mac) hoặc AltStore, đăng nhập Apple ID miễn phí.
   - iPhone: Cài đặt > Quyền riêng tư & Bảo mật > Chế độ nhà phát triển (bật), rồi tin cậy chứng chỉ trong Cài đặt > Cài đặt chung > VPN & Quản lý thiết bị.
   - Apple ID miễn phí: app hết hạn sau 7 ngày, cài lại để gia hạn. Tài khoản Developer 99$/năm: 1 năm.
5. Muốn dùng ảnh mặt sau thẻ riêng: đặt backcard.png vào thư mục www/ (nó tự ưu tiên hơn backcard.svg).
6. Muốn icon riêng: thêm thư mục assets/ với icon.png 1024x1024 rồi chạy npx @capacitor/assets generate --ios trước bước cap sync.
