---
repo: "https://github.com/AlistGo/alist?tab=readme-ov-file"
category: "List"
---

# Docker Run Command

```bash
docker run -d --restart=always -v /etc/alist:/opt/alist/data -p 5244:5244 -e PUID=0 -e PGID=0 -e UMASK=022 xhofe/alist:beta-aio
```
