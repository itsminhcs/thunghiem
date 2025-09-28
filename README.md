# DSGROUP Website

Website chính thức của **DSGROUP - Nhóm Nghiên cứu Khoa học Dữ liệu** được xây dựng trên nền tảng Hugo với theme Research Group.

## 🌟 Giới thiệu

DSGROUP là nhóm nghiên cứu chuyên sâu về Khoa học Dữ liệu, Machine Learning và Trí tuệ Nhân tạo tại Việt Nam. Chúng tôi tập trung vào nghiên cứu ứng dụng và phát triển các giải pháp công nghệ tiên tiến.

## 🚀 Tính năng

- **Trang chủ hiện đại** với hero section và các block nội dung
- **Trang giới thiệu** về sứ mệnh và tầm nhìn của DSGROUP
- **Trang nghiên cứu** giới thiệu các lĩnh vực nghiên cứu chính
- **Trang đội ngũ** giới thiệu các thành viên nghiên cứu
- **Blog tin tức** cập nhật các sự kiện và tin tức mới nhất
- **Trang công trình** hiển thị các ấn phẩm khoa học
- **Trang sự kiện** thông báo các hội thảo và workshop
- **Trang liên hệ** với form liên hệ và thông tin liên lạc
- **Responsive design** tương thích với mọi thiết bị
- **SEO tối ưu** với meta tags và structured data

## 🛠️ Công nghệ sử dụng

- **Hugo**: Static site generator
- **Wowchemy Research Group Theme**: Theme chuyên nghiệp cho nhóm nghiên cứu
- **Markdown**: Ngôn ngữ đánh dấu cho nội dung
- **YAML**: Cấu hình website
- **SCSS/CSS**: Tùy chỉnh giao diện
- **JavaScript**: Tương tác người dùng

## 📁 Cấu trúc dự án

```
ds_group_site/
├── content/                 # Nội dung website
│   ├── _index.md           # Trang chủ
│   ├── about/              # Trang về chúng tôi
│   ├── research/           # Trang nghiên cứu
│   ├── people/             # Trang đội ngũ
│   ├── contact/            # Trang liên hệ
│   ├── post/               # Blog tin tức
│   ├── publication/        # Công trình nghiên cứu
│   └── event/              # Sự kiện
├── config/                  # Cấu hình
│   └── _default/
│       ├── params.yaml     # Tham số website
│       └── menus.yaml      # Menu điều hướng
├── static/                  # Tài nguyên tĩnh
├── themes/                  # Theme Hugo
├── hugo.toml               # Cấu hình Hugo chính
└── README.md               # Hướng dẫn này
```

## 🚀 Cài đặt và chạy

### Yêu cầu hệ thống
- Hugo Extended version (>= 0.100.0)
- Git
- Node.js (>= 16.0.0)

### Bước 1: Clone dự án
```bash
git clone https://github.com/your-username/ds_group_site.git
cd ds_group_site
```

### Bước 2: Cài đặt theme
```bash
git submodule update --init --recursive
```

### Bước 3: Chạy website
```bash
hugo server -D
```

Website sẽ chạy tại: http://localhost:1313

## 📝 Cách sử dụng

### Thêm bài viết mới
```bash
hugo new post/tên-bài-viết/index.md
```

### Thêm trang mới
```bash
hugo new tên-trang/_index.md
```

### Thêm công trình nghiên cứu
```bash
hugo new publication/tên-công-trình/index.md
```

### Thêm sự kiện mới
```bash
hugo new event/tên-sự-kiện/index.md
```

### Thêm thành viên mới
```bash
hugo new authors/tên-thành-viên/_index.md
```

## 🎨 Tùy chỉnh giao diện

### Thay đổi màu sắc
Chỉnh sửa file `assets/scss/custom.scss`:
```scss
:root {
  --primary-color: #007bff;
  --secondary-color: #6c757d;
}
```

### Thay đổi font chữ
Chỉnh sửa file `config/_default/params.yaml`:
```yaml
appearance:
  font: custom
  font_size: L
```

### Thay đổi logo
Thay thế file `static/media/logo.png` với logo của bạn

## 📱 Responsive Design

Website được thiết kế responsive và tương thích với:
- Desktop (>= 1200px)
- Tablet (768px - 1199px)
- Mobile (< 768px)

## 🔍 SEO

Website được tối ưu SEO với:
- Meta tags tự động
- Structured data
- Sitemap XML
- Open Graph tags
- Twitter Cards

## 📊 Analytics

Tích hợp Google Analytics:
1. Thêm Google Analytics ID vào `config/_default/params.yaml`
2. Website sẽ tự động gửi dữ liệu analytics

## 🚀 Deploy

### Netlify
1. Kết nối repository với Netlify
2. Build command: `hugo`
3. Publish directory: `public`

### GitHub Pages
1. Tạo GitHub Actions workflow
2. Build và deploy tự động khi push code

### Vercel
1. Kết nối repository với Vercel
2. Framework preset: Hugo
3. Build command: `hugo`

## 🤝 Đóng góp

Chúng tôi chào đón mọi đóng góp từ cộng đồng:

1. Fork dự án
2. Tạo feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit thay đổi (`git commit -m 'Add some AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Tạo Pull Request

## 📄 Giấy phép

Dự án này được phân phối dưới giấy phép MIT. Xem file `LICENSE` để biết thêm chi tiết.

## 📞 Liên hệ

- **Website**: https://dsgroup.org
- **Email**: info@dsgroup.org
- **GitHub**: https://github.com/dsgroup-vn
- **LinkedIn**: https://linkedin.com/company/dsgroup-vn

## 🙏 Lời cảm ơn

Cảm ơn [Wowchemy](https://wowchemy.com/) đã cung cấp theme Research Group tuyệt vời này.

---

**DSGROUP - Định hình tương lai của Khoa học Dữ liệu tại Việt Nam**
