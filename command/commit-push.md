# Commands - Git Operations

## Commit và Push Codebase

```bash
# 1. Kiểm tra status
git status

# 2. Add tất cả thay đổi
git add -A

# 3. Commit với message
git commit -m "feat: <mô tả thay đổi>"

# 4. Push lên remote
git push origin main
```

## One-liner

```bash
git add -A && git commit -m "feat: update codebase" && git push origin main
```

## Conventional Commit Messages

| Prefix | Mục đích |
|--------|----------|
| `feat:` | Tính năng mới |
| `fix:` | Sửa bug |
| `docs:` | Cập nhật documentation |
| `refactor:` | Refactor code |
| `perf:` | Cải thiện performance |
| `chore:` | Maintenance tasks |
