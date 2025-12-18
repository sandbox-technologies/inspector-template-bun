# Inspector Bun Template

A modern React + Vite template styled with the Inspector design language and powered by shadcn/ui.

**Test Scenario:** B3 - Bun with `packageManager: bun@1.1.38` field

## Package Manager Configuration

This template uses the `packageManager` field in `package.json`:

```json
{
  "packageManager": "bun@1.1.38"
}
```

This allows Inspector to detect and use the bundled Bun 1.1.38 runtime.

## 🛠️ Tech Stack

- **React 19** - A JavaScript library for building user interfaces
- **Vite** - A fast, opinionated frontend build tool
- **TypeScript** - Typed superset of JavaScript
- **Tailwind CSS v3** - Utility-first CSS framework
- **shadcn/ui** - Beautifully designed components
- **Radix UI** - Accessible component primitives
- **Lucide Icons** - Beautiful, consistent icon set

## ⚙️ Prerequisites

- Bun 1.1.38 (specified via packageManager field)

## 🚀 Getting Started

1. Install dependencies:

   ```bash
   bun install
   ```

2. Start the development server:

   ```bash
   bun dev
   ```

3. Open [http://localhost:5173](http://localhost:5173) in your browser.

## 📜 Available Scripts

| Command | Description |
|---------|-------------|
| `bun dev` | Start development server |
| `bun run build` | Build for production |
| `bun run preview` | Preview production build |
| `bun run lint` | Run ESLint |

## 📄 License

MIT License - see [LICENSE](LICENSE) for details.
