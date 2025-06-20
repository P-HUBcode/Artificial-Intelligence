#1. Công nghệ sử dụng:
Bài toán 4-Queens và 8-Queens trong bài thực hành sử dụng:
Ngôn ngữ lập trình python.
Sử dụng các thư viện: numpy, random
Thuật toán quay lại (Backtracking)
#2. Giải thích cách hoạt động:
Chương trình tìm cách đặt N quân hậu lên bàn cờ NxN sao cho không quân hậu nào tấn công quân hậu khác. Tức là không có 2 quân hậu nào nằm trên cùng hàng, cùng cột hoặc cùng đường chéo.
Cách hoạt động theo từng bước:
Đặt quân hậu vào vị trí đầu tiên trên bàn cờ.
Kiểm tra tính hợp lệ: Xem quân hậu có bị tấn công bởi quân nào khác không (cùng hàng, cột, hoặc đường chéo).
Di chuyển sang hàng tiếp theo: Nếu hợp lệ, tiếp tục với quân hậu tiếp theo.
Quay lại khi không hợp lệ: Nếu không tìm được vị trí hợp lệ cho quân hậu, quay lại bước trước và thử lại.
Dừng khi tìm được tất cả các giải pháp hợp lệ.
Thuật toán quay lại hoạt động bằng cách thử tất cả các khả năng có thể, kiểm tra tính hợp lệ, và quay lại khi gặp phải sai sót. Đây là một phương pháp mạnh mẽ nhưng có thể yêu cầu nhiều phép thử, đặc biệt với các bài toán có không gian tìm kiếm lớn.
