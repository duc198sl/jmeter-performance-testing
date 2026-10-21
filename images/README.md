# Hướng dẫn chụp ảnh minh họa kết quả kiểm thử JMeter

Để báo cáo `README.md` tự động hiển thị đầy đủ hình ảnh, bạn mở file kịch bản `test-plans/dummyjson_performance_test.jmx` trên ứng dụng Apache JMeter, chạy thử và lưu 4 ảnh chụp màn hình vào thư mục `images/` này với đúng tên file tương ứng:

| Tên file ảnh | Thành phần JMeter cần chụp | Hướng dẫn thao tác |
| :--- | :--- | :--- |
| `01_jmeter_test_plan_overview.png` | Cấu hình **Thread Group** | Trong cây thư mục bên trái của JMeter, click vào mục **`Thread Group - 10 Users Simulation`** -> Chụp màn hình khung cấu hình bên phải thấy rõ các thông số: Number of Threads = 10, Ramp-up period = 5, Loop Count = 5. |
| `02_view_results_tree.png` | Listener **View Results Tree** | Bấm nút chạy màu xanh lá (**Start** ▶️) trên thanh công cụ -> Click vào mục **`View Results Tree`** ở cây bên trái -> Chụp lại màn hình thấy danh sách các request đã thực thi kèm icon màu xanh lá (thành công). |
| `03_summary_report.png` | Listener **Summary Report** | Click vào mục **`Summary Report`** ở cây bên trái -> Chụp lại bảng số liệu tổng kết: Samples, Average, Min, Max, Error %, Throughput. |
| `04_aggregate_report.png` | Listener **Aggregate Report** | Click vào mục **`Aggregate Report`** ở cây bên trái -> Chụp lại bảng số liệu phân tích chuyên sâu: Median, 90% Line, 95% Line, 99% Line, Throughput. |

*(Mẹo: Trên Windows, bạn chỉ cần nhấn phím tắt `Windows + Shift + S` để quét chọn vùng màn hình rồi lưu ảnh dạng PNG vào thư mục `images/`).*
