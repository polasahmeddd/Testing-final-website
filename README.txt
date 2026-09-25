POLAS AHMED PORTFOLIO — UNIFIED SITE PACKAGE
============================================

This package is the updated version of the supplied GitHub Pages repository.

WHAT WAS CHANGED
----------------
1. A single, consistent portfolio header is now used across all 13 HTML pages.
2. The portfolio header is sticky at the top of the page.
3. Home, About, Skills, Projects and Contact use the same navigation structure.
4. All eight individual SEO case-study pages now use the same main portfolio header.
5. The old case-study-specific headers are visually disabled so their existing
   page scripts remain safe without showing a second header.
6. A single professional footer is used across the entire website.
7. The footer includes navigation, expertise links, LinkedIn, GitHub and email.
8. The header and footer are responsive for desktop and mobile screens.
9. The active navigation item is selected automatically based on the current page.
10. Individual case studies are treated as part of the Projects section, so
    Projects is highlighted while a case-study page is open.
11. The existing page content, case-study content and image assets were preserved.
12. Broken project-folder links found in index.html were changed to the actual
    root-level case-study filenames in this repository.

REPOSITORY STRUCTURE
--------------------
Keep the files in the same root-level structure used by GitHub Pages:

portfolio-site/
├── index.html
├── about.html
├── skills.html
├── projects.html
├── contact.html
├── better-appliance-dmv.html
├── better-appliance-md.html
├── iv-better.html
├── legacy-rides.html
├── deluxeside.html
├── streetwearness.html
├── highclassrep.html
├── aqualuxe.html
├── assets/
├── images/
├── README.md
└── README.txt

GITHUB PAGES
------------
Upload/replace the files in your GitHub repository while preserving the
assets/ and images/ folders.

Do not put the HTML files into additional subfolders. The navigation and
case-study links are written for the root-level structure shown above.

IMPORTANT NOTE ABOUT RESUME
---------------------------
The supplied repository does not currently contain resume.pdf. The unified
header keeps the existing Resume button and its resume.pdf target. If you want
the Resume button to work, upload a file named exactly:

resume.pdf

at the repository root.

If you do not want a resume link, change that button later to another valid
page or destination.

HEADER BEHAVIOR
---------------
The same header appears on:
- index.html
- about.html
- skills.html
- projects.html
- contact.html
- all eight case-study pages

On desktop it shows the full navigation and Resume/Hire Me actions.
On mobile it changes to a compact menu button.

FOOTER BEHAVIOR
---------------
The same footer appears on every page. The older page-specific footers are
visually disabled so there is only one visible footer.

CASE STUDY BEHAVIOR
-------------------
The unique content and design of each case study remain in place. The old
case-study navigation bars are no longer displayed as the website's main
header. The global portfolio header is the only visible main header.

BACKUP
------
Before replacing your live GitHub files, keep the original ZIP you downloaded
from GitHub as a backup.
