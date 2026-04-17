# Report 1 Page – FIT4012 Lab 1

## 1. Mục tiêu
Tóm tắt ngắn gọn mục tiêu của bài lab.

## 2. Cách làm
- Đọc hiểu chương trình entropy mẫu.
- Bổ sung hàm tính redundancy.
- Hoàn thiện hàm mod_inverse().
- Chạy thử trên nhiều test case.

## 3. Kết quả chính
### 3.1 Entropy và redundancy
| Input | Entropy | Redundancy | Nhận xét |
|---|---:|---:|---|
| aaaa | 0.0 | 8.0 | Entropy thấp vì chỉ có 1 ký tự, redundancy cao |
| abcd | 2.0 | 6.0 | Entropy cao hơn vì ký tự đa dạng |
| hello world | 2.845 | 5.155 | Entropy trung bình với sự phân bố ký tự |

### 3.2 Modulo inverse
| a | m | Kết quả mong đợi | Kết quả chương trình |
|---:|---:|---|---|
| 3 | 7 | 5 | 5 |
| 10 | 17 | 12 | 12 |
| 6 | 9 | Không tồn tại | Không tồn tại |

## 4. Kết luận
Từ bài lab này, em đã học được cách tính entropy và độ dư thừa thông tin, cũng như ứng dụng thuật toán Euclid mở rộng để tìm nghịch đảo modulo. Khó khăn lớn nhất là hiểu đúng công thức redundancy và xử lý trường hợp không tồn tại nghịch đảo. Việc chạy thử nhiều test case giúp em hiểu rõ hơn về các khái niệm này trong thực tế.
