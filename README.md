# DL@MBL Course Website

To add pages:
- Create a new md page in `_pages`
- Add a link to the new page in the header
    - Edit `_includes/header.html` and find the comment about adding new pages to navbar

To add year: 
```
/assets/js/2026/calendar.js # mostly copy, change dates, ptentially CalendarId+Key
_data/2026 # staff.yml
_includes/header.html # selector + course name 
_pages/2026 # mostly copy and changing 2025 -> 2026 references
_pages/*.md # change links to 2026
```
eventually:
`assets/img/groups/` add 2026 picture

# Local Development
If this is your first time working with jekyll:
- Install ruby following the jekyll [installation guide](https://jekyllrb.com/docs/installation/) for your os
- `gem install jekyll bundler`

To build and serve the website locally
- Run `bundle install` if you haven't already
- `bundle exec jekyll serve`
