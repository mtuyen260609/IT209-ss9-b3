# Bài 3: Viết Dockerfile 3 dòng đóng gói trang Web HTML tĩnh

## Các lệnh thực thi
```bash
# Build image
docker build -t my-html-app:v1 .

# Run container
docker run -d -p 8081:80 --name html-app my-html-app:v1

# Kiem tra kết quả
curl http://localhost:8081
```
