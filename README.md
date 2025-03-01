Tôi sẽ tạo một file README.md chi tiết cho dự án máy tính của bạn:

```markdown
# Modern Calculator

![Calculator Preview](/screenshots/calculator-preview.png)

Một ứng dụng máy tính hiện đại được xây dựng bằng Java Swing, với giao diện người dùng đẹp mắt và các tính năng toán học nâng cao.

## 🌟 Tính năng

- 🎨 Giao diện người dùng hiện đại với thiết kế phẳng
- 🌓 Phối màu tối với các nút có hiệu ứng
- ➗ Hỗ trợ các phép tính cơ bản và nâng cao:
  - Phép tính cộng, trừ, nhân, chia
  - Phân số
  - Căn bậc hai
  - Lũy thừa
  - Phần trăm
- 📝 Lịch sử tính toán
- ⌨️ Hỗ trợ nhập dấu ngoặc
- 🎯 Hiển thị biểu thức toán học theo chuẩn:
  - Số mũ được hiển thị nhỏ và cao hơn
  - Dấu căn bậc hai với đường gạch ngang
  - Phân số với đường phân số ngang
- 🖱️ Hỗ trợ kéo thả cửa sổ
- ⚡ Hiệu ứng nút nhấn động

## 🛠️ Yêu cầu hệ thống

- Java Runtime Environment (JRE) 8 trở lên
- Hệ điều hành hỗ trợ: Windows, macOS, Linux

## 📦 Cài đặt

1. Đảm bảo bạn đã cài đặt Java trên máy tính
2. Tải xuống file JAR từ phần Releases
3. Chạy file bằng lệnh:
```bash
java -jar modern-calculator.jar
```

## 🏗️ Cấu trúc dự án

```plaintext
modern-calculator/
├── src/
│   ├── com/
│   │   └── calculator/
│   │       ├── main/
│   │       │   └── ModernCalculator.java
│   │       ├── constants/
│   │       │   └── MauSac.java
│   │       ├── utils/
│   │       │   └── TrinhVeMayTinh.java
│   │       └── components/
│   │           ├── ButtonCalculator.java
│   │           └── DisplayPanel.java
├── resources/
│   └── fonts/
├── screenshots/
└── README.md
```

## 💻 Sử dụng

### Các phép tính cơ bản

- Sử dụng các nút số và phép tính như máy tính thông thường
- Nhấn `=` để xem kết quả
- Nhấn `C` để xóa tất cả
- Nhấn `⌫` để xóa số cuối cùng


### Phép tính nâng cao

- **Căn bậc hai**: Nhấn `√` rồi nhập số cần tính
- **Phân số**: Nhập tử số, nhấn `⁄`, nhập mẫu số
- **Lũy thừa**: Nhập số cơ sở, nhấn `xⁿ`, nhập số mũ
- **Phần trăm**: Nhập số, nhấn `%`


## 🎨 Tùy chỉnh giao diện

Các màu sắc được định nghĩa trong file `MauSac.java`:

```java
public static final Color BACKGROUND_COLOR = new Color(22, 22, 24);
public static final Color BUTTON_DARK = new Color(44, 44, 46);
public static final Color BUTTON_OPERATOR = new Color(255, 159, 10);
// ...
```

Bạn có thể thay đổi các giá trị màu để tùy chỉnh giao diện theo ý muốn.

## 🤝 Đóng góp

Nếu bạn muốn đóng góp cho dự án:

1. Fork dự án
2. Tạo nhánh mới (`git checkout -b feature/AmazingFeature`)
3. Commit thay đổi (`git commit -m 'Add some AmazingFeature'`)
4. Push lên nhánh (`git push origin feature/AmazingFeature`)
5. Mở Pull Request


## 📝 Ghi chú

- Ứng dụng sử dụng Java Swing cho giao diện người dùng
- Các phép tính được thực hiện với độ chính xác cao
- Hỗ trợ hiển thị số thập phân tới 8 chữ số


## 🔑 Phím tắt

- `Enter`: Thực hiện phép tính (tương đương nút `=`)
- `Esc`: Xóa tất cả (tương đương nút `C`)
- `Backspace`: Xóa số cuối cùng (tương đương nút `⌫`)


## 📄 Giấy phép

Dự án này được phân phối dưới giấy phép MIT. Xem file `LICENSE` để biết thêm chi tiết.

## 👥 Tác giả

- Tên của bạn
- Profile: [@truongdat](https://truongdat.glitch.me)


## 🙏 Cảm ơn

Cảm ơn bạn đã quan tâm đến dự án Modern Calculator. Nếu bạn thấy dự án hữu ích, hãy cho nó một ngôi sao ⭐️!

```plaintext

File README.md này cung cấp:

1. Mô tả tổng quan về dự án
2. Danh sách tính năng chính
3. Yêu cầu hệ thống và hướng dẫn cài đặt
4. Cấu trúc dự án
5. Hướng dẫn sử dụng chi tiết
6. Hướng dẫn tùy chỉnh giao diện
7. Thông tin về đóng góp và giấy phép
8. Phím tắt và ghi chú quan trọng

Bạn có thể:
1. Thêm ảnh chụp màn hình vào thư mục `screenshots/`
2. Cập nhật thông tin tác giả
3. Thêm các ví dụ sử dụng cụ thể
4. Bổ sung thêm các tính năng mới khi phát triển
```
