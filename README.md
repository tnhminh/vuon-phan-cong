# Vườn Phản Công

Game bắn ná vật lý chạy trên trình duyệt: kéo ná, bắn trái cây, đánh sập pháo đài của lũ chuột.

- 48 màn, 8 chương: Vườn nhà, Ruộng lúa, Rừng tre, Đồi chè, Bến sông, Hang chuột, Đèo tuyết, Núi lửa
- Mỗi chương một cơ chế riêng: gió đồng, tre đàn hồi, tảng đá lăn, sông nước và bè nổi, hang tối với đèn lồng, băng trơn và bão tuyết, dung nham với thép rèn và bệ hơi nước
- 4 loại trái cây: Xoài, Chanh (lao tới), Dừa (nện xuống), Ớt (nổ)
- Thùng pháo Tết, giỏ trái cây thưởng lượt, thử thách sao thứ 3 cho từng màn
- Cốt truyện truyện tranh mở đầu và kết thúc mỗi chương, trận trùm có thanh máu và 2 pha
- 2 trùm cuối mới: Chuột Tuyết Khổng Lồ (đổi chiều bão tuyết sau mỗi lượt) và Chuột Hoàng Đế (3 pha: đứng trên bệ hơi nước, gọi viện binh, cuồng nộ nhảy giữa các tháp)
- Túi bảo bối: Ống nhòm, Phân bón thần, Sét đánh, Trống đồng; mua bằng xu, rương báu trong màn tặng thêm
- Vườn hồi sinh ở trang đầu theo số chương đã qua
- Kho đồ (skin ná, vệt bay, trái trợ chiến Dưa hấu, Sầu riêng, Mít), thử thách hằng ngày, sổ 12 chuột lạ
- Xưởng trái cây: tự tạo nhân vật (thân, cỡ, độ nặng, kiểu bay zig zag/lượn sóng/nhào lộn/bay bổng, chiêu, đặc tính vừa bay vừa ỉa, phụ kiện)
- Chế độ vô tận "Đêm giao thừa", chế độ "Đấu trùm" đánh liền các trùm đã hạ, 22 thành tích, phát lại cú bắn đẹp nhất
- Hiệu ứng: chuột văng vào màn hình, hit-stop, quay chậm, đồng xu bay về bảng điểm, nhạc nền tự tạo bằng Web Audio

## Chạy thử

Toàn bộ game nằm trong một file `index.html`. Mở file đó bằng trình duyệt là chơi được.
Cần có mạng để tải thư viện vật lý [Matter.js 0.19.0](https://brm.io/matter-js/) và font từ Google Fonts.

## Đăng lên GitHub Pages

1. Push thư mục này lên một repository.
2. Vào **Settings → Pages**, chọn nhánh `main`, thư mục `/ (root)`, rồi lưu.
3. Sau khoảng một phút game sẽ có ở `https://<tên-tài-khoản>.github.io/<tên-repo>/`.

## Điều khiển

- Kéo trái cây trên ná ra sau rồi thả để bắn
- Chạm màn hình (hoặc phím Space) khi trái đang bay để dùng chiêu
- Chạm biểu tượng vật phẩm ở bên phải khi đang ngắm để dùng (mỗi món một lần mỗi màn)
- Esc: tạm dừng · R: chơi lại màn

Tiến độ và số sao được lưu trong `localStorage` của trình duyệt. Trái tự tạo chia sẻ được bằng mã dạng `VPC-…`.

Bảng xếp hạng chung chỉ hoạt động khi chơi qua link artifact trên Claude (dùng kho dữ liệu dùng chung của artifact). Bản chạy trên GitHub Pages vẫn chơi đủ mọi thứ khác, chỉ hiện thông báo ở mục Bảng xếp hạng.
