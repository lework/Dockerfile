### 构建
---

```
docker build . -t centos7.4_ssh
```

### 运行
---

```
docker run -p 2222:22 -tid centos7.4_ssh
```