# Kiểm Tra Checksum SHA256

Ứng dụng **Kiểm Tra Checksum SHA256** giúp người dùng tính toán và so sánh checksum SHA256 của các tệp tin. Nó cung cấp một giao diện đơn giản để tải lên tệp, tính toán checksum SHA256, và so sánh với một giá trị checksum được nhập vào để kiểm tra tính chính xác.

Checksum SHA256 là một giá trị mã hóa duy nhất được tính từ nội dung của tệp tin. Nó hoạt động như một dấu vết số học, giúp xác minh tính toàn vẹn của tệp. Nếu một tệp tin bị chỉnh sửa hoặc bị tấn công, checksum của nó sẽ thay đổi, cho phép bạn nhận diện ngay lập tức.

## Tính Năng

-   **Tính Toán Checksum SHA256**: Tải lên tệp và ứng dụng sẽ tính toán checksum SHA256 của tệp đó. Tính toán được thực hiện theo từng khối 1MB để đảm bảo xử lý hiệu quả cho các tệp lớn.
-   **So Sánh Checksum**: Nhập một giá trị checksum và so sánh nó với checksum được tính toán từ tệp. Kết quả so sánh sẽ được hiển thị rõ ràng.
-   **Thanh Tiến Trình**: Hiển thị thanh tiến trình để theo dõi tiến độ tính toán checksum.
-   **Giao Diện Người Dùng Thân Thiện**: Thiết kế đơn giản và dễ sử dụng với các thông báo rõ ràng.

## Hướng Dẫn Sử Dụng

1. **Chọn Tệp**:

    - Nhấp vào nút "Chọn tệp" để chọn tệp bạn muốn kiểm tra.

2. **Tính Toán Checksum**:

    - Nhấp vào nút "Tính Toán" để bắt đầu quá trình tính toán checksum SHA256. Thanh tiến trình sẽ hiển thị tiến độ tính toán.

3. **So Sánh Checksum**:
    - Sau khi tính toán xong, nhập giá trị checksum vào ô "Nhập checksum để so sánh" và nhấp vào nút "So Sánh".
    - Kết quả so sánh sẽ được hiển thị ngay bên dưới.

## Yêu Cầu

-   **Trình duyệt Web**: Ứng dụng hoạt động trên các trình duyệt hiện đại như Chrome, Firefox, Edge, và Safari.

## Công Nghệ

-   **HTML/CSS**: Cung cấp giao diện người dùng.
-   **JavaScript**: Xử lý logic tính toán checksum và tương tác người dùng.
-   **CryptoJS**: Thư viện JavaScript để tính toán checksum SHA256.
