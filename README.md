<div align="center">
  <br />
  <h1>🍹 Calgary Cowboys Cocktail Website</h1>
  <br />

   <div>
    <img src="https://img.shields.io/badge/-React-blue?style=for-the-badge&logo=react&logoColor=white" />
    <img src="https://img.shields.io/badge/-GSAP-88CE02?style=for-the-badge&logo=greensock&logoColor=white" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />
    <img src="https://img.shields.io/badge/-Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" />
  </div>

  <p>A stunning, modern cocktail website for Calgary Cowboys featuring advanced GSAP animations, scroll-driven effects, and a fully responsive design.</p>
</div>

## 📋 Table of Contents

1. [Introduction](#introduction)
2. [Tech Stack](#tech-stack)
3. [Features](#features)
4. [Project Structure](#project-structure)
5. [Quick Start](#quick-start)
6. [Scripts](#scripts)
7. [Contact Information](#contact-information)

## 🤖 <a name="introduction">Introduction</a>

Calgary Cowboys Cocktail Website is a modern, scroll-driven web experience showcasing a cocktail bar's offerings with stunning animations powered by GSAP. The site features dynamic text reveals, parallax scrolling, scroll-synced video playback, custom carousels, and seamless timeline animations across multiple sections.

Built with React and Tailwind CSS, this project demonstrates advanced animation techniques while maintaining a fully responsive design that adapts beautifully across all screen sizes.

## ⚙️ <a name="tech-stack">Tech Stack</a>

- **[GSAP](https://gsap.com/)** - Powerful JavaScript animation library for creating dynamic, scroll-driven visuals
  - SplitText for animated text reveals
  - ScrollTrigger for timeline control and scroll-based animations
  - Parallax scrolling effects
  - Pinned sections and scroll-synced video playback

- **[React](https://react.dev/)** - Declarative JavaScript library for building interactive UIs
  - Component-based architecture
  - Hooks for state management and side effects
  - Integration with GSAP via `@gsap/react`

- **[Tailwind CSS](https://tailwindcss.com/)** - Utility-first CSS framework
  - Rapid UI development with utility classes
  - Custom theme configuration
  - Responsive design utilities

- **[Vite](https://vitejs.dev/)** - Lightning-fast build tool and development server
  - Instant hot module replacement
  - Optimized production builds
  - Minimal configuration

## 🔋 <a name="features">Features</a>

✨ **SplitText Animations** - Dynamic text reveals using GSAP's SplitText for impactful intros and section highlights

✨ **ScrollTrigger Effects** - Scroll-based animations and timeline control with GSAP's ScrollTrigger

✨ **Parallax Scrolling** - Immersive depth with smooth parallax effects that respond to user scroll

✨ **Pinned Sections** - Lock sections in view while animating content for engaging scroll experiences

✨ **Scroll-Synced Video Playback** - Sync video progress with scroll position for cinematic storytelling

✨ **Image Masking Effects** - Scroll-triggered pins and masks for visually striking image transitions

✨ **Custom Carousel** - Fully customized carousel with multiple navigation options and animated slides

✨ **Seamless Timeline Animations** - Smooth animation timelines that span across multiple sections

✨ **Responsive Design** - Fluid UI and adaptive GSAP animations across all screen sizes

✨ **Modern UI/UX** - Beautiful, modern interface with smooth transitions and interactions

## 📁 <a name="project-structure">Project Structure</a>

```
gsap-cocktails/
├── public/
│   ├── fonts/          # Custom fonts
│   ├── images/         # Image assets
│   └── videos/         # Video assets
├── src/
│   ├── components/
│   │   ├── About.jsx      # About section component
│   │   ├── Art.jsx        # Art showcase component
│   │   ├── Cocktails.jsx  # Cocktails listing component
│   │   ├── Contact.jsx    # Contact/Footer component
│   │   ├── Hero.jsx       # Hero section with video
│   │   ├── Menu.jsx       # Menu component
│   │   └── Navbar.jsx     # Navigation component
│   ├── App.jsx           # Main app component
│   ├── main.jsx          # Entry point
│   └── index.css         # Global styles
├── constants/
│   └── index.js          # App constants and data
├── index.html            # HTML template
├── vite.config.js        # Vite configuration
└── package.json          # Dependencies and scripts
```

## 🤸 <a name="quick-start">Quick Start</a>

### Prerequisites

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en) (v18 or higher recommended)
- [npm](https://www.npmjs.com/) (comes with Node.js)

### Installation

1. **Clone the repository**

```bash
git clone <your-repo-url>
cd gsap-cocktails
```

2. **Install dependencies**

```bash
npm install
```

3. **Start the development server**

```bash
npm run dev
```

4. **Open your browser**

Navigate to [http://localhost:5173](http://localhost:5173) to view the project.

The development server will automatically reload when you make changes to the code.

## 🚀 <a name="scripts">Scripts</a>

- `npm run dev` - Start the development server
- `npm run build` - Build the project for production
- `npm run preview` - Preview the production build locally
- `npm run lint` - Run ESLint to check for code issues

## 📞 <a name="contact-information">Contact Information</a>

**Calgary Cowboys**

- **Address**: 456 12 Ave SE, Calgary, AB T2G 0B4
- **Phone**: (403) 265-0699
- **Email**: info@calgarycowboys.com

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Built with [GSAP](https://gsap.com/) for powerful animations
- Styled with [Tailwind CSS](https://tailwindcss.com/)
- Powered by [Vite](https://vitejs.dev/) for fast development

---

<div align="center">
  <p>Made with ❤️ for Calgary Cowboys</p>
</div>
