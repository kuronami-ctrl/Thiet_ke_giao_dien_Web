# **1. Mổ xẻ đề bài**

Trước tiên, hãy hiểu tình huống:

Bạn đang sử dụng ShopeeFood để đặt đồ ăn. Sau khi đặt hàng, bạn mở màn hình theo dõi đơn hàng.

Đơn hàng có 4 trạng thái:

1.  Chờ quán xác nhận.
    
2.  Quán đang chuẩn bị món.
    
3.  Tài xế đang đến quán.
    
4.  Đang giao hàng.
    

Hiện tại, đơn hàng của khách đang ở trạng thái số 2, tức là quán đã nhận đơn và đang chuẩn bị đồ ăn.

**Vấn đề:** Nhóm thiết kế cũ đã làm giao diện không hợp lý, gây khó hiểu và có thể khiến khách hàng thao tác nhầm.
# **2 . Hướng dẫn làm Bước 1: Liệt kê 4 lỗi thiết kế**

Đây là phần phân tích lỗi của giao diện cũ.

Bạn có thể trình bày đúng 4 lỗi như sau:

**Lỗi 1: Sử dụng màu sắc không phù hợp**

-   Vị trí: Toàn bộ giao diện.
    
-   Biểu hiện: Sử dụng màu cam đậm và chữ trắng.
    
-   Vi phạm: Quy chuẩn Wireframe Low-Fidelity.
    
-   Cách sửa: Chỉ sử dụng đen, trắng và xám.
    

**Lỗi 2: Thanh tiêu đề thiếu chức năng cần thiết**

-   Vị trí: Phần đầu màn hình.
    
-   Biểu hiện: Tiêu đề ghi tiếng Anh `Order Tracking`, không có nút Quay lại.
    
-   Vi phạm: Heuristic #3 – Quyền kiểm soát của người dùng.
    
-   Cách sửa: Đổi thành `Theo dõi đơn hàng` và thêm nút `← Quay lại`.
    

**Lỗi 3: Tiến trình đơn hàng không rõ ràng**

-   Vị trí: Khu vực hiển thị trạng thái đơn hàng.
    
-   Biểu hiện: Chỉ có dòng chữ `Processing...`, không hiển thị 4 chặng.
    
-   Vi phạm: Heuristic #1 – Hiển thị trạng thái hệ thống.
    
-   Cách sửa: Thiết kế thanh tiến trình 4 chặng, đánh dấu chặng hiện tại và thời gian còn lại.
    

**Lỗi 4: Khu vực tài xế và nút hủy đơn chưa hợp lý**

-   Vị trí: Khối thông tin tài xế và khu vực cuối màn hình.
    
-   Biểu hiện: Tên tài xế là `Lorem Ipsum`, nút Gọi điện/Nhắn tin chỉ có kích thước 32 × 32 dp. Nút Hủy đơn luôn bấm được và đặt sát nút hỗ trợ.
    
-   Vi phạm: Heuristic #5 – Phòng ngừa lỗi và quy chuẩn vùng chạm tối thiểu.
    
-   Cách sửa: Thay tên giả bằng nội dung thực tế hoặc thông tin mẫu tiếng Việt; tăng kích thước nút lên ít nhất 48 × 48 dp; khóa nút Hủy đơn và tách biệt nút Liên hệ hỗ trợ.
# **4. Hướng dẫn làm Bước 2: Dựng Wireframe trên FigJam**
link Figjam: https://www.figma.com/board/w3murv7UpFyyfg0U5u8e6D/Untitled?node-id=0-1&t=GE2UTdTzqt1kMHVf-1
