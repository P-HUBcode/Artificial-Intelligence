Bài toán 4-Queens và 8-Queens
# 1. Công nghệ sử dụng
Bài toán 4-Queens và 8-Queens được giải quyết bằng cách sử dụng Python với các thư viện sau:

NumPy: Để xử lý các mảng và dữ liệu.

Random: Để hỗ trợ việc sinh ngẫu nhiên các vị trí.

Thuật toán Quay lại (Backtracking): Được áp dụng để tìm ra các giải pháp hợp lệ.

# 2. Giải thích cách hoạt động
Chương trình tìm cách đặt N quân hậu lên bàn cờ NxN sao cho không quân hậu nào tấn công quân hậu khác. Điều này có nghĩa là không có hai quân hậu nào nằm trên cùng hàng, cột, hoặc đường chéo.

Các bước thực hiện:
Đặt quân hậu vào vị trí đầu tiên trên bàn cờ.

Kiểm tra tính hợp lệ: Xem quân hậu có bị tấn công bởi quân nào khác không (cùng hàng, cột, hoặc đường chéo).

Di chuyển sang hàng tiếp theo: Nếu vị trí hợp lệ, tiếp tục đặt quân hậu vào ô tiếp theo.

Quay lại khi không hợp lệ: Nếu không thể đặt quân hậu vào vị trí hợp lệ, quay lại bước trước đó và thử các vị trí khác.

Dừng khi tìm được tất cả các giải pháp hợp lệ: Thuật toán tiếp tục thử tất cả các khả năng và quay lại khi gặp lỗi cho đến khi tìm được một giải pháp hợp lệ.

Thuật toán Quay lại (Backtracking):
Thuật toán quay lại thử tất cả các khả năng, kiểm tra tính hợp lệ, và quay lại khi gặp phải sai sót. Đây là phương pháp mạnh mẽ để giải quyết các bài toán có không gian tìm kiếm lớn, nhưng đôi khi cần thử nghiệm nhiều lần.
