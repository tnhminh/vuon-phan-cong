# Vườn Phản Công

Game bắn ná vật lý chạy trên trình duyệt: kéo ná, bắn trái cây, đánh sập pháo đài của lũ chuột.

- 36 màn, 6 chương: Vườn nhà, Ruộng lúa, Rừng tre, Đồi chè, Bến sông, Hang chuột
- Mỗi chương một cơ chế riêng: gió đồng, tre đàn hồi, tảng đá lăn, sông nước và bè nổi, hang tối với đèn lồng
- 4 loại trái cây: Xoài, Chanh (lao tới), Dừa (nện xuống), Ớt (nổ)
- Thùng pháo Tết, giỏ trái cây thưởng lượt, thử thách sao thứ 3 cho từng màn
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
- Esc: tạm dừng · R: chơi lại màn

Tiến độ và số sao được lưu trong `localStorage` của trình duyệt.
