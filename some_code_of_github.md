# Một vài lệnh cơ bản của Git

1. git không phải github
2. `git clone *link-repo-that-need-to-clone-to-local*`: Clone repository về máy local
3. git remote -v: Check hiển thị thông tin về remote repository mà máy kết nối
4. git pull origin master/main: Kéo nguyên nhánh chính về local
5. git checkout -b *name-of-new-branch*: Tạo branch mới
6. git push origin *name-of-new-branch*: Đẩy nhánh mới lên repo
7. git branch: Check hiển thị thông tin nhánh chính và nhánh làm việc hiện tại (có dấu *)
8. tại sao là pull request mà không phải là push request?  
- vì pull (kéo) miêu tả hành động nhánh chính kéo chỉnh sửa của nhánh phụ về chính nó, request (yêu cầu) là hành động nhánh phụ gửi yêu cầu đến nhánh chính xin phép được merge những thay đổi của nó vào. không phải push vì đơn giản là nhánh phụ không có quyền ép (đẩy) sự thay đổi của nó vào nhánh chính mà khi không được chấp nhận.
9. chuỗi phím để save, commit và push change lên repo tốc độ:
- crt + s: lưu thay đổi
- crt + enter: viết commit message
- crt + shift + p: push thay đổi lên repo
là một thằng gà thì sẽ xài qua UI, còn đỡ hơn một chút thì xài qua git cmd đi nào:
- git add .: thêm tất cả các thay đổi vào vùng nhớ tạm
- git commit -m *commit-message*: commit các thay đổi và điền note cho commit
- git push: đẩy lên repo  
có thể sử dụng ';' (dấu cách lệnh trong powershell) ở giữa các lên trên để nối các lệnh và thực hiện một lần.
10. có nhiều loại terminal: cmd, powershell, git. terminal là giao diện command line interface (CLI) để tương tác với hệ điều hành. 
- cmd: mặc định của window, cổ điển, cú pháp lệnh đơn giản, không phù hợp với các lệnh unix-like
- powershell: hiện tại, sử dụng rộng rãi, câu lệnh cmdlet mạnh mẽ, quản trị hệ thống, tự động hoá, chạy được lệnh của cmd luôn
- git bash: là CLI cho git, chủ yếu để làm việc với git hoi, chạy được git trong cmd và powershell.
11. git push --set-upstream origin *branch-that-need-to-connect-upstream*: Gắn branch hiện tại với branch trên repo để push lên.
