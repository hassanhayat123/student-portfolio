# Student Portfolio - University Clubs Portal

A small static website for our university's Student Clubs Portal, built as a group
project for DevOps Fundamentals (Assignment 01).

The site introduces the student clubs on campus and helps new students find a club,
see upcoming events and learn how to join.

## Pages

| Page | File | Owner |
|------|------|-------|
| Home | `src/index.html` | Team Lead |
| Club Categories | `src/clubs.html` | Team Lead |
| Upcoming Events | `src/events.html` | Team Lead |
| How to Join | `src/join.html` | Member |
| Highlights | `src/highlights.html` | Member |

All pages share one stylesheet: `styles/style.css`.

## Branches

- `main` - production ready code
- `develop` - all active development is merged here
- `feature/<page-name>` - one branch per page, opened as a PR into `develop`
- `release/v1.0` - release branch for testing before it goes to `main`

## Running it

No build step. Just open `src/index.html` in a browser.
