--> Lesson 1: 
- Phân biệt thẻ inline và block , thẻ đóng và thẻ có thẻ đóng
- Thẻ p và div thường được sử dụng để phân biệt phần tử block
- Thẻ span thường được sử dụng phân biệt phần tử inline
=> Thẻ block là thẻ sẽ ăn toàn bộ chiều ngang của màn hình, thẻ inline là nó chỉ chiếm toàn bộ nội dung bên trong 
- thẻ tự đóng vs thẻ có thẻ đóng
- Thẻ tự đóng :
+ Nghĩa là thẻ tự đóng, không cần (và không được) có thẻ đóng như </hr> hay </br>
+ <br> (break) : Ngắt dòng (xuống dòng)
+ <hr> (horizontal rule) : Tạo đường kẻ ngang ngăn cách nội dung
- Thẻ có thẻ tự đóng : thẻ có thể có thẻ đóng, hoặc có thể bỏ thẻ đóng mà trình duyệt vẫn hiểu đúng có thể như là <li> hay<p>
- Cách dùng đúng cấu trức HTML :
+ ấn dấu ! sẽ cấu chúc chuẩn của định dạng HTML
+ giải thích :
+ Cặp thẻ <HTML>…</HTML>
Một tài liệu HTML luôn bắt đầu bằng <HTML> và kết thúc bằng </HTML>. Cặp thẻ này dùng để trình duyệt nhận biết đây là một tài liệu HTML. Toàn bộ nội dung, bao gồm các tag khác sẽ đƣợc chứa bên trong cặp thẻ này.
+ Thẻ <HEAD>…</HEAD>
Trong cặp thẻ <Head>…</Head> chứa tất cả phần mở đầu của một trang web. Các thẻ thƣờng nằm trong cặp thẻ Head có thể là: <title>, <style>, <meta>, <link>, <script> và
<base>. Trong cặp thẻ “Head” ta còn có thể đƣa rất nhiều thông tin vào cho browser, search engine.… Các thông tin đó sẽ đƣợc đề cập đến trong phần sau

+ Cặp thẻ <BODY>…</BODY> :Cặp thẻ này đƣợc dùng để xác định phần nội dung chính của tài liệu, tại đây ta có thể nhập vào các đoạn văn bản cùng các thẻ khác quy định về định dạng của dữ liệu lên trang web.

- Thẻ văn bản từ h1 đến h6, p , a ,img :
+ Gồm 6 mức từ H1 cho đến H6, có cỡ chữ giảm dần từ H1 đến H6
+ Thẻ <p> :Dùng để định dạng một đoạn văn bản. Cặp thẻ này tự động tạo khoảng cách giữa các đoạn trước đó và sau nó.
+ Thẻ <a> — liên kết (anchor) :Dùng để tạo liên kết đến một địa chỉ khác (trang web khác, trang trong cùng website hoặc một file tải về).Thuộc tính quan trọng: href (nơi liên kết đến) 
<a href=""></a>
+ Thẻ <img> — hình ảnh : dùng để chèn ảnh cho trang web  <img src="" alt=""> cho ảnh vào thư mục html ms lấy link được
+ thuộc tính quan trọng 
+ src (đường dẫn tới file ảnh) 
+ alt (văn bản thay thế khi ảnh không hiển thị) khi hình ảnh không hiển thị thì sẽ hiển thị nội dung của alt 

-->  LESSON 2
1) Phân biệt các loại input(text,pasword,email,check box,radio,vv,....)
- Thẻ <input> : là loại thẻ xác định loại giao diện và điểu khiển hiện thị trên from
+ Điều khiển text : <input type="text"> : tạo điều khiển nhập văn bản có 1 dòng 
+ Hộp văn bản dạng pasword : <INPUT type=”PASSWORD” name=”tenpass”>: là ô nhập dữ liệu cho mật khẩu , khi người dùng gõ vào kí tự sẽ hiện *** để bảo mật
+ Thẻ <input type="checkbox"> là một ô chọn kiểu tích vào (dạng hình vuông nhỏ).
* Người dùng có thể tích chọn hoặc bỏ chọn.
* Có thể chọn một hoặc nhiều ô cùng lúc.
+ Thẻ <input type="email"> : nhập địa chỉ email.
Nó sẽ tự kiểm tra dữ liệu nhập vào có đúng định dạng email hay không (ví dụ phải có dấu @ và dấu .)
+ Thẻ radio : <input type="radio"> : là ô hình tròn cho phép người dùng chọn 1 trong các ô đó chỉ được chọn 1 ô
+ Thẻ <input type="button"> cũng dùng để tạo một nút bấm, nhưng khác với <button> là nó không có nội dung giữa thẻ mà nội dung hiển thị nằm ở thuộc tính value
2) Cách dùng label đúng cách :
- Tag <label> định nghĩa nhãn cho thành phần <input />.
- Tag <label> không hiển thị bất cứ gì đặc biệt cho người dùng, tuy nhiên nó cung cấp một cải thiện cho người sử dụng chuột, nếu click chuột vào nhãn, sẽ đưa con trỏ chuột vào vùng <input />.
- Muốn sử dụng hiệu quả <label>, cần thiết phải cho giá trị id của <input /> và giá trị for của <label>, hai giá trị này phải trùng nhau
- tôi không hiểu lý thuyết phần này lắm tôi hiểu là label này nó có liên kết đến phần input như ví dụ tôi lấy là liên kết với input id 
- Validate đơn giản: dùng các thứ có sẵn của html để kiểm tra dữ liệu mà không cần viết code JavaScript
- Validate trong HTML có nghĩa là kiểm tra dữ liệu người dùng nhập vào ô input trước khi gửi form.
--> LESSON 3 : table , các thẻ con 
1) Cấu trúc bảng :
- <table>	Tạo bảng
- <thead>	Phần tiêu đề cột
- <tbody>	Phần thân dữ liệu
- <tr>	Dòng dữ liệu
- <th>	Ô tiêu đề (in đậm, căn giữa)
- <td>	Ô dữ liệu thường
2) GỘP Ô TRONG BẢNG HTML — colspan & rowspan
- dùng colspan :gộp nhiều cột làm 1 ô ngang
- dùng rowspan :gộp nhiều hàng lại thành 1 ô dọc
- col trong colspan = column (cột)
- row trong rowspan = hàng
3) Tạo viền cho bảng
 -   Bo viền	border: 1px solid black;	Tạo viền cho bảng và ô
 -  Ghép viền lại	border-collapse: collapse;	Ghép viền giữa các ô
 -  Canh giữa chữ	text-align: center;	Đưa chữ vào giữa ô
 -->  GIT  và GITHUB 
 - GIT là một phần mềm quản lý phiên bản :
 + có thể lưu lại lưu lại từng phiên bản của  dự án mỗi khi chỉnh 
 + quay lại phiên bản cũ 
 + Làm việc nhóm dễ dàng, ai chỉnh sửa gì, ở đâu đều biết rõ.
 + Kết hợp, phân nhánh nhiều tính năng hoặc bản thử nghiệm mà không ảnh hưởng bản chính.
 - GitHub là một trang web lưu trữ mã nguồn (source code) trực tuyến.
 + Nó giống như một kho lưu trữ code online, nơi bạn có thể đưa code của mình lên, quản lý phiên bản và làm việc nhóm với người khác.
 --> Cách sử dụng git :
 - git --version : kiem tra mk dung phien ban nao
 - git config --global user.name : khai bao ten muon su dung 
 - git config --global user.email : khai bao ten email muon su dung ( enmail sử dụng dùng cho github luôn )
 - cat ~/.gitconfig :kiểm tra lại tên kahi báo và email vừa thiết lập 
 - mkdir myproject :  khởi tạo folder
 - cd myproject : đi vào folder vừa tạo
 -  git init : khởi tạo local repository
 - git add + tên ảnh.jpg vừa tạo ở trong folder trên 




















































