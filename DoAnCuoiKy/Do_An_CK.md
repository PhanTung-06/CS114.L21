<a href="https://colab.research.google.com/github/PhanTung-06/CS114.L21/blob/main/DoAnCuoiKy/Do_An_CK.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

<h1 align="center"><b>CS114.L21 - MÁY HỌC</b></h1>
<h1 align="center"><b>ĐỒ ÁN CUỐI KÌ</b></h1>
<h1 align="center"><b>Đề tài: NHẬN DẠNG BIỂN BÁO GIAO THÔNG ĐƯỜNG BỘ (TRAFFIC SIGNS DETECTION)</b></h1>

**Giảng viên:** 
- Lê Đình Duy
- Phạm Nguyễn Trường An

**Thành viên:**
- Phan Tung - 19522495
- Huỳnh Thị Mỹ Duyên - 19521438
- Hoàng Tiến Dũng - 19521388

## **1. Mô tả bài toán**  
- Trong sự phát triển không ngừng của nhân loại, thì xe tự hành (automatic car) là một trong những phát minh rất tuyệt vời. Và nó tập trung nghiên cứu vào 2 lĩnh vực chính: phát hiện làn đường và nhận dạng đối tượng.
  
- Và nhóm chúng em lựa chọn nhận dạng biển báo giao thông (traffic signs detection) làm đề tài cho đồ án cuối kỳ. Từ đây, có thể nghiên cứu, phát triển và ứng dụng vào hệ thống của xe tự hành.

**Input:** Video chứa objects (biển báo giao thông) được quay từ góc nhìn của xe hơi.

**Output:** Video chứa bounding boxes và nhãn cho từng bounding box đó.

## **2. Mô tả bộ dữ liệu**  
2.1. Thu thập dữ liệu:
- Thu thập từ internet, video từ camera hành trình với các điều kiện khác nhau: trời mưa, trời nắng, ban đêm,...
- Bộ dữ liệu đang được thu thập với **8 classes** cụ thể là: No entry, No parking / waiting, No turning, Max Speed, Other prohibition signs, Warning, Mandatory, Indication. 

2.2. Số lượng, độ đa dạng:
 - Updating...

2.3. Các thao tác tiền xử lý dữ liệu:
- Cắt video thành các frame ảnh, loại bỏ các ảnh bị mờ, che khuất hoặc không chứa object.
- Gán nhãn dữ liệu.
- Updating...

2.4. phân chia (split) - train/dev/test:
- Updating...




2.5. Các class:

- No entry

![No entry](https://github.com/PhanTung-06/CS114.L21/tree/main/DoAnCuoiKy/classes/class1.png?raw=true)

- No parking / waiting

![No parking / waiting](https://github.com/PhanTung-06/CS114.L21/tree/main/DoAnCuoiKy/classes/class2.png?raw=true)

- No turning

![No turning](https://github.com/PhanTung-06/CS114.L21/tree/main/DoAnCuoiKy/classes/class3.png?raw=true)

- Max Speed

![Max Speed](https://github.com/PhanTung-06/CS114.L21/tree/main/DoAnCuoiKy/classes/class4.png?raw=true)

- Other prohibition signs

![Other prohibition signs](https://github.com/PhanTung-06/CS114.L21/tree/main/DoAnCuoiKy/classes/class5.png?raw=true)

- Warning

![Warning](https://github.com/PhanTung-06/CS114.L21/tree/main/DoAnCuoiKy/classes/class6_1.png?raw=true)
![Warning](https://github.com/PhanTung-06/CS114.L21/tree/main/DoAnCuoiKy/classes/class6_2.png?raw=true)

- Mandatory

![Mandatory](https://github.com/PhanTung-06/CS114.L21/tree/main/DoAnCuoiKy/classes/class7.png?raw=true)

- Indication

![Indication](https://github.com/PhanTung-06/CS114.L21/tree/main/DoAnCuoiKy/classes/class8.png?raw=true)

## **3. Mô tả về đặc trưng**
- Updating...
