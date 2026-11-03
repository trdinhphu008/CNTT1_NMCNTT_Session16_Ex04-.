# PHẦN 1. PHÂN TÍCH

### 1. So sánh Incognito Mode và Dedicated Profile

-   **Incognito Mode:** Là chế độ ẩn danh, dữ liệu duyệt web chỉ được lưu tạm thời. Khi đóng cửa sổ, lịch sử và Cookie của phiên ẩn danh sẽ bị xóa.
    
-   **Dedicated Profile:** Là hồ sơ trình duyệt riêng, lưu lâu dài trên ổ cứng, bao gồm tài khoản, mật khẩu, lịch sử và Bookmark.

So sánh như sau :
|tiêu chí|incognito|dedicated profile|
|:----:|:----:|:----:|
|lưu trữ |tạm thời |lâu dài|
|cookie|xóa khi đóng cửa sổ|được lưu lại|
|bookmark|không đồng bộ như profile|có thể đồng bộ|
|mục đích |ruyệt wed riêng tư tạm thời|quản lý nhiều tài khoản|

# PHẦN 2. TRIỂN KHAI

### 1. Thiết lập 3 Profile

Em tạo 3 Profile riêng biệt:

-   **Personal:** Dùng cho tài khoản cá nhân, email và mạng xã hội.
    
-   **Work:** Dùng cho tài khoản quản trị GreenLog, GitHub, Canvas LMS và Portal công ty.
    
-   **Sandbox:** Dùng để kiểm thử website và tài khoản thử nghiệm.
    

Mỗi Profile có Cookie, lịch sử, mật khẩu và Bookmark riêng nên hạn chế được tình trạng đăng nhập nhầm tài khoản.

### 2. Tổ chức Bookmark

Em sắp xếp Bookmark thành các thư mục:

-   Personal
    
    -  Email cá nhân
        
    -   Mạng xã hội
        
-   Work
    
    -   GitHub
        
    -   Canvas LMS
        
    -   Portal GreenLog
        
    -   Công cụ quản trị
        
-   Sandbox
    
    -   Website kiểm thử
        
    -   Tài khoản thử nghiệm
        
    -   Tài liệu kiểm thử
        

### 3. Thiết lập Cloud Sync

Em thực hiện như sau:

1.  Mở từng Profile trên trình duyệt.
    
2.  Đăng nhập tài khoản Google tương ứng.
    
3.  Bật tính năng Sync.
    
4.  Chọn đồng bộ Bookmark và các dữ liệu cần thiết.
    
5.  Khi chuyển sang máy tính khác, đăng nhập lại đúng tài khoản để khôi phục Bookmark.
    

**Lưu ý:** Em không sử dụng chung tài khoản đồng bộ cho Profile cá nhân và công việc để tránh lẫn dữ liệu.

# PHẦN 3. KIỂM THỬ

### 1. Quy tắc sử dụng Guest Profile trên máy tính công cộng

Khi sử dụng máy tính công cộng, em thực hiện các quy tắc sau:

1.  Chọn chế độ Guest (Khách) để truy cập Internet.
    
2.  Không đăng nhập tài khoản cá nhân hoặc lưu mật khẩu trên máy.
    
3.  Không bật Cloud Sync.
    
4.  Không tải hoặc lưu tài liệu cá nhân trên máy tính công cộng.
    
5.  Sau khi sử dụng, đóng toàn bộ cửa sổ Guest để xóa dữ liệu phiên làm việc.
    

**Kết luận:** Guest Profile giúp hạn chế lưu lại lịch sử và Cookie sau khi kết thúc phiên sử dụng, bảo vệ thông tin cá nhân trên máy tính công cộng.

