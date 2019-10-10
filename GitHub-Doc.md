# Github document
**Up file lên github**
1. **git init**: cài đặt git vào thư mục cần sử dụng
1. **git add .** : thêm tất cả các file trong thư mục bạn đã cài git
3. **git status**: kiểm tra tình trạng các file trong thư mục bạn đã cài git (nên sử dụng ở mỗi bước để kiểm tra tình trạng của github)
4. **git commit -m "content"** : commit file bạn đã add lên git
6. **git remote add origin [your github link]**: thêm đường dẫn để git biết bạn muốn làm việc với git ở đâu
7. **git push origin [bracnch name]** : up file bạn đã add lên github với nhánh mà bạn muốn
---
**Kéo file từ github xuống**
1. **git clone [ url ]**: kéo tất cả các file trên lib github
2. **git pull**: kéo các file đã thay đổi trong github
---
**Một vài lệnh cơ bản khi sử dụng github**
1. **git status**: kiểm tra tình trạng của các file trên git
2. **git fetch**: lấy thay đổi của các file trên github
3. **git branch**: liệt kê tất cả các nhánh có trong github
4. **git branch [branch name]**: tạo một nhánh mới trong github
5. **git branch -d [branch name]**: xóa một nhánh trong github
6. **git checkout [branch name]**: đổi sang một nhánh có trong github
7. **git checkout -b [branch name]**: tạo một nhánh mới và chuyển vị trí của mình đến nhánh đó trong github
8. **git pull**: kéo các file đã thay đổi trong nhánh github
9. **git clone [ url ]**: kéo tất cả các file trong nhánh xuống (chỉ làm một lần)
10. **git log**: hiện thị lịch sử trong github
11. **git remote add origin [your github link]**: thêm đường dẫn để github biết bạn đang làm việc ở đâu