# LOG.md: TCSS 490 Portfolio (Artifact 1)

**Author:** Harman Sandhu
**Repo:** https://github.com/hsandhu14/Portfolio
**Live site:** https://hsandhu14.github.io/Portfolio/

This is my record of what I asked the AI for while building my portfolio site, what came back, and what I changed along the way.

## Setup

- **Chat AIs used:** ChatGPT first, then Claude (free plan)
- **Stack:** Plain HTML with Tailwind CSS (CDN), FontAwesome icons, and the Inter font. A single `index.html`, front end only.
- **Hosting:** GitHub Pages

## Entry 1: First attempt in ChatGPT

**What I asked:** I asked ChatGPT to build the portfolio site from the Artifact 1 assignment: an intro, five artifact cards, and links for my log and repository.

**What came back:** A working page with the cards and links in place.

**What I changed / what it misread:** The colors were too light for me and I prefer darker colors. I put together my own darker design (`portfolio_temp.html`) with a dark-mode toggle, a sticky header, a hero section, and a card grid where Artifact 1 is highlighted as "Active" and cards 2 to 5 are dimmed as "Upcoming".

## Entry 2: Switching to Claude

**Why I switched:** I wanted to try something new and learn to use Claude better, since we will be using Claude Code for the rest of the term.

**What I asked:** I gave Claude the full assignment text and asked it to help build the site.

**What came back:** A simple single-page site with an intro, five cards with title, link, and reflection areas, plus a template for this log. It used plain CSS with a light or dark theme based on the device setting.

**What I changed / what it misread:** It was not the look I wanted, so I kept using my own darker Tailwind design and used Claude for edits to it.

## Entry 3: Adding my name

**What I asked:** I shared my page and asked Claude to add my name, Harman Sandhu.

**What came back:** My name added in the browser tab title, the header brand (logo changed from "CS" to "HS"), the hero badge, and the footer. The rest of my design stayed the same.

**What I changed / what it misread:** Nothing needed fixing. Claude also pointed out what the page was still missing for the assignment: an About section, a reflection on the Artifact 1 card, ideas on cards 2 to 5, working links, and this log file.

## Entry 4: About Me section

**What I asked:** I told Claude I'm a senior at UW Tacoma, that I enjoy coding, and that my goal is to build five nice artifacts I can use on my resume.

**What came back:** A new "About Me" section between the hero and the artifacts grid, matching the rest of the design.

**What I changed / what it misread:** Nothing needed fixing.

## Entry 5: Links

**What I asked:** I gave Claude my GitHub username (`hsandhu14`) and repo name (`Portfolio`) and asked it to fill in the links.

**What came back:** All five placeholder `#` links were replaced. The two LOG.md buttons point to `LOG.md` in the repo and the three repository buttons point to the repo itself. They open in a new tab.

**What I changed / what it misread:** Claude could not test the links in a browser, so I need to click each one after deploying.

## Entry 6: Ideas for cards 2 to 5

**What I asked:** I asked the AI for ideas for what I could use as placeholders on cards 2 to 5. I told it I want to make a web app for one of my projects this quarter, and that even a calendar would be nice.

**What came back:** Four ideas, starting with my calendar web app idea, plus ideas for a data tool, a study tool, and something for a real user.

**What I kept:** These are only brainstorming and I am not held to them:
- Artifact 2: a calendar web app
- Artifact 3: an expense tracker with charts
- Artifact 4: a study tool that turns class notes into flashcards and quizzes
- Artifact 5: a tool for a real user, such as a club or small business

## Deployment

1. Uploaded `index.html` and `LOG.md` to the root of the `Portfolio` repo.
2. Turned on GitHub Pages (Settings > Pages, deploy from the `main` branch, root folder).
3. Opened the live site and tested the buttons and the theme toggle.

## Reflection

- **What went well:** I knew the look I wanted, so I built my own darker design, then used Claude for quick edits like my name, the About section, and the links.
- **Where the AI misread me:** Both first versions (ChatGPT's and Claude's) had lighter colors than I wanted, so neither was the final look.
- **What I'd do differently:** I would think about what I want to ask Claude and come up with a plan first, instead of winging what to say.
- **Did I switch AIs?** Yes, from ChatGPT to Claude, to try something new and learn to use Claude better before we use Claude Code for the rest of the term.
