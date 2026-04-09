# AlaEddine Derbel - *Portfolio*

> Personal portfolio website of AlaEddine Derbel, Embedded Systems Engineer.  
> Built with pure HTML, CSS, and vanilla JavaScript.

🌐 **Live**: [alaeddinederbel.github.io](https://alaeddinederbel.github.io)

---

## Preview

```
Loader animation (0–100%) → Home → About → Skills → Experience → Projects → Contact
```
---

## Features

- **Animated loader** : embedded-themed boot sequence (0% → 100%)
- **Typewriter effect** : cycling through roles in the hero section
- **Interactive terminal** : fully functional CLI in the contact section (type `help` to start)
- **CV version picker** : dropdown to download CV with or without photo
- **Education timeline** : clean vertical timeline in the About section
- **Project pipeline diagrams** : data-flow notation for each project
- **GitHub links** : every project and internship linked to its repository
- **Scroll fade-in animations** : sections animate on scroll via IntersectionObserver
- **Responsive design** : mobile-first, works on all screen sizes
- **No frameworks** : zero dependencies, zero build step

---

## Tech Stack

| Layer      | Technology                          |
|------------|-------------------------------------|
| Structure  | HTML5                               |
| Styling    | CSS3 (custom properties, grid, flexbox) |
| Logic      | Vanilla JavaScript (ES6+)           |
| Icons      | Font Awesome 6.7.1                  |
| Fonts      | Google Fonts : Syne + Space Mono    |
| Hosting    | GitHub Pages                        |

---

## Project Structure

```
portfolio/
├── index.html                         # Main HTML file
├── style.css                          # All styles
├── images/
│   └── cyan.png                       # Hero profile image
└── cv/
    ├── AlaEddine_Derbel_CV.pdf        # With photo
    └── CV_AlaEddine_Derbel.pdf        # Without photo
```

---

## Sections

| Section     | Description                                              |
|-------------|----------------------------------------------------------|
| Home        | Hero with typewriter, profile image, stats row           |
| About       | Bio, quick facts, education timeline                     |
| Skills      | 7 skill cards with tech tags                             |
| Experience  | Vertical timeline with 3 internships                     |
| Projects    | 4 project cards with pipeline diagrams and GitHub links  |
| Contact     | Info cards + interactive terminal + work preferences     |

---

## Terminal Commands

The contact section includes a working terminal. Available commands:

```bash
help      # List all commands
about     # Who I am
skills    # Technical skills
contact   # How to reach me
projects  # My projects
status    # Current availability
clear     # Clear the terminal
```
 
**NB:** Feel free to use it as inspiration, just don't copy it directly without attribution.

---

*Designed & built by **AlaEddine Derbel** - Embedded Systems Engineer*
