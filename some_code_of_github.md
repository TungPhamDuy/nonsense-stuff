# Một vài lệnh cơ bản của Git

1. Git không phải github
2. git clone *link-repo-that-need-to-clone-to-local*: Clone repository về máy local
3. git remote -v: Check hiển thị thông tin về remote repository mà máy kết nối
4. git pull origin master/main: Kéo nguyên nhánh chính về local
5. git checkout -b *name-of-new-branch*: Tạo branch mới
6. git push origin *name-of-new-branch*: Đẩy nhánh mới lên repo
7. git branch: Check hiển thị thông tin nhánh chính và nhánh làm việc hiện tại (có dấu *)
8. tại sao là pull request mà không phải là push request?  
- vì pull (kéo) miêu tả hành động nhánh chính kéo chỉnh sửa của nhánh phụ về chính nó, request (yêu cầu) là hành động nhánh phụ gửi yêu cầu đến nhánh chính xin phép được merge những thay đổi của nó vào. không phải push vì đơn giản là nhánh phụ không có quyền ép (đẩy) sự thay đổi của nó vào nhánh chính mà khi không được chấp nhận.