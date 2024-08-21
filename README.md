![OKX banner](https://raw.githubusercontent.com/zuydd/image/main/okx.jpg)
# Tool Auto OKX Racer NodeJS by ZuyDD

**Tool phát triển và chia sẻ miễn phí bởi ZuyDD**

<a href="https://www.facebook.com/zuy.dd"><img src="https://raw.githubusercontent.com/zuydd/image/main/facebook.svg" alt="Facebook"></a>
<a href="https://t.me/zuydd"><img src="https://raw.githubusercontent.com/zuydd/image/main/telegram.svg" alt="Telegram"></a>
> [!WARNING]
> Mọi hành vi buôn bán tool dưới bất cứ hình thức nào đều không được cho phép!


## 🛠️ Hướng dẫn cài đặt
> Yêu cầu đã cài đặt NodeJS

- Bước 1: Tải về phiên bản mới nhất của tool [tại đây ⬇️](https://github.com/zuydd/okx/archive/refs/heads/main.zip)
- Bước 2: Giải nén tool
- Bước 3: Tại thư mục tool vừa giải nén, chạy lệnh `npm install` để cài đặt các thư viện bổ trợ


## 💾 Cách thêm dữ liệu tài khoản
> Tool sử dụng `query_id` làm dữ liệu đầu vào cho mỗi tài khoản

> Tất cả dữ liệu mà bạn cần nhập đều nằm ở các file trong thư mục 📁 `src / data`

- [users.txt](src/data/users.txt) : chứa danh sách `query_id` của các tài khoản, mỗi dòng ứng với một tài khoản
- [proxy.txt](src/data/proxy.txt) : chứa danh sách proxy, proxy ở mỗi dòng sẽ ứng với tài khoản ở dòng đó trong file users.txt phía trên, để trống nếu không dùng proxy

> Lưu ý: Nếu nhận được thông báo đăng nhập thất bại, hãy lấy mới lại `query_id`


## >_ Các lệnh và chức năng tương ứng
| Lệnh | Chức năng |
|----------|----------|
| `npm run start` | Dùng để chạy chơi game (dự đoán giá), làm nhiệm vụ,.... tóm lại game có gì là nó làm cái đó |
| `npm run boost` | Dùng để nâng cấp các loại boost cho xe đua |

> Các lệnh trên chạy hoàn toàn độc lập với nhau


## 🕹️ Các tính năng có trong tool
- Đa luồng, tự động chạy khi đủ lượt (mặc định sẽ chạy khi còn thiếu 1 lượt để tối ưu, có thể tìm biến `numberX = 1` sửa lại theo ý thích)
- Tự động nhận diện proxy
- Tự động làm nhiệm vụ nếu có
- Chơi game dự đoán auto win. Mặc định chế độ auto win bị tắt để tránh ban acc, ai thích thì vào file [services/game.js](src/services/game.js) tìm dòng `this.autoWin = false` đổi false thành true để bật chế độ dự đoán giá auto win
- Nâng cấp boost hàng loạt
- Tự động chuyển đổi định dạng query_id, encode hay decode vứt vô chạy láng hết 🤣
- Mặc định mỗi tài khoản sẽ chạy cách nhau 30s để tránh spam request, có thể tìm biến `DELAY_ACC = 30` để điều chỉnh


## 🔄 Lịch sử cập nhật
> Phiên bản mới nhất: `v0.0.1`

<details>
<summary>v0.0.1 - 📅 21/08/2024</summary>
  
- Chia sẻ tool cho cộng đồng
- Bổ sung readme
</details>

## 🎁 Donate
🌟 Kêu gọi ủng hộ 🌟

Chúng tôi rất vui được chia sẻ các mã script và tài nguyên mã nguồn miễn phí đến cộng đồng làm airdrop. Nếu bạn thấy các công cụ và tài liệu của chúng tôi hữu ích và muốn ủng hộ chúng tôi tiếp tục phát triển và duy trì các dự án này, bạn có thể đóng góp hỗ trợ qua hình thức donate.

Mỗi đóng góp của bạn sẽ giúp chúng tôi duy trì chất lượng dịch vụ và tiếp tục cung cấp những tài nguyên giá trị cho cộng đồng làm airdrop. Chúng tôi chân thành cảm ơn sự hỗ trợ và ủng hộ của bạn!

Mãi iu 😘😘😘

<div style="display: flex; gap: 20px;">
  <img src="https://raw.githubusercontent.com/zuydd/image/main/qr-momo.png" alt="QR Momo" height="340" />
  <img src="https://raw.githubusercontent.com/zuydd/image/main/qr-binance.jpg" alt="QR Binance" height="340" />
</div>
