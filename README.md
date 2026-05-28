# 🔐 Similock - Landing Page

Landing page chuyên nghiệp cho **Khoá Thông Minh Similock Đà Nẵng**

## 📋 Mô Tả Dự Án

Similock là một landing page hiện đại, responsive và tối ưu cho công ty cung cấp khoá thông minh tại Đà Nẵng. Website được thiết kế để tạo ấn tượng chuyên nghiệp và khuyến khích khách hàng tiềm năng liên hệ hoặc đặt mua sản phẩm.

## ✨ Tính Năng Chính

- 🎨 **Design Hiện Đại**: Giao diện đẹp mắt với gradient và hiệu ứng animation
- 📱 **Responsive Design**: Tương thích hoàn hảo trên mọi thiết bị (desktop, tablet, mobile)
- ⚡ **Performance Tối Ưu**: Tải nhanh, chỉ sử dụng HTML/CSS/JavaScript
- 🔍 **SEO Friendly**: Cấu trúc semantic, meta tags đầy đủ
- 📧 **Contact Form**: Form liên hệ tích hợp sẵn
- 🎯 **Call-to-Action**: Buttons rõ ràng, dễ sử dụng

## 📑 Các Phần Chính

1. **Navigation Bar**: Menu dễ sử dụng với hamburger menu cho mobile
2. **Hero Section**: Banner chào mừng với hiệu ứng animation
3. **Features**: Giới thiệu 6 tính năng chính của khoá thông minh
4. **Products**: Hiển thị 3 dòng sản phẩm (Basic, Pro, Premium)
5. **Benefits**: 6 lợi ích chính của Similock
6. **Testimonials**: Đánh giá từ khách hàng
7. **Contact**: Form liên hệ và thông tin công ty
8. **Footer**: Liên kết nhanh, mạng xã hội, thông tin công ty

## 🚀 Cách Sử Dụng

### 1. Sao Chép Repository
```bash
git clone https://github.com/similockdn/landingf07.git
cd landingf07
```

### 2. Mở Trực Tiếp
Chỉ cần mở file `index.html` trong trình duyệt:
```bash
# Windows
start index.html

# macOS
open index.html

# Linux
xdg-open index.html
```

### 3. Triển Khai trên GitHub Pages

#### Cách 1: Tự động (nên)
1. Vào **Settings** của repository
2. Chọn **Pages** ở sidebar
3. Chọn branch: `main`
4. Chọn folder: `/root`
5. Bấm **Save**

Website sẽ tự động triển khai tại: `https://similockdn.github.io/landingf07`

#### Cách 2: Sử dụng GitHub CLI
```bash
gh repo view --web
```

## 📁 Cấu Trúc File

```
landingf07/
├── index.html      # File HTML chính
├── styles.css      # Stylesheet tất cả các style
├── script.js       # JavaScript cho interactivity
├── README.md       # File hướng dẫn này
```

## 🎨 Màu Sắc & Styling

| Tên | Giá Trị | Sử Dụng |
|-----|--------|---------|
| Primary | `#2563eb` | Buttons, icons, links |
| Secondary | `#1e40af` | Hover states |
| Accent | `#f59e0b` | CTA buttons, highlights |
| Text Dark | `#1f2937` | Main text |
| Text Light | `#6b7280` | Secondary text |
| Background | `#f9fafb` | Sections |

## 📱 Responsive Breakpoints

- **Desktop**: 1200px+
- **Tablet**: 768px - 1199px
- **Mobile**: < 768px

## 🔧 Tuỳ Chỉnh

### Thay Đổi Thông Tin Công Ty
Chỉnh sửa trong `index.html`:
- Số điện thoại: `+84 (383) 888-888`
- Email: `info@similock.vn`
- Địa chỉ: `Đà Nẵng, Việt Nam`
- Giờ làm việc

### Thay Đổi Giá Sản Phẩm
Tìm phần "Products" trong `index.html` và cập nhật giá tiền

### Thêm Sản Phẩm Mới
1. Sao chép một `.product-card`
2. Thay đổi tên, giá, tính năng
3. Lưu file

## 🌐 Chức Năng Đã Triển Khai

- ✅ Navigation menu responsive
- ✅ Smooth scrolling
- ✅ Form validation
- ✅ Hamburger menu cho mobile
- ✅ Animations & transitions
- ✅ Scroll animations
- ✅ Active nav links on scroll

## 💡 Tính Năng Có Thể Thêm

- 📊 Google Analytics
- 💬 Live chat widget
- 📅 Booking system
- 🎁 Promotion banner
- 🔐 SSL certificate
- 📧 Email notifications

## 📊 SEO & Analytics

Website đã tối ưu cho:
- ✅ Meta tags (description, keywords)
- ✅ Heading hierarchy (H1, H2, H3)
- ✅ Image alt text
- ✅ Semantic HTML structure

### Thêm Google Analytics
Thêm vào `<head>` của `index.html`:
```html
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_ID');
</script>
```

## 🔒 Bảo Mật

- ✅ HTTPS (tự động trên GitHub Pages)
- ✅ Không có dependencies bên ngoài
- ✅ Input validation
- ✅ Không lưu dữ liệu nhạy cảm

## 🐛 Troubleshooting

### Trang không hiển thị đúng
- Xóa cache trình duyệt (Ctrl+Shift+Delete)
- Kiểm tra đường dẫn file

### Mobile menu không hoạt động
- Kiểm tra console (F12)
- Kiểm tra `script.js` có được load

### CSS không áp dụng
- Kiểm tra tên file `styles.css`
- Kiểm tra `<link>` tag

## 📞 Liên Hệ & Hỗ Trợ

- 📧 **Email**: info@similock.vn
- 📱 **Phone**: +84 (383) 888-888
- 📍 **Location**: Đà Nẵng, Vietnam
- 🕒 **Hours**: Thứ 2 - Thứ 7, 8:00 - 18:00

## 📄 License

Copyright © 2026 Similock. All rights reserved.

## 👨‍💻 Team

- **Developer**: Similock Team
- **Created**: May 2026
- **Version**: 1.0

---

## 🎯 Roadmap

- [ ] Blog section
- [ ] Backend integration
- [ ] Payment gateway
- [ ] Multi-language support
- [ ] Dark mode
- [ ] Performance optimization

---

**Made with ❤️ for Similock Đà Nẵng**
