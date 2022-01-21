# joaopalmeiro.github.io

## References

- Matt Dray's [personal website](https://github.com/matt-dray/postcard).
- Rasmus Andersson's [Inter](https://rsms.me/inter/) ([SIL Open Font License 1.1](https://choosealicense.com/licenses/ofl-1.1/)). `Inter-3.19`.
- {[postcards](https://github.com/seankross/postcards)} package.
- {[emo](https://github.com/hadley/emo)} package.

## Profiles/Pages

- [Medium](https://joaompalmeiro.medium.com/)
- [DEV](https://dev.to/joaompalmeiro)
- [Writings](https://joaopalmeirowritings.vercel.app/)
- [Behance](https://www.behance.net/joaopalmeiro)
- [Goodreads](https://www.goodreads.com/joaopalmeiro)
- [Master's thesis](http://hdl.handle.net/10362/119698)
- [PyPI](https://pypi.org/user/joaopalmeiro/)
- [npm](https://www.npmjs.com/~joaopalmeiro)
- [Mastodon/Masto.pt](https://masto.pt/@joaopalmeiro)

## Development

- **Versions**:
  - RStudio 1.3.1093 (`rstudioapi::versionInfo()`).
  - R 3.6.3 (`sessionInfo()`).
  - {renv} 0.14.0.
- In the `index.Rmd` file, run the `setup` [chunk](https://rmarkdown.rstudio.com/lesson-3.html) first. In this way, the development environment, with the necessary dependencies, will be loaded.
- To generate the HTML file, click on the `Knit` button in RStudio.

## Notes

- Save env: `renv::snapshot()`.
- `postcards::create_postcard(template = "jolla")`.
- [Jolla template example](https://github.com/seankross/postcards#jolla).
- `renv::update(c("renv", "postcards"))`.
- {[rstudioapi](https://rstudio.github.io/rstudioapi/index.html)}.
- [Upgrading renv](https://rstudio.github.io/renv/articles/renv.html#upgrading-renv-1) documentation.
