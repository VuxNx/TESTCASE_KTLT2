# TESTCASE_KTLT2
-Đây là bản kiểm thử cho bài tập lớn kỹ thuật lập trình 2. Đây là bộ kiểm hoàn toàn được tạo nên theo kết quả của chủ tus :D
- Để thực hiện chạy testcase này, đầu tiên bạn cần tải về trước và follow theo các bước sau:
    - Bước 1: giải nén tập tin.
    - Bước 2: copy file study_in_pink2.cpp, study_in_pink2.h, main.cpp, main.h vào thư viện để thực hiện vài sửa đổi nhá.
    - Bước 3: (*Quan trọng*) trong file mà bạn định nghĩa hàm run() của class StudyPinkProgram, thực hiện các thay đổi sau:
        - Đầu tiên, thêm tham số id như hình (thêm cả trong .h và .cpp nhé). Tiếp theo, tiếp tục bổ sung 2 dòng như trong hình (ngay dưới khai báo hàm):![image](https://github.com/VuxNx/TESTCASE_KTLT2/assets/158649859/64706743-62dc-4f2b-90ef-b2a651bc116d)
        - Tiếp theo, đặt dòng này vào trước khi thoát vòng for lớn, trên điều kiện break vòng for nếu isStop() == true: ![image](https://github.com/VuxNx/TESTCASE_KTLT2/assets/158649859/59e7819d-4a8d-4e8b-8ab9-f751d9e66007). Sau đó tiến hành comment dòng prinstep().
        - Tiến hành sửa đổi path dẫn cả trong judge.cpp và study_in_pink2.cpp. Vì một số lý do chưa rõ nên, *hãy chia ra làm hai lần chạy, lần 1 từ 1 đến 67, lần 2 từ 68 đến 100.*
- Tiến hành compile và exec như bình thường.


