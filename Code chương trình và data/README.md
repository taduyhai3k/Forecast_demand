# Hướng dẫn chạy code

1. **Yêu cầu tiên quyết**
    - Đảm bảo bạn đã cài đặt Python trên máy tính của mình. Nếu chưa, bạn có thể tải Python tại https://www.python.org/ và cài đặt theo hướng dẫn.
    - Phiên bản Python nhóm sử dụng là Python 3.10.9

2. **Mã nguồn**
    - Đảm bảo phải có mã nguồn của dự án.
    - Gồm 3 file cho 3 phương pháp:
    + VAR.ipynb: VAR ước lượng hệ số bằng OLS
    + Durbin-Levinson.ipynb: VAR ước lượng hệ số bằng Durbin-Levinson
    + Holt_Winter.ipynb

3. **Cài đặt thư viện phụ thuộc**
    - Mở terminal hoặc command prompt, điều hướng đến thư mực chứa file requirements.txt.
    - Chạy lệnh sau để cài đặt các thư viện cần thiết:
        ```
        pip install -r requirements.txt
        ```
4. **Dữ liệu**
    - Đảm bảo phải có Data để chạy chương trình, ít nhất bao gồm file chứa dữ liệu các quý của cả 5 trường A, B1, B2, A đối thủ và B đối thủ:
    |  A   |  B1  |  B2  | A_doithu | B_doithu |
    |------|------|------|----------|----------|
    |  0   |  0   |  0   | 180315   | 5403820  |
    |  0   |  0   |  0   | 293248   | 11458146 |
    |  0   |  0   |  0   | 177016   | 18438880 |
    |  0   |  0   |  0   | 327871   | 10013404 |
    | 735  | 450  | 560  | 181098   | 4864172  |
    | 330  | 350  | 600  | 270405   | 10889213 |
    | 560  | 360  | 630  | 90514    | 4774831  |
    | 750  | 420  | 805  | 355380   | 9768208  |
    | 730  | 450  | 850  | 202572   | 6012674  |
    | 450  | 400  | 750  | 244208   | 9402112  |
    | 600  | 500  | 950  | 169769   | 11288509 |
    | 450  | 400  | 750  | 279109   | 7350389  |
    | 555  | 650  | 1050 | 336751   | 3838228  |
    | 600  | 470  | 850  | 252855   | 6486889  |
    | 400  | 550  | 350  | 306091   | 7652448  |
    | 800  | 1100 | 1600 | 107311   | 3320751  |

5. **Chạy code**
    - Cần chỉnh sửa đường dẫn dẫn đến file data.
    - Nhấn "Run All" để chạy toàn bộ cell
    - Cách chỉnh sửa thông số các mô hình đều được ghi chú trong các file ipynb.

5. **Xem kết quả**
    - Sau khi chạy thành công, chương trình sẽ hiển thị kết quả.

6. **Sửa lỗi (nếu có)**
    - Nếu gặp lỗi trong quá trình chạy, hãy xem thông báo lỗi để tìm hiểu nguyên nhân.
    - Kiểm tra lại các yêu cầu tiên quyết và cài đặt lại thư viện phụ thuộc nếu cần thiết.
    - Kiểm tra mã nguồn và điều chỉnh các lỗi nếu có.

Lưu ý: Hướng dẫn chạy code này chỉ mang tính chất tổng quan. Các dự án cụ thể có thể có cấu hình và yêu cầu riêng, vui lòng kiểm tra tài liệu và mã nguồn của dự án cụ thể để biết cách chạy chính xác. Nếu có thắc mắc về code, vui lòng liên hệ: nghiem.nv206206@sis.hust.edu.vn, son.nh206165@sis.hust.edu.vn, hai.td20206197@sis.hust.edu.vn
