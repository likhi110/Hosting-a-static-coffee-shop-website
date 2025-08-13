# ☕ Café Bliss – Static Website Hosting on AWS S3

This project is a **static coffee shop website** designed for hosting on **Amazon S3**.  
It’s a simple, responsive, and elegant website for a fictional coffee shop called **Café Bliss**.

---

## 📌 Features
- **Responsive Design** – Works on desktop, tablet, and mobile
- **Multi-Section Layout** – Home, Menu, About, and Contact
- **Custom Styling** – Modern, coffee-inspired color palette
- **Static Hosting** – Perfect for AWS S3 deployment

---

## 🛠️ Technologies Used
- **HTML5**
- **CSS3**
- **AWS S3** (for hosting)

---

## 📂 Project Structure

coffee-shop/
│
├── index.html # Main HTML file
├── style.css # Styling file
└── README.md # Project documentation


---

## 🚀 How to Host on AWS S3

1. **Create an S3 Bucket**
   - Go to AWS Management Console → S3 → Create bucket
   - Give it a unique name (e.g., `cafe-bliss-website`)
   - Choose a region and uncheck "Block all public access"  
     *(for public website hosting)*

2. **Upload Website Files**
   - Upload `index.html` and `style.css` to your bucket

3. **Enable Static Website Hosting**
   - Go to **Properties** → Enable **Static website hosting**
   - Set **index document** as `index.html`

4. **Set Permissions**
   - Go to **Permissions** → **Bucket policy** and allow public read access  
   *(only if hosting a public website)*

5. **Access Your Website**
   - Copy the **endpoint URL** provided in Static Website Hosting settings
   - Open it in your browser

## 📷 Preview

**Home**
<img width="951" height="377" alt="image" src="https://github.com/user-attachments/assets/5f00eaa3-704e-4e9e-a3bf-207441a2c25c" />

**Menu**
<img width="1897" height="421" alt="image" src="https://github.com/user-attachments/assets/b109c8ff-b833-4dbf-bed2-e367d2bf469c" />

**About & Contact**
<img width="1892" height="811" alt="image" src="https://github.com/user-attachments/assets/2bb54830-6cf3-4941-bb4c-da27f7066742" />
