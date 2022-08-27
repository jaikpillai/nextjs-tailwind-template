# **Next.js + TailwindCSS + Typescript** Template

A template for Next.js app with TailwindCSS and Typescript.

## File/Folder structure

- **/components**
- **/pages**
  - **/api**
  - \_app.tsx
  - \_document.tsx
  - index.tsx
- **/public**
- **/styles**

## Tailwind configuration

```
module.exports = {
  content: [
    "./pages/**/*.{js,ts,jsx,tsx}",
    "./components/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

## Run Locally

Install dependencies

```bash
  npm install
```

Start development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
