Project: Aplikasi Pencatatan Saldo Member (E-Wallet Style) - CodeIgniter 3

Struktur ini berisi folder `application` (controllers, models, views) + contoh SQL dan tambahan routes.

Cara pakai singkat:
1. Download CodeIgniter 3 original.
2. Ekstrak ke htdocs, misal folder: htdocs/saldo_member_ci3
3. Timpa/merge folder `application` dari ZIP ini ke `application` di CI3.
4. Import SQL dari folder `sql/db_ewallet_example.sql` ke MySQL.
5. Sesuaikan:
   - application/config/config.php  -> $config['base_url'] = 'http://localhost/saldo_member_ci3/';
   - application/config/database.php -> koneksi ke database `db_ewallet`
   - application/config/autoload.php -> pastikan database, session, form_validation, url, form di-autoload
   - application/config/routes.php  -> tambahkan isi dari `routes_addition.php` (file ini juga disertakan di folder application/config).

Login contoh:
- Email: member1@example.com
  Password: 123456
- Email: member2@example.com
  Password: 123456
