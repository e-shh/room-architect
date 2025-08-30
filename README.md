# 🏠 Alex's Creative Home Office Portfolio 💼

![Page screenshot](public/media/og-image.webp?raw=true "Page screenshot")

# Updates!!!

- Overlay component split into two useEffects for gsap set not triggering edge case.
- Updated video texture to useVideoTexture from React Three Drei.

# 🪵 Resources mentioned 🪨

- [Nukleos (mesh cleanup Blender addon)](https://www.youtube.com/watch?v=fTYhSvOolvk)
- [Mesh Repair](https://extensions.blender.org/add-ons/mesh-repair-tools/)
- [Clean Mesh Converter](https://nanomanpro.gumroad.com/l/sxerq)
- [UVPACKMASTER3](https://uvpackmaster.com/)
- [SimpleBake](https://blendermarket.com/products/simplebake---simple-pbr-and-other-baking-in-blender-2)

# Credits!!! 💖

- [Image by Marc Mueller](https://www.pexels.com/photo/man-sitting-in-front-of-computer-380769/)
- [Image by Daniel McCullough](https://unsplash.com/photos/person-drafting-on-blueprint--FPFq_trr2Y)
- [Image by R ARCHITECTURE](https://unsplash.com/photos/black-wooden-table-and-chairs-wDDfbanbhl8)
- [Blender asset pack referral link](https://blendermarket.com/products/interior-models?ref=603)
- [Oscarherry3d's keyboard](https://sketchfab.com/3d-models/keyboard-66f5ca31bf154c82ae5284a32a362a4e)
- [LagzDesign's mouse](https://sketchfab.com/3d-models/computer-mouse-low-poly-95eb7d0363bb4db79bd50168280ea1c7)
- [Spookyghostboo's books](https://sketchfab.com/3d-models/variety-of-books-9ecd80af3b7e4cd59efb4c141511a55b)
- [Naira's books and magazines](https://sketchfab.com/3d-models/books-and-magazines-d0b76eada5bd495abcdfb2b20e6f7ee6)
- [Mfb64's vogue magazines](https://sketchfab.com/3d-models/vogue-magazines-bf47eea601784059aa52f2929a0c9ada)
- [Igrium's water bottle](https://sketchfab.com/3d-models/water-bottle-885543a7679c4026abbd6499185caf08)

# Alex's Creative Home Office Portfolio

This project is a portfolio website showcasing Alex's home office setup, creative skills, and innovative projects. It is built using modern web technologies and is designed to be visually stunning, interactive, and fully responsive across all devices.

## ✨ Features

- **Interactive 3D Environment**: Immersive 3D elements using `three.js` and `react-three-fiber`
- **Smart State Management**: Efficient state handling with `zustand`
- **Smooth Animations**: Professional animations powered by `gsap`
- **Modular Architecture**: Clean, reusable, and maintainable component structure
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Performance Optimized**: Fast loading times and smooth interactions

## 🚀 Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/) (v18 or higher recommended)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

## 📦 Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/alexs-creative-home-office-portfolio.git
   cd alexs-creative-home-office-portfolio
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

   or

   ```bash
   yarn install
   ```

## 🛠️ Usage

### Development Server

To start the development server with hot reload:

```bash
npm run dev
```

or

```bash
yarn dev
```

The application will be available at `http://localhost:3000`.

### Build for Production

To create an optimized production build:

```bash
npm run build
```

or

```bash
yarn build
```

The output will be generated in the `dist` folder.

### Preview Production Build

To preview the production build locally:

```bash
npm run preview
```

or

```bash
yarn preview
```

## 📁 Project Structure

```
alexs-creative-home-office-portfolio
├── src/                # Source code
│   ├── components/     # React components
│   │   ├── UI/         # User interface components
│   │   ├── 3D/         # Three.js components
│   │   └── Layout/     # Layout components
│   ├── assets/         # Static assets (images, fonts, models)
│   ├── styles/         # CSS and styling files
│   ├── hooks/          # Custom React hooks
│   ├── utils/          # Utility functions
│   ├── state/          # Zustand store configuration
│   └── App.tsx         # Main application entry point
├── public/             # Public static files
├── package.json        # Project metadata and dependencies
├── package-lock.json   # Dependency lock file
├── README.md           # Project documentation
├── tsconfig.json       # TypeScript configuration
└── vite.config.ts      # Vite configuration
```

## 🔧 Key Dependencies

This project leverages cutting-edge web technologies:

- **React & React DOM**: Modern UI library for building interactive interfaces
- **Three.js**: Powerful 3D graphics library for WebGL rendering
- **@react-three/fiber**: React renderer for Three.js with declarative syntax
- **@react-three/drei**: Useful helpers and abstractions for react-three-fiber
- **Zustand**: Lightweight and flexible state management solution
- **GSAP**: Professional-grade animation library
- **TypeScript**: Enhanced JavaScript with static typing
- **Vite**: Next-generation frontend tooling for faster development

## 🎨 Customization

Feel free to customize this portfolio to match your own style:

1. **Colors & Themes**: Update the CSS variables in `src/styles/`
2. **3D Models**: Replace models in `public/models/` with your own
3. **Content**: Modify text content in components to reflect your experience
4. **Animations**: Adjust GSAP animations to match your preferred style

## 🚀 Deployment

This project can be deployed to various platforms:

- **Vercel**: `vercel --prod`
- **Netlify**: Drag and drop the `dist` folder
- **GitHub Pages**: Use GitHub Actions for automated deployment

## 📄 License

This project is licensed under the [MIT License](LICENSE).

## 🙏 Acknowledgments

Special thanks to the amazing open-source community:

- [Three.js](https://threejs.org/) - The foundation of our 3D world
- [React](https://reactjs.org/) - For the fantastic component architecture
- [Zustand](https://github.com/pmndrs/zustand) - Simple and scalable state management
- [GSAP](https://greensock.com/gsap/) - Industry-standard animation platform
- [React Three Fiber](https://docs.pmnd.rs/react-three-fiber) - Bringing React to 3D

## 📧 Contact

For questions, suggestions, or collaboration opportunities, feel free to reach out!

---

*Built with ❤️ and lots of ☕ by Alex*
