# 🧍‍♂️ Fall Detection using CNN & YOLO

## 📖 Giới thiệu
Đây là dự án phát hiện ngã (Fall Detection) được xây dựng trong quá trình học tập và nghiên cứu về **Deep Learning**.  
Hệ thống kết hợp **YOLO (You Only Look Once)** để phát hiện người trong khung hình, và **CNN (Convolutional Neural Network)** để phân loại trạng thái **Ngã / Không Ngã**.  
Ngoài ra, dự án áp dụng **Smooth Prediction** (làm mượt dự đoán theo chuỗi frame) để giảm nhiễu, tránh tình trạng kết quả bị dao động liên tục giữa các frame liền kề.  

## 🚀 Tính năng chính
- **Phát hiện người** trong ảnh hoặc video theo thời gian thực bằng YOLO.  
- **Phân loại hành động** của người được phát hiện (Ngã hoặc Không Ngã) bằng CNN.  
- **Huấn luyện mô hình CNN** từ đầu với PyTorch.  
- **Smooth Prediction**: áp dụng kỹ thuật làm mượt dự đoán theo thời gian (sliding window / majority voting) để tăng độ ổn định của hệ thống.  
- **Đánh giá hiệu năng**: trực quan hóa loss, accuracy, confusion matrix.  
- **Inference trực tiếp**: chạy thử trên video/ảnh/real-time, kết quả hiển thị bounding box và nhãn **Fall / No Fall** ổn định hơn nhờ smoothing.

## 📌 Ghi chú

Dự án được thực hiện trong quá trình học tập, vì vậy khó tránh khỏi những sai sót và nhầm lẫn.  
Mình rất mong nhận được sự góp ý, phản hồi từ các bạn để hoàn thiện hơn.  

📧 Liên hệ: ..........

