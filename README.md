## Sử dụng git command

### Cài đặt GIT trên Linux

- Với Ubuntu

```
apt-get update
apt-get install -y git
```

- Với CentOS

```
yum install -y git
```

### Tải một repo bất kỳ trên git

> git clone <link-git>

### Đẩy dữ liệu lên git

Vào thư mục đã clone từ git về, chỉnh sửa/biên soạn các file cần thiết. 

```
git add .
git commit -m "This is comment."
git push
```