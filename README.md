# Hey, I'm Kapish 👋

**2nd year CSE @ VIT Vellore · Founder of OneCart · Building real things**

I don't wait until graduation to ship. I build production systems that real people depend on, right now.

---

## 🛒 OneCart — What I'm Built

A multi-outlet campus food delivery platform live at VIT. Users order from multiple outlets in one checkout, one payment, one delivery — something Swiggy and Zomato structurally can't do.

**The real insight:** 7.5 million street food vendors in India are locked out of existing platforms because they need zero tech to operate. OneCart onboards them with PDF menus and free-text ordering. Zero tech requirement on the vendor side is the moat.

**What's live:**
- React Native customer app — outlet selection, multi-cart, Razorpay payments, real-time order tracking
- React Native delivery partner app — order acceptance, earnings tracking, push notifications
- Vite React admin dashboard — live orders, analytics, payout tracker with UPI QR codes per partner
- Node.js + Express + MongoDB REST API — deployed on Render, processing real transactions

**Real engineering problems solved in production:**
- Atomic order acceptance via MongoDB `findOneAndUpdate` — prevents two delivery partners from accepting the same order simultaneously
- Razorpay payment verification with HMAC-SHA256 signature — cryptographic proof that payment is real before order status updates
- Push notifications on Android via Firebase + Expo — hours of `metadata.bin` corruption and Gradle issues to get this working
- Email provider migration mid-production — Gmail SMTP timed out on Render, Resend had sandbox limits, migrated to Brevo API
- Delivery cancellation race condition — local state was clearing before server confirmation, fixed by only clearing after confirmed 200

→ **[github.com/kapish-18/ONECART](https://github.com/kapish-18/ONECART)**

---

## 🛠️ Tech Stack

**Mobile:** React Native (Expo), Expo Notifications, AsyncStorage, React Navigation

**Frontend:** Vite React, TailwindCSS

**Backend:** Node.js, Express.js, MongoDB + Mongoose, REST API

**Payments & Auth:** Razorpay (live), HMAC-SHA256 verification, OTP auth via Brevo

**Infrastructure:** MongoDB Atlas, Render, Firebase (FCM), EAS Build

**Languages:** JavaScript, TypeScript, C++

**Other:** Git, GitHub, Python (NumPy, Pandas, scikit-learn)

---

## 📊 GitHub Stats

![](https://github-readme-stats.vercel.app/api?username=kapish-18&theme=dark&hide_border=true&include_all_commits=false&count_private=false)
![](https://nirzak-streak-stats.vercel.app/?user=kapish-18&theme=dark&hide_border=true)
![](https://github-readme-stats.vercel.app/api/top-langs/?username=kapish-18&theme=dark&hide_border=true&include_all_commits=false&count_private=false&layout=compact)

---

## 🌐 Find Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/kapish-tickoo)
[![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:kapishtickoo.dev@gmail.com)

---

*"The best way to learn systems is to build one that real people depend on."*
