# module2-reflection

# reflection 02/02/2021
* clean code:
+ Đơn giản
+ Dễ hiểu
+ có ít phụ thuộc
+ không có code lặp
# clean code được gì:




# reflection 01/02/2021
+ abstract class và class:
+ giống:
+ đều là một class
+ đều chứa thuộc tính và phương thức
+ khác nhau:
+ Abstract class có tính trừu tượng rất cao, không thể tạo được các đối tượng của lớp đó.
+ phương thức chỉ khai báo mà không có phần thân
+ lớp kế thừa interface thì phải triển khai chính xác phương thức đã được m
+ interface :Là cấu trúc giống như lớp,chứa hằng số và abstract method.Nó quy định các hành vi chung cho các lớp triển khai nó, nó là bản thiết kế cho  method, Các method có định nghĩa giống nhau nhưng khác nhau về bản chất. Sử dụng từ khóa (interface).Một lớp triển khai interface thì cần triển khai tất cả các phương thức được khai báo trong đó






### reflection 29/01/2021
+ Khi một class được khai báo là final thì không lớp nào có thể kế thừa nó và nó chỉ có thể khởi tạo được thôi.
# so sánh override và overload :
# override :
+ Thay đổi hành vi hiện tại của phương thức.
+ Thay đổi hành vi hiện tại của phương thức.	
+ Phương thức ghi đè ở lớp con phải có quyền truy cập bằng hoặc lớn hơn phương thức được ghi đè ở lớp cha.	
+ Kiểu trả về bắt buộc phải giống nhau.	
+ Danh sách tham số phải giống nhau.	
# overload:
+ Thêm hoặc mở rộng cho hành vi của phương thức.
+ Thể hiện tính đa hình tại compile time.
+ Danh sách tham số có thể khác nhau.
+ Các phương thức nạp chồng có thể có quyền truy cập khác nhau.
+ Kiểu trả về có thể khác nhau.
+ Xảy ra trong phạm vi cùng 1 class.
# constructor :
+ là một phương thức , được thực thi khi tạo ra đối tượng. Nó thường được sử dụng để khởi tạo các chức năng như gán thuộc tính với giá trị hay tạo ra các đối tượng khác từ đối tượng vừa tạo.không thể tạo nhiều constructor trong một class,
+ -Khi nào thì lớp cha không cho phép lớp con kế thừa các thuộc tính và phương thức.khi khai báo private




### reflection 28/01/2021
+ Access modifile là các từ khóa sử dụng để quy định mức độ phạm vi truy cập đến lớp và thành phần của lớp
+ public:dùng cho cả lớp, thuộc tính và phương thức của lớp ,có thể truy cập đến bất cứ đâu
+ protected: dùng cho thuộc tính và phương thức của lớp chỉ được truy cập trong cùng một lớp và các lớp con kế thừa
+ private: dùng cho thuộc tính phương thức của lớp ,đươc phép truy cập trong một lớp đó
+  $this là một biến đặc biệt (được sử dụng trong tất cả các đối tượng) nó lưu một tham chiếu đến đối tượng hiện tại,Bạn sử dụng $this để truy cập các thuộc tính và gọi các phương thức cho đối tượng hiện tại được tạo ra từ lớp.
+ Từ khóa new để tạo một đối tượng từ lớp đã định nghĩa
+ setter là phương thức cho phép thay đổi giá trị của thuộc tính, getter là phương thức cho phép lấy về giá trị của thuộc tính 
+ Namespace (tên miền không gian) là một hình thức để đóng gói các hạng mục có liên quan lại với nhau
+ namespace phân biệt chữ hoa và chữ thường
+ Khi sử dụng từ khoá static với các thành phần của một lớp thì chúng có thể được truy cập thông qua tên của lớp mà không cần khởi tạo đối tượng, Một thuộc tính static thì không thể được truy cập thông qua một đối tượng của lớp đó, nhưng một phương thức static thì có thể được gọi thông qua một đối tượng của lớp.





### reflection 27/01/2021
+ Access modifile là các từ khóa sử dụng để quy định mức độ phạm vi truy cập đến lớp và thành phần của lớp
+ public:dùng cho cả lớp, thuộc tính và phương thức của lớp ,có thể truy cập đến bất cứ đâu
+ protected: dùng cho thuộc tính và phương thức của lớp chỉ được truy cập trong cùng một lớp và các lớp con kế thừa
+ private: dùng cho thuộc tính phương thức của lớp ,đươc phép truy cập trong một lớp đó
+  $this là một biến đặc biệt (được sử dụng trong tất cả các đối tượng) nó lưu một tham chiếu đến đối tượng hiện tại,Bạn sử dụng $this để truy cập các thuộc tính và gọi các phương thức cho đối tượng hiện tại được tạo ra từ lớp.
+ Từ khóa new để tạo một đối tượng từ lớp đã định nghĩa
+ setter là phương thức cho phép thay đổi giá trị của thuộc tính, getter là phương thức cho phép lấy về giá trị của thuộc tính 


### reflection 26/01/2021
+ Một mảng là một biến đặc biệt, cái mà có thể chứa nhiều hơn một giá trị tại một thời điểm.
+ có thể dùng vòng lặp foreach để duyệt mảng
+ Hàm count() được sử dụng để trả về độ dài (số lượng phần tử) của một mảng.
+ phân biệt required vs required_one:
+ Câu lệnh require sẽ tung ra thông báo lỗi nghiêm trọng (E_COMPILE_ERROR) và dừng thực thi trang hiện tại
+ required-once: chỉ import đúng một lần, nghĩa là khi bạn sử dụng hai lệnh require_once cùng một file thì ở lệnh require_once thứ hai nó sẽ thấy là đã xử lý rồi nên nó sẽ không thực thi nữa.
+ Câu lệnh include sẽ tung ra một cảnh báo (E_WARNING) và tiếp tục thực thi trang hiện tại.
+ include-once: giống required-once


### reflection 25/01/2021
+ Website là một tập hợp các trang web con có thể chứa văn bản, hình ảnh, âm thanh, video. Trang đầu tiên của website được gọi là trang chủ
+ có hai loại website : 
+ Website tĩnh là loại website cơ bản mà có thể tạo ra dễ dàng. Bạn không cần sử dụng tới các ngôn ngữ lập trình web như Java, PHP,là trang web sử dụng hoàn toàn ngôn ngữ HTML
+ Website động là tập hợp của những trang web mà nội dung có khả năng thay đổi. Sự thay đổi có thể là tùy theo thời gian, tùy theo người dùng,Sử dụng ngôn ngữ phía máy chủ như PHP, Java , Python để phát triển một website.
+ LAMP :
+ LAMP là từ viết tắt để chỉ một bộ công nghệ được ưa chuộng và sử dụng phổ biến dùng trong xây dựng các ứng dụng web. Tên gọi LAMP xuất phát từ các chữ cái đầu của các công nghệ thành phần, bao gồm: Linux (hệ điều hành), Apache (ứng dụng web server), MySQL (hệ quản trị cơ sở dữ liệu) và PHP (ngôn ngữ lập trình PHP,Perl và Python)









