#Term

Repository (Repo)
Branch: Cành
Conflict: Xung đột
Local
Remote

#Commands

- git init: biến dự án/repo trở thành git repo (là đã sử dụng được git)
- git status: thấy được trạng thái của dự án
- git add: chuẩn bị lưu lại thời điểm hiện tại
- git reset: reset lại các file đã chuẩn bị lưu
- git commit: chính thức lưu ( git commit -m 'initial commit': ghi chú thời điểm đầu tiên)
- git log: xem những thời điểm chúng ta đã lưu
- git log --oneline: xem những thời điểm chúng ta đã lưu một cách gọn hơn
- git checkout {id}: trở lại commit vói id
- git checkout {branch-name} : để trở về với hiện tại
- git branch: xem branch hiện tại đang có
- git checkout -b {branch-name}: tạo ra 1 nhánh khác
- git merge {branch-name}: tổng hợp branch khác với nhau
- git branch -d {branch-name}: xoá branch
- git push: đẩy lên remote repo
- git remote add origin {repo url}:
- git pull: đồng bộ dữ liệu từ trên github về
- git push -u origin {branch-name} :đẩy branch lên github
- git fetch origin:
- git checkout -b {branch-name} origin/{branch-name}: lấy branch từ github xuống
- git clone {repo url}: lấy code từ github về

#Git Ignore:

- .gitignore: trong thư mục này sẽ xác định những file hoặc thư mục nào sẽ ẩn và không đưa lên github
