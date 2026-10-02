CÂU 1:
  Value Types là kiểu dữ liệu lưu trực tiếp giá trị của biến.
  Khi gán một biến kiểu giá trị cho biến khác thì giá trị được sao chép sang biến mới, hai biến hoạt động độc lập với nhau. 
  Các kiểu dữ liệu như int, double, bool, struct thuộc nhóm này.
  Trong nhiều trường hợp, biến cục bộ của Value Type được lưu trên Stack.

  Reference Types là kiểu dữ liệu lưu tham chiếu đến đối tượng trong bộ nhớ.
  Đối tượng thường được cấp phát trên Heap, còn biến giữ địa chỉ tham chiếu đến đối tượng đó.
  Khi gán một biến Reference Type cho biến khác thì tham chiếu được sao chép, vì vậy hai biến có thể cùng trỏ đến một đối tượng.
  Các kiểu như class, array, object thuộc nhóm Reference Types.

CÂU 2:
    init là tính năng được giới thiệu từ C# 9, cho phép một thuộc tính chỉ được thiết lập giá trị trong quá trình khởi tạo đối tượng.
    Sau khi đối tượng được khởi tạo, thuộc tính sử dụng init không thể thay đổi giá trị thông qua thuộc tính đó.

    Trong khi đó, set cho phép thuộc tính được gán giá trị cả khi khởi tạo và trong quá trình chương trình đang chạy.

    Vì vậy, init phù hợp với những thuộc tính cần được thiết lập một lần và không muốn thay đổi sau khi đối tượng được tạo, giúp đảm bảo tính nhất quán của dữ liệu.

CÂU 3:
   virtual là từ khóa được sử dụng ở phương thức của lớp cha, cho phép phương thức đó có thể được lớp con thay đổi cách triển khai.

   override được sử dụng ở lớp con để ghi đè phương thức virtual của lớp cha và cung cấp cách thực hiện riêng phù hợp với lớp con.

   Sự kết hợp giữa virtual và override giúp C# thực hiện tính đa hình, 
   nghĩa là cùng một phương thức nhưng khi chương trình chạy có thể thực hiện hành vi khác nhau tùy thuộc vào đối tượng thực tế.

CÂU 4:
    Thành phần được khai báo static thuộc về Class chứ không thuộc về một Object Instance cụ thể. 
    Khi khai báo static, thành phần đó được dùng chung cho toàn bộ các đối tượng thuộc lớp và chỉ có một bản ở cấp độ lớp.

    Vì vậy, thành phần static được truy xuất thông qua tên lớp thay vì thông qua đối tượng được tạo bằng toán tử new.
    Điều này thể hiện sự khác nhau giữa thành phần thuộc về lớp và thành phần thuộc về từng đối tượng.
