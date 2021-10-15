# Thử thách 30 ngày HTML - CSS

### Thẻ inline và thẻ block

1. Thẻ inline:
    + có độ rộng và chiều cao bằng nội dung mà nó chứa.
    + nếu có nhiều thẻ inline nó sẽ năm trên cùng 1 hàng.
    + bị hạn chế về thuộc tính css.
2. Thẻ block:
    + có độ rộng bằng phẩn tử cha chứa nó.
    + nếu có nhiều thẻ block thì nó sẽ xuống dòng.

### Class và Id

1. Class:
    + Có thể trùng nhau.
    + Sử dụng cho nhiều phần tử khác nhau.
2. Id:
    + Mỗi phần tử chỏ có 1 id duy nhất.

### BEM (Block Element Modifier)

- Ví dụ: 1 thực thể máy tính (block) có các thành phần (element) màn hình, touchpad, keyboard,... chẳng hạn có máy tính
  to, màn hình 15 inch, bàn phím các (Modifier)

- Quy tắc đặt tên
   ```text
   Block__Element--modifier: laptop__keyboard--small
   Block--modifier: laptop--big
   Block__Element: laptop__display   ```