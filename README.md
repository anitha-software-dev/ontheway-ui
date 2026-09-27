# On The Way (OTW)

An interactive, responsive web platform for **On The Way (OTW)** — an initiative dedicated to educating, inspiring, and mobilizing individuals and communities for cross-cultural missions, faith engagement, and cultural understanding of Buddhist and Hindu communities worldwide.

---

## 🚀 Key Features

- **Interactive 21-Day Journey Hub**: A multi-day guided devotional and educational curriculum with day-by-day modules, embedded audio reflections, scripture focus, and interactive daily journal prompts (`21-day-main.html`, `21-day-hub.html`, `21-day-journal-day1.html`).
- **World & Cultural Exploration Hub**: In-depth cultural spotlights, demographic data, and spiritual traditions across South and Southeast Asia—including Bhutan, Thailand, Cambodia, Nepal, India, and Sri Lanka (`buddhist-hindu-world.html`, `buddhism.html`, `hindhuism.html`).
- **Interactive Multi-Step Readiness Quiz**: A 9-step guided assessment ("Where do I go from here?") that walks users through personal motivations, cross-cultural readiness, and contact inquiries with visual progress indicators (`start.html`, `quiz-page1.html` through `quiz-page10.html`).
- **Action Triad (Pray, Give, Go)**: Dedicated engagement pathways allowing users to explore curated prayer guides, financial support / giving tiers, and mission application onboarding ("Ready to Go?") (`pray-give-go.html`, `pray.html`, `give-page.html`, `go-page.html`).
- **Rich Media & Video Gallery**: "The Joy Project" visual media library featuring high-resolution photography, responsive lightbox galleries, and Vimeo video players (`joy-gallery.html`, `joy-video-single.html`).
- **Engaging UI & Animations**: Dynamic word rotators, responsive country statistics carousels, smooth scroll navigation, and custom interactive components.

---

## 🛠️ Technologies Used

- **Frontend Core**: HTML5, CSS3, JavaScript (ES6+)
- **UI Framework**: [Bootstrap 5](https://getbootstrap.com/) (Responsive Grid, Modals, Flexbox utilities)
- **Sliders & Carousels**: [Owl Carousel 2](https://owlcarousel2.github.io/OwlCarousel2/)
- **Lightboxes & Media**: [Magnific Popup](https://dimsemenov.com/plugins/magnific-popup/)
- **Animations & Effects**: Circle Flip Slideshow, GSAP, Animate.css, Vivus
- **Typography & Icons**: [FontAwesome 6](https://fontawesome.com/), Simple Line Icons, Google Fonts (Poppins, Shadows Into Light)
- **Performance**: Lazysizes (progressive image loading), Modernizr (feature detection)
- **Backend Utilities (Optional Templates)**: PHP (PHPMailer for contact forms, Mailchimp newsletter integration, social feed utilities)

---

## 📂 Project Structure

```
ontheway-ui/
├── index.html                  # Main homepage with country spotlights & mission intro
├── 21-day-main.html            # 21-Day Journey landing and overview
├── 21-day-hub.html             # Interactive 21-Day Journey curriculum hub
├── 21-day-journal-day1.html    # Day 1 interactive reflection journal
├── 21-day-journey-day4+.html   # Day 4+ devotional and reflection modules
├── 21-day-last.html            # 21-Day Journey completion summary
├── buddhist-hindu-world.html   # World demographic explorer & statistics
├── buddhism.html               # Buddhist culture & faith overview
├── hindhuism.html              # Hindu culture & faith overview
├── pray-give-go.html           # Main action hub (Pray, Give, Go)
├── pray.html                   # Guided prayer focuses and requests
├── give-page.html              # Giving and sponsorship portal
├── go-page.html                # Mission onboarding & application inquiry
├── start.html                  # Readiness quiz landing page
├── quiz-page1.html - page10.html # Multi-step readiness assessment funnel
├── send-me-quiz.html           # Quiz submission & results confirmation
├── joy-gallery.html            # "The Joy Project" photo and media gallery
├── joy-video-single.html       # Video feature player page
├── Utility.html                # UI component and style reference guide
├── assets/                     # Media assets (images, audio tracks, video clips)
├── css/                        # Custom stylesheets, themes, and skins
├── js/                         # Theme logic, view controllers, and initializations
├── php/                        # Backend contact form & API integration templates
└── vendor/                     # Third-party CSS/JS vendor libraries
```

---

## ⚡ Getting Started

### Prerequisites

A modern web browser (Google Chrome, Mozilla Firefox, Microsoft Edge, or Safari).

### Local Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/anitha-software-dev/ontheway-ui.git
   cd ontheway-ui
   ```

2. **Run locally:**
   - You can open `index.html` directly in any web browser.
   - Or serve with a local development server for full feature support (recommended for AJAX / media):
     ```bash
     # Using Python:
     python -m http.server 8000

     # Using Node.js (npx serve):
     npx serve .

     # Using VS Code:
     # Right-click index.html and select "Open with Live Server"
     ```

3. Open your browser and navigate to `http://localhost:8000`.

---

## 📱 Responsive & Cross-Browser Support

- Fully responsive across desktop, tablet, and mobile breakpoints.
- Tested and optimized for modern evergreen browsers: Chrome, Firefox, Safari, Edge.

---

## 👤 Author

**Anitha**
- GitHub: [@anitha-software-dev](https://github.com/anitha-software-dev)
