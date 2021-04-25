[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Xdx2wuToDbgC1pdcDJt6mnvPtJEm-NHa)
# BÀI TẬP COLAB 01

## Kết Luận

1. Kết quả chạy thực tế với webcam của laptop và giấy viết tay của các bạn có tốt không?
    - Kết quả đạt được chưa được như mong đợi
2. Ủa mà nhìn vào đâu để kết luận là tốt hay không?
    - Do qua nhiều lần thử thì số lần predict đúng khá là ít. Kết quả bên trên là 1 trong những lần hiếm hoi nhóm chúng em predict đúng như thực tế 
3. Nếu không tốt thì lý do tại sao?
    - Theo em nghĩ là do chất lượng, độ phân giải của bức ảnh được chụp từ webcam laptop chưa thực sự tốt.
    - Bức ảnh được chụp từ webcam có giá trị các phần tử trong ma trận ảnh thuộc đoạn 0 đến 255 nên sau khi đưa về đoạn 0 đến 15 giống với dữ liệu training thì một phần thông tin sẽ bị mất mát.
    - Model overfit với tập dataset mà thư viện scikit-learn cung cấp nên khi đưa input 1 ảnh được chụp từ webcam thì khó có thể có 1 ảnh giống với dataset trên nên dẫn đến predict sai.
4. Nếu tốt thì tiếp theo có thể dùng model digits recognition này vào các bài toán phức tạp hơn như nhận dạng biển số nhà không?
    - Không.
    - Vì các bài toán phức tạp hơn trong thực tế đòi hỏi độ chính xác cao, việc áp dụng model digits recognition cần lượng data lớn để đạt được kết quả tốt với nhiều input phức tạp. 
    - Thứ 2 là do dataset trên chưa đủ độ phong phú để có thể đào tạo ra 1 model tốt được. Vì trong thực tế, khi áp dụng vào thì ảnh có thể được chụp trong các môi trường khác nhau và góc chụp khác nhau, ảnh input có thể nghiêng lệch,.. nên model được đào tạo trên chưa đáp ứng được các bài toán thực tế
    - Hiện nay có nhiều phương pháp tốt hơn là sử dụng model digits recognition giúp giảm thiểu chi phí và đạt được kết quả tốt hơn.
    - Ngoài ra thì deep learning đang ngày càng phát triển và có thể hỗ trợ rất nhiều đồng thời có độ chính xác cao,...điển hình như các mô hình của mạng CNN ,LSTM hay transformer, Bert,...những mô hình trên còn trích xuất được nội dung 1 cách khách quan nên việc áp dụng model trên vào thực tế là thiếu thuyết phục.


