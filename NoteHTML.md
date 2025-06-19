--> Lesson 1: HTML: Thẻ cơ bản: so sánh, phân biệt, cách dùng
1 block and inline
![alt text](image.png)
![alt text](image-1.png)
- Thẻ HTML giá trị mặc định ban đầu việc hiển thị đó là block và inline
- Thẻ Block bắt đầu dòng mới chiếm toàn bộ cái chiều ngang của thiết bị  website đó (<h1>,<article>,<div>,<header>,<main>,<table>,.......)
Thẻ Inline ở trên một dòng. chiều dài phụ thuộc vào nội dung bên trong không hiceesm hết chiều dài của thiết bị (<a>,<img>,<button>,<span>,.....)
Tại sao phải chọn ?
Chọn thẻ để phù hợp với mục đích sử dụng của mình 
Block : thì chiếm cả 1 dòng và bắt đầu dòng mới
Inline : trên 1 dòng liền luôn không xuống dòng 
Giúp xác định vị trí của inline trên trang web
Giá trị mặc định->sử dụng CSS để custum vị trí 
Block-level-elements : hiện thị trên một dòng mới cứ trông lên nhau chiếm cả 1 cái with
Inline-level-elements : nối tiếp elements hết thì xuống dòng không trồng lên nhau
Inline
Phần tử có thuộc tính display thuộc kiểu Inline sẽ nằm cùng dòng với các phần tử cạnh nó.
Ta có thể coi phần tử Inline như là các từ thuộc một đoạn văn, khi còn chỗ trống thì nó nằm bên cạnh phần tử trước nó, khi hết chỗ trống thì nó "xuống dòng"
Khoảng cách giữa phần tử Inline và các phần tử cạnh nó được để mặc định là khoảng cách giữa các từ của font-size
Ta không thể định nghĩa các thuộc tính width, height, padding và margin theo chiều dọc (top, bottom) dành cho các phần tử Inline

2.Phân biệt thẻ tự đóng và thẻ có thẻ đóng
thẻ mở là thẻ có thể mở có thể đóng : có cấu trúc ở giữa có phần nội dung như <p> hay <h1> đến <h6>
Thẻ tự đóng <hr> và <br>  có cách viết khác là <br> or <br /> ( kết thúc luôn không có thẻ mở hay thẻ đóng gì cả chỉ có 1 thẻ này thôi)
<br> : break ( thẻ tự đóng self-closing tag) "phá vỡ" hoặc "ngắt dòng"
<hr> : horizontal rule ( thẻ tự đóng self-closing tag) tạo "đường kẻ ngang" ngăn cách trên trang 