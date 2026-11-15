# Thực hành Git & GitHub

## Thông tin sinh viên
- Họ và tên: Nguyễn Văn Đức
- MSSV: 1822991155
- Lớp: 22DTH5
- Môn học: Quản lý mã nguồn với Git & GitHub

## Nội dung bài tập
1. Khởi tạo Local Repository.
2. Tạo README.md và index.html.
3. Thực hành staging và commit.
4. Tạo nhánh feature/them-giao-dien.
5. Tạo và liên kết style.css.
6. Push nhánh feature lên GitHub.
7. Merge feature vào main và push main.

## Các lệnh Git tham khảo
```bash
git init
git branch -M main
git remote add origin https://github.com/USERNAME/ThucHanhGit_MSSV.git
git add README.md index.html
git commit -m "Initial commit: Them README va cau truc HTML"
git checkout -b feature/them-giao-dien
git add .
git commit -m "Add CSS giao dien co ban"
git push -u origin feature/them-giao-dien
git checkout main
git merge feature/them-giao-dien
git push origin main
```

Thay `USERNAME`, `MSSV` và các thông tin trong ngoặc vuông bằng thông tin của bạn.
