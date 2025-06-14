
# 📄 ohidreza0 portfolio?huh? – all cat-inspected, some cat-approved..
🔗 [Live site here](https://ohidreza0.arioron.com/)

Hey! 👋 If you're reading this, you're probably peeking under the hood of my portfolio(?) site. Let’s walk through what’s going on in this single-page, tailwind-fueled, cat-approved HTML file.



## General Vibes

- Built using **HTML + Tailwind CSS**
- Fonts? Fancy! It's using `Montserrat` (with Inter vibes)
- Layout? Responsive and clean (but no clutter allowed)
- Color Scheme: 
  - Primary: `#343131`
  - Accent: `#EEDF7A`
  - Backgrounds: Variants of slate for that cool dark mode aesthetic



## Navigation

- Sticky header with a smooth blur + border bottom.
- Responsive hamburger menu for mobile users – collapses neatly and toggles on tap.
- All links use smooth scroll and auto-highlight when in view (yep, no more getting lost).



## Hero Section

- Profile image with a glowing online status dot. 
- Big intro with “Hey, I'm Ohid 👋” and a quick blurb.
- Two CTA buttons: “View My Work” and “Get in Touch” – both styled for max clickability.



## About Me

- Two-column layout (flips to one on mobile).
- Left: Origin story and thoughts on solving problems.
- Right: Interest box with fun little icons (Lucide is pulling the icon duty here).

Bonus: Mentions cats, MUNs, and Calculus — the holy trinity.



## Skills Section

- Gridded cards for different domains (Langs, Web, Backend, AI/ML, DB, Soft Skills)
- Skill badges look like sweet lil' chips with solid contrast.
- Scales beautifully from mobile to wide screens.



## Projects Section

- Tabbed layout (Tools, AI, Academic) — custom JS to switch content with style.
- Every card is:
  - Clickable
  - Stack-tagged (tech used)
  - Has impact descriptions because context matters.



## Timeline

- Vertical timeline with alternating sides.
- Dots mark each year (🟢 = current year).
- On **mobile**, this section is hidden entirely (we're not squishing your eyeballs).

How? Tailwind’s `hidden md:block` class. That’s it. Clean.



## Journal

- “Coming Soon” message.
- Hints at blog posts about failed projects, random life updates, maybe a cat pic or two.

Stay tuned. Or don’t. The semester decides.



## Contact

- Two big buttons: email + GitHub
- Fully mobile-friendly and click-ready.



## Favicon

Yes, that tiny cat icon in the tab? Totally intentional. It's not just a vibe — it’s a **data URI SVG emoji**. No extra files, no fluff.

```html
<link rel="icon" href="data:image/svg+xml,<svg xmlns=%22http://www.w3.org/2000/svg%22 viewBox=%220 0 100 100%22><text y=%22.9em%22 font-size=%2290%22>😸</text></svg>">
```



## Cleanup & Scripting

- Custom JS handles:
  - Tab switching
  - Scroll-activated nav link highlighting
  - Smooth scroll
  - Mobile menu toggle

No jQuery, no nonsense.



## Final Notes

- Timeline responsiveness? Fixed (or rather, **hidden** for small screens)
- Nav gaps, underlines, colors? All polished 
- Font + logo? Using `Inter` vibes via Montserrat 
- Emoji favicon? 😸 Hell yah



Built with caffeine, code, and a questionable number of cat distractions.
**— ohidreza0** june 14
