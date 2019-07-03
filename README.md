Jekyll static conference site
=========================

Static website for academic conferences designed for easy maintenance, previously used for [SCR 2019](scr2019.caltech.edu).

# Documentation

With jekyll installed,  run
```
jekyll serve --livereload
```
for development and  build the final site with
```
jekyll build
``` 

Refer to [jekyllrb.com](https://jekyllrb.com/) for further documentation, including how to install Jekyll.

## Site-wide settings

Colors and links are controlled in ```_config.yml```

## Layout

The ```_includes``` folder contains a number of sections that are included in the layout files in ```_layouts```. Three layouts are available now: early (no speakers, paper submission instructions), before (lists of speakers and submissions), and after (includes pictures from the event). 

The layout file is specified in ```index.html```.

## Adding content

Invited speakers, accepted contributions, organizers, advisors, and schedule items (sessions) are controlled by placing markdown files in the corresponding folder (```_advisors```, ```_invited_speakers```, ```_organizers```, ```_papers``` and ```_sessions```). Refer to the examples for the format of these files.

For configuring the remaining content (sponsors, text changes, etc), manually edit the files in ```_includes```.


