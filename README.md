<h1 align="center">🐦 Twitter Clone</h1>
<p align="center">
  <b>A modern Twitter-like social media platform built with PHP & MySQL</b><br>
  <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square" />
  <img src="https://img.shields.io/badge/License-MIT-blue?style=flat-square" />
</p>



---

## 🚀 Tech Stack

<p align="center">
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white" />
  <img src="https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
</p>

---

## ✨ Features

- 📝 User registration & login
- 🐦 Post tweets (with images)
- ❤️ Like & 💬 comment on tweets
- 👥 Follow/unfollow users
- 👤 Edit profile and cover photo
- 🔔 Real-time notifications



## 📂 Project Structure

```
.
├── account.php
├── home.php
├── index.php
├── notification.php
├── profile.php
├── status.php
├── assets/
│   ├── css/
│   ├── images/
│   └── js/
├── controllar/
├── core/
├── includes/
├── twitter/
└── README.md
```

---

## ⚙️ Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/Youssef-Ahmed-k/Twitter.git
   ```
2. **Import the database**
   - Import the SQL file from the `twitter/` folder into your MySQL server.

3. **Configure database connection**
   - Edit `core/init.php` with your database credentials.

4. **Run the project**
   - Use XAMPP/WAMP and open `index.php` in your browser.

---

## 📝 Example: Image Upload

```php
// Upload profile image
$image = $_FILES['image'];
$v->rules('image', $image, ['image']);
if (empty($v->errors)) {
    $img = new \validation\Image('image', $image);
    $img->upload();
}
```

---

## 🤝 Contributors

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/Youssef-Ahmed-k">
        <img src="https://avatars.githubusercontent.com/u/000000?v=4" width="80;" alt=""/>
        <br /><sub><b>Youssef Ahmed</b></sub>
      </a>
    </td>
  </tr>
</table>

---

## 📧 Contact

For any questions or suggestions:<br>
[✉️ Email me](mailto:Youssefahmed8878@icloud.com)

---

<p align="center">
  <b>⭐️ If you like this project, please star the repo!</b
