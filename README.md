# Câu lệnh Stata
## dùng dữ liệu hệ thống
<br>`sysuse auto // dùng dữ liệu hệ thống` 
<br/>
## xem tần số của 1 biến
`tab + (biến bất kỳ trong dữ liệu)` 
- VD: tab foreign
  - ⭐ nếu thêm , nol vào câu lệnh trên đó thì nó sẽ hiện data dưới dạng nhị phân.
<br>
## thể hiện tên biến, storange type v.v, tiêu đề của biến
`d + (biến bất kỳ trong dữ liệu)`
<br>
##  xóa hết lệnh đã gõ và data
`clear`
<br>
## đổi directory để save file log cho đúng chỗ (chọn chỗ save file log )
`cd "tên source của m" // đổi directory để save file log cho đúng chỗ (chọn chỗ save file log )`
<br>
`log using "source của m/**tên_file.log**" // tạo file và ghi lại dữ liệu`
⭐nhớ đặt tên file ending with .log


