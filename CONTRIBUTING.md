# Hướng dẫn đóng góp cho dự án

Chào mừng bạn đến với dự án của chúng tôi! Dự án này nhằm mục đích cung cấp các
kiến thức và tài liệu về Front End, Back End, Linux và Design cho những bạn HR
mới bước chân vào nghề tuyển dụng. Đây là một dự án đầy tham vọng và chúng tôi
tin rằng với sự đóng góp của nhiều người, nó sẽ trở thành một nguồn tài liệu
tuyệt vời cho những bạn HR mới vào nghề.

Chúng tôi rất mong nhận được sự đóng góp từ bạn với dự án này. Bất kỳ đóng góp
nào của bạn đều rất quan trọng đối với chúng tôi. Để giúp bạn đóng góp cho dự án
của chúng tôi, dưới đây là một số hướng dẫn cho bạn.

## Cách đóng góp

### 1. Fork dự án

Trước khi bắt đầu đóng góp cho dự án của chúng tôi, bạn cần phải tạo một bản sao
của dự án trên tài khoản Github của bạn. Quá trình này được gọi là "fork" dự án.
Để thực hiện fork, bạn có thể nhấp vào nút "Fork" ở góc trên bên phải của dự án
này trên Github. Sau đó, một bản sao của dự án sẽ được tạo ra trên tài khoản
Github của bạn và bạn có thể bắt đầu đóng góp cho dự án này.

### 2. Clone dự án

Sau khi đã fork dự án, bạn cần phải sao chép nó về máy tính của mình bằng cách
sử dụng lệnh sau trên Terminal:

```bash
git clone https://github.com/vnodesign/hr-document.git
```

### 3. Tạo một branch mới

Trước khi bắt đầu đóng góp, bạn cần phải tạo một nhánh mới để làm việc trên đó.
Hãy sử dụng lệnh sau để tạo một nhánh mới:

```bash
git checkout -b ten-nhanh-moi
```

Với "ten-nhanh-moi" là tên của branch mới mà bạn muốn tạo.

### 4. Đóng góp cho dự án

Sau khi đã tạo branch mới, bạn đã sẵn sàng để đóng góp cho dự án. Có thể bạn
muốn tạo mới hoặc chỉnh sửa các tài liệu và các file trong dự án. Bạn có thể sử
dụng các công cụ phù hợp để tạo và chỉnh sửa các file như Typora, StackEdit,
Dillinger, Mark Text, hoặc MacDown. Ngoài ra, hãy đảm bảo rằng tất cả các thay
đổi của bạn đều đã được kiểm tra kỹ trước khi tạo pull request.

### 5. Commit và push thay đổi

Sau khi đã hoàn thành các thay đổi, bạn cần phải thực hiện commit và push các
thay đổi lên branch mới của bạn. Bạn có thể sử dụng các lệnh sau để thực hiện
commit và push:

Sử dụng lệnh `git add` hoặc `git add .` để thêm các file đã thay đổi vào stage:

`git add ten-file` hoặc `git add .`

**Lưu ý**: `git add .` sẽ thêm tất cả các file đã thay đổi vào stage.

Sử dụng lệnh `git commit -m` để commit các thay đổi với một thông điệp:

```bash
git commit -m "Thông điệp commit của bạn"
```

Với "Thông điệp commit của bạn" là thông điệp mô tả các thay đổi mà bạn đã thực
hiện.

Sử dụng lệnh `git push` để push các thay đổi lên branch mới của bạn trên Github:

```bash
git push origin ten-nhanh-moi
```

Với "ten-nhanh-moi" là tên của branch mà bạn vừa tạo ở bước trước.

### 6. Tạo Pull Request

Sau khi bạn đã push các thay đổi lên branch mới của mình, bạn cần tạo một Pull
Request để yêu cầu xem xét và chấp nhận các thay đổi của bạn vào dự án chính.
Hãy làm theo các bước sau để tạo Pull Request:

- Truy cập vào Repository của dự án trên GitHub và chọn branch mới của bạn.
- Tại đây bạn nhấp vào nút "New Pull Request".
- Chọn branch mới của bạn và branch chính của dự án.
- Điền thông tin về Pull Request của bạn, bao gồm mô tả chi tiết về các thay đổi
  của bạn.
- Nhấp vào nút "Create Pull Request" để tạo Pull Request của bạn.

Chúng tôi rất cảm kích các đóng góp của bạn vào dự án của chúng tôi. Chúng tôi
sẽ xem xét và kiểm tra các thay đổi của bạn. Nếu chúng tôi thấy rằng các thay
đổi của bạn sẽ đóng góp tích cực cho dự án, chúng tôi sẽ thực hiện Merge Pull
Request của bạn vào branch chính của dự án. Nếu cần thay đổi hoặc chỉnh sửa,
chúng tôi sẽ cập nhật với bạn để cùng nhau hoàn thiện và nâng cao chất lượng của
dự án.

## Quy tắc đóng góp

Để đảm bảo rằng các đóng góp cho dự án của bạn được chấp nhận, chúng tôi yêu cầu
bạn tuân thủ các quy tắc đóng góp sau:

- Đảm bảo rằng các thay đổi của bạn phù hợp với mục tiêu của dự án.
- Đảm bảo rằng các thay đổi của bạn không vi phạm bản quyền hoặc các quyền sở
  hữu trí tuệ khác.
- Đảm bảo rằng các thay đổi của bạn không ảnh hưởng đến hoạt động của các thành
  phần khác trong dự án.
- Đảm bảo rằng các thay đổi của bạn đã được kiểm tra kỹ trước khi tạo Pull
  Request.

Chúng tôi rất trân trọng mọi đóng góp của bạn cho dự án và sẵn sàng hỗ trợ nếu
bạn có bất kỳ câu hỏi hoặc đóng góp nào.

## Lời cảm ơn

Chúng tôi rất trân trọng mọi đóng góp của bạn cho dự án này. Sự đóng góp của bạn
giúp chúng tôi hỗ trợ những người mới bắt đầu trong lĩnh vực tuyển dụng và cung
cấp cho họ các tài liệu hữu ích để phát triển kỹ năng.

Chúng tôi đánh giá cao tất cả những đóng góp của bạn và nếu bạn có bất kỳ câu
hỏi hoặc ý kiến đóng góp, hãy liên hệ với chúng tôi bằng cách tạo một issue hoặc
gửi Messenger trực tiếp đến địa chỉ trang Facebook của chúng tôi.

Một lần nữa, chúng tôi xin cảm ơn những đóng góp của bạn cho dự án HR
Documentation của chúng tôi và hy vọng bạn có được trải nghiệm đáng nhớ trong
quá trình đóng góp này.

Facebook Fanpage:
[https://www.facebook.com/102793352173146/](https://www.facebook.com/102793352173146/).
