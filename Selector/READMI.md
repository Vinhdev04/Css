### Ôn tập Selectors:

1. Simple selectors:
   -> class
   -> id
   -> element: div,.....
   -> element.class: p.desc,
   -> "\*"
   -> element, element : div p......
   ->....

2. Combinator selectors:
   -> descendant selector (space) => Bộ chọn con cháu khớp với tất cả các phần tử là con của một phần tử được chỉ định.

   -> child selector (>) => chọn thẻ (element) con trực tiếp của thẻ (element) đang chỉ định

   -> adjacent sibling selector (+) => chọn element nằm cùng cấp

   -> general sibling selector (~) => chọn element nằm cùng cấp ko nhất thiết phải liền kề

3. Pseudo-class selectors:
   -> :root => sử dụng để đặt các biến CSS toàn cục bằng cách sử dụng biến

   <!-- --------- Sử dụng cho button, link, text,input,.. ---------- -->

   -> :target => áp dụng cho phần tử được chỉ định bằng một định danh (ID) trong URL. Nó thường được sử dụng để thiết kế và hiển thị một phần tử cụ thể trên trang dựa trên định danh mục tiêu trong URL.

   -> :visited => liên kết đã được truy cập

   -> :hover => di chuột vào phần tử liên kết

   -> :link => liên kết chưa được click

   -> :active => liên kết đang được click

   -> :disabled => Vô hiệu hóa phần tử

   -> :enabled => kích hoạt phần tử

<!-- --------- Sử dụng cho button, link, text,input,.. ---------- -->

-> :empty => áp dụng các kiểu cho các phần tử HTML khi chúng không có bất kỳ nội dung nào bên trong, bao gồm cả các nút không có văn bản và các phần tử không có nội dung HTML.

-> :focus => áp dụng khi một phần tử nhận được trạng thái lấy trọng tâm, thường là do người dùng nhấp chuột vào hoặc sử dụng phím điều hướng để di chuyển đến phần tử đó.

-> :checked => áp dụng cho pháp dụng khi một phần tử nhận được trạng thái lấy trọng tâm, thường là do người dùng nhấp chuột vào hoặc sử dụng phím điều hướng để di chuyển đến phần tử đó.ần tử đang được chọn (checked).

-> :valid => bộ chọn chọn các thành phần của biểu mẫu có giá trị xác thực theo cài đặt của thành phần. Sử dụng cho thẻ: : form,input,textarea,select..

-> :invalid => nếu ko nhập đủ thông tin yêu cầu cảu required hoặc ko đúng định dạng yêu cầu -> hoạt động .Sử dụng cho thẻ : form,input,textarea,select..

-> :in-range => bộ chọn chọn tất cả các phần tử có giá trị nằm trong phạm vi được chỉ định.

-> out-of-range => bộ chọn chọn tất cả các phần tử có giá trị nằm ngoài phạm vi được chỉ định.

<!-- --------- Sử dụng cho button, link, text,input,.. ---------- -->

-> :first-child
-> :last-child
-> :nth-child(n)
-> :nth-last-child(n)
-> :only-child
-> :first-of-type
-> :last-of-type
-> :nth-of-type(n)
-> :only-of-type
-> :optional
-> :out-of-range
-> :read-write
-> :nth-last-of-type(n)
-> :not(selector)

### Hiệu quả sử dụng

==> Tạo kiểu cho một phần tử khi người dùng di chuột qua nó
==> Tạo kiểu khác nhau cho các liên kết đã truy cập và chưa truy cập
== >Tạo kiểu cho một phần tử khi nó được lấy nét

4. Pseudo-elements selectors:
   -> ::after
   -> ::before
   -> ::first-letter
   -> ::first-line
   -> ::marker
   -> ::selection 5. Attribute selectors:

### Thứ tự ưu tiên:

1. !important
2. Inline
3. Selector specificity: \* < element < class,attributes < id < ....
