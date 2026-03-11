# Turbo Domain Finder

> Instantly check domain name availability across 50+ TLD extensions — built with Flask.

[![Python](https://img.shields.io/badge/Python-3.10+-blue?style=flat-square&logo=python)](https://python.org)
[![Flask](https://img.shields.io/badge/Flask-3.x-black?style=flat-square&logo=flask)](https://flask.palletsprojects.com)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

## Features

- Check single domain availability instantly
- Bulk search across `.com`, `.net`, `.org`, `.io`, `.dev` and 45+ more TLDs
- Clean, responsive UI
- Fast parallel DNS lookups
- Simple one-file Flask backend

## Screenshots

![Search](show2.png)
![Results](show3.png)

## Getting Started

```bash
git clone https://github.com/prasangapokharel/turbo-domain-finder.git
cd turbo-domain-finder
pip install -r requirements.txt
cp .env.example .env
python app.py
```

Open `http://localhost:5000` in your browser.

## Environment Variables

```env
SECRET_KEY=your_secret_key
DATABASE_URL=sqlite:///domain.db
```

## License

MIT License — © 2025 Prasanga Pokharel
