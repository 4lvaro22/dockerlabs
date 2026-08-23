# DockerLabs write-ups

This repository is the source of truth for the security write-ups published on my portfolio. It contains my solutions for challenges from [DockerLabs](https://dockerlabs.es/#/).

## Adding a write-up

1. Copy [`WRITEUP_TEMPLATE.md`](WRITEUP_TEMPLATE.md) into a new top-level directory as `README.md`.
2. Complete every frontmatter field at the beginning of the file.
3. Store screenshots in an `assets` directory next to the write-up and use relative links.
4. Set `status` to `published` when the entry is ready for the portfolio.

The portfolio validates the metadata during synchronisation. Invalid or incomplete entries stop the build instead of being published with guessed information.

## Challenges completed

- [Injection](injection/README.md)
