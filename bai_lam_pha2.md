# BÀI LÀM PHA 2 

- **Họ tên:**Vũ Lê Huy
- **Lớp:**CNTT1
- **Link repository Pha2:**
- **Công cụ AI đã dùng (ChatGPT/Claude/Gemini):**ChatGPT

> Pha 2 (20 phút cuối). Mỗi mục: mở cuộc trò chuyện mới, gửi nguyên văn prompt đã viết trong bai_lam_pha1.md, dán câu trả lời và link chia sẻ vào đây. Xong, kéo thả file này vào repository Pha2.

## 4.2. Trích xuất tin nhắn đặt vé ra JSON

**KET QUA AI**

```text
[
{
"ma_goi": "SVT",
"ngay_su_kien": "2026-12-20",
"nguoi_lon": 2,
"tre_em": 1,
"loai_ve": "thuong",
"ghi_chu": null
},
{
"ma_goi": "FZ",
"ngay_su_kien": "2027-01-05",
"nguoi_lon": 3,
"tre_em": 0,
"loai_ve": null,
"ghi_chu": "hỗ trợ xe lăn"
},
{
"ma_goi": "VIP",
"ngay_su_kien": null,
"nguoi_lon": 4,
"tre_em": 0,
"loai_ve": "vip",
"ghi_chu": "hỗ trợ tìm chỗ"
}
]
```

**Link trò chuyện:**https://chatgpt.com/s/cx_6b063896fb048191a67be3dfcbd53010

## 4.3. Báo giá vé bằng Chain-of-Thought

**KET QUA AI**

```text
Tiền người lớn: 5 × 1.200.000 = 6.000.000 đồng

Tiền trẻ em:
- Trẻ 8 tuổi: 70% × 1.200.000 = 840.000 đồng
- Trẻ 10 tuổi: 70% × 1.200.000 = 840.000 đồng
- Bé 3 tuổi: miễn phí
- Tổng tiền trẻ em: 840.000 + 840.000 + 0 = 1.680.000 đồng
Tiền vé trước giảm: 6.000.000 + 1.680.000 = 7.680.000 đồng

Giảm giá nhóm: 5% × 7.680.000 = 384.000 đồng

Tiền vé sau giảm: 7.680.000 − 384.000 = 7.296.000 đồng

Phụ thu khu ghế ưu tiên: 1 × 300.000 = 300.000 đồng

Tổng tiền: 7.296.000 + 300.000 = 7.596.000 đồng

[RESULT: 7.596.000 đồng]
```

**Link trò chuyện:**https://chatgpt.com/s/cx_6b0638de07f48191b7a2e04b4e75f2ca

### b) Kiểm tra kết quả AI
Đúng
## 4.4. Dây chuyền xử lý khiếu nại – kết quả Trạm 1

**KET QUA AI**

```text
{"loai_su_co":"sai_khu_vuc","so_khach":2,"so_hiep_bi_anh_huong":2,"tom_tat":"Hai khách bị xếp vào khu không mái trong hai hiệp đầu dù mua gói có mái che."}
```

**Link trò chuyện:**https://chatgpt.com/s/cx_6b063954ceb08191bc2463f95b94c8d6

## 4.5. Prompt chấm bài theo Rubric

**KET QUA AI**

```text
(Dán câu trả lời của AI vào đây (bấm nút Copy dưới câu trả lời) – xoá dòng này)
```

**Link trò chuyện:**
