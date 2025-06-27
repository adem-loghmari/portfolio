# Vite React TypeScript Portfolio

A modern, responsive portfolio website built with React, TypeScript, Tailwind CSS, and Vite.  
Showcases projects, experience, and contact information for Adam Hmida Loghmari.

## Features

- ⚡ Fast development with [Vite](https://vitejs.dev/)
- 💅 Styled using [Tailwind CSS](https://tailwindcss.com/)
- ⚛️ Built with [React](https://react.dev/) and [TypeScript](https://www.typescriptlang.org/)
- 📱 Responsive design for all devices
- 🧑‍💻 Project, experience, and contact sections
- 🌙 Dark mode support (via system preference)
- 🔗 Social and contact links

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18+ recommended)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/adem-loghmari/portfolio.git
   cd portfolio
   ```

2. Install dependencies:
   ```sh
   npm install
   # or
   yarn install
   ```

3. Start the development server:
   ```sh
   npm run dev
   # or
   yarn dev
   ```

4. Open [http://localhost:5173](http://localhost:5173) in your browser.

### Build for Production

```sh
npm run build
# or
yarn build
```

### Preview Production Build

```sh
npm run preview
# or
yarn preview
```

## Project Structure

- `src/` - Main source code
  - `components/` - React components (About, Contact, Experience, Footer, Header, Hero, Projects)
  - `assets/` - Images used in the project
  - `App.tsx` - Main app component
  - `main.tsx` - Entry point
  - `index.css` - Tailwind and custom styles

## Customization

- Update your profile image (`pfp.jpg`) and resume (`resume.pdf`) in the project root.
- Edit project and experience data in their respective components in [`src/components/`](src/components/).
- Change social links in [`Hero.tsx`](src/components/Hero.tsx) and [`Contact.tsx`](src/components/Contact.tsx).

## License

This project is licensed under the MIT License.

---

Made with ❤️ by Adam Hmida Loghmari
