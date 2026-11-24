# طرح مرحله‌بندی MG v2
## فاز ۱: اسکلت
- [ ] راه‌اندازی Electron با یک پنجره ساده
- [ ] بیلد موفق روی سه سیستم‌عامل با GitHub Actions
- [ ] انتشار خودکار در Releases
- [ ] ساخت فایل های README
- [ ] انتشار نسخه برای mac, windows, android,IOS
- [ ] نسخه ی android و IOS با expo
## فاز ۲: مرورگر پایه
- [ ] تب‌ها
- [ ] نوار آدرس + جستجو در Google
- [ ] عقب/جلو/رفرش
- [ ] صفحه خانه سفارشی
- [ ] و تمام قابلیت های گوگل(تاکید می کنم)
- [ ] 9 موتور جستجو
- [ ] ظاهری مدرن
## فاز ۳: امکانات روزمره
- [ ] تاریخچه و بوکمارک
- [ ] دانلودها
- [ ] میانبرهای Mail / Docs / Drive
- [ ] تمام قابلیت های روزمره ی گوگل(تاکید می کنم)
## فاز ۴: پیشرفته
- [ ] دیتابیس PostgreSQL
- [ ] هوش مصنوعی داخلی
- [ ] پشتیبانی از افزونه‌ها (بررسی محدودیت‌های Electron)
## فاز ۵: انتشار
- [ ] سایت معرفی روی GitHub Pages
- [ ] ثبت لایسنس‌ها
# MG v2 Development 

## Phase 1: Foundation
- [ ] Set up Electron with a simple window
- [ ] Successfully build for all three desktop operating systems using GitHub Actions
- [ ] Automatically publish builds to GitHub Releases
- [ ] Create README files
- [ ] Release versions for macOS, Windows, Android, and iOS
- [ ] Build Android and iOS versions using Expo

## Phase 2: Core Browser
- [ ] Tab management
- [ ] Address bar + Google Search integration
- [ ] Back / Forward / Refresh navigation
- [ ] Custom homepage
- [ ] All Google features (I emphasize ALL of them)
- [ ] 9 search engines
- [ ] Modern UI design

## Phase 3: Everyday Features
- [ ] History and bookmarks
- [ ] Downloads manager
- [ ] Shortcuts for Mail / Docs / Drive
- [ ] All everyday Google features (I emphasize ALL of them)

## Phase 4: Advanced Features
- [ ] PostgreSQL database integration
- [ ] Built-in AI
- [ ] Extension support (investigate Electron limitations)

## Phase 5: Release
- [ ] Create a product landing page using GitHub Pages
- [ ] Register and document all licenses
---
# Development Rules for Claude Code

## 1. General Rules
- Always inspect the existing project before making changes.
- Preserve the existing project structure whenever possible.
- Never delete or overwrite working features without a valid reason.
- Write clean, modular, maintainable, and scalable code.
- Avoid unnecessary dependencies.
- Prioritize performance, stability, security, and user experience.
- Never use fake buttons or non-functional features.
- Never mark incomplete features as completed.

## 2. Cross-Platform Development
- Desktop: Electron.
- Android and iOS: React Native with Expo.
- Ensure platform-specific compatibility.
- Share code between platforms whenever practical.
- Maintain a consistent user experience across all platforms.

## 3. Browser Functionality
MG Browser must aim to provide a complete modern browsing experience.

Important requirements:
- Fully functional tab management.
- Address bar and navigation.
- Nine search engines.
- Customizable homepage.
- History and bookmarks.
- Download management.
- Modern settings and preferences.
- Dark and light themes.
- Google services integration.

## 4. Google Integration
Google ecosystem compatibility is a major priority.

Investigate and integrate relevant Google services, including:
- Google Search
- Google Accounts
- Gmail
- Google Drive
- Google Docs
- Google Maps
- Google Translate
- Google Calendar

Use official APIs and supported integration methods where available. Respect Google's terms, authentication requirements, and licensing.

## 5. Architecture
- Keep frontend and backend responsibilities separated.
- Use PostgreSQL
  
## 6. Screenshots and Visual Documentation
- Capture real screenshots of the MG Browser application on both desktop (PC) and mobile devices (Android and iOS).
- Screenshots must show the actual running application, not mockups or concept designs.
- Capture screenshots of important screens, features, and user interfaces.
- Use high-quality screenshots with appropriate resolution.
- Save screenshots inside a dedicated `screenshots/` directory in the repository.
- Organize screenshots into separate `desktop/` and `mobile/` folders.
- Include screenshots in the project's README files to demonstrate the actual application.
- Update screenshots whenever major UI changes are made.
- Never use screenshots from other browsers or unrelated applications.
- If a platform is not available for testing, clearly indicate that its screenshots are pending.
- Do not fabricate screenshots or present unfinished interfaces as completed features.

**The goal is to visually document MG Browser on both PC and mobile throughout development.**
