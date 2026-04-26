# Hi there 👋 I'm Tom

I'm a web developer focused on privacy tools and automation. 

## 🛠 Featured Project: Temptom
**[Temptom](https://www.temptom.com/)** is a lightning-fast, anonymous temporary email service designed to protect your inbox from spam.

### Why I built it:
* **Zero Tracking:** Privacy-first approach with no registration.
* **Global Support:** Fully localized in 10+ languages.
* **High Performance:** Real-time email delivery with a clean, ad-free UI.

### 🚀 Quick Links:
- **Official Website:** [https://www.temptom.com/](https://www.temptom.com/)


---

### 💻 How to use (API Example):
```javascript
// Simple fetch example for Temptom-inspired logic
async function getTempMail() {
  const response = await fetch('[https://www.temptom.com/api/v1/generate](https://www.temptom.com/api/v1/generate)');
  const data = await response.json();
  console.log(`Your temporary email: ${data.email}`);
}
