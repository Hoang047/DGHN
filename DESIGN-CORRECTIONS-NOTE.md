# Kế hoạch tải và thay đổi notebook

File chính đã được thay bằng notebook tái cấu trúc 10 bước, dựa trên các audit và log demo.

Các thay đổi chính:

- tách core `c` khỏi thread pool `P`; giữ `K` riêng;
- thêm `t_err > 0` vào closed-loop;
- dùng tải $\\gamma$ tuyệt đối hoặc chuẩn hóa CPU chung cho E1/E3;
- tách rõ metric hiện có và metric planned;
- chuẩn hóa ký hiệu;
- ghi rõ Node Cluster khác Loom;
- ghi rõ trạng thái demo synchronous cần điều tra;
- dùng LaTeX cho công thức và bảng model queue.
