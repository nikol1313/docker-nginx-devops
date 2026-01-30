## Dockerized Nginx Web Server

მარტივი DevOps პროექტი, რომელიც აჩვენებს Docker-ის გამოყენებას ვებ-სერვერის გასაშვებად.

### გამოყენებული ტექნოლოგიები
- Docker
- Nginx
- Linux

### როგორ გაეშვას პროექტი
```bash
docker build -t devops-nginx .
docker run -p 8080:80 devops-nginx
