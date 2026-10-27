# VTBIM — BIM và hồ sơ kiến trúc ngay trong SketchUp

VTBIM biến SketchUp thành một công cụ làm việc kiểu **Archicad**: dựng mô hình bằng cấu kiện BIM thật
(tường, cột, dầm, sàn, mái, cửa, cầu thang…), vẽ 2D ngay trên mặt bằng, **tự động lập bộ hồ sơ** (mặt bằng,
mặt đứng, mặt cắt, chi tiết, bảng thống kê), dàn trang thành tờ và xuất **PDF / DWG**, tất cả trong một file SketchUp.

## ⬇ Tải về

**[Tải VTBIM 3.2.4 (.rbz)](https://github.com/mencom95/vtbim/releases/download/v3.2.4/vtbim_3.2.4.rbz)**

Các phiên bản: [Releases](https://github.com/mencom95/vtbim/releases)

**Yêu cầu:** SketchUp 2024 trở lên, Windows.

## Cài đặt

1. Mở SketchUp → **Extensions → Extension Manager**.
2. Bấm **Install Extension**, chọn file `vtbim_3.2.4.rbz` vừa tải.
3. Khởi động lại SketchUp. Menu và thanh công cụ **VTBIM** sẽ xuất hiện.

---

## Tính năng

### 🧱 Mô hình BIM
- **Tường**: nhiều lớp cấu tạo, tự nối góc L / T, tự khoét lỗ cửa.
- **Cột, dầm, sàn, mái, trần**: dựng theo thông số, sửa thông số là mô hình dựng lại.
- **Cửa đi, cửa sổ, lỗ mở, vách kính**: đặt bám tường, xem trước khi rê chuột.
- **Cầu thang + lan can**: thang BTCT / thang thép, chiếu nghỉ, bậc rẻ quạt, tay vịn liền mạch.
- **Thiết bị vệ sinh**: đặt trên mặt bằng, có ký hiệu 2D và mô hình 3D.
- **Vùng / phòng (Zone)**: tên, diện tích, tem phòng.
- **Loại cấu kiện**: cấu tạo lớp, tiết diện, vật liệu xây dựng; tạo cấu kiện tự định nghĩa.
- **Tầng (Story)**: quản lý cao độ tầng, copy cấu kiện giữa các tầng.

### ✏️ Vẽ 2D kiểu Archicad
- Mặt bằng 2D sống động ngay từ mô hình (Plan Viewer): nét, cung, polyline, chữ, ghi chú, ảnh.
- **Fill / hatch** theo vật liệu, thư viện mẫu hatch, kiểu nét, **bộ bút** (độ dày nét in).
- **Kích thước**: chuỗi kích thước bám đối tượng, cốt cao độ, cắt / sắp xếp dim.
- **Hệ trục** (tự tạo trục), ký hiệu mặt cắt / mặt đứng, ký hiệu tự định nghĩa.
- Thao tác quen tay Archicad: Ctrl + bấm để cắt nét, ống hút / ống nhả thuộc tính, grip kéo điểm,
  tầng tham chiếu (Trace), kính lúp, copy 2D sang tầng khác.
- Font **SHX tiếng Việt** (Vnsimli…), TCVN3 và TrueType.

### 📐 Mặt bằng, mặt đứng, mặt cắt
- Tạo **mặt cắt, mặt đứng, mặt đứng nội thất** trực tiếp từ mô hình, khử nét khuất.
- Vết cắt tường / cột có hatch theo vật liệu.
- Mỗi bản vẽ giữ tỷ lệ riêng; chữ, dim, đầu trục tự co giãn theo tỷ lệ.

### 📚 Lập hồ sơ tự động
Một lệnh tạo bộ hồ sơ kiến trúc:
- **Mặt bằng kiến trúc** và các mặt bằng con: tường xây – lỗ mở, định vị cột, định vị dầm, định vị cửa,
  lát sàn, trần – đèn.
- **Mặt đứng, mặt cắt**, mặt bằng + mặt cắt **cầu thang**, hồ sơ **khu vệ sinh** (mỗi WC một tờ).
- Tự đặt **kích thước ngoài nhiều lớp**, đầu trục, cốt cao độ, tem phòng, tag cửa / sàn tự né nhau.
- **Bảng thống kê** cột, cửa, thiết bị tự cập nhật; tự bố trí dầm.
- **Kiểm tra hồ sơ**: báo hình tràn khổ, hình trống, chồng nhau.

### 🗂 Dàn trang (LayoutBook) và xuất bản
- Tờ bản vẽ, **khung tên**, layout mẫu, thông tin dự án, khung hình vắt nhiều ô (BIG view).
- Hình trên tờ tự cập nhật khi sửa mô hình.
- **Xuất PDF** cả bộ đúng tỷ lệ; **xuất DXF/DWG** từng tờ.
- Quản lý bản vẽ: Project Map, Navigator, Views, sửa đổi (Revision).

### 🔁 AutoCAD DWG / DXF
- **Nhập DWG/DXF**: giữ layer, block, chữ, dim, hatch; bảng ghép layer.
- **Xuất DXF** mở được bằng AutoCAD: hatch, dim, chữ là thực thể thật, component thành BLOCK dùng chung.

### 🏢 Mặt tiền và chi tiết
- Công cụ dựng **mặt tiền** theo profile, vật liệu, texture.
- **Thư viện chi tiết** cấu tạo, dùng lại trong hồ sơ.

### 🤖 Điều khiển bằng AI
- Máy chủ **MCP** tích hợp: Claude, ChatGPT / Codex… đọc mô hình, dựng cấu kiện, lập và kiểm tra hồ sơ
  bằng lời nói tiếng Việt.

---

## Góp ý, báo lỗi

Mở mục [Issues](https://github.com/mencom95/vtbim/issues) để báo lỗi hoặc đề xuất tính năng.
