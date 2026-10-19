# TuteDude MERN Stack – Task: CSS Laundry Services Button Interactive (Transforms)

## Files Included
- `index.html` — HTML structure
- `style.css` — CSS with Transforms and Hover Effects
- `README.md` — This file

## How to Run
1. Unzip the folder.
2. Open `index.html` in Chrome or Firefox.
3. Hover over the **"Book a service today!"** button to see the effect.

## Hover Effect on CTA Button

| CSS Property | Value | Effect |
|---|---|---|
| `transform: scale(1.12)` | 1.12 | Button grows 12% bigger on hover |
| `transform: rotate(-6deg)` | -6deg | Button tilts to the left on hover |
| `transition: 0.3s ease` | 0.3s | Smooth animation in and out |

## CSS Used
```css
.book-btn {
  transition: transform 0.3s ease, background-color 0.3s ease;
}

.book-btn:hover {
  transform: scale(1.12) rotate(-6deg);
  background-color: #0399d4;
}
```

## Key Concepts
- **CSS Transform** — used to visually change an element's size, rotation, position
- **scale()** — increases or decreases size of the element
- **rotate()** — tilts the element by a given degree
- **transition** — makes the change animate smoothly instead of jumping
- **:hover pseudo-class** — triggers styles when the mouse is over the element

## Requirements Completed
- ✅ Button size increases on hover (`scale`)
- ✅ Button looks tilted on hover (`rotate`)
- ✅ Smooth animation using `transition`
- ✅ No JavaScript used — pure CSS only
- ✅ No Bootstrap
- ✅ CSS properly linked to HTML

## Submission
1. Put all 3 files in one folder (e.g. `YourName_Task9/`)
2. Compress to `.zip`
3. Rename → `YourName_Task9.zip`
4. Upload ZIP + deployed link on TuteDude portal