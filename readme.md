# CampusOS

CampusOS is a student-focused college portal built with semantic HTML5 and CSS3. It brings academic guidance, campus events, student life, learning resources, and support information together in one responsive experience.

## Pages

- `index.html` — overview, quick access, upcoming events, and campus highlights
- `academics.html` — subjects, study resources, academic information, exams, and study tips
- `events.html` — featured event, categories, upcoming events, and participation benefits
- `campus-life.html` — clubs, hostel life, cafeteria, sport, and student activities
- `resources.html` — coding, study, career, learning-platform, and student-service resources
- `contact.html` — support information, contact form, and FAQs

## Project structure

```text
CampusOS/
├── index.html
├── academics.html
├── events.html
├── campus-life.html
├── resources.html
├── contact.html
├── css/
│   └── style.css
└── assets/
    ├── images/
    │   ├── academics/
    │   │   └── coding-collaboration.jpg
    │   ├── campus/
    │   │   ├── campus-library.jpg
    │   │   └── technology-space.jpg
    │   ├── community/
    │   │   └── student-team.jpg
    │   ├── events/
    │   │   └── campus-event.jpg
    │   └── resources/
    │       └── study-library.jpg
    ├── icons/
    └── logos/
```

## Visual system

The design keeps CampusOS’s dark navy foundation and cyan/purple accents, with responsive grids, image-led feature sections, glass-like overlays, subtle gradients, and accessible focus states. Photographs are used only where they clarify the page topic: collaborative coding for Academics, a student gathering for Events, a project team for Campus Life, books for Resources, and a work space for Contact.

## Image sources

The photographs are downloaded from [Unsplash](https://unsplash.com/) and are used under the [Unsplash License](https://unsplash.com/license). The local files retain the original Unsplash image IDs in the download URLs used during selection:

- `campus-library.jpg` — `photo-1498243691581-b145c3f54a5a`
- `coding-collaboration.jpg` — `photo-1531482615713-2afd69097998`
- `campus-event.jpg` — `photo-1517457373958-b7bdd4587205`
- `student-team.jpg` — `photo-1521737604893-d14cc237f11d`
- `study-library.jpg` — `photo-1521587760476-6c12a4b040da`
- `technology-space.jpg` — `photo-1519389950473-47ba0277781c`

## Technical notes

- HTML5 and CSS3 only
- No JavaScript or frontend framework
- Responsive layouts for desktop, tablet, and mobile
- The contact form is a complete static HTML form and needs a backend endpoint to process submissions
