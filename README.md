Bu proje, mikroservis mimarisinde çalışan product-service uygulamasını Eureka Server'a register etme örneğidir.


# Gereksinimler:
- Docker
- Docker Compose
- IntelliJ

# Projenin Çalıştırılması

https://medium.com/@haticezeren0/docker-nedir-docker-kavramlar%C4%B1-ve-docker-kullan%C4%B1m%C4%B1n%C4%B1n-avantajlar%C4%B1-e5da7869fbcb


## Mysql Database Bilgileri:



```

CREATE SCHEMA IF NOT EXISTS product_example;

-- product tablosunu oluşturma
CREATE TABLE IF NOT EXISTS product_example.product (
    product_id BIGINT AUTO_INCREMENT PRIMARY KEY,
    product_name VARCHAR(255) NOT NULL,
    quantity INT NOT NULL,
    price DOUBLE NOT NULL
);
      
```


