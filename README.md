# EnterAnimation - Framer Motion Animation Showcase

## Overview
This project demonstrates various animations using [Framer Motion](https://www.framer.com/motion/). It includes different animation techniques such as scaling, rotation, hover effects, exit animations, and shared layouts.

## Installation
To run this project locally, install dependencies and start the development server:

```sh
npm install
npm run dev
```

## Components & Animations
Each button in the interface corresponds to an animation type, which is displayed inside a bordered container.

### 1. Ball Glimmer (B.G)
- **Animation:** The ball scales up from 0 to 1 and fades in.
- **Techniques Used:** Initial & animate props, spring transition.

### 2. Box Rotate (B.R)
- **Animation:** A box rotates 360 degrees continuously.
- **Techniques Used:** Animate with rotation property.

### 3. Transform Hover (T.H)
- **Animation:** Moves slightly on load and scales up on hover.
- **Techniques Used:** Initial & animate props, `whileHover`, `whileTap`.

### 4. Exit Animation (Exit)
- **Animation:** A box appears and disappears on button click with scale and opacity effects.
- **Techniques Used:** `AnimatePresence`, exit animations.

### 5. Shared Layout Animation (Layout)
- **Animation:** Tab switching with a shared underline animation.
- **Techniques Used:** `layoutId`, animated tabs with transition effects.

### 6. Gestures (Genstures)
- **Animation:** A box scales, rotates, and reacts to drag gestures.
- **Techniques Used:** `whileHover`, `whileTap`, `whileDrag`, `drag`.

### 7. Variants (Var)
- **Animation:** Expanding/collapsing navigation panel using variants.
- **Techniques Used:** Variants API, ref for measuring dimensions dynamically.

## Customization
You can customize animations by modifying transition properties and animation values inside each component.

## Credits
Built using Framer Motion and React.

