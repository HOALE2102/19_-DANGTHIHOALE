# Câu a:
# Vòng đời Phát triển Phần mềm (SDLC) Truyền thống (Mô hình Thác nước)

SDLC truyền thống bao gồm 6 giai đoạn chính được thực hiện theo trình tự. Dưới đây là mục tiêu cơ bản của từng giai đoạn:

---

## 1. Phân tích Yêu cầu (Requirements Analysis) 📝
* **Mục tiêu:** Xác định chính xác **CÁI GÌ** cần xây dựng. Thu thập, phân tích và ghi lại toàn bộ nhu cầu của khách hàng.
* **Sản phẩm chính:** Tài liệu Đặc tả Yêu cầu Phần mềm (SRS - Software Requirements Specification).

---

## 2. Thiết kế (Design) 
* **Mục tiêu:** Xác định **LÀM NHƯ THẾ NÀO**. Tạo ra kiến trúc, cấu trúc tổng thể và chi tiết cho phần mềm.
* **Sản phẩm chính:** Tài liệu Thiết kế Phần mềm (SDD - Software Design Document).

---

## 3. Triển khai/Lập trình (Implementation) 💻
* **Mục tiêu:** Chuyển đổi thiết kế thành **MÃ NGUỒN** thực tế và tiến hành kiểm thử đơn vị.
* **Sản phẩm chính:** Mã nguồn hoạt động.

---

## 4. Kiểm thử (Testing) 🧪
* **Mục tiêu:** **Xác minh** rằng phần mềm hoạt động đúng theo yêu cầu và không có lỗi (bug).
* **Hoạt động chính:** Kiểm thử tích hợp, hệ thống và kiểm thử chấp nhận (UAT).

---

## 5. Triển khai (Deployment) 
* **Mục tiêu:** Cài đặt phần mềm đã hoàn thành vào môi trường **sử dụng thực tế** (Production).
* **Kết quả:** Hệ thống chính thức đi vào hoạt động.

---

## 6. Bảo trì (Maintenance) 
* **Mục tiêu:** **Duy trì, sửa lỗi** phát sinh, và thực hiện các cải tiến/thích nghi cần thiết sau khi bàn giao.
* **Hoạt động chính:** Phát hành các bản vá lỗi và cập nhật.

# Câu b:
# Bài Kiểm tra Ngắn: Sprint Planning cho User Story

**User Story:** "Là một người dùng, tôi muốn tạo một ghi chú mới."

Dưới đây là các hoạt động chính diễn ra trong buổi **Sprint Planning** để lên kế hoạch triển khai User Story này:

## I. Xác định Phạm vi và Mục tiêu (The "What")

1.  **Trình bày và Thảo luận:**
    * **Mục tiêu:** Chủ sở hữu Sản phẩm (PO) trình bày giá trị nghiệp vụ của Story.
    * **Hoạt động:** Nhóm Phát triển (Development Team) thảo luận để thống nhất về tính năng cần xây dựng.

2.  **Định nghĩa Tiêu chí Chấp nhận (Acceptance Criteria - A/C):**
    * **Mục tiêu:** Xác định rõ các điều kiện cụ thể để Story được coi là **Hoàn thành (Done)**.
    * **Ví dụ A/C:** Ghi chú phải có Tiêu đề; Dữ liệu phải lưu thành công vào Database.

## II. Phá vỡ và Ước tính Công việc (The "How")

3.  **Phá vỡ thành Nhiệm vụ (Task Breakdown):**
    * **Mục tiêu:** Chia Story thành các **Nhiệm vụ kỹ thuật (Tasks)** nhỏ, có thể quản lý được.
    * **Ví dụ Tasks:** Xây dựng giao diện Form (FE); Thiết lập API Endpoint (BE); Viết Unit Tests.

4.  **Ước tính Công việc (Estimation):**
    * **Mục tiêu:** Ước tính thời gian (bằng giờ) cần thiết để hoàn thành **mỗi Task**.
    * **Hoạt động:** Giúp kiểm soát tổng khối lượng công việc.

5.  **Kiểm tra Khả năng và Cam kết:**
    * **Mục tiêu:** Đảm bảo tổng khối lượng công việc ước tính không vượt quá khả năng của nhóm trong Sprint.
    * **Cam kết:** Nhóm chính thức cam kết hoàn thành User Story này trong Sprint sắp tới.