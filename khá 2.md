# BÀI TẬP VỀ NHÀ – XÂY DỰNG CÂY CHỈ SỐ PHÂN RÃ DOANH THU TẠI THE COFFEE HOUSE

## PHẦN 1. SƠ ĐỒ CÂY CHỈ SỐ KPI TREE

### 1. Công thức tổng quát

**Doanh thu = Số lượng đơn hàng × AOV**

Trong đó:

**AOV = Doanh thu đồ uống bình quân/đơn + Doanh thu đồ ăn bán kèm bình quân/đơn**

Tiếp tục:

**Doanh thu đồ ăn bán kèm bình quân/đơn = Food Attachment Rate × Giá trị đồ ăn mua kèm bình quân**

### 2. KPI Tree dạng phân cấp Markdown

```text
DOANH THU
│
├── SỐ LƯỢNG ĐƠN HÀNG
│   └── Số khách hàng phục vụ/tháng
│       └── 10.000 lượt khách
│
└── AOV – GIÁ TRỊ TRUNG BÌNH ĐƠN HÀNG
    │
    ├── DOANH THU ĐỒ UỐNG BÌNH QUÂN/ĐƠN
    │   └── 57.200 VNĐ/đơn
    │
    └── DOANH THU ĐỒ ĂN BÁN KÈM BÌNH QUÂN/ĐƠN
        │
        ├── Food Attachment Rate
        │   └── 8%
        │
        └── Giá trị đồ ăn mua kèm
            └── 35.000 VNĐ/món
```

### 3. Tính AOV hiện tại

AOV hiện tại:

**60.000 VNĐ/đơn**

Doanh thu đồ ăn bán kèm bình quân:

> 8% × 35.000 = **2.800 VNĐ/đơn**

Do đó, doanh thu đồ uống bình quân:

> 60.000 − 2.800 = **57.200 VNĐ/đơn**

Kiểm tra:

> 57.200 + 2.800 = **60.000 VNĐ/đơn**

Như vậy:

> **AOV = 57.200 + (8% × 35.000) = 60.000 VNĐ**

---

# PHẦN 2. PHÂN TÍCH ĐỘ NHẠY FOOD ATTACHMENT RATE

## 1. Bài toán giả định

Food Attachment Rate tăng từ:

> **8% → 25%**

Giả định:

- Số đơn hàng không thay đổi: **10.000 đơn/tháng**
- Doanh thu đồ uống bình quân/đơn không đổi: **57.200 VNĐ**
- Giá trị đồ ăn mua kèm: **35.000 VNĐ/món**

### 2. AOV mới

Doanh thu đồ ăn bán kèm bình quân/đơn mới:

> 25% × 35.000 = **8.750 VNĐ**

AOV mới:

> 57.200 + 8.750 = **65.950 VNĐ/đơn**

### 3. Mức tăng AOV

> 65.950 − 60.000 = **5.950 VNĐ/đơn**

Tỷ lệ tăng AOV:

> 5.950 / 60.000 × 100% = **9,92%**

### 4. Doanh thu tháng mới

Công thức:

> **Doanh thu mới = Số đơn hàng × AOV mới**

> 10.000 × 65.950 = **659.500.000 VNĐ/tháng**

Doanh thu hiện tại:

> **600.000.000 VNĐ/tháng**

Mức tăng doanh thu:

> 659.500.000 − 600.000.000 = **59.500.000 VNĐ/tháng**

Tỷ lệ tăng trưởng doanh thu:

> 59.500.000 / 600.000.000 × 100% = **9,92%**

### 5. Bảng phân tích độ nhạy

| Chỉ tiêu | Hiện tại | Sau cải thiện |
|---|---:|---:|
| Food Attachment Rate | 8% | 25% |
| Giá trị đồ ăn mua kèm | 35.000 VNĐ | 35.000 VNĐ |
| Doanh thu đồ ăn bình quân/đơn | 2.800 VNĐ | 8.750 VNĐ |
| Doanh thu đồ uống bình quân/đơn | 57.200 VNĐ | 57.200 VNĐ |
| **AOV** | **60.000 VNĐ** | **65.950 VNĐ** |
| Số đơn/tháng | 10.000 | 10.000 |
| **Doanh thu/tháng** | **600 triệu VNĐ** | **659,5 triệu VNĐ** |
| **Mức tăng doanh thu** | – | **59,5 triệu VNĐ** |
| **Tăng trưởng** | – | **9,92%** |

### Kết luận phân tích độ nhạy

Việc tăng **Food Attachment Rate từ 8% lên 25%** giúp:

- AOV tăng **5.950 VNĐ/đơn**.
- AOV tăng **9,92%**.
- Doanh thu tăng **59,5 triệu VNĐ/tháng**.
- Tăng trưởng doanh thu đạt **9,92%** mà **không cần tăng số lượng đơn hàng hoặc chi phí mặt bằng**.

→ Vì vậy, **Cross-sell đồ ăn là một đòn bẩy tăng trưởng đáng ưu tiên**.

---

# PHẦN 3. HỆ THỐNG LEADING INDICATORS TẠI QUẦY THU NGÂN

Leading Indicator là **chỉ số dẫn dắt**, đo lường hành vi xảy ra trước khi kết quả kinh doanh cuối cùng xuất hiện.

Đối với nhân viên thu ngân, có thể sử dụng 2 chỉ số sau:

### 1. Tỷ lệ tư vấn đồ ăn

**Công thức:**

> Tỷ lệ tư vấn đồ ăn = Số đơn được nhân viên chủ động giới thiệu đồ ăn / Tổng số đơn hàng × 100%

**Mục đích:**

Đo mức độ chủ động của nhân viên trong việc thực hiện hành vi cross-sell.

**Ví dụ:**

Nếu nhân viên phục vụ 100 đơn và chủ động giới thiệu đồ ăn cho 80 đơn:

> Tỷ lệ tư vấn = 80 / 100 × 100% = **80%**

### 2. Tỷ lệ chuyển đổi bán kèm đồ ăn

**Công thức:**

> Tỷ lệ chuyển đổi = Số đơn có mua đồ ăn / Số đơn được tư vấn đồ ăn × 100%

**Mục đích:**

Đánh giá khả năng biến hành vi tư vấn của nhân viên thành **đơn hàng thực tế**.

Ví dụ:

- 80 đơn được tư vấn đồ ăn.
- 20 đơn thực sự mua thêm đồ ăn.

> Tỷ lệ chuyển đổi = 20 / 80 × 100% = **25%**

---

# KẾT LUẬN

Cây KPI cho thấy doanh thu The Coffee House có thể được phân rã thành **Số lượng đơn hàng × AOV**, trong đó AOV tiếp tục được phân rã thành **doanh thu đồ uống + doanh thu đồ ăn bán kèm**.

Với dữ liệu hiện tại, việc nâng **Food Attachment Rate từ 8% lên 25%** có thể đưa AOV từ **60.000 lên 65.950 VNĐ**, giúp doanh thu tăng từ **600 triệu lên 659,5 triệu VNĐ/tháng**, tương đương **tăng 9,92%**.

Do đó, **Food Attachment Rate là một đòn bẩy quan trọng để tăng trưởng doanh thu mà không cần mở rộng mặt bằng**. Để tác động vào chỉ số này, doanh nghiệp có thể theo dõi 2 Leading Indicators tại quầy: **Tỷ lệ tư vấn đồ ăn** và **Tỷ lệ chuyển đổi bán kèm đồ ăn**.
