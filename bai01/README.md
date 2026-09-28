Nguyên nhân lỗi:
- Chuỗi JavaScript phân biệt chữ hoa và chữ thường.
- startsWith("MED-") sẽ trả về false nếu chuỗi đang là "med-".
- Cần trim() trước để loại bỏ khoảng trắng thừa.
- Cần toUpperCase() để chuẩn hóa mã trước khi kiểm tra và cắt chuỗi.
- String trong JavaScript là bất biến, các hàm trim() và toUpperCase()
  không thay đổi chuỗi ban đầu mà tạo ra chuỗi mới.