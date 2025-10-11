# Đề tài: Nhận diện vi phạm đi sai làn (ô tô / xe máy)
**Nhóm:** Nhóm 8

## Thành viên (Họ và tên – MSSV)
- Bùi Thanh Lịch (NT) – 052205001776
- Phan Ngọc Hiếu – 089205008371
- Nguyễn Hồ Quang Khải – 040205000310
- Phạm Quốc Chánh – 089205003605

## Mô tả
Hệ thống phát hiện ô tô/xe máy **đi sai làn** từ video giám sát bằng mô hình phát hiện đối tượng (YOLO) và theo dõi ID; khi phát hiện vi phạm sẽ ghi log và lưu ảnh bằng chứng.

## Cài đặt nhanh
pip install opencv-python numpy ultralytics deep-sort-realtime

## Cách chạy
1) Vẽ đa giác làn:  
python lane_selector.py

2) Phát hiện & ghi vi phạm:  
python violation_detector.py --video duong_pho4.mp4

## Cấu trúc tối thiểu
lanes/  
violated_vehicles/  
lane_selector.py  
violation_detector.py  
duong_pho4.mp4   # (tùy chọn: video ví dụ)  
README.md
