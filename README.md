# Smart Travel Planner (Hệ thống AI Lập kế hoạch du lịch)

[cite_start]**Tên môn học:** Introduction to AI (Nhập môn Trí tuệ Nhân tạo) [cite: 109]
[cite_start]**Mã môn học:** [Điền mã môn] [cite: 109]
[cite_start]**Học kỳ:** II - Năm học 2025 – 2026 [cite: 109]
**Giảng viên hướng dẫn:** TS. [cite_start]Trương Vĩnh Lân [cite: 110]

## [cite_start]👥 Thông tin thành viên nhóm [cite: 111]
| STT | Họ và Tên | MSSV | Email |
|---|---|---|---|
| 1 | [Vạn Trường Thành] | [2353107] | [thanh.van081205@hcmut.edu.vn] |
| 2 | [Tên thành viên 2] | [Mã số] | [Email SV] |
| 3 | [Tên thành viên 3] | [Mã số] | [Email SV] |

## [cite_start]🎯 Mục tiêu bài tập lớn [cite: 112]
Xây dựng một hệ thống AI tích hợp nhằm tự động thiết kế lịch trình tham quan. Hệ thống tiếp nhận sở thích, ngân sách và thời gian của người dùng, sau đó ứng dụng các trụ cột của AI để đưa ra quyết định:
* **Mạng Bayes (Bayesian Network):** Đánh giá các yếu tố rủi ro (thời tiết, trễ tàu).
* **Học máy (Machine Learning):** Phân loại và gợi ý địa điểm phù hợp (Decision Tree/Naive Bayes).
* **Suy luận Tri thức (Knowledge Representation):** Áp dụng luật IF-THEN để lọc địa điểm theo ngữ cảnh thực tế.
* **Tìm kiếm (Search) & CSP:** Sử dụng thuật toán A* và bài toán thỏa mãn ràng buộc (thời gian, chi phí) để tìm ra lộ trình di chuyển tối ưu nhất trên bản đồ.

## 📂 Cấu trúc thư mục [cite: 114]
* `/notebooks`: Chứa file Google Colab Notebook chính để chạy toàn bộ luồng hệ thống.
* `/modules`: Các mã nguồn Python hỗ trợ tự viết (được import vào Colab).
* `/reports`: Báo cáo phân tích thực nghiệm và đánh giá kết quả (PDF).
* `/features`: Chứa các file vector đặc trưng đã trích xuất (.npy, .h5).

## [cite_start]🚀 Hướng dẫn chạy (How to Run) [cite: 113]
1. Mở file Notebook chính tại thư mục `/notebooks` bằng Google Colab.
2. Môi trường sẽ tự động chạy các lệnh `pip install` để tải thư viện (như `folium`, `scikit-learn`) và dùng lệnh `wget` để tải tập dữ liệu du lịch Nhật Bản trực tiếp vào máy chủ Colab.
3. Chọn chức năng **Runtime -> Run all** để hệ thống tự động thực thi toàn bộ pipeline từ xử lý dữ liệu đến in ra lộ trình cuối cùng.

## [cite_start]🔗 Liên kết dự án [cite: 115]
* [Báo cáo PDF (Bản Final)](#)
* [Google Colab Notebook](#)
