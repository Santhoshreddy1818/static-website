
# 🌐 Static Website

This is a simple **HTML + CSS** static website hosted for free using **GitHub Pages**, and also deployed on an **EC2 instance** for demonstration purposes.

---

## 🚀 Live Site

You can view the live website here:  
🔗 [https://santhoshreddy1818.github.io/static-website/](https://santhoshreddy1818.github.io/static-website/)

---

## 📁 Project Structure

```
static-website/
├── index.html        # Main HTML page
├── styles.css        # Custom CSS styling
```

---

## 📦 Deployment

### ✅ GitHub Pages

This website is hosted via GitHub Pages:

1. Pushed `index.html` and `styles.css` to `main` branch
2. Enabled GitHub Pages from the repo settings
3. Selected the `main` branch as the source
4. GitHub provides a public URL for the website

### 🖥 EC2 Deployment

This website is also cloned and hosted on an EC2 instance:

```bash
# On EC2
cd /var/www/html
sudo git clone https://github.com/Santhoshreddy1818/static-website.git
```

Accessible from your EC2's public IP like:
```
http://<your-ec2-public-ip>/static-website/
```

---

## 🎨 Customization

- HTML structure in `index.html`
- CSS styling in `styles.css`
- You can expand with more pages like `about.html`, `contact.html`, etc.

---

## 📚 Learning Goal

> The goal of this project was to understand how to deploy static websites using GitHub Pages and mirror the same on an EC2 server.

---

## 🧑‍💻 Author

**Santhosh Reddy**  
🔗 [GitHub Profile](https://github.com/Santhoshreddy1818)
