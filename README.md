# rajan-sust.github.io

Live at: https://rajan-sust.github.io/

#### How to run the site locally
```
export PATH="$HOME/Library/Python/3.14/bin:$PATH"
bundle exec jekyll serve
```

## Which file controls which page

| Page / Section                          | File(s)                                 |
| --------------------------------------- | --------------------------------------- |
| Home / About                            | `_pages/about.md`                       |
| CV                                      | `_pages/cv.md`, `_data/cv.yml`          |
| Publications                            | `_bibliography/papers.bib`              |
| Projects                                | `_projects/*.md`                        |
| Teaching                                | `_pages/teaching.md`, `_teachings/*.md` |
| News (homepage feed)                    | `_news/*.md`                            |
| Repositories (GitHub showcase)          | `_data/repositories.yml`                |
| Social icons / CV PDF link              | `_data/socials.yml`                     |
| Profile photo                           | `assets/img/prof_pic.jpg`               |
| CV PDF download                         | `assets/pdf/cv.pdf`                     |
| Site title, description, footer, navbar | `_config.yml`                           |
