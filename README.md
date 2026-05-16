# 🔥 Lilith Temple — Security & Performance Case Study

## 🔗 Live Project
https://www.lilithtemple.com

---

## 🧠 About the Project

**Lilith Temple** is a frontend-heavy artistic web experience focused on:

- immersive visuals  
- atmospheric storytelling  
- video and audio interaction  

This case study analyzes:

- 🔐 Security configuration  
- ⚡ Performance optimization  

---

## 🎯 Objective

The goal was to evaluate:

- How secure a static Netlify-based application is  
- How a media-heavy project performs after optimization  

---

## 🔍 Key Findings

- No critical security issues detected (static architecture)
- Security headers properly configured via Netlify
- Significant performance improvement after optimization (~460MB → ~70MB)
- Fast and stable rendering behavior

---

## 🔐 Security Analysis

Key checks:

- HTTP security headers  
- CDN configuration (Netlify)  
- Resource exposure  
- Client-side behavior  

📄 Full report:  
👉 [Full Security Report](./reports/security-report.md)

---

## ⚡ Performance Optimization

Focus:

- Load speed  
- Media optimization
- Rendering behavior
- Network efficiency

📄 Full report:  
👉 [Full Performance Report](./reports/performance-report.md)

---

## 📸 Screenshots

### Performance

- Summary metrics  
- Waterfall analysis  
- Optimization score  
- Network requests  

### Security

- HTTP headers (curl)  
- Burp Suite analysis  
- Request inspection  

---

## 🛠 Tech Stack

- HTML / CSS / JavaScript  
- Netlify (CDN & hosting)  
- WebPageTest  
- Burp Suite  
- curl  

---

## 💡 Key Takeaways

- Static architecture reduces attack surface  
- CDN improves performance and delivery  
- Media-heavy apps can be optimized effectively  
- Security headers are critical even for static sites  

---

## 📉 Results

- Site size reduced: **~460 MB → ~70 MB**  
- Fast rendering (FCP < 1s)  
- Stable layout (low CLS)  
- Minimal requests  

---

## 👩‍💻 Author

Tetiana Trunova  

Aspiring Application Security / Pentester  

---

## ⚠️ Note

This project was created as a **technical and creative experiment**, combining:

- frontend development  
- security awareness  
- performance engineering  

---


## 🛡️ Conclusion

The application demonstrates a low attack surface due to its static architecture.

Key strengths:
- Proper CDN usage (Netlify)
- No dynamic backend exposure
- Clean request structure

Recommendation:
- Maintain strict header configuration
- Monitor asset exposure in future updates
