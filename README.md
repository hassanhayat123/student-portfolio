# Student Portfolio - University Clubs Portal

A small static website for our university's Student Clubs Portal, built as a group
project for DevOps Fundamentals (Assignment 01).

The site introduces the student clubs on campus and helps new students find a club,
see upcoming events and learn how to join.

## Pages

| Page | File | Owner |
|------|------|-------|
| Home | `src/index.html` | Team Lead (Hassan Hayat) |
| Club Categories | `src/clubs.html` | Team Lead (Hassan Hayat) |
| Upcoming Events | `src/events.html` | Team Lead (Hassan Hayat) |
| How to Join | `src/join.html` | Member (Abeer Arif) |
| Highlights | `src/highlights.html` | Member (Abeer Arif) |

All pages share one stylesheet: `styles/style.css`.

## Branches

- `main` - production ready code
- `develop` - all active development is merged here
- `feature/<page-name>` - one branch per page, opened as a PR into `develop`
- `release/v1.0` - release branch for testing before it goes to `main`

## Team

| Name | GitHub | Role |
|------|--------|------|
| Hassan Hayat | hassanhayat123 | Team Lead |
| Abeer Arif | sameedsaeed123 | Member |

## Running it

No build step. Clone the repo and open `src/index.html` in a browser.

```
git clone https://github.com/hassanhayat123/student-portfolio.git
cd student-portfolio
open src/index.html
```

## Releases

- **v1.0** - first release with all five pages, responsive layout and current page highlight in the nav.
