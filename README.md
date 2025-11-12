# 💻 HTML Practice Repository  

> 🚀 *A hands-on collection of HTML experiments — where every tag tells a story!*  

---

## 🌟 Overview  

Welcome to my **HTML Practice Repository** — a creative sandbox where I explore and demonstrate the power of **HTML5**.  
This repo is built to document my learning journey and to serve as a quick reference for anyone new to HTML.  

---

## 🧱 What’s Inside  

Here’s what you’ll find in this repository 👇  

- 🧩 **Basic Structure** — HTML boilerplate, document setup, and essential tags.  
- 📝 **Text Formatting** — headings, paragraphs, links, quotes, and more.  
- 🖼️ **Images & Figures** — how to use `<img>` and `<figure>` effectively.  
- 📋 **Lists & Tables** — organizing information beautifully.  
- 🎧 **Multimedia Elements** — embedding audio, video, and iframes.  
- 🧭 **Semantic HTML** — `<header>`, `<main>`, `<article>`, `<footer>`, etc.  
- 🧾 **Forms & Inputs** — learning how user interaction works.  

Each file focuses on **one HTML concept at a time**, making it super easy to learn, review, or reuse later.  

---

## 🧠 Learning Goals  

Through this repository, I aim to:  
✅ Strengthen my understanding of HTML5 fundamentals.  
✅ Write clean, semantic, and accessible code.  
✅ Build a foundation for upcoming **CSS** and **JavaScript** learning.  
✅ Share my journey so others can learn from it too!  

---

## 🖼️ Featured Project: Interactive Image Map

In this HTML exercise, I created an **interactive image map** where different areas of a single image lead to different links.

Clicking on the **laptop**, **mobile**, or **coffee cup** in the image below takes you to their respective shopping pages — all within one image!

```html
<img src="https://i.pinimg.com/736x/90/b3/5d/90b35dd180df0df48ea5c8e7666a7f1a.jpg" alt="Workplace Setup" usemap="#workplace">

 <img src="https://i.pinimg.com/736x/90/b3/5d/90b35dd180df0df48ea5c8e7666a7f1a.jpg" alt="Workplace Setup" usemap="#workplace">

<map name="workplace">
    <area shape="poly" coords="140,36,349,40,349,312,147,312" href="https://www.amazon.com/s?k=Laptop" target="_blank" alt="Laptop">
    <area shape="poly" coords="77,191,117,193,118,287,73,291" href="https://www.amazon.com/s?k=Cell+phone" target="_blank" alt="Mobile">
    <area target="_blank" alt="" title="" href="https://www.amazon.com/s?k=ceremic+coffee+cups&amp;crid=1YAK7XOM1M80K&amp;sprefix=ceramic+coffee+cups%2Caps%2C395&amp;ref=nb_sb_noss_1" coords="425,92,433,82,410,52,470,57,405,121,461,125,480,90,391,85,441,46,431,130" shape="poly">
    <area target="_blank" alt="" title="" href="https://www.amazon.com/s?k=Tablet&amp;crid=29066UK41HI8G&amp;sprefix=table%2Caps%2C644&amp;ref=nb_sb_noss_1" coords="378,304,494,154" shape="rect">
    <area target="_blank" alt="" title="" href="https://www.amazon.com/s?k=Indoor+Plant&amp;crid=3EQTMD6YMWNL&amp;sprefix=indoorplant%2Caps%2C393&amp;ref=nb_sb_noss_2" coords="80,41,101,137,112,45,76,129,96,41,81,72,78,83,110,92" shape="poly">

</map>
 
 

