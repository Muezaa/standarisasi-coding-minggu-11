# Pengujian dan Integrasi Kode

## Deskripsi

Project ini dibuat untuk memenuhi tugas praktikum Standarisasi Coding.
Project menggunakan Jest untuk melakukan unit testing dan GitHub Actions
untuk menjalankan CI Pipeline secara otomatis.

## Teknologi

- Node.js
- JavaScript
- Jest
- Git
- GitHub Actions

## Struktur Project

```text
minggu_11/
├── .github/
│   └── workflows/
│       └── ci.yml
├── src/
│   ├── User.js
│   └── ShoppingCart.js
├── tests/
│   ├── User.test.js
│   └── ShoppingCart.test.js
├── ANALISIS.md
├── README.md
└── package.json
```

## Menjalankan Pengujian

Install dependency:

```bash
npm install
```

Menjalankan test:

```bash
npm test
```

Menjalankan coverage:

```bash
npm run test:coverage
```

## Hasil Pengujian

- Total test: 25
- Test berhasil: 25
- Test gagal: 0
- Test coverage: 100%

## CI Pipeline

Project menggunakan GitHub Actions untuk menjalankan unit test
dan test coverage secara otomatis ketika terdapat push atau pull request
ke branch main.

## Repository

https://github.com/Muezaa/standarisasi-coding-minggu-11
