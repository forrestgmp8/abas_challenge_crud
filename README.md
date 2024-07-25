# abas_challenge_crud

CRUD API
# Proje Açıklaması
Bu proje, basit bir Spring Boot uygulaması olarak geliştirilmiş bir Çalışan (Employee) CRUD API'sidir. 

Uygulama, çalışanları eklemek, listelemek, güncellemek ve silmek için RESTful endpoint'ler sağlar. Veri tabanı olarak H2 kullanıldı.

## Kullanım
### GET /api/employees: Tüm çalışanları listelemek için.
### GET /api/employees/{id}: Belirli bir çalışanı ID ile getirmek için.
### POST /api/employees: Yeni bir çalışan eklemek için.
### PUT /api/employees/{id}: Var olan bir çalışanı güncellemek için.
### DELETE /api/employees/{id}: Bir çalışanı silmek için.

# H2 Konsoluna Erişim
H2 veri tabanı konsoluna erişmek için: http://localhost:8080/h2-console
JDBC URL: jdbc:h2:mem:testdb
Kullanıcı adı: sa
şifre: (Varsayılan olarak boş bırakılabilir)
