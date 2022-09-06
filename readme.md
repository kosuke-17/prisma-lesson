# prisma setup

## [公式 set up](https://www.prisma.io/docs/getting-started/setup-prisma/start-from-scratch/relational-databases-typescript-postgres)

### パッケージ管理 : yarn

- [yarn のメリット](https://qiita.com/mzmz__02/items/4ba43b69c8878a9ca99e)
  - インストール速後の高速化
  - 高いセキュリティ
  - バージョン管理が行いやすい

## .env ファイル設置

## prisma.schema のマイグレーション

```
// 初めてのマイグレーション(初回のみ)
npx prisma migrate dev --name init

// 2回目以降のマイグレーション
npx prisma migrate dev --name <migration_file_name>
```

## Git Tips

[commit 取り消し](https://qiita.com/shuntaro_tamura/items/06281261d893acf049ed)

```
// 直前の commit 取り消し
git reset --soft HEAD^

// n個前の commit 取り消し
git reset --soft HEAD~{n}
```
