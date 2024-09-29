# LẬP TRÌNH PHÂN TÍCH DỮ LIỆU

Chào mừng bạn đến với project phân tích dữ liệu của tôi! Dự án này được thực hiện trong khuôn khổ môn học "Lập trình Phân tích Dữ liệu" và nhằm mục đích áp dụng các kiến thức đã học vào thực tế. 

## Mục tiêu dự án

Trong project này, tôi sẽ phân tích dữ liệu liên quan đến tỷ lệ tử vong sớm tại các Quận ở Hoa Kỳ. Cụ thể, dự án bao gồm:

1. **Phân tích và trực quan hóa dữ liệu**: Trình bày bảng số liệu và tạo các biểu đồ trực quan về tỷ lệ số năm mất sớm (YPLL Rate) theo từng Quận bằng cách sử dụng thư viện pandas và matplotlib.
  
2. **Xây dựng mô hình dự đoán**: Từ bộ dữ liệu `additional-measures.csv`, tôi sẽ sử dụng các chỉ số khác để dự đoán tỷ lệ tử vong sớm (YPLL Rate). Đây là bước quan trọng trong việc hiểu rõ mối quan hệ giữa các chỉ số y tế và tỷ lệ tử vong.

## Bài 1:

Sử dụng bộ dữ liệu `ypll.csv` chứa tỷ lệ số năm mất sớm trong 100000 người ở mỗi Quận tại Hoa Kỳ với các thuộc tính:

- FIPS: mã quận
- State: bang
- County: quận
- Unreliable: đánh dấu dòng dữ liệu có thể bị thu nhập sai
- YPLL Rate: tỷ lệ tử vong sớm trên 100000

Bộ dữ liệu YPLL được sử dụng để đo tỷ lệ tử vong sớm (trước 75 tuổi). Mỗi dòng dữ liệu được đo trong 100000 người (một trăm nghìn người) và tính tổng số năm họ mất sớm hơn trước 75 tuổi. Ví dụ, một người mất năm 73 tuổi thì xem như họ mất sớm 2 năm. Nếu họ mất năm 77 tuổi thì số năm mất sớm là 0 năm.

## Bài 2: 

Sử dụng bộ dữ liệu `additional-measures.csv`

Bộ dữ liệu này chứa tất cả các chỉ số khác ở mỗi Quận. Nhiệm vụ của bạn là xây dựng một mô hình dự đoán tỷ lệ tử vong sớm YPLL Rate dựa vào các chỉ số khác.

## Đặc điểm nổi bật

- **Sử dụng pandas** để xử lý, phân tích dữ liệu nhanh chóng và dễ hiểu.
- **Trực quan dữ liệu với matplotlib**: Tạo ra các biểu đồ sống động và trực quan, giúp dễ dàng phân tích và rút ra kết luận.
- **Dự đoán bằng mô hình học máy**: Xây dựng mô hình dự đoán tỷ lệ tử vong dựa trên các biến độc lập từ bộ dữ liệu khác.

## Giá trị mang lại

Dự án không chỉ là một bài tập phân tích dữ liệu thông thường, mà nó còn mở ra một góc nhìn sâu sắc về sức khỏe cộng đồng, giúp hiểu rõ hơn về sự chênh lệch trong tử vong sớm giữa các Quận tại Hoa Kỳ. Với mô hình dự đoán, tôi kỳ vọng có thể tạo ra một công cụ hữu ích để dự đoán tỷ lệ tử vong dựa trên các yếu tố sức khỏe quan trọng.

Xin mời các bạn xem và tham khảo source code của tôi. Hy vọng rằng những gì bạn học được từ dự án này sẽ giúp ích cho bạn trong những dự án phân tích dữ liệu khác, nó sẽ mang lại cho bạn những ý tưởng hữu ích, cũng như trong sự nghiệp phát triển kỹ năng lập trình của mình.
