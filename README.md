# Demo App Docker

// Build docker
docker build -t spring-boot:1.0 .

// Run docker
docker run -d -p 8080:8080 -t spring-boot:1.0

// Cek Container yang sedang jalan
docker ps

// Cara stop docker
docker stop container_id