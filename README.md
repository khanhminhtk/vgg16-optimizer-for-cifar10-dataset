# vgg16-optimizer-for-cifar10-dataset
Áp dụng kiến thức về các thuật toán tối ưu hóa để cải thiện hiệu suất của mô hình CNN trên bộ dữ liệu CIFAR10, nổi tiếng với độ khó cao.
Tăng độ chính xác trên tập validation từ 75% lên 92% bằng cách tự xây dựng mô hình VGG16. Sử dụng kỹ thuật tăng độ chính xác và giảm overfitting như skip connection, batchnormal, dropout, tăng cường dữ liệu (data augmentation), hàm phạt (regularization), và áp dụng Adam optimizer cùng với lịch trình học (learning rate schedule)
# Kết quả thu được:

Train với mô hình CNN cơ bản:

![image](https://github.com/user-attachments/assets/e56fae64-f9e0-4df6-91d7-ae9648ad985c)
![image](https://github.com/user-attachments/assets/52c77494-d9bc-4d90-8734-c4ecf01f84ae)

Train với mô hình VGG16:

![image](https://github.com/user-attachments/assets/fbf25e33-4804-45a9-ad04-813223134231)
![image](https://github.com/user-attachments/assets/2d33b517-77a0-493a-bde8-9f193e10d458)
