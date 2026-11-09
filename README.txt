RADAR XANH PLEIKU - BẢN NÂNG CẤP

CÀI TRÊN HONOR 400 / ANDROID
1. Giải nén ZIP trên máy tính.
2. Đưa các tệp bên trong thư mục radar_xanh_pleiku lên một hosting HTTPS (có thể dùng GitHub Pages).
3. Mở đường dẫn HTTPS bằng Chrome trên điện thoại.
4. Cấp quyền vị trí khi được hỏi, nhấn Định vị tôi rồi Quét địa điểm.
5. Menu Chrome ⋮ > Cài đặt ứng dụng / Add to Home screen.

CÁCH DÙNG
- Chọn bán kính 2 km (mặc định), nhấn Định vị tôi, sau đó Quét địa điểm.
- Bản đồ hiển thị các POI công khai lấy từ OpenStreetMap/Overpass.
- Lưới nhiệt chia ô 250 m. Chỉ số khảo sát được tính tương đối trong lần quét từ trọng số loại địa điểm và nhật ký cuốc đã ghi có tọa độ.
- Trong danh sách vùng tiềm năng, nhấn Chọn để xem vùng trên bản đồ hoặc Đi để mở chỉ đường.
- Khi ghi nhật ký cuốc, hãy định vị trước để lưu tọa độ. Có thể xuất CSV để sao lưu.

CÁCH HIỂU ĐIỂM SỐ
- Khi chưa có nhật ký có tọa độ: điểm số phản ánh mật độ và loại POI công khai trong các ô lưới, được chuẩn hóa tương đối theo lần quét.
- Khi đã có nhật ký: điểm kết hợp 65% tín hiệu POI và 35% kết quả cuốc/thời gian chờ đã ghi. Đây là chỉ số khảo sát thử nghiệm, không phải xác suất có khách.
- Dữ liệu địa điểm không phải dữ liệu đơn hàng trực tiếp. Ứng dụng không truy cập hệ thống Xanh SM, không biết khách đang đặt xe hoặc vị trí tài xế khác.

NGUỒN VÀ QUYỀN RIÊNG TƯ
- Bản đồ nền và địa điểm: OpenStreetMap, Overpass API.
- Vị trí: GPS của trình duyệt, chỉ lấy khi người dùng cấp quyền.
- Nhật ký: lưu trên thiết bị bằng localStorage, không tự gửi lên máy chủ. Xuất CSV định kỳ vì xóa dữ liệu trình duyệt có thể làm mất nhật ký.
- Dữ liệu bản đồ cần internet. PWA không đảm bảo GPS liên tục khi khóa màn hình.

LƯU Ý AN TOÀN
Chỉ xem bản đồ và chọn điểm khi đã dừng xe ở nơi an toàn. Không thao tác điện thoại khi đang lái xe. Radar là công cụ khảo sát, không đảm bảo có đơn ở điểm được xếp hạng cao.

DỰ ÁN ĐỘC LẬP, KHÔNG LIÊN KẾT HOẶC ĐƯỢC XANH SM BẢO TRỢ.
