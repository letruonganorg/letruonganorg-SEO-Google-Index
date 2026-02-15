# Google Indexing Automation Tool

## Giới thiệu

Google Indexing Automation Tool là công cụ Python giúp tự động gửi URL lên Google thông qua Google Indexing API.

Công cụ giúp:
- Tăng tốc độ index bài viết mới
- Thông báo cập nhật nội dung
- Tối ưu quy trình SEO Technical
- Giảm thao tác thủ công cho SEOer

Phù hợp cho:
- SEO Agency
- Website tin tức
- Website thương mại điện tử
- Website có số lượng bài viết lớn

---

## Yêu cầu hệ thống

- Python 3.8+
- Google Cloud Service Account
- Đã bật Google Indexing API trong Google Cloud Console
- Website đã xác minh trong Google Search Console

---

## Cài đặt thư viện

Chạy lệnh sau để cài đặt các thư viện cần thiết:

```bash
pip install oauth2client httplib2 pandas
Cấu trúc thư mục dự án
/project-folder
│
├── apidetails.json     # File chứa Service Account Key
├── indexing.py         # Script gửi URL lên Google
├── data.csv            # Danh sách URL cần submit
└── README.md           # Hướng dẫn sử dụng
Cấu hình API
Truy cập Google Cloud Console

Tạo Service Account

Bật Google Indexing API

Tải file JSON Key

Thay nội dung private_key và private_key_id trong file apidetails.json

Lưu ý: Không chia sẻ file JSON Key công khai để tránh lộ bảo mật.

Chuẩn bị dữ liệu
File data.csv cần có cấu trúc:

URL	date
Chỉ cần cột URL để gửi lên Google.

Ví dụ:

https://example.com/bai-viet-1
https://example.com/bai-viet-2
Cách sử dụng
Chạy lệnh:

python indexing.py
Sau khi chạy, hệ thống sẽ:

Gửi từng URL lên Google Indexing API

Hiển thị trạng thái thành công hoặc lỗi

Trả về thông tin metadata nếu submit thành công

Lưu ý quan trọng
Service Account phải được thêm quyền Owner trong Google Search Console

Google Indexing API chỉ hỗ trợ một số loại nội dung (JobPosting, BroadcastEvent)

Không lạm dụng API để tránh bị giới hạn quota

Ứng dụng trong SEO
Công cụ giúp:

Index nhanh bài viết mới

Cập nhật nội dung khi chỉnh sửa

Tối ưu quy trình SEO Automation

Hỗ trợ chiến lược SEO Technical

Nếu bạn cần triển khai SEO bài bản, tối ưu hệ thống, Entity SEO và chiến lược tăng trưởng traffic dài hạn, tham khảo thêm tại:

Dịch vụ SEO
