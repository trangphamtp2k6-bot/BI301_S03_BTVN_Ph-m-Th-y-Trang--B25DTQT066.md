# BÀI THỰC HÀNH – XÁC ĐỊNH BUSINESS PROBLEM VÀ PHÂN LOẠI MEASURE/METRIC

## PHẦN 1. XÁC ĐỊNH VẤN ĐỀ KINH DOANH

### 1. Business Problem

**Business Problem của mô hình Kiosk mang đi so với cửa hàng tiêu chuẩn:**

> **Mô hình Kiosk mang đi đang có hiệu quả kinh doanh và vận hành thấp hơn cửa hàng tiêu chuẩn, thể hiện qua lượng khách thấp hơn, tỷ lệ khách quay lại thấp, giá trị đơn hàng trung bình thấp và thời gian phục vụ dài hơn.**

Cụ thể:

- Lượt khách/ngày: **350 lượt**, thấp hơn cửa hàng tiêu chuẩn **800 lượt**, giảm **56,25%**.
- Tỷ lệ khách quay lại: **22%**, thấp hơn **55%**, giảm **33 điểm %**.
- AOV: **38.000 VNĐ**, thấp hơn **58.000 VNĐ**, giảm khoảng **34,5%**.
- Thời gian phục vụ: **14 phút**, cao hơn **8 phút**, tăng **75%**.
- Đánh giá sao: **3,2/5**, thấp hơn mức **4,3/5** của cửa hàng tiêu chuẩn.

### 2. Đánh giá Business Problem theo 3 tiêu chí

**① Cụ thể – Đạt**

Vấn đề tập trung rõ vào **hiệu quả kinh doanh và vận hành của mô hình Kiosk**, đồng thời có đối tượng so sánh cụ thể là cửa hàng tiêu chuẩn.

**② Đo lường được – Đạt**

Có thể đo lường bằng các chỉ số:

- Lượt khách/ngày
- Tỷ lệ khách quay lại
- AOV
- Thời gian phục vụ
- Đánh giá sao
- Doanh thu/ngày

**③ Có tầm ảnh hưởng – Đạt**

Vấn đề ảnh hưởng trực tiếp đến:

**Hiệu quả vận hành → Trải nghiệm khách hàng → Khả năng quay lại → Doanh thu của Kiosk.**

### Kết luận

Business Problem **thỏa mãn cả 3 tiêu chí: Cụ thể – Đo lường được – Có tầm ảnh hưởng**.

---

# PHẦN 2. PHÂN LOẠI MEASURE VÀ METRIC

### 1. Khái niệm

- **Measure:** Thước đo dữ liệu thô, phản ánh một đại lượng được ghi nhận trực tiếp.
- **Metric:** Chỉ số được tính toán hoặc xây dựng từ Measure để đánh giá hiệu suất kinh doanh/vận hành.

### 2. Phân loại dữ liệu

| Loại | Chỉ số | Giải thích |
|---|---|---|
| **Measure** | Lượt khách/ngày | Số lượt khách được ghi nhận trực tiếp |
| **Measure** | Giá trị trung bình đơn (AOV) | Giá trị đơn hàng được ghi nhận/tính từ dữ liệu giao dịch |
| **Metric** | Doanh thu trung bình/ngày | Được tính bằng Lượt khách × AOV |
| **Metric** | Tỷ lệ khách quay lại | Dùng để đánh giá khả năng giữ chân khách hàng |

### 3. Tính doanh thu trung bình mỗi ngày của Kiosk

**Công thức:**

> Doanh thu/ngày = Lượt khách/ngày × AOV

**Dữ liệu Kiosk:**

- Lượt khách = **350 lượt/ngày**
- AOV = **38.000 VNĐ**

**Tính:**

> 350 × 38.000 = **13.300.000 VNĐ/ngày**

### Kết quả

**Doanh thu trung bình mỗi ngày của Kiosk ≈ 13,3 triệu VNĐ/ngày.**

---

## KẾT LUẬN CHUNG

Mô hình **Kiosk mang đi đang có hiệu quả thấp hơn cửa hàng tiêu chuẩn** ở cả khía cạnh doanh thu, khả năng giữ chân khách hàng và hiệu quả phục vụ. Đặc biệt, **lượt khách thấp, AOV thấp và thời gian phục vụ cao** là những vấn đề cần được Operations BI Analyst tiếp tục phân tích để xác định nguyên nhân gốc rễ.

**Business Problem chuẩn có thể phát biểu ngắn gọn:**

> **“Doanh thu và hiệu quả vận hành của Kiosk mang đi đang thấp hơn đáng kể so với cửa hàng tiêu chuẩn, do lượng khách, tỷ lệ quay lại và giá trị đơn hàng thấp trong khi thời gian phục vụ cao.”**
