# Spring Boot Relations Practice

Bu repo, **Spring Boot + JPA (Hibernate)** kullanılarak
entity ilişkilerini pratik etmek amacıyla oluşturulmuştur.

## İçerik
- **User – Profile** → OneToOne / OneToOne
- **Author – Book** → OneToMany / ManyToOne
- **Student – Course** → ManyToMany **(ara entity: `StudentCourse`)**

## Amaç
- `mappedBy`, `JoinColumn` ve owner kavramlarını anlamak
- Gerçek projelerde kullanılan doğru ilişki yapılarını öğrenmek

## Teknolojiler
- Java
- Spring Boot
- Spring Data JPA
- Hibernate
- Lombok
