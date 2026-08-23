# Technical write-ups

This repository is the source of truth for every write-up published on my portfolio: software engineering, UI and UX, cybersecurity, product development and future areas of study.

## Adding a write-up

1. Copy [`WRITEUP_TEMPLATE.md`](WRITEUP_TEMPLATE.md) into a new top-level directory as `README.md`.
2. Complete every required frontmatter field at the beginning of the file.
3. Store screenshots in an `assets` directory next to the write-up and use relative links.
4. Set `status` to `published` when the entry is ready for the portfolio.

The universal required fields are `title`, `slug`, `excerpt`, `date`, `status`, `category` and `tags`. Optional fields such as `context` and `difficulty` can add useful detail when they apply to the subject.

The portfolio validates the metadata during synchronisation. Invalid or incomplete entries stop the build instead of being published with guessed information.

## Published write-ups

- [Injection](injection/README.md)
