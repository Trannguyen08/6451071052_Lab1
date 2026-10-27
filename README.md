# LAB1 – Trần Chí Nguyên (6451071052)

Thư mục này có 36 notebook, tương ứng 6 nhóm trong template. Mỗi notebook độc lập, có in họ tên/MSSV và tự tải đúng dataset được chia sẻ trong file `Link truy cập dataset.txt`.

## Chạy trên Colab

1. Mở notebook trong thư mục `notebooks` bằng Google Colab.
2. Chạy lần lượt hai cell code. Các bộ dữ liệu Titanic, Bank Marketing, Online Retail và Groceries được tải tự động.
3. Các notebook tải đúng file được chia sẻ trong thư mục Google Drive môn học.

## Lưu ý dữ liệu Groceries

Ở min_sup từ 0.01% đến 0.1%, số tập phổ biến tăng rất mạnh. Để các lần chạy trên Colab hoàn tất ổn định, Apriori và FP-Growth dùng cùng giới hạn `max_len=3`. Có thể đặt `MAX_ITEMSET_LENGTH=None` trong cả hai notebook để bỏ giới hạn khi máy đủ tài nguyên.

## Nguồn dữ liệu

- Titanic: `titanic.csv`.
- Bank Marketing: `bank-full.csv` (CSV phân tách bằng dấu chấm phẩy).
- Online Retail: `Online Retail.xlsx`.
- Groceries: `groceries.csv` (mỗi dòng là một giao dịch, các mặt hàng ngăn cách bằng dấu phẩy).
- Tracking nhà xưởng: `tb_tracking.xlsx`.

Các file dataset nằm trong thư mục Drive được trỏ tới từ `Link truy cập dataset.txt`; các notebook tải theo ID file đã được chia sẻ.
