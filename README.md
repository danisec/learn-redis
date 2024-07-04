## Learn Redis With Docker

## Daftar Isi

- [Konfigurasi Redis di Docker](#konfigurasi-redis-di-docker)
- [Mengapa Redis](materi/1.%20mengapa-redis.md)
- [Operasi Data String](materi/2.%20operasi-data-string.md)
- [Expiration](materi/3.%20expiration.md)
- [Increment dan Decrement](materi/4.%20increment-dan-decrement.md)
- [Flush](materi/5.%20flush.md)
- [Pipeline](materi/6.%20pipeline.md)
- [Transaction](materi/7.%20transaction.md)

## Konfigurasi Redis di Docker

### 1. Install Docker

- [Docker](https://docs.docker.com/get-docker/)
- [File redis.conf](https://github.com/redis/redis/blob/7.2.4/redis.conf)

### 2. Jalankan file docker-compose.yaml di Docker

```bash
docker-compose up -d
```

### 3. Masuk ke dalam container redis

```bash
docker exec -it redis /bin/bash
```

### 4. Masuk ke dalam redis-cli

```bash
redis-cli -h localhost -p 6379
```

### 5. Cek apakah redis sudah berjalan

```bash
ping
```

## Referensi

- [Docker](https://docs.docker.com)
- [Redis](https://redis.io/docs/latest)
- [Youtube: Programmer Zaman Now](https://www.youtube.com/playlist?list=PL-CtdCApEFH-7hBhz1Q-4rKIQntJoBNX3)
