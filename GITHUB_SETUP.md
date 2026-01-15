# 📋 Hướng dẫn Setup GitHub Repository cho Portfolio

## Bước 1: Tạo Repository mới trên GitHub

1. Đăng nhập vào GitHub
2. Click vào dấu **+** ở góc trên bên phải → chọn **New repository**
3. Đặt tên repository (ví dụ: `capstonebara-portfolio` hoặc `capstonebara-demo`)
4. Chọn **Public** hoặc **Private** tùy ý
5. **KHÔNG** tích vào "Initialize with README" (vì chúng ta đã có sẵn)
6. Click **Create repository**

## Bước 2: Khởi tạo Git trong thư mục portfolio

Mở terminal/PowerShell và chạy các lệnh sau:

```bash
# Di chuyển vào thư mục portfolio
cd portfolio

# Khởi tạo git repository
git init

# Thêm tất cả các file
git add .

# Commit lần đầu
git commit -m "Initial commit: Portfolio demo for CapstoneBara"

# Thêm remote repository (thay YOUR_USERNAME và REPO_NAME)
git remote add origin https://github.com/YOUR_USERNAME/REPO_NAME.git

# Đổi tên branch thành main (nếu cần)
git branch -M main

# Push lên GitHub
git push -u origin main
```

## Bước 3: Cấu hình .gitignore

File `.gitignore` đã được tạo sẵn để đảm bảo:
- ✅ Không commit source code
- ✅ Không commit file cấu hình nhạy cảm
- ✅ Chỉ commit các file demo/documentation

## Bước 4: Kiểm tra

Sau khi push, truy cập repository trên GitHub và kiểm tra:
- ✅ README.md hiển thị đúng
- ✅ demo.html có thể xem được
- ✅ Assets/images được hiển thị
- ✅ Không có file source code nào bị commit

## Lưu ý quan trọng

⚠️ **KHÔNG BAO GIỜ** commit:
- Source code (`.py`, `.js`, `.jsx`, `.ts`, `.tsx`)
- File cấu hình (`.env`, `config.py`)
- Database files
- Node modules hoặc virtual environments
- File log hoặc build artifacts

✅ **CHỈ** commit:
- README.md
- demo.html
- Assets/images (trong thư mục assets/)
- LICENSE
- .gitignore

## Cập nhật Repository

Khi có thay đổi trong thư mục portfolio:

```bash
cd portfolio
git add .
git commit -m "Update: Mô tả thay đổi"
git push
```

## Tùy chọn: GitHub Pages

Để host demo.html trên GitHub Pages:

1. Vào **Settings** của repository
2. Scroll xuống **Pages** section
3. Chọn branch **main** và folder **/ (root)**
4. Click **Save**
5. Truy cập: `https://YOUR_USERNAME.github.io/REPO_NAME/demo.html`

---

**Chúc bạn thành công! 🎉**
