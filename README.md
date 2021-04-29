# Pendahuluan

VissiCMS menggunakan CodeIgniter Framework versi 3.1.11 dengan penambahan dan modifikasi beberapa bagian, diantaranya:

- HMVC (Hierarchical MVC) dengan modifikasi https://bitbucket.org/wiredesignz/codeigniter-modular-extensions-hmvc
- Latte Template Engine https://latte.nette.org/
- Base Model dengan modifikasi https://github.com/avenirer/CodeIgniter-MY_Model
- Admin Template terintegrasi
- PHPASS untuk enkripsi password https://asecuritysite.com/encryption/phpass

Berikut ini struktur folder dari VissiCMS:

```folder
project/
├── docs/
├── application/
│   ├── cli/
│   ├── config/
│   ├── controllers/
│   ├── core/
│   ├── entries/
│   ├── helpers/
│   ├── hooks/
│   ├── language/
│   ├── libraries/
│   ├── migrations/
│   ├── models/
│   ├── modules/
│   ├── routes/
│   ├── shortcodes/
│   ├── tests/
│   └── third_party/
├── public/
|   ├── uploads/
|   ├── views/
|   └── index.php
├── src/
|   ├── configs/
|   ├── entries/
|   ├── modules/
|   ├── resources/
|   ├── routes/
|   ├── settings/
|   ├── shortcodes/
|   └── env.json
├── vendor/
└── composer.json
```

## Fitur

Beberapa fitur utama yang sudah tersedia di VissiCMS diantaranya:

- Page Management
- Post Management
- User Management
- Site Settings
- File Manager
- Entry & CRUD Generator
- Dynamic variables

## Development

Ada beberapa pilihan cara yang dapat digunakan untuk menambahkan fitur di VissiCMS, diantaranya:
- [Membuat Module](Membuat-Modul)
- [Membuat Entry](Membuat-Entry)