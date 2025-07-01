# Fares Adda Portfolio - Next.js

A modern, responsive personal portfolio website built with [Next.js](https://nextjs.org/). This project showcases the work, skills, and services of **Fares Adda** (Full Stack Developer & Tech Consultant), and provides an easy way for clients and collaborators to get in touch.

---

## 🚀 Live Demo
[https://faresadda.vercel.app](https://faresadda.vercel.app)

---

## ✨ Features
- Clean, modern, and fully responsive design
- About, Projects, Services, and Skills sections
- Downloadable CV
- Contact form with email notifications (user & admin)
- Social media links
- Professional email templates
- Dark footer with copyright

---

## 📬 Contact & Social Links
- **Email:** [faresadda2001@gmail.com](mailto:faresadda2001@gmail.com)
- **Phone:** [(+213) 560-869-608](tel:+213560869608)
- **Location:** [Boumerdes, Algeria](https://maps.app.goo.gl/yrrucr9uNBRrrTzMA)
- **LinkedIn:** [linkedin.com/in/faresadda](https://linkedin.com/in/faresadda)
- **GitHub:** [github.com/faresadda](https://github.com/faresadda)
- **Upwork:** [upwork.com/freelancers/~01eb480f5c441bf58d](https://upwork.com/freelancers/~01eb480f5c441bf58d)
- **Facebook:** [facebook.com/profile.php?id=61571967693139](https://facebook.com/profile.php?id=61571967693139)
- **Instagram:** [instagram.com/faresaddadev](https://instagram.com/faresaddadev)
- **TikTok:** [tiktok.com/@faresaddadev](https://tiktok.com/@faresaddadev)

---

## 🛠️ Getting Started

### Prerequisites
- Node.js 18+
- An SMTP email account for sending messages

### Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/faresadda/nextjs-portfolio.git
   cd nextjs-portfolio
   ```
2. **Install dependencies:**
   ```bash
   npm install
   ```
3. **Configure environment variables:**
   Create a `.env.local` file in the root directory:
   ```env
   EMAIL_HOST=smtp.example.com
   EMAIL_PORT=465
   EMAIL_USER=your@email.com
   EMAIL_PASSWORD=your_email_password
   ADMIN_EMAIL=admin@email.com
   ```
4. **Run the development server:**
   ```bash
   npm run dev
   ```
   Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 📁 Project Structure
```
nextjs/
  app/
    api/contact/route.js      # Contact form API
    components/               # UI components
    context/                  # Data context
    functions/                # Helper functions
    utils/sendEmail.js        # Email logic
    ...
  public/                     # Static files & images
  package.json                # Dependencies
  README.md                   # Project info
```

---

## 📝 Notes
- Make sure your email credentials are correct in `.env.local`.
- Do **not** commit sensitive data to public repositories.
- For any questions or collaboration, feel free to contact me via [email](mailto:faresadda2001@gmail.com) or [LinkedIn](https://linkedin.com/in/faresadda).

---

**Developed by Fares Adda**
