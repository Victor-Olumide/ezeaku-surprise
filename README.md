# Birthday Tribute Website

A multi-page birthday tribute website celebrating Engr. Iyke Ezeaku with a birthday message, personal letter, biography, achievements, memories, photos, and video.

## Pages

- `index.html` - Home page with the main birthday hero and quick links.
- `second.html` - Birthday letter page with a photo slideshow.
- `about.html` - About page describing Dad's life, values, and impact.
- `achievements.html` - Achievements page highlighting education, honors, and leadership milestones.
- `memories.html` - Photo and video gallery of family memories.

Each page has its own stylesheet:

- `index.css`
- `second.css`
- `about.css`
- `achievements.css`
- `memories.css`

## Assets

All photos and videos are stored in the `media/` folder. The pages reference images and video using relative paths such as:

```html
./media/new.jpeg
./media/27v.mp4
```

Keep new images or videos inside `media/` so the links remain organized.

## How To Run

No build tools or server are required. Open `index.html` directly in a browser.

Recommended start file:

```text
index.html
```

From there, use the navigation links to visit the other pages.

## Project Structure

```text
.
|-- index.html
|-- index.css
|-- second.html
|-- second.css
|-- about.html
|-- about.css
|-- achievements.html
|-- achievements.css
|-- memories.html
|-- memories.css
`-- media/
    |-- images
    `-- videos
```

## Customization

To change text, edit the matching `.html` file.

To change colors, spacing, fonts, or layout, edit the matching `.css` file. The main design colors are defined near the top of each CSS file inside `:root`.

To replace photos, add the new file to `media/` and update the matching `src` attribute in the HTML.

## Notes

The project uses plain HTML and CSS only, so it is easy to host on GitHub Pages, Netlify, Vercel, or any static hosting service.
