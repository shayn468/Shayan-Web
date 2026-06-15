---
version: alpha
name: Shayan — Freelance Web Consultant
description: A premium, dark-themed portfolio for a high-end web consultant and studio. The visual language blends brutalist typography with cinematic motion, featuring a sophisticated palette of deep blacks, off-whites, and high-energy safety orange.
colors:
  background: "#060706"
  panel: "#10110f"
  cream: "#f3f0e8"
  orange: "#ff5a1f"
  muted: "rgba(243, 240, 232, 0.58)"
  line: "rgba(243, 240, 232, 0.10)"
typography:
  fontFamily: "Inter, sans-serif"
  weights:
    regular: 400
    medium: 500
    semibold: 600
    bold: 700
    black: 900
  wordmark: "tracking-[-0.08em]"
spacing:
  containerPadding: "px-5 md:px-12"
  gridGap: "80px"
rounded:
  cards: "28px"
  buttons: "999px"
  outerSections: "32px"
components:
  buttons: "magnetic-button border-[#f3f0e8]/12 uppercase tracking-[0.18em]"
  cards: "glass border-[#line] backdrop-blur-[18px] transition-transform"
  labels: "section-label text-[11px] font-800 tracking-[0.14em]"
---

## Overview
Shayan's digital presence is defined by a high-density, performance-oriented aesthetic that balances technical precision with organic, atmospheric elements. The experience is heavily motion-driven, utilizing GSAP and Lenis for smooth, inertia-based scrolling. The layout feel is expansive and layered, using depth-stacking (hero cards), grid-based overlays, and film-grain noise to create a tactile, premium environment.

## Colors
The palette is rooted in a dark obsidian base (`#060706`), utilizing `Cream (#f3f0e8)` for high-legibility content and `International Orange (#ff5a1f)` as a singular, high-contrast accent for interactive elements, status indicators, and branding dots. Gradients are used sparingly to create atmospheric glows and masked textures.

## Typography
Inter is the sole typeface, used across a wide range of weights. Large-scale display text uses negative letter-spacing (up to -0.1em) and heavy weights (900) for a brutalist, editorial impact. Navigation and labels utilize uppercase characters with wide tracking (0.14em to 0.18em) to provide structural contrast.

## Layout
The design uses a flexible 12-column grid. Key layout features include:
- Fixed "Page Rail": A vertical text element on the bottom-left identifying the site.
- Pin Spacing: Sections that lock during scroll for content transitions.
- Asymmetrical Compositions: Heavy use of offsets and rotation (4° to 18°) to avoid rigid alignment.

## Elevation & Depth
Depth is achieved through:
- Glassmorphism: Semi-transparent surfaces with 18px backdrop blur.
- Overlays: A 4x4px noise pattern and an 80px grid veil for texture.
- Parallax: Floating image figures that move at varying speeds relative to the scroll.
- Card Stacks: Rotated layers in the hero section creating a physical 3D feel.

## Shapes
- Smooth Radii: Large containers use 28px to 38px corner rounding.
- Circular Motifs: Interaction points like the "View Work" arrow and secondary buttons are perfect circles.
- Slanted Imagery: Cards are frequently rotated slightly to suggest dynamic energy.

## Components
- **Nav Links**: Text-only with a scaleX(0) underline that expands from the left on hover.
- **Magnetic Buttons**: Interactive elements that translate -2px on hover with a glow effect.
- **Service Cards**: Framed glass panels that lift (translateY(-8px)) and brighten on hover.
- **Section Labels**: Prefixed with a glowing orange dot indicator.
- **Masked Numbers**: Giant display numbers (e.g., "03") masked with photographic textures.

## Page Sections

### Navigation
Fixed top-bar. Left-aligned wordmark. Center-aligned links with dot-indicators for the active "Work" section. Mobile toggle is a glass-circle icon.

### Hero Section
A pinned layout featuring a stack of rotated cards (offset 4° to 18°) at the center. Left side contains dense copy and a magnetic CTA. A massive background wordmark sits behind the card stack. Right side features a floating glass "Availability" card.

### Brand "Studio" Section
Focused on typography-driven values (Design, Develop, Optimize). A drifting background wordmark creates a slow-moving layer behind static columns of description text.

### Services
Features a top-aligned atmospheric strip image. Four glass cards arranged in a 2x2 grid (desktop) or vertical stack (mobile). High-contrast numbering (01, 02) defines the hierarchy.

### Who I Work With (Telemetry)
An asymmetrical section with floating parallax architecture photos. Left column features a fiverr-specific CTA. Right-aligned stat grid uses small "Note Cards" for client categories.

### Selected Work Gallery
A horizontal scroll section where large image and video figures (archive-cards) slide through the viewport. Video cards feature a custom play-icon overlay on hover.

### Experience Section
High-contrast cards including an inverse-colored (Cream background) primary card for the current role. Uses large, subtle background numbering (01) for depth.

## Motion & Interaction
- **Smooth Scroll**: Lenis integration for fluid inertia.
- **Magnetic Pull**: Buttons and icons react to mouse proximity.
- **Scroll-Triggered Reveals**: Elements use `translateY(32px)` and opacity 0 until scrolled into view.
- **Parallax Scaling**: Background images within cards scale from 1.08 to 1.16 on hover.
- **Loading State**: A fixed brand loader with a scaling horizontal bar and blurred text reveal.

## Do's and Don'ts
- **Do** use negative tracking for large display headers.
- **Do** maintain the 4px dot noise overlay across all sections.
- **Don't** use standard box-shadows; use semi-transparent borders or intense atmospheric glows.
- **Don't** use pure white; always use the Cream (`#f3f0e8`) variable.

## Accessibility
- Color scheme is forced to dark mode using `color-scheme: dark`.
- Reduced motion support via CSS media query that kills animations and loaders.
- Semantic labels on buttons and images.
- High-contrast text ratios for cream-on-black.

## Assets
1. `Other`: https://cdn.tailwindcss.com
2. `Other`: https://unpkg.com/lucide@latest/dist/umd/lucide.min.js
3. `Other`: https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.5/gsap.min.js
4. `Other`: https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.5/ScrollTrigger.min.js
5. `Other`: https://cdn.jsdelivr.net/npm/lenis@1.1.20/dist/lenis.min.js
6. `Font`: https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800;900&display=swap
7. `Main Portrait`: https://hoirqrkdgbmvpwutwuwj.supabase.co/storage/v1/object/public/assets/assets/09c772e4-09b6-4912-a345-460bbfbe16ce_1600w.png
8. `Green Strip`: https://hoirqrkdgbmvpwutwuwj.supabase.co/storage/v1/object/public/assets/assets/3b2725ca-5b05-49fe-b2ff-9de382bf26ef_1600w.webp
9. `Architecture Detail`: https://hoirqrkdgbmvpwutwuwj.supabase.co/storage/v1/object/public/assets/assets/2a6d2145-68de-4484-bde1-e7c84b2b2502_800w.png
10. `Landscape Color`: https://hoirqrkdgbmvpwutwuwj.supabase.co/storage/v1/object/public/assets/assets/bb68db84-4141-4849-b241-5c349a01444b_800w.png
11. `CPA Mockup`: https://hoirqrkdgbmvpwutwuwj.supabase.co/storage/v1/object/public/assets/assets/2e233402-8ffe-41e4-b55c-d3c2384436ff_1600w.png
12. `Archive Video`: https://hoirqrkdgbmvpwutwuwj.supabase.co/storage/v1/object/public/user-files/fed9ca1c-81d9-4744-8dd6-daed21423db2/2013aa6e-158f-49f5-9eac-60c1cf3b8df7-Chrome-Capture-2026-06-13-1.m4v?v=1781296512801
13. `Food Truck Mockup`: https://hoirqrkdgbmvpwutwuwj.supabase.co/storage/v1/object/public/assets/assets/b31a24c8-c70e-4032-81eb-81b3d9c35bbb_800w.png
14. `Structural Detail`: https://hoirqrkdgbmvpwutwuwj.supabase.co/storage/v1/object/public/assets/assets/79e4228e-37c5-45bc-a352-ae8b41b6d71b_3840w.png
15. `Mask Number Texture`: https://images.unsplash.com/photo-1551836022-d5d88e9218df?auto=format&fit=crop&w=1600&q=90

### Exported Codebase Asset Inventory
1. embed: https://fonts.gstatic.com
   Context: index.html: markup attribute; index.html: absolute url literal
2. other: https://www.googletagmanager.com/gtag/js?id=G-2M6V79H761
   Context: index.html: markup attribute; index.html: absolute url literal
3. image: https://hoirqrkdgbmvpwutwuwj.supabase.co/storage/v1/object/public/assets/assets/f40546b7-20d7-4568-851a-df21a32472f6_1600w.png
   Context: index.html: markup attribute; index.html: absolute url literal; index.html: asset string literal
4. image: https://hoirqrkdgbmvpwutwuwj.supabase.co/storage/v1/object/public/assets/assets/88578977-576e-4c52-9624-aa1fa34eae22_800w.png
   Context: index.html: markup attribute; index.html: absolute url literal; index.html: asset string literal
5. image: https://hoirqrkdgbmvpwutwuwj.supabase.co/storage/v1/object/public/assets/assets/e1f39209-cbcc-4857-bc13-744562e16d78_3840w.png
   Context: index.html: markup attribute; index.html: absolute url literal; index.html: asset string literal
6. other: https://github.com/shayn468
   Context: index.html: markup attribute; index.html: absolute url literal
7. image: https://hoirqrkdgbmvpwutwuwj.supabase.co/storage/v1/object/public/assets/assets/bf697fb6-c82a-4c34-95ec-cbfc47b8622f_3840w.png
   Context: index.html: markup attribute; index.html: absolute url literal; index.html: asset string literal
8. image: https://hoirqrkdgbmvpwutwuwj.supabase.co/storage/v1/object/public/assets/assets/095918f0-0508-4c1f-867f-ec46e9f0720d_3840w.png
   Context: index.html: markup attribute; index.html: absolute url literal; index.html: asset string literal
9. image: https://hoirqrkdgbmvpwutwuwj.supabase.co/storage/v1/object/public/assets/assets/92ae1957-bb5d-4fef-b4fe-26a43ca6c254_3840w.png
   Context: index.html: markup attribute; index.html: absolute url literal; index.html: asset string literal
10. image: https://hoirqrkdgbmvpwutwuwj.supabase.co/storage/v1/object/public/assets/assets/38e3087c-9469-4548-bb3d-7d45defa6c81_800w.png
   Context: index.html: css url()
11. other: https://images.unsplash.com/photo-1551836022-d5d88e9218df?auto=format&amp;fit=crop&amp;w=1600&amp;q=90
   Context: index.html: css url(); index.html: absolute url literal
12. other: http://www.w3.org/2000/svg
   Context: index.html: absolute url literal
