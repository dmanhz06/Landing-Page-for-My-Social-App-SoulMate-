# 📱 Dmanhz Social App (SoulMate) - Mobile Social Network

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Android-brightgreen?style=for-the-badge&logo=android" alt="Platform Android">
  <img src="https://img.shields.io/badge/Language-Java%20%2F%20Kotlin-orange?style=for-the-badge&logo=kotlin" alt="Languages">
  <img src="https://img.shields.io/badge/Backend-Firebase-ffca28?style=for-the-badge&logo=firebase" alt="Backend Firebase">
</p>

**Dmanhz Social App (SoulMate)** là một ứng dụng mạng xã hội di động hiện đại, kết hợp độc đáo giữa việc kết nối cộng đồng, không gian nghe nhạc thư giãn và góc viết nhật ký chia sẻ cảm xúc cá nhân. Dự án được tích hợp các dịch vụ đám mây tiên tiến, hệ thống quản lý dữ liệu thời gian thực và giải pháp thông báo đẩy thông minh nhằm tối ưu hóa trải nghiệm tương tác của người dùng.

---

### 🌐 Web giới thiệu sản phẩm App 

> [!TIP]
> **Khám phá, tìm hiểu SoulMate ngay trên trình duyệt!**  
> Để xem chi tiết các tính năng, hình ảnh trực quan sinh động và toàn bộ giao diện tương tác mượt mà của ứng dụng, hãy truy cập ngay phiên bản Landing Page chính thức tại đường dẫn dưới đây:
>
> 🔗 **[Ghé thăm SoulMate Web Landing Page](https://dmanhz06.github.io/Landing-Page-for-My-Social-App-SoulMate-/)**

---

### 🚀 Tính Năng Nổi Bật

- 🔐 **Xác Thực An Toàn:** Đăng ký, đăng nhập và bảo mật thông tin tài khoản thông qua **Firebase Authentication** (Hỗ trợ Đăng nhập bằng Google, Facebook).
- 💬 **Tương Tác Thời Gian Thực:** Cập nhật bảng tin (feed), tương tác thả cảm xúc, bình luận, tải ảnh và trò chuyện tức thời nhờ sức mạnh của **Firebase Realtime Database / Firestore**.
- 🎵 **Social Music & Diary:** Không gian cá nhân cho phép người dùng vừa nghe nhạc giải trí từ hệ thống, vừa viết nhật ký lưu trữ những mảnh ghép cảm xúc hàng ngày.
- 🎙️ **Ghi Âm Nhật Ký (Audio Journal):** Tự động ghi âm, nhận diện giọng nói và chuyển đổi nội dung hội thoại thành nhật ký văn bản hoặc lưu trữ trạng thái nhanh chóng theo thời gian thực.
- 🌓 **Chuyển Đổi Giao Diện (Dark Mode):** Linh hoạt thay đổi giữa chế độ Sáng (Light Mode) và Tối (Dark Mode) dựa trên hệ thống **Theme Management**, giúp tối ưu hóa trải nghiệm thị giác và tiết kiệm pin cho thiết bị.
- 🔔 **Thông Báo Đẩy (Push Notifications):** Tích hợp dịch vụ **OneSignal** gửi thông báo tức thì về hoạt động tương tác, tin nhắn mới, duy trì kết nối liên tục.
- ☁️ **Tối Ưu Hóa Media:** Sử dụng **Cloudinary** để lưu trữ, truyền tải hình ảnh và file âm thanh chất lượng cao với tốc độ tối ưu.

---

### 🛠️ Công Nghệ Sử Dụng (Tech Stack)

- **Frontend:** Java / Kotlin (Android SDK)
- **IDE:** Android Studio
- **Backend & Cloud Services:**
  - **Firebase:** Authentication, Realtime Database, Cloud Functions, Firestore.
  - **OneSignal:** Giải pháp gửi thông báo đẩy (Push Notifications).
  - **Cloudinary:** Quản lý và lưu trữ dữ liệu truyền thông (Cloud Storage).
- **Kiến trúc:** MVVM (Model-View-ViewModel) đảm bảo mã nguồn sạch, dễ bảo trì và mở rộng.

---

### 📸 Hình Ảnh Giao Diện (Screenshots)

#### 🔐 1. Xác Thực Hệ Thống (Authentication)
*Hỗ trợ phương thức đăng nhập truyền thống và tích hợp tài khoản mạng xã hội (Google, Facebook).*

| Màn hình Đăng ký | Màn hình Đăng nhập |
| :---: | :---: |
| <img src="https://raw.githubusercontent.com/dmanhz06/Landing-Page-for-My-Social-App-SoulMate-/main/screenshots/signup.png" width="260" alt="Sign Up"> | <img src="https://raw.githubusercontent.com/dmanhz06/Landing-Page-for-My-Social-App-SoulMate-/main/screenshots/login.png" width="260" alt="Log In"> |

#### 🌐 2. Trang Chủ & Bảng Tin Tương Tác (Home & Feeds)
*Nơi cập nhật dòng trạng thái, chia sẻ hình ảnh, tải đa phương tiện và không gian tương tác bình luận của cộng đồng.*

| Trang chủ (Home) | Bảng tin (Feeds 1) | Bảng tin (Feeds 2) |
| :---: | :---: | :---: |
| <img src="https://raw.githubusercontent.com/dmanhz06/Landing-Page-for-My-Social-App-SoulMate-/main/screenshots/home.jpg" width="220" alt="Home"> | <img src="https://raw.githubusercontent.com/dmanhz06/Landing-Page-for-My-Social-App-SoulMate-/main/screenshots/feeds1.jpg" width="220" alt="Feeds 1"> | <img src="https://raw.githubusercontent.com/dmanhz06/Landing-Page-for-My-Social-App-SoulMate-/main/screenshots/feeds2.jpg" width="220" alt="Feeds 2"> |

| Tương tác bình luận | Tải ảnh từ bài đăng |
| :---: | :---: |
| <img src="https://raw.githubusercontent.com/dmanhz06/Landing-Page-for-My-Social-App-SoulMate-/main/screenshots/comment_feeds.jpg" width="220" alt="Comment"> | <img src="https://raw.githubusercontent.com/dmanhz06/Landing-Page-for-My-Social-App-SoulMate-/main/screenshots/download_img_feeds.jpg" width="220" alt="Download Media"> |

#### 🎵 3. Góc Tâm Trạng & Âm Nhạc (Music & Journal)
*Không gian thư giãn kết hợp trình phát nhạc trực tuyến và trình quản lý nhật ký cảm xúc theo hai chế độ giao diện sáng/tối.*

| Trình phát nhạc (Music) | Viết nhật ký mới | Nhật ký (Chế độ Tối) | Nhật ký (Chế độ Sáng) |
| :---: | :---: | :---: | :---: |
| <img src="https://raw.githubusercontent.com/dmanhz06/Landing-Page-for-My-Social-App-SoulMate-/main/screenshots/music.jpg" width="180" alt="Music Player"> | <img src="https://raw.githubusercontent.com/dmanhz06/Landing-Page-for-My-Social-App-SoulMate-/main/screenshots/nhatky.jpg" width="180" alt="Write Journal"> | <img src="https://raw.githubusercontent.com/dmanhz06/Landing-Page-for-My-Social-App-SoulMate-/main/screenshots/journal_darkmode.jpg" width="180" alt="Journal Dark"> | <img src="https://raw.githubusercontent.com/dmanhz06/Landing-Page-for-My-Social-App-SoulMate-/main/screenshots/journal_lightmode.jpg" width="180" alt="Journal Light"> |

#### 🎙️ 4. Tính Năng Ghi Âm Nhật Ký (Audio Journal)
*Luồng tính năng tương tác bằng giọng nói: Bắt đầu, ghi âm thời gian thực, xác nhận gửi và đồng bộ hóa vào hệ thống nhật ký.*

| Giao diện Sẵn sàng | Đang Ghi âm (Live) | Nhấn/Vuốt gửi dữ liệu | Đồng bộ thành công |
| :---: | :---: | :---: | :---: |
| <img src="https://raw.githubusercontent.com/dmanhz06/Landing-Page-for-My-Social-App-SoulMate-/main/screenshots/start_mic.jpg" width="180" alt="Start Mic"> | <img src="https://raw.githubusercontent.com/dmanhz06/Landing-Page-for-My-Social-App-SoulMate-/main/screenshots/record_mic.jpg" width="180" alt="Recording"> | <img src="https://raw.githubusercontent.com/dmanhz06/Landing-Page-for-My-Social-App-SoulMate-/main/screenshots/nhan_mic.jpg" width="180" alt="Action Mic"> | <img src="https://raw.githubusercontent.com/dmanhz06/Landing-Page-for-My-Social-App-SoulMate-/main/screenshots/send_mic.jpg" width="180" alt="Send Success"> |

#### 💬 5. Trò Chuyện Thời Gian Thực & Thông Báo (Realtime Chat & Notifications)
*Hệ thống tin nhắn tức thời, quản lý cuộc hội thoại, xem thông tin bạn bè và trung tâm nhận thông báo đẩy.*

| Danh sách cuộc trò chuyện | Hộp thoại nhắn tin 1 | Hộp thoại nhắn tin 2 |
| :---: | :---: | :---: |
| <img src="https://raw.githubusercontent.com/dmanhz06/Landing-Page-for-My-Social-App-SoulMate-/main/screenshots/chat_all.jpg" width="220" alt="Chat List"> | <img src="https://raw.githubusercontent.com/dmanhz06/Landing-Page-for-My-Social-App-SoulMate-/main/screenshots/chat1.jpg" width="220" alt="Chat 1"> | <img src="https://raw.githubusercontent.com/dmanhz06/Landing-Page-for-My-Social-App-SoulMate-/main/screenshots/chat2.jpg" width="220" alt="Chat 2"> |

| Tùy chọn cuộc trò chuyện | Hồ sơ bạn bè (Other Profile) | Thông báo đẩy (Push) |
| :---: | :---: | :---: |
| <img src="https://raw.githubusercontent.com/dmanhz06/Landing-Page-for-My-Social-App-SoulMate-/main/screenshots/user_chat.jpg" width="220" alt="User Chat Ops"> | <img src="https://raw.githubusercontent.com/dmanhz06/Landing-Page-for-My-Social-App-SoulMate-/main/screenshots/other_profile.jpg" width="220" alt="Other Profile"> | <img src="https://raw.githubusercontent.com/dmanhz06/Landing-Page-for-My-Social-App-SoulMate-/main/screenshots/push_notifi.jpg" width="220" alt="Push Notification"> |

#### ⚙️ 6. Quản Lý Tài Khoản & Cài Đặt (Profile & Settings)
*Thiết lập thông tin cá nhân, liên kết mạng xã hội, tùy chỉnh Theme (Dark Mode) và bảo mật quyền riêng tư.*

| Trang cá nhân | Chỉnh sửa hồ sơ 1 | Chỉnh sửa hồ sơ 2 |
| :---: | :---: | :---: |
| <img src="https://raw.githubusercontent.com/dmanhz06/Landing-Page-for-My-Social-App-SoulMate-/main/screenshots/user_profile.jpg" width="220" alt="User Profile"> | <img src="https://raw.githubusercontent.com/dmanhz06/Landing-Page-for-My-Social-App-SoulMate-/main/screenshots/edit_profile.jpg" width="220" alt="Edit Profile 1"> | <img src="https://raw.githubusercontent.com/dmanhz06/Landing-Page-for-My-Social-App-SoulMate-/main/screenshots/edit_profile2.jpg" width="220" alt="Edit Profile 2"> |

| Cài đặt chung | Cài đặt liên hệ | Bảo mật & Quyền riêng tư |
| :---: | :---: | :---: |
| <img src="https://raw.githubusercontent.com/dmanhz06/Landing-Page-for-My-Social-App-SoulMate-/main/screenshots/setting.jpg" width="220" alt="Settings 1"> | <img src="https://raw.githubusercontent.com/dmanhz06/Landing-Page-for-My-Social-App-SoulMate-/main/screenshots/setting2.jpg" width="220" alt="Settings 2"> | <img src="https://raw.githubusercontent.com/dmanhz06/Landing-Page-for-My-Social-App-SoulMate-/main/screenshots/privacy_setting.jpg" width="220" alt="Privacy Settings"> |

---

### 📦 Cài Đặt Dự Án (Installation & Setup)

Để chạy thử nghiệm hoặc phát triển tiếp dự án này trên máy cục bộ của bạn, hãy làm theo các bước sau:

1. **Clone repository này về máy:**
```bash
   git clone [https://github.com/dmanhz06/Dmanhz_Social_App.git](https://github.com/dmanhz06/Dmanhz_Social_App.git)
   cd Dmanhz_Social_App
