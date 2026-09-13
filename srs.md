# 1. Stakeholders

| Stakeholder                         | Vai trò                                                                                                                                                                          |
| ----------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Ban lãnh đạo Công ty ABC**        | Định hướng mục tiêu kinh doanh, đưa ra kỳ vọng đối với hệ thống và theo dõi các chỉ số hoạt động như số lượng chuyến, doanh thu, tỷ lệ hoàn thành, tỷ lệ hủy và hiệu quả tài xế. |
| **Khách hàng**                      | Đăng ký tài khoản, đặt xe, theo dõi chuyến đi, xem lịch sử, thanh toán và đánh giá tài xế.                                                                                       |
| **Tài xế**                          | Đăng ký hoặc được vận hành tạo tài khoản, quản lý hồ sơ và phương tiện, nhận/từ chối chuyến, cập nhật trạng thái chuyến và vị trí.                                               |
| **Nhân viên vận hành**              | Quản lý khách hàng, tài xế, phương tiện, chuyến đi; theo dõi chuyến đang diễn ra; xử lý các chuyến bị lỗi và tra cứu lịch sử giao dịch.                                          |
| **Nhà cung cấp dịch vụ thanh toán** | Xử lý thanh toán điện tử cho hệ thống; CAB System không lưu trực tiếp thông tin nhạy cảm của thẻ hoặc tài khoản thanh toán.                                                      |
| **Nhà cung cấp dịch vụ thông báo**  | Cung cấp các kênh gửi thông báo đến khách hàng và tài xế, đồng thời hỗ trợ mở rộng thêm kênh thông báo trong tương lai.                                                          |


# 2. Stakeholder Matrix

| Stakeholder                         | Mức độ quan tâm | Mức độ ảnh hưởng | Chiến lược quản lý                                             |
| ----------------------------------- | --------------- | ---------------- | -------------------------------------------------------------- |
| **Ban lãnh đạo Công ty ABC**        | Cao             | Cao              | Quản lý chặt chẽ, báo cáo định kỳ về hiệu quả hệ thống         |
| **Khách hàng**                      | Cao             | Cao              | Thu thập phản hồi và đảm bảo trải nghiệm sử dụng               |
| **Tài xế**                          | Cao             | Cao              | Hỗ trợ thường xuyên và đảm bảo quy trình nhận chuyến hiệu quả  |
| **Nhân viên vận hành**              | Cao             | Cao              | Phối hợp chặt chẽ và cung cấp đầy đủ công cụ quản lý           |
| **Nhà cung cấp dịch vụ thanh toán** | Trung bình      | Cao              | Theo dõi tích hợp và xử lý kịp thời các sự cố thanh toán       |
| **Nhà cung cấp dịch vụ thông báo**  | Trung bình      | Trung bình       | Theo dõi chất lượng dịch vụ và khả năng mở rộng kênh thông báo |


# 3. Business Goals (Mục tiêu Kinh doanh)

| ID       | Business Goal                                   | Mô tả                                                                        |
| -------- | ----------------------------------------------- | ---------------------------------------------------------------------------- |
| **BG01** | Xây dựng nền tảng đặt xe trực tuyến             | Cung cấp nền tảng giúp khách hàng đặt xe và theo dõi chuyến đi thuận tiện.   |
| **BG02** | Tự động hóa việc tìm và phân công tài xế        | Tự động tìm tài xế phù hợp dựa trên vị trí, trạng thái và tiêu chí vận hành. |
| **BG03** | Nâng cao trải nghiệm khách hàng                 | Cung cấp quy trình đặt xe, theo dõi, thanh toán và đánh giá thuận tiện.      |
| **BG04** | Nâng cao hiệu quả quản lý vận hành              | Tập trung quản lý khách hàng, tài xế, phương tiện và các chuyến đi.          |
| **BG05** | Quản lý thanh toán và doanh thu                 | Hỗ trợ tính cước, thanh toán và theo dõi lịch sử giao dịch.                  |
| **BG06** | Đảm bảo hệ thống ổn định và có khả năng mở rộng | Đảm bảo hệ thống hoạt động ổn định khi tải tăng và dễ dàng mở rộng.          |
| **BG07** | Đảm bảo an toàn và bảo mật dữ liệu              | Bảo vệ thông tin cá nhân, vị trí, giao dịch và kiểm soát quyền tr            |

# 4. Minimum Viable Product (MVP) Modules

| Module                             | Mô tả                                  | Chức năng chính                                         |
| ---------------------------------- | -------------------------------------- | ------------------------------------------------------- |
| **User & Driver Management**       | Quản lý thông tin khách hàng và tài xế | Đăng ký, đăng nhập, cập nhật hồ sơ, quản lý trạng thái  |
| **Booking Management**             | Quản lý yêu cầu đặt xe                 | Tạo, tiếp nhận và theo dõi yêu cầu đặt xe               |
| **Driver Matching & Dispatch**     | Tìm và phân công tài xế                | Tìm tài xế phù hợp, gửi yêu cầu và xử lý phản hồi       |
| **Trip Management**                | Quản lý quá trình thực hiện chuyến     | Cập nhật trạng thái, vị trí và kết thúc chuyến          |
| **Fare & Payment**                 | Tính cước và thanh toán                | Tính tiền, thanh toán tiền mặt hoặc điện tử             |
| **Notification**                   | Gửi thông báo                          | Thông báo đặt xe, nhận chuyến, trạng thái và thanh toán |
| **History & Rating**               | Quản lý lịch sử và đánh giá            | Xem lịch sử chuyến, số tiền và đánh giá tài xế          |
| **Operation Management**           | Quản lý hoạt động vận hành             | Quản lý khách hàng, tài xế, phương tiện và chuyến đi    |
| **Reporting**                      | Báo cáo hoạt động                      | Thống kê chuyến đi, doanh thu và hiệu quả tài xế        |
| **Authentication & Authorization** | Xác thực và phân quyền                 | Kiểm soát đăng nhập và quyền truy cập chức năng         |
