# 📦 nest-prisma-pagination

**nest-prisma-pagination** is an advanced helper for [NestJS](https://nestjs.com/) that enhances [Prisma ORM](https://www.prisma.io/) with a powerful and flexible solution for **filtering**, **sorting**, **searching**, **column selection**, **nested relation inclusion**, and **pagination (offset & cursor-based)** — all following the [JSON:API](https://jsonapi.org/) specification.

---

## 🚀 Features

- ✅ Offset and cursor-based pagination (`page[number]`, `page[size]`, `page[cursor]`)
- 🔍 Full-text search across multiple fields (`q`)
- 📊 Multi-column sorting (`sort=field1,-field2`)
- 🎯 Advanced filtering with supported operators:  
  `$eq`, `$not`, `$null`, `$in`, `$gt`, `$gte`, `$lt`, `$lte`, `$btw`, `$ilike`, `$sw`, `$contains`
- 🧩 Field selection (`fields`)
- 🔗 Nested relation inclusion (`include`)
- 👻 Virtual/computed field support
- 📐 Standardized syntax aligned with JSON:API
- 🧱 Seamless integration with any Prisma-based service

---

