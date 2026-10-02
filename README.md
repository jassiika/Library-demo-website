# Greenwood Public Library – Landing Page

A minimal, editorial-style landing page for a public library, built with HTML and **native Tailwind CSS via the CDN**. No other CSS frameworks and no custom fonts.

## Run it
Keep `index.html` and the `images/` folder together, then open `index.html` in a browser. An internet connection is needed to load the Tailwind CDN.

## Sections
1. Sticky navbar with `backdrop-blur-md`, "Open Sat" badge, animated underline links (`after:w-0 hover:after:w-full`) and an inverting "Visit Us" pill. Links are hidden on mobile.
2. Hero with light headline, two CTAs, hover-zoom image (`hover:scale-105`) and a 4-column stats row.
3. Sections grid (1 column mobile, 2 desktop) with six cards, each with its own hover background and animated text colours.
4. Gallery: 2x2 image grid with `overflow-hidden`, `rounded-lg`, `group-hover:scale-105` and floor tags.
5. Values bento grid built with column and row spans and pastel cards.
6. About text using `columns-1 sm:columns-2`.
7. Membership: intro card plus Basic, Student (with "Popular" badge) and Family cards, with `brightness-95` headers and hover zoom.
8. Testimonial with a grayscale avatar that turns to colour on hover (`grayscale hover:grayscale-0 transition-all duration-500`).
9. Contact block with tinted background, address, opening hours, "Get Directions" and mailto buttons.
10. Events: 4-column grid with image zoom, title and date.
11. Footer with Brand, Pages, Sections and Details columns, social circles and a legal row.

## Tailwind setup
Custom `fadeUp` and `fadeIn` keyframes and animations are added in the inline `tailwind.config`. Content below the hero fades up with staggered delays when it scrolls into view. Motion is turned off for visitors who prefer reduced motion. Containers use `max-w-7xl`.

## Images (in `images/`)
`sheld.jpg` (hero), `reading_room.jpg`, `childrem_area.jpg`, `study_hall.jpg`, `digital_workspace.jpg` (gallery), `basic.jpg`, `student.jpg`, `family.jpg` (membership), `avatar.jpg` (testimonial), `author_meet.webp`, `book_club.jpg`, `summer_reading.jpg`, `archive.jpg` (events).

## Notes
Text, address, prices and dates are placeholder content. Swap them for the real details before submitting.
