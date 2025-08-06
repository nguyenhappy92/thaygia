# Nhà Thuốc Bắc Thầy Gia - Website

Website chính thức của Nhà Thuốc Bắc Thầy Gia - Chăm sóc sức khỏe gia đình bằng phương pháp y học cổ truyền.

## 🌿 Giới Thiệu

Nhà Thuốc Bắc Thầy Gia với hơn 30 năm kinh nghiệm trong nghề thuốc nam, chuyên cung cấp các dịch vụ:

- **Khám bệnh** theo phương pháp y học cổ truyền
- **Bốc thuốc** nam, thuốc bắc chất lượng cao
- **Tư vấn sức khỏe** và chế độ ăn uống
- **Khám tại nhà** cho bệnh nhân không thể đến nhà thuốc

## 🚀 Tính Năng Website

### ✨ Giao Diện Hiện Đại
- Thiết kế responsive, tương thích mọi thiết bị
- Giao diện đẹp mắt với màu sắc tự nhiên
- Animation mượt mà và chuyên nghiệp

### 📱 Responsive Design
- Tối ưu cho desktop, tablet và mobile
- Menu hamburger cho thiết bị di động
- Layout linh hoạt theo kích thước màn hình

### 🎯 Tính Năng Tương Tác
- Smooth scrolling navigation
- Form liên hệ với validation
- Back to top button
- Loading animations
- Parallax effects

### 📄 Các Trang Chính
1. **Trang Chủ** - Giới thiệu tổng quan
2. **Về Chúng Tôi** - Lịch sử và đội ngũ
3. **Dịch Vụ** - 6 dịch vụ chính
4. **Liên Hệ** - Thông tin và form liên hệ

## 🛠️ Công Nghệ Sử Dụng

- **HTML5** - Cấu trúc semantic
- **CSS3** - Styling và animations
- **JavaScript ES6+** - Tương tác và effects
- **Font Awesome** - Icons
- **Google Fonts** - Typography

## 📁 Cấu Trúc Dự Án

```
store/
├── index.html          # Trang chủ
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
├── README.md           # Hướng dẫn
└── .gitignore          # Git ignore file
```

## 🚀 Hướng Dẫn Deploy GitHub Pages

### Bước 1: Chuẩn Bị Repository
```bash
# Khởi tạo Git repository (nếu chưa có)
git init

# Thêm tất cả files
git add .

# Commit changes
git commit -m "Initial commit - Nhà Thuốc Bắc Thầy Gia website"

# Thêm remote repository (thay YOUR_USERNAME và YOUR_REPO_NAME)
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git

# Push lên GitHub
git push -u origin main
```

### Bước 2: Cấu Hình GitHub Pages

1. **Vào repository trên GitHub**
2. **Chọn tab "Settings"**
3. **Scroll xuống phần "Pages"**
4. **Chọn source:**
   - Source: `Deploy from a branch`
   - Branch: `main` (hoặc `master`)
   - Folder: `/ (root)`
5. **Click "Save"**

### Bước 3: Kiểm Tra Website

Sau khi cấu hình xong, website sẽ có URL:
```
https://YOUR_USERNAME.github.io/YOUR_REPO_NAME
```

## 📝 Tùy Chỉnh Nội Dung

### Thay Đổi Thông Tin Liên Hệ
Chỉnh sửa trong file `index.html`:

```html
<!-- Thay đổi địa chỉ -->
<p>Số 3, đường 12, xã Sơn Mỹ, tỉnh Lâm Đồng (Bình Thuận Cũ)</p>

<!-- Thay đổi số điện thoại -->
<p>0901 234 567</p>

<!-- Thay đổi email -->
<p>info@nhathuocbacthaygia.com</p>
```

### Thay Đổi Màu Sắc
Chỉnh sửa trong file `styles.css`:

```css
/* Màu chủ đạo */
:root {
    --primary-color: #4a7c59;
    --secondary-color: #2c5530;
    --accent-color: #6b8e23;
}
```

### Thêm Hình Ảnh
1. Thêm hình ảnh vào thư mục `images/`
2. Cập nhật đường dẫn trong HTML
3. Tối ưu hóa hình ảnh cho web

## 🔧 Tùy Chỉnh Nâng Cao

### Thêm Google Analytics
Thêm vào `<head>` của `index.html`:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

### Thêm Meta Tags SEO
```html
<meta name="keywords" content="nhà thuốc bắc, thuốc nam, y học cổ truyền, khám bệnh">
<meta name="author" content="Nhà Thuốc Bắc Thầy Gia">
<meta property="og:title" content="Nhà Thuốc Bắc Thầy Gia">
<meta property="og:description" content="Chăm sóc sức khỏe gia đình bằng phương pháp y học cổ truyền">
```

## 📞 Liên Hệ

- **Địa chỉ:** Số 3, đường 12, xã Sơn Mỹ, tỉnh Lâm Đồng (Bình Thuận Cũ)
- **Điện thoại:** 0901 234 567
- **Email:** info@nhathuocbacthaygia.com
- **Giờ làm việc:** Thứ 2 - Chủ nhật: 7:00 - 21:00

## 📄 License

© 2024 Nhà Thuốc Bắc Thầy Gia. Tất cả quyền được bảo lưu.

---

**Lưu ý:** Đây là website demo. Vui lòng cập nhật thông tin thực tế trước khi sử dụng cho mục đích thương mại. 