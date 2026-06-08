# kaito-portfolio

Personal engineering portfolio — [live site](https://YOUR-USERNAME.github.io/kaito-portfolio)

## Structure

```
index.html              ← Main landing page (hero, projects grid, experience)
subc-hull.html          ← SUBC Hull Team Lead project page
subc-steering.html      ← SUBC Steering Member project page
rc-car.html             ← RC Car project page
mech368.html            ← MECH 368 Instrumentation Lab page
PROJECT-TEMPLATE.html   ← Copy this to add new projects
images/                 ← Drop all photos here
```

## Adding images

Name your images descriptively and drop them in `images/`. Then in the HTML, replace:

```html
<div class="img-placeholder">[ ... ]</div>
```

with:

```html
<img src="images/your-image.jpg" alt="Description" />
```

inside the existing `<div class="img-full">` wrapper.

## Adding a new project

1. Copy `PROJECT-TEMPLATE.html` → `your-project-name.html`
2. Edit all `<!-- EDIT: -->` sections
3. Add your images to `images/`
4. Add a card to `index.html` in the `projects-grid` div (template comment is already there)
5. Update the `← / →` nav links at the bottom of adjacent project pages

## Deploying to GitHub Pages

1. Create a repo named `kaito-portfolio` (or `YOUR-USERNAME.github.io` for root site)
2. Push all files
3. Settings → Pages → Source: main branch, root folder
4. Live in ~60 seconds
