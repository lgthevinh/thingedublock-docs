# Giải thích các khối lệnh trong ThingEduBlock của từng thiết bị

## Các khối lệnh chung

Vì ThingEduBlock sử dụng Arduino CLI để biên dich chương trình, nên các khối lệnh trong ThingEduBlock tương tự như các khối lệnh trong Arduino IDE. Dưới đây là một số khối lệnh chung trong ThingEduBlock:

### Khối lệnh `When Arduino begin` tương đương với khối lệnh `void setup()` 

Khối lệnh `When Arduino begin` được sử dụng để khởi tạo các thiết bị và biến trong chương trình. Khối lệnh này chỉ được thực thi một lần khi chương trình bắt đầu chạy.

### Vòng lặp `forever` tương đương với khối lệnh `void loop()`

Vòng lặp `forever` được sử dụng để chứa các khối lệnh mà bạn muốn lặp lại nhiều lần trong chương trình. Các khối lệnh trong vòng lặp `forever` sẽ được thực thi liên tục cho đến khi chương trình kết thúc.