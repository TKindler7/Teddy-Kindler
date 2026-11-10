# Teddy Kindler's Coding Portfolio

My portfolio for **Coding with AI at Menlo School**. This site is a place to share the games and apps I build, link to working projects, and document what I learn along the way.

**[Visit the portfolio](https://tkindler7.github.io/Teddy-Kindler/)**

## Projects

### Little Rehearsal

[Open Little Rehearsal](https://little-rehearsal.tk7272.chatgpt.site/)

An app that helps actors learn their lines, one scene at a time. It supports short daily practice sessions and progress tracking, with encouragement from a playful scarecrow rehearsal buddy. It is designed with iPad practice in mind.

Sign in with ChatGPT in the app to save plays and progress. Little Rehearsal is hosted separately; this repository contains its portfolio listing, not the app's source code.

### Good Hour Diner

[Open Good Hour Diner](https://appledesignlanguageamericandinerdop.vercel.app/) · [View the source on GitHub](https://github.com/TKindler7/GoodHourDiner)

A fictional American diner with 23 original dishes, ingredient customization, interactive 3D previews, meal building, an animated kitchen, and a receipt that reflects the money not spent. No payment or delivery occurs. The app is hosted separately on Vercel; its source code is in the GoodHourDiner repository.

The portfolio card includes a screenshot of the diner menu (`assets/good-hour-diner-screenshot.jpg`).

### Questline

[Open Questline](https://tkindler7.github.io/Teddy-Kindler/questline/) · [View the source on GitHub](https://github.com/TKindler7/Teddy-Kindler/blob/main/questline/index.html)

A medieval homework planner starring the Menlo Knight. Organize assignments as quests, divide larger projects into boss battle stages, and complete Pomodoro focus sessions to earn XP and grow your castle. Subjects, assignments, and progress are saved in the current browser using localStorage; no account is required.

The portfolio card includes a live app preview. The complete app is hosted in this repository at `questline/index.html` and uses plain HTML, CSS, JavaScript, Canvas, and synthesized Web Audio, with no external dependencies.

### Orbit Breakout

[Explore Orbit Breakout](https://tkindler7.github.io/Teddy-Kindler/orbit-breakout/)

A native Unreal Engine 5.8 sci-fi escape game featuring two weapons, enemy awareness, a solo Bull Sentinel boss and an escape sequence. The showcase explains the gameplay, development approach, controls and verification status. There is no browser demo or current standalone download. The complete editable game is in [TKindler7/OrbitBreakout](https://github.com/TKindler7/OrbitBreakout), a private repository containing the source, saved level and licensed assets. Access requires permission from the owner.

### Name Game — coming soon

A planned game for matching names to faces. The portfolio currently includes a placeholder card; the game files and live demo are not yet in this repository.

## How the site works

The portfolio uses plain HTML and CSS and is published with GitHub Pages.

- All page content and styling live in `index.html`.
- CSS variables control the colors.
- The project grid uses one column on narrow screens and two columns at widths of 620 pixels and above.
- There are no JavaScript dependencies, package installs, or build commands needed to preview the portfolio.

## Repository structure

```text
Teddy-Kindler/
├── index.html   # Portfolio homepage and CSS
├── assets/      # Project screenshots
├── questline/   # Questline app (index.html)
└── README.md    # Project overview and editing guide
```

## Preview locally

Download or clone this repository, then open `index.html` in a web browser. Edit the file in a text editor and refresh the browser to see your changes.

## Update the portfolio

1. Edit the introduction or project cards in `index.html`.
2. To add a project, copy an existing `<div class="card">` block inside `<div class="projects">`.
3. Replace the title, description, and link with the new project's details. Use its full URL if hosted elsewhere, or a relative link such as `./project-name/` if its files are in this repository.
4. Check the page at narrow and wide window sizes, and click each project link.
5. Commit the changes to `main`. GitHub Pages publishes updates automatically; check the repository's [Actions page](https://github.com/TKindler7/Teddy-Kindler/actions) for deployment status.

Only enable a demo link once its destination is ready.

---

Built by hand + AI for Coding with AI, Menlo School.
