# danielzhang122.github.io

Nothing to see here. The actual portfolio lives at
**[danielzhang122.github.io/website](https://danielzhang122.github.io/website/)**
([source](https://github.com/danielzhang122/website)).

I wanted a shorter link. The trouble is, I'd already sent the
long one to every recruiter who'd read my resume, and "Hi, I'm detail-oriented"
reads worse right above a 404. So now both links work and nobody has to know.

- `index.html` sends https://danielzhang122.github.io/ to the site.
- `404.html` catches everything else and sends it to the same path under `/website`,
  so `/Daniel_Zhang_Resume.pdf` still finds `/website/Daniel_Zhang_Resume.pdf`.
