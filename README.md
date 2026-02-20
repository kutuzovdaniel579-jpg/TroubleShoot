# 🚨 TroubleShooter

TroubleShooter is a lightweight, dynamic error page that automatically displays information based on URL parameters.  
The page supports multiple languages and can be used for websites that are under development, temporarily offline, or require custom error messages.

---

## ✨ Features

- Dynamic error codes via URL parameters  
- Multi‑language support (EN, NL, FR)  
- Automatic language selection using `?lang=`  
- Custom title, description, and owner fields  
- Fully client‑side (no backend required)  
- Works seamlessly on GitHub Pages

---

## 🔗 URL Structure

Use the following structure to display dynamic error messages:
`https://kutuzovdaniel579-jpg.github.io/TroubleShoot/?lang=XXX?error_code=XXX?title=XXX?description=XXX?owner=XXX`

> [!TIP]
> By using `%20` u can create an spacing between words.

> [!WARNING]
> We only included 3 translations (English,Dutch,French)

## 🧩 Supported Parameters

| Parameter      | Description                          | Example              |
|----------------|--------------------------------------|----------------------|
| `lang`         | Language of the error page           | `en`, `nl`, `fr`     |
| `error_code`   | Error code to display                | `404`                |
| `title`        | Custom title                         | `Site Down`          |
| `description`  | Custom description                   | `Server offline`     |
| `owner`        | Name of the reporter/owner           | `FoL`             |


---

## 🛠 Technologies Used

- HTML5  
- CSS3  
- JavaScript  
- GitHub Pages hosting

---

## 📜 License

This project is open‑source. You may use or modify it freely. Tho u will have to mention FoL or kutuzovdaniel579-jpg as it are the creators of the repo and website
