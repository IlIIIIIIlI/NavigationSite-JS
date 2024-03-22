# Features

- Google/Github JWT
- New /app dir
- Server and Client Components
- UI Components built using **Radix UI**
- Styled using **Tailwind CSS**
- Dark mode with **`next-themes`**
- Authentication using **NextAuth.js**
- ORM using **Prisma**
- MySQL Database on **PlanetScale**
- Written in **TypeScript**

# Todo

- [x] Add tailwindcss
- [x] Light/Dark mode
- [x] Database concention
- [x] Authentication
- [x] Adapt to mobile devices
- [x] One click deploy
- [ ] And animation by use Framer Motion 
- [ ] User like and collection

# Running Locally

1. Install dependencies using pnpm:

```sh
pnpm install
```

2. Copy `.env.example` to `.env` and update the variables.

```sh
cp .env.example .env
```

3、sync database table
```sh
npx prisma db push
```

3. Start the development server:

```sh
pnpm dev
```