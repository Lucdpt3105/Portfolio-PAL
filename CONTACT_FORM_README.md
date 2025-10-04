# 📧 Contact Form & GIF Update

## ✅ Đã hoàn thành:

### 1. **Thay thế ảnh Contact bằng GIF** 🎬
   - ✅ File: `Comp 1_1.gif` (thay thế v144_1179.png)
   - ✅ Max-width: 400px
   - ✅ Border-radius: 15px
   - ✅ Box shadow đẹp

### 2. **Thêm Contact Form hoàn chỉnh** 📝

#### **Tính năng:**
- ✅ Gửi email trực tiếp đến: **phunganhluc3105@gmail.com**
- ✅ Sử dụng FormSubmit.co (free, không cần backend)
- ✅ Auto-redirect đến trang Thank You sau khi gửi
- ✅ Không có CAPTCHA (tắt để UX tốt hơn)
- ✅ Custom email subject

#### **Các trường trong form:**
1. 📛 **Name** - Tên người gửi
2. 📧 **Email** - Email người gửi (để reply)
3. 🏷️ **Subject** - Tiêu đề
4. 💬 **Message** - Nội dung tin nhắn

### 3. **Design Form** 🎨

#### **Styling:**
- Background: Blur glass effect (rgba + backdrop-filter)
- Border: 1px solid với opacity
- Border-radius: 20px
- Padding: 40px
- Box shadow: 0px 10px 40px

#### **Input fields:**
- Background: Semi-transparent white
- Border: 2px solid rgba
- Focus: Glow effect với box-shadow
- Placeholder: Màu nhạt
- Icon: Font Awesome bên trái label

#### **Submit button:**
- Gradient background (purple)
- Full width
- Icon paper-plane
- Hover: translateY + shadow
- Transition mượt mà

### 4. **Thank You Page** 🎉
   - ✅ Tạo file: `thank-you.html`
   - ✅ Success icon với animation
   - ✅ Gradient text
   - ✅ Button quay về trang chủ
   - ✅ Social links

## 📧 **Cách hoạt động:**

### **FormSubmit.co Flow:**
```
1. User điền form → 2. Submit → 3. FormSubmit xử lý 
                                           ↓
4. Gửi email đến bạn ← 5. Redirect đến thank-you.html
```

### **Email bạn nhận được:**
```
From: FormSubmit
To: phunganhluc3105@gmail.com
Subject: New Portfolio Contact from Website!

Name: [Tên người gửi]
Email: [Email người gửi]
Subject: [Tiêu đề]
Message: [Nội dung]
```

## 🎨 **Form Design Details:**

### **Colors:**
- Background: rgba(255, 255, 255, 0.05)
- Border: rgba(255, 255, 255, 0.1)
- Input bg: rgba(255, 255, 255, 0.1)
- Input border: rgba(255, 255, 255, 0.2)
- Focus border: #667eea
- Button gradient: #667eea → #764ba2

### **Spacing:**
- Form padding: 40px
- Input padding: 15px 20px
- Margin between fields: 25px
- Border-radius: 10px (input), 30px (button)

### **Icons:**
- 👤 User icon (name)
- 📧 Envelope icon (email)
- 🏷️ Tag icon (subject)
- 💬 Comment icon (message)
- ✈️ Paper-plane icon (submit)

## 📱 **Responsive:**
- Mobile: padding giảm xuống 30px 20px
- Tablet: form full width
- Desktop: max-width 800px, center

## 🔧 **Configuration:**

### **FormSubmit Settings trong HTML:**
```html
<input type="hidden" name="_captcha" value="false">
<input type="hidden" name="_next" value="https://lucdpt3105.github.io/portfolio/thank-you.html">
<input type="hidden" name="_subject" value="New Portfolio Contact from Website!">
```

### **Lần đầu sử dụng:**
1. Deploy website lên GitHub Pages
2. Truy cập form và gửi 1 test message
3. Check email để confirm FormSubmit
4. Click link confirm trong email
5. Xong! Từ giờ mọi form submit đều gửi về email

## 🚀 **Next Steps khi deploy:**

1. **Push lên GitHub:**
   ```bash
   git add .
   git commit -m "Add contact form and GIF animation"
   git push origin main
   ```

2. **Enable GitHub Pages:**
   - Settings → Pages
   - Source: main branch
   - Save

3. **Cập nhật URL trong form:**
   - Đổi URL trong `_next` thành URL GitHub Pages của bạn
   - Format: `https://lucdpt3105.github.io/[repo-name]/thank-you.html`

4. **Test form:**
   - Gửi 1 message test
   - Confirm email từ FormSubmit
   - Done! 🎉

## 📂 **Files Updated:**

1. `index.html` - Thêm form và đổi GIF
2. `main.css` - Style cho form
3. `thank-you.html` - NEW: Thank you page
4. `images/Comp 1_1.gif` - NEW: GIF animation

## ✨ **Features:**

- ✅ No backend needed (FormSubmit handles everything)
- ✅ Free forever
- ✅ Spam protection
- ✅ Email notifications
- ✅ Custom redirect
- ✅ Beautiful UI
- ✅ Mobile responsive
- ✅ Smooth animations

---
**Updated:** October 4, 2025  
**Status:** ✅ Ready to deploy!
