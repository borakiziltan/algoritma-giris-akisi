# Kullanıcı Giriş Sistemi Algoritması

Bu projede bir kullanıcı giriş sisteminin algoritması ve akış diyagramı hazırlanmıştır.

## Algoritmanın Çalışma Mantığı

1. Başarısız giriş sayacı 0 olarak başlatılır.
2. Hesabın geçici olarak kilitli olup olmadığı kontrol edilir.
3. Hesap kilitliyse kullanıcıya hesabın geçici olarak kilitlendiği bilgisi verilir ve işlem sonlandırılır.
4. Hesap kilitli değilse kullanıcıdan e-posta ve şifre bilgileri alınır.
5. E-posta veya şifre alanlarından biri boşsa kullanıcıdan tüm alanları doldurması istenir.
6. Girilen bilgiler doğruysa giriş başarılı olur ve işlem sonlandırılır.
7. Bilgiler yanlışsa başarısız giriş sayacı 1 artırılır.
8. Başarısız giriş sayısı 3'e ulaştığında hesap geçici olarak kilitlenir.
9. Başarısız giriş sayısı 3'e ulaşmadıysa kullanıcı tekrar giriş yapabilir.

## Akış Diyagramı

Akış diyagramının PNG çıktısı ve düzenlenebilir `.drawio` dosyası repository içerisinde bulunmaktadır.

- `drawio.png` — Akış diyagramının görsel çıktısı
- `flowchart.drawio` — Akış diyagramının düzenlenebilir kaynak dosyası

## Kullanılan Araçlar

- diagrams.net (draw.io)
- GitHub
