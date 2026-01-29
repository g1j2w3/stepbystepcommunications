# Step By Step Communications Website

## Folder Structure

```
stepbystepcommunications/
├── index.html              (Home page)
├── about.html              (About page)
├── services.html           (Services page)
├── accomplishments.html    (Accomplishments page)
├── clients.html            (Clients page)
├── README.md
└── images/
    ├── logo.webp                    (✓ Already included)
    ├── hero-bg.jpg                  (Home - Chicago skyline night, dark)
    ├── about-hero.jpg               (About - Chicago skyline, golden/sepia tones)
    ├── elverage-allen.jpg           (About - Photo of Elverage Allen with award)
    ├── services-hero.jpg            (Services - Chicago skyline night)
    ├── service-strategy.jpg         (Services - Strategy/analytics image)
    ├── service-multicultural.jpg    (Services - Diverse hands/team image)
    ├── service-planning.jpg         (Services - Planning/wireframe image)
    ├── service-creative.jpg         (Services - Creative/paint splatter image)
    ├── accomplishments-hero.jpg     (Accomplishments - Team group photo)
    ├── client-outlaw.jpg            (Clients - OUTLAW western channel promo)
    └── client-the365.jpg            (Clients - THE365 promo, teal colors)
```

## Page Navigation

All pages link to each other through the navigation menu. Here's how the linking works:

### Header Navigation (all pages)
- Home → `index.html`
- About → `about.html`
- Services → `services.html`
- Accomplishments → `accomplishments.html`
- Clients → `clients.html`

### Footer Quick Links (all pages)
Same links as header navigation.

### Page-Specific Links

**Home Page (index.html)**
- "Learn More" button in hero → `about.html`
- "Learn more" button in About section → `about.html`
- "Read More on Accomplishments" button → `accomplishments.html`
- "The Diversity Discussion" link → External: `http://www.thediversitydiscussion.com/speaker/elverage-allen/`

**About Page (about.html)**
- "Learn About Accomplishments" button → `accomplishments.html`
- "Contact us to get started" link → `contact.html` (if you create this page)

**Services Page (services.html)**
- "CONTACT US" button → `contact.html` (if you create this page)

**Accomplishments Page (accomplishments.html)**
- "CONTACT US" button → `contact.html` (if you create this page)

## Images Required

### Home Page (index.html)
- `images/hero-bg.jpg` - Chicago skyline at night (dark, with city lights and water reflection)

### About Page (about.html)
- `images/about-hero.jpg` - Chicago skyline with golden/sepia tones
- `images/elverage-allen.jpg` - Photo of Elverage Allen with Broadcast & Cable award

### Services Page (services.html)
- `images/services-hero.jpg` - Chicago skyline at night
- `images/service-strategy.jpg` - Strategy/whiteboard/analytics image (square)
- `images/service-multicultural.jpg` - Diverse team hands together (square)
- `images/service-planning.jpg` - Planning/wireframe/sketching image (square)
- `images/service-creative.jpg` - Creative/colorful paint splatter (square)

### Accomplishments Page (accomplishments.html)
- `images/accomplishments-hero.jpg` - Team group photo

### Clients Page (clients.html)
- `images/client-outlaw.jpg` - OUTLAW The Western Channel promotional image
- `images/client-the365.jpg` - THE365 promotional image (teal/cyan colors)

## GitHub Pages Deployment

1. Create a new repository on GitHub
2. Upload all files maintaining the folder structure above
3. Go to Settings > Pages
4. Set Source to "Deploy from a branch"
5. Select "main" branch and "/ (root)" folder
6. Save - your site will be live at `https://[username].github.io/[repo-name]/`

## Notes

- All navigation links use relative paths (e.g., `about.html` not `/about.html`)
- Images use relative paths from the HTML files (e.g., `images/logo.webp`)
- The site is fully responsive with mobile hamburger menu
- No external dependencies except Google Fonts
- Contact buttons currently link to `contact.html` - create this page or update links as needed
