# Github document 
---
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
| Syntax | Description |
| ----------- | ----------- |
| **git status** | kiểm tra tình trạng của các file trên git |
| **git fetch** | lấy thay đổi của các file trên github |
| **git branch**| liệt kê tất cả các nhánh có trong github |
| **git branch [branch name]**| tạo một nhánh mới trong github |
| **git branch -d [branch name]**| xóa một nhánh trong github |
| **git checkout [branch name]**| đổi sang một nhánh có trong github |
| **git checkout -b [branch name]**| tạo một nhánh mới và chuyển vị trí của mình đến nhánh đó trong github |
| **git pull** | kéo các file đã thay đổi trong nhánh github |
| **git clone [ url ]** | kéo tất cả các file trong nhánh xuống (chỉ làm một lần) |
| **git log** | hiện thị lịch sử trong github |
| **git remote add origin [your github link]** | thêm đường dẫn để github biết bạn đang làm việc ở đâu |

