# 🏠 Daniel's Award-Winning Home Office Portfolio 💼

**[Live site](https://daniels-architects.com/)**

This repo contains code of Daniel's [Award-Winning](https://www.cssdesignawards.com/sites/daniels-architects/47206/) Home Office Portfolio. You can learn how to create a porfolio like this [here](https://youtu.be/aNJN8h_QsPA)!!! Get the Blender files from my [Google Drive](https://drive.google.com/file/d/1i8vPLDbOWoC_U8DXnRTY_-FqcOF3w0SO/view?usp=sharing).

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

# Daniel's Home Office Portfolio

This project is a portfolio website showcasing Daniel's home office setup, skills, and projects. It is built using modern web technologies and is designed to be visually appealing and responsive.

## Features

- Interactive 3D elements using `three.js` and `react-three-fiber`.
- State management with `zustand`.
- Smooth animations with `gsap`.
- Modular and reusable components.

## Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/) (v16 or higher recommended)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/daniels-home-office-portfolio.git
   cd daniels-home-office-portfolio-main
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

   or

   ```bash
   yarn install
   ```

## Usage

### Development Server

To start the development server:

```bash
npm run dev
```

or

```bash
yarn dev
```

The application will be available at `http://localhost:3000`.

### Build for Production

To build the project for production:

```bash
npm run build
```

or

```bash
yarn build
```

The output will be in the `dist` folder.

### Preview Production Build

To preview the production build locally:

```bash
npm run preview
```

or

```bash
yarn preview
```

## Folder Structure

```
daniels-home-office-portfolio-main
├── src/                # Source code
│   ├── components/     # React components
│   ├── assets/         # Static assets (images, fonts, etc.)
│   ├── styles/         # CSS or styling files
│   ├── state/          # Zustand store
│   └── App.tsx         # Main application entry point
├── public/             # Public static files
├── package.json        # Project metadata and dependencies
├── package-lock.json   # Dependency lock file
├── README.md           # Project documentation
└── tsconfig.json       # TypeScript configuration
```

## Dependencies

Key dependencies used in this project:

- `react` and `react-dom`: For building the user interface.
- `three`: For 3D rendering.
- `@react-three/fiber`: React renderer for `three.js`.
- `zustand`: For state management.
- `gsap`: For animations.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- [Three.js](https://threejs.org/)
- [React](https://reactjs.org/)
- [Zustand](https://github.com/pmndrs/zustand)
- [GSAP](https://greensock.com/gsap/)
