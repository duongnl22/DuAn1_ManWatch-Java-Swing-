Đề tài : Phần mềm bán đồng hồ ManWatch - Công nghệ sử dụng : Java Swing , Hibernate
• Luồng nghiệp vụ chính của phần mềm: Bán hàng 
  1.Khi nhân viên tạo một hóa đơn mới, mặc định trạng thái của hóa đơn sẽ là chờ thanh toán, sau đó nhân viên sẽ thêm những sản phẩm mà khách hàng lựa chọn vào giỏ hàng và số lượng ở danh sách sản phẩm cũng bị trừ theo.
  2.Trong trường hợp khách hàng đổi ý thì nhân viên có thể giảm số lượng hoặc bỏ hẳn sản phẩm đó ra khỏi giỏ hàng, sản phẩm bị bỏ sẽ được công lại số lượng vào danh sách sản phẩm. 
  3.Sau khi thêm xong sản phẩm mà khách yêu cầu vào giỏ hàng thì nhân viên sẽ hỏi và xin thông tin của khách, nếu khách hàng không muốn để lại thông tin thì mặc định đó là khách lẻ. Trong trường hợp khách muốn lưu thông tin thì nhân viên sẽ tìm kiếm khách hàng đó theo số điện thoại …, để biết xem là khách hàng này đã mua tại cửa hàng của mình hay chưa, nếu chưa thì có thể thêm mới khách hàng.
  4.Tiếp theo đó là đến phần thanh toán thì khách hàng có thể thanh toán được dưới hình thức là: Tiền mặt.
  5.Sau khi chọn được hình thức thanh toán thì nhân viên sẽ nhập số tiền mà khách đã giao dịch, số tiền phải lớn hơn hoặc bằng tổng tiền cần phải thanh toán thì mới cho thanh toán.
  6.Sau đó nhân viên thực hiện thanh toán, hệ thống sẽ hỏi có muốn in hóa đơn hay không?. Trạng thái của hóa đơn sau khi thanh toán sẽ trở thành đã thanh toán.

