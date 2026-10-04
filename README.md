# Hexed News

Hexed News is a student-made, horror-themed news website presented as an independent publication reporting from the edges of the unexplained. Its stories cover fictional local sightings, eerie places, and gaming mysteries. The site uses a dark, newspaper-inspired visual style, with short headlines, bylines, story categories, and recurring newsroom details to make the pages feel like parts of one publication.

## What’s on the site

### The Daily

The home page introduces the publication with a featured story about voices coming from the woods near Black Hollow. Below it is a selection of recent stories, including reports of unexplained lights over Lake Apopka and an arcade cabinet that appears to keep playing after closing. Links on the lead story and story cards take readers to the related section.

### Local Haunts

This section focuses on mysterious places and reports from the surrounding area. It features an investigation about a supposedly empty house on Cypress Road, followed by short reports set around Lake Apopka, Seminole County, and Winter Park.

### Gamer Graveyard

This section collects fictional gaming folklore: unexplained high scores, impossible game levels, strange multiplayer lobbies, returning save files, and other digital oddities. Its stories use gaming language and imagery to distinguish it from the local-reporting section.

### Contact

The contact page provides a tip form with optional name and email fields, a required subject selection, and a required message. The form is configured to open an email to `tips@hexed.news` using the visitor’s email application.

## Design and behavior

- All four pages share a masthead, edition bar, section navigation, and footer.
- The active navigation link indicates which section is currently open.
- The stylesheet provides the site’s colors, typography, story layouts, image treatments, form controls, and responsive rules for narrower screens.
- Story photography is assigned through external image URLs in `style.css`; an internet connection is needed to load those images.
- The pages are static HTML and CSS. There is no JavaScript, server, database, or build process.

## Open the site

1. Keep the HTML pages and `style.css` together in the same folder.
2. Open `index.html` in a modern web browser.
3. Use the navigation at the top of each page to browse the sections.

For local development, you can also open the folder in a code editor and edit the HTML and CSS directly. Save a file and refresh the browser to see the update; no compilation step is required.

## Project files

| File | Purpose |
| --- | --- |
| `index.html` | Home page and latest-story selection |
| `local_haunts.html` | Local mysteries and featured investigation |
| `gamers_graveyard.html` | Gaming mysteries and folklore |
| `contact.html` | Newsroom tip form |
| `style.css` | Shared visual styles and responsive layouts |

## Notes and limitations

The contact form is a front-end mail link, not a secure submission service. Whether it opens successfully depends on the visitor having an email application configured. The site does not receive, validate on a server, or store tips, and it cannot guarantee anonymous or confidential delivery. The “secure channel” wording on the page is part of its visual theme, not a claim of technical encryption.

## Content Attribution
Please note that the news articles, headlines, and story text used in this project were generated using AI. The text serves purely as placeholder content to demonstrate the CSS Grid layouts, typography, and responsive design requirements of this assignment.
