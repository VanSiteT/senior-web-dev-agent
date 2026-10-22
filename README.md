# Senior Web Developer Agent (Aggressive Mode)

> AI Agent yang bertindak seperti **Senior Full-Stack Web Developer** yang agresif, kritis, dan tidak toleran terhadap kode jelek.

Dirancang khusus untuk **Cursor** dan **Continue.dev**.

---

## Fitur Utama

- Blunt & slightly sarcastic
- Langsung call-out anti-pattern dan technical debt
- TypeScript mandatory
- Default stack modern: Next.js App Router + Tailwind + shadcn/ui + Prisma/Drizzle
- Hanya menghasilkan production-ready code
- Prioritas: clean, simple, maintainable, performant

---

## Cara Pakai

### 1. Cursor (Recommended)

**Cara cepat:**
```bash
# Dari root project kamu
curl -o .cursorrules https://raw.githubusercontent.com/VanSiteT/senior-web-dev-agent/main/.cursorrules
```

Atau:
1. Download file [`.cursorrules`](./.cursorrules)
2. Taruh di **root project** kamu
3. Cursor akan otomatis membacanya

Alternatif: Buka **Cursor Settings → Rules for AI** lalu paste isinya.

### 2. Continue.dev

1. Buka file `config.json` Continue
2. Copy isi dari [`continue-systemMessage.txt`](./continue-systemMessage.txt)
3. Paste ke field `"systemMessage"`

### 3. Versi Super Pendek (Context Window Terbatas)

Gunakan file [`short-version.txt`](./short-version.txt) jika token terbatas.

---

## Default Stack Preference

| Layer       | Technology                          |
|-------------|-------------------------------------|
| Framework   | Next.js (App Router)                |
| Language    | TypeScript                          |
| Styling     | Tailwind CSS + shadcn/ui            |
| Database    | Prisma / Drizzle + PostgreSQL       |
| Auth        | Auth.js / Clerk / Lucia             |

---

## Filosofi

> "You are not a yes-man. You are the senior engineer who will tell the truth even when it’s uncomfortable."

Agent ini dibuat agar AI tidak membiarkan kode jelek, over-engineering, atau pola usang lolos begitu saja.

---

## License

MIT License — bebas digunakan, dimodifikasi, dan didistribusikan.
