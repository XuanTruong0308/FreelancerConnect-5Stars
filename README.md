# FreeLancerConnect - Nền tảng kết nối Freelancer và Khách hàng

## Giới thiệu

FreeLancerConnect là một trang web hoàn chỉnh được xây dựng bằng Bootstrap 5, cung cấp nền tảng kết nối giữa freelancer và khách hàng tại Việt Nam.

## Cấu trúc trang web

### 🏠 Trang chính

- **index.html** - Trang chủ với hero section, tính năng nổi bật, thống kê, và testimonials
- **about.html** - Giới thiệu về công ty, sứ mệnh, tầm nhìn, timeline phát triển
- **community.html** - Cộng đồng với forum thảo luận, thống kê, và trending topics
- **featured.html** - Freelancer và dự án nổi bật với filter và search
- **login.html** - Trang đăng nhập với form validation và social login
- **register.html** - Trang đăng ký với account type selection và form validation

## 🎨 Thiết kế & Tính năng

### Bootstrap Components được sử dụng:

- **Navigation** - Responsive navbar với dropdown menu
- **Cards** - Profile cards, project cards, discussion cards
- **Forms** - Login/register forms với validation
- **Modals** - (Có thể thêm cho các tính năng tương tác)
- **Buttons** - Custom styled buttons với hover effects
- **Alerts** - Notification system
- **Progress bars** - Password strength indicator

### Tính năng JavaScript:

- **Smooth scrolling** - Cuộn mượt khi click anchor links
- **Animation on scroll** - Cards xuất hiện với animation khi scroll
- **Counter animation** - Số liệu thống kê tăng dần
- **Form validation** - Real-time validation cho forms
- **Password strength checker** - Kiểm tra độ mạnh mật khẩu
- **Account type toggle** - Chuyển đổi form dựa trên loại tài khoản
- **Back to top button** - Nút cuộn lên đầu trang
- **Responsive navbar** - Navigation thay đổi khi scroll

## 🎯 Responsive Design

- **Desktop** (>= 992px) - Layout đầy đủ với sidebar và multi-column
- **Tablet** (768px - 991px) - Layout 2 cột, navigation thu gọn
- **Mobile** (< 768px) - Single column, hamburger menu

## 📁 Cấu trúc thư mục

```
UI/
├── css/
│   └── style.css          # Custom CSS styles
├── js/
│   └── main.js           # Custom JavaScript
├── images/               # Placeholder cho hình ảnh
├── index.html           # Trang chủ
├── about.html           # Giới thiệu
├── community.html       # Cộng đồng
├── featured.html        # Nổi bật
├── login.html           # Đăng nhập
├── register.html        # Đăng ký
└── README.md           # Tài liệu hướng dẫn
```

## 🚀 Cách sử dụng

### 1. Mở trực tiếp trong browser

```bash
# Mở file index.html trong trình duyệt web
start index.html  # Windows
open index.html   # macOS
```

### 2. Sử dụng Live Server (VS Code)

- Cài đặt extension "Live Server" trong VS Code
- Right-click vào `index.html` → "Open with Live Server"

### 3. Sử dụng local web server

```bash
# Python
python -m http.server 8000

# Node.js (npx)
npx serve .

# PHP
php -S localhost:8000
```

## 🎨 Customization

### Thay đổi màu sắc chủ đạo:

Chỉnh sửa CSS variables trong `css/style.css`:

```css
:root {
  --primary-color: #007bff; /* Màu chính */
  --secondary-color: #6c757d; /* Màu phụ */
  --success-color: #28a745; /* Màu thành công */
  /* ... */
}
```

### Thêm hình ảnh:

- Thay thế các placeholder URLs trong HTML
- Đặt hình ảnh thật vào thư mục `images/`
- Cập nhật đường dẫn trong các file HTML

### Tùy chỉnh nội dung:

- Chỉnh sửa text trong các file HTML
- Thêm/xóa sections theo nhu cầu
- Cập nhật thông tin liên hệ, social media links

## 📱 Tính năng nổi bật

### Trang chủ (index.html):

- Hero section với call-to-action
- Features showcase với icons
- Statistics counter với animation
- Popular categories
- Customer testimonials
- Newsletter signup

### Trang giới thiệu (about.html):

- Company mission & vision
- Timeline phát triển
- Team member profiles
- Core values
- Contact information

### Trang cộng đồng (community.html):

- Community statistics
- Discussion categories
- Recent discussions with user avatars
- Trending topics sidebar
- Top contributors
- Upcoming events

### Trang nổi bật (featured.html):

- Featured freelancer profiles với ratings
- Successful project showcases
- Filter và sort options
- Success stories
- Skill tags và categories

### Trang đăng nhập (login.html):

- Clean, modern login form
- Password visibility toggle
- Remember me option
- Social login buttons
- Responsive design

### Trang đăng ký (register.html):

- Account type selection (Freelancer/Client)
- Dynamic form fields based on account type
- Password strength indicator
- Terms & conditions checkbox
- Real-time form validation

## 🔧 Công nghệ sử dụng

- **HTML5** - Semantic markup
- **CSS3** - Custom styles với CSS Variables
- **Bootstrap 5.3.2** - Responsive framework
- **Font Awesome 6.0** - Icons
- **Vanilla JavaScript** - Custom interactions
- **Google Fonts** - Typography (có thể thêm)

## 📈 Performance

### Optimization đã áp dụng:

- CSS và JS được minify từ CDN
- Images sử dụng placeholder nhẹ
- Lazy loading cho animations
- Debounce cho search functionality
- Intersection Observer API cho scroll animations

### SEO-friendly:

- Semantic HTML structure
- Meta tags cơ bản
- Alt attributes cho images
- Proper heading hierarchy
- Clean URLs structure

## 🌟 Tính năng có thể mở rộng

### Frontend:

- Thêm dark mode toggle
- Multi-language support
- Advanced search với filters
- Real-time chat system
- File upload functionality
- Calendar integration cho events

### Backend integration:

- User authentication system
- Database integration
- API endpoints
- Payment gateway integration
- Email notification system
- Admin dashboard

## 📞 Hỗ trợ

Nếu có câu hỏi hoặc cần hỗ trợ:

- Email: boiznews.fpoly@gmail.com
- Phone: +84 (039) 9760 075

## 📄 License

Dự án này được phát triển cho mục đích học tập và demo. Vui lòng tuân thủ các điều khoản sử dụng của Bootstrap và Font Awesome khi sử dụng trong dự án thương mại.
