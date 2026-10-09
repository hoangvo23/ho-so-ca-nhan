1. git init: khởi tạo 1 git dưới máy local
2. git clone <link>: tải 1 repo từ github(thường là làm việc nhóm) về máy
3. git status: kiểm tra trạng thái của file
4. git add <tên file>: đưa file vào giỏ hàng nơi chứa những gì cần commit lần tới
5. git commit -m "cmt": lưu các thay đổi của file vào vùng Local repo (lịch sử Git)
6. git log --oneline: xem lịch sử commit ngắn gọn
7. git branch: xem nhánh đang có và xem mình đang ở nhánh nào
8. git switch -c <tên nhánh>: tạo và vào luôn nhánh(git branch <tên file>+ switch)
9. git swtich <tên nhánh>: chuyển đến nhánh đang có
10. git merge <tên nhánh>: gộp code từ nhánh khác vào nhánh đang ở
11. git push origin <tên nhánh>: đẩy commit từ vùng Local Repo lên Github
12. git pull origin <tên nhánh>: kéo code mới nhất từ Repo Github đó về máy local
13. git stash push -m "": Cất tạm code đang làm vào ngăn kéo riêng
14. git stash pop: lấy lại code trong ngăn kéo đó ra(xóa luôn khác với apply lấy nhưng vẫn lưu) 
15. git restore <tên file>: hủy các thay đổi chưa đc add vào staging của 1 file