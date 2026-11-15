# 🍽 Restuarant (Django)

**Django** asosida qurilgan restoran veb-sayti: menyu, aloqa, "biz haqimizda" sahifalari va foydalanuvchi tizimi.

---

## ✨ Imkoniyatlar

- 🍲 **Menyu** ko'rsatish
- ℹ️ **Biz haqimizda** va **Aloqa** sahifalari
- 👤 **Ro'yxatdan o'tish va kirish** (`users` app)
- 🎨 **Bootstrap shablonlar**
- 🖼 **Media fayllar**

---

## 🛠 Texnologiyalar

| Texnologiya | Maqsad |
|---|---|
| **Python 3.10+** | Asosiy til |
| **Django** | Veb-framework |
| **SQLite** | Ma'lumotlar bazasi |
| **Pipenv** | Bog'liqliklar |

---

## ⚙️ O'rnatish

```bash
git clone https://github.com/dastonbek8747/Restuarant.git
cd Restuarant
pipenv install
pipenv shell
```

---

## ▶️ Ishga tushirish

```bash
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```

Brauzerda: `http://127.0.0.1:8000`

---

## 📁 Loyiha tuzilishi

```
Restuarant/
├── config/            # Django sozlamalari
├── menu/              # Menyu app
├── users/             # Foydalanuvchi app
├── templates/         # Shablonlar
├── static/            # Statik fayllar
└── manage.py
```

---

## 📄 Litsenziya

Litsenziya ko'rsatilmagan.
