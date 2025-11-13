# Modern Presentations 🎭# 🎨 Modern Presentations



A stunning presentation platform built with Next.js, TypeScript, Tailwind CSS, and Framer Motion.A professional, feature-rich presentation web application built with Next.js 14, TypeScript, Tailwind CSS, and Framer Motion. Create stunning animated presentations with smooth transitions and elegant design.



## 🎯 Features![Modern Presentations](https://img.shields.io/badge/Next.js-14+-black?style=for-the-badge&logo=next.js)

![TypeScript](https://img.shields.io/badge/TypeScript-5+-blue?style=for-the-badge&logo=typescript)

✅ **Code-Based Presentations** - Create presentations programmatically  ![Tailwind CSS](https://img.shields.io/badge/Tailwind-4+-06B6D4?style=for-the-badge&logo=tailwind-css)

✅ **16 Beautiful Slides** - Test presentation with creative animations  ![Framer Motion](https://img.shields.io/badge/Framer_Motion-11+-FF0055?style=for-the-badge&logo=framer)

✅ **Multiple Slide Types** - Cover, Plan, Chapter, Content, Quote, Split, Thanks  

✅ **5 Design Templates** - Unique visual styles  ## ✨ Features

✅ **Smooth Animations** - Fade, slide, zoom, flip transitions  

✅ **Fullscreen Mode** - Immersive experience  ### 🎭 Animations & Transitions

✅ **Keyboard Navigation** - Full control  - **Multiple Animation Types**: Fade, slide, zoom, and flip transitions

✅ **Responsive Design** - Works everywhere  - **Smooth Page Transitions**: Powered by Framer Motion

- **Animated UI Elements**: Elegant enter/exit animations

## 🚀 Quick Start- **Custom Keyframe Animations**: Beautiful blob animations on the home page



```powershell### 🖥️ Presentation Mode

cd "c:\Users\Hamza\Documents\EMSI 5\PFA\program\programm"- **Fullscreen Support**: Immersive presentation experience

npm run dev- **No Overflow Issues**: Perfect layout stability in all modes

```- **Keyboard Navigation**: Arrow keys, space, home, end, and ESC support

- **Progress Tracking**: Visual progress bar and slide counter

**Access at: http://localhost:3001**

### 🎨 Design & UI

## 📊 Current Test Presentation- **Modern Gradient Backgrounds**: Beautiful color transitions

- **Responsive Design**: Perfect on all screen sizes

**"The Future of Technology"** - 16 slides including:- **Glass Morphism Effects**: Backdrop blur and transparency

- **Dark Theme**: Eye-friendly dark interface

1. 🎬 **Cover** - Dramatic entrance- **Creative Layouts**: Multiple slide types (title, content, quote, split, image)

2. 📋 **Plan** - Journey ahead

3. 🌐 **Digital Revolution** (Chapter + Content)### 🛠️ Developer Experience

4. 🤖 **AI Era** (Chapter + Content + Quote)- **TypeScript**: Full type safety

5. ⚛️ **Quantum Computing** (Chapter + Content)- **Clean Architecture**: Modular and scalable code structure

6. 🌱 **Sustainable Tech** (Chapter + Content + Split)- **Component-Based**: Reusable React components

7. 🚀 **Future Vision** (Chapter + Content + Quote)- **No Runtime Errors**: Thoroughly tested and validated

8. 🙏 **Thanks** - Closing

## 🚀 Getting Started

## ⌨️ Keyboard Controls

### Prerequisites

| Key | Action |- Node.js 18+ 

|-----|--------|- npm or yarn

| `→` `↓` `Space` `Enter` | Next slide |

| `←` `↑` | Previous slide |### Installation

| `F` | Toggle fullscreen |

| `Escape` | Exit fullscreen |1. **Install dependencies:**

   ```bash

## 🎨 Slide Types   npm install

   ```

1. **Cover** - Title, subtitle, author, date

2. **Plan** - Table of contents2. **Run the development server:**

3. **Chapter** - Chapter titles with numbers   ```bash

4. **Content** - Bullet points or text   npm run dev

5. **Quote** - Inspirational quotes   ```

6. **Split** - Two-column layout

7. **Thanks** - Closing slide3. **Open your browser:**

   Navigate to [http://localhost:3000](http://localhost:3000)

## 💻 Creating Presentations in Code

## 📖 Usage

Edit `lib/presentations.ts`:

### Creating a New Presentation

```typescript1. Click the **"New Presentation"** button on the home page

// Simple example2. Enter a title and optional description

{3. Click **"Create & Open"** to start presenting

  id: 'my-pres',

  title: 'My Presentation',### Navigation Controls

  design: 'design2',

  slides: [#### Keyboard Shortcuts

    {- `→` or `↓` - Next slide

      type: 'cover',- `←` or `↑` - Previous slide

      content: {- `Space` - Next slide

        title: 'My Title',- `Home` - First slide

        subtitle: 'My Subtitle',- `End` - Last slide

      },- `F` - Toggle fullscreen

      animation: 'zoom',- `ESC` - Exit fullscreen

    },

    {#### On-Screen Controls

      type: 'content',- **Navigation Buttons**: Previous/Next slide buttons

      content: {- **Slide Dots**: Click to jump to specific slides

        title: 'Key Points',- **Fullscreen Toggle**: Enter/exit presentation mode

        bulletPoints: [- **Progress Bar**: Visual representation of progress

          '✨ Point one',

          '🚀 Point two',### Slide Types

          '💡 Point three',

        ],1. **Title Slide**: Large centered title with optional subtitle

      },2. **Content Slide**: Title with bullet points or paragraph text

      background: 'bg-gradient-to-br from-blue-600 to-purple-600',3. **Quote Slide**: Centered quote with attribution

      animation: 'slide',4. **Split Slide**: Two-column layout with title and content

    },5. **Image Slide**: Title with image display

  ],

}## 📁 Project Structure

```

```

### Creating 60+ Slide Presentationsprogramm/

├── app/

Just tell me what you need and I'll generate it! Examples:│   ├── layout.tsx              # Root layout with metadata

- "Create 60 slides about AI"│   ├── page.tsx                # Home page with presentation list

- "Make 100 slides with 10 chapters"│   ├── globals.css             # Global styles and animations

- "Generate large presentation on technology"│   └── presentation/

│       ├── [id]/

I'll create the entire presentation in code with:│       │   └── page.tsx        # Presentation viewer page

- All content organized│       └── components/

- Varied animations│           ├── Slide.tsx                    # Individual slide component

- Beautiful gradients│           └── PresentationControls.tsx     # Navigation controls

- Chapter structure├── lib/

- Any slide types you want│   ├── types.ts                # TypeScript type definitions

│   └── presentations.ts        # Presentation management logic

## 🎬 Animations├── public/                     # Static assets

├── package.json                # Dependencies

- **fade** - Smooth opacity└── README.md                   # This file

- **slide** - Slide from right```

- **zoom** - Scale up

- **flip** - 3D flip effect## 🎯 Key Technologies



## 🎨 Design Templates- **[Next.js 14](https://nextjs.org/)**: React framework with App Router

- **[TypeScript](https://www.typescriptlang.org/)**: Type-safe JavaScript

- **design1** - Professional Blue- **[Tailwind CSS](https://tailwindcss.com/)**: Utility-first CSS framework

- **design2** - Vibrant Gradient ⭐ (current)- **[Framer Motion](https://www.framer.com/motion/)**: Animation library

- **design3** - Dark Minimalist- **[React](https://react.dev/)**: UI component library

- **design4** - Nature Green

- **design5** - Sunset Warm## 🎨 Design Features



## 📂 Project Structure### Color Schemes

- Dynamic gradient backgrounds using Tailwind CSS

```- Predefined color combinations for visual appeal

app/- Glass morphism effects with backdrop blur

├── page.tsx                    # Landing page- Smooth color transitions

├── presentation/[id]/page.tsx  # Presentation viewer

└── presentation/components/### Typography

    ├── Slide.tsx              # Slide renderer- Geist Sans font family for modern look

    └── Controls.tsx           # Navigation- Responsive font sizes

- Proper hierarchy and spacing

lib/- High contrast for readability

├── types.ts                   # TypeScript definitions

├── presentations.ts           # Data & CRUD### Animations

└── designs.ts                 # Design configs- Framer Motion variants for smooth transitions

```- Staggered animations for list items

- Custom blob animations

## 🛠️ Tech Stack- Page transition effects



- Next.js 16.0.1## 🔧 Development

- TypeScript

- Tailwind CSS 4+### Build for Production

- Framer Motion 11+```bash

npm run build

## 📝 Notes```



- No manual UI - all presentations created in code by agent### Start Production Server

- Single presentation focus```bash

- Fullscreen optimizednpm start

- 60 FPS animations```

- Zero errors

- Production ready### Lint Code

```bash

---npm run lint

```

**Ready?** Open http://localhost:3001 and click "Start Presentation"! 🎉

## 📝 Customization

### Adding New Slide Types
1. Update the `SlideType` in `lib/types.ts`
2. Add rendering logic in `app/presentation/components/Slide.tsx`
3. Update the presentation creation logic

### Changing Animation Types
Modify the animation variants in `Slide.tsx`:
```typescript
const variants = {
  fade: { initial: { opacity: 0 }, animate: { opacity: 1 } },
  // Add your custom animations
};
```

### Styling
- Modify `app/globals.css` for global styles
- Update Tailwind classes in components
- Add custom CSS animations as needed

## 🐛 Troubleshooting

### Fullscreen Not Working
- Ensure you're not in an iframe
- Check browser permissions
- Try using the F key or the fullscreen button

### Animations Laggy
- Check your browser's hardware acceleration
- Reduce animation complexity if needed
- Close other resource-intensive applications

## 📄 License

This project is open source and available under the MIT License.

## 🙏 Acknowledgments

- Next.js team for the amazing framework
- Framer Motion for smooth animations
- Tailwind CSS for utility-first styling
- Vercel for deployment platform

---

**Built with ❤️ using Next.js, TypeScript, Tailwind CSS, and Framer Motion**
