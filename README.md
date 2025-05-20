# 🧪 React Dashboard — ShadCN UI + Vite + TypeScript

A responsive and modern dashboard built using [ShadCN UI](https://ui.shadcn.com/), Vite, and TypeScript. This project includes a collapsible sidebar, data table, chart visualization, and clean component architecture — inspired by the assignment spec.

---

## 🛠️ Tech Stack

- ⚛️ **React** (v18+)
- ⚡ **Vite** (super fast bundler)
- ⛓️ **TypeScript**
- 🧩 **ShadCN UI** (Radix + Tailwind + Next-inspired components)
- 🎨 **Tailwind CSS**
- 📊 **Recharts** (charts)
---

## 📁 Project Structure

```bash
src/
├── app/
│   └── dashboard/
│       ├── page.tsx
│       └── data.json
├── components/
│   ├── app-sidebar.tsx
│   ├── chart-area-interactive.tsx
│   ├── data-table.tsx
│   ├── section-cards.tsx
│   ├── site-header.tsx
│   └── ui/ (shadcn blocks)
├── hooks/
│   └── use-mobile.ts
├── App.tsx
└── main.tsx
````

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/MOHDNEHALKHAN/Dashboard-Shadcn.git
cd Dashboard-Shadcn
```

### 2. Install Dependencies

```bash
npm install
# or
yarn
```

### 3. Start the Development Server

```bash
npm run dev
```

Visit `http://localhost:5173` in your browser.

---

## 🧪 Scripts

| Script            | Description              |
| ----------------- | ------------------------ |
| `npm run dev`     | Start local dev server   |
| `npm run build`   | Create production build  |
| `npm run preview` | Preview production build |

---