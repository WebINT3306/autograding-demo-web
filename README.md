# Bài tập demo – Autograding (Phát triển ứng dụng Web)

Bài tập mẫu dùng Node.js và Jest để làm quen với autograding trên GitHub Classroom.

## Yêu cầu bài tập

Hiện tại test **đang fail** vì hàm `hello()` trong `hello.js` trả về sai chuỗi.

- **Nhiệm vụ:** Sửa `hello.js` để hàm `hello()` trả về đúng chuỗi `"Hello world!"`.
- Khi sửa đúng, chạy `npm test` sẽ pass và GitHub Actions (autograding) sẽ báo đạt.

## Chạy trên máy (test local)

```bash
npm install
npm test
```

## Cấu trúc

- `hello.js` – code cần sửa
- `hello.test.js` – test (không cần sửa khi làm bài)
- `.github/workflows/autograding.yml` – workflow chạy test trên mỗi push/PR
