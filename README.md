A single-page, one-column resume for software developers. 
It uses the base latex templates and fonts to provide ease of use and installation when trying to update the resume. 
The different sections are clearly documented and custom commands are used to provide consistent formatting. 
The main sections in the resume are Profile, Skills, Experience, and Education.

### Motivation

I created this template because managing resumes in the profile is inefficient, when changing a large amount of information I may have to redo everything if the original file is not available on the created website.

Most currently available templates either focus on two columns, or are multiple pages long that didn't work well for career fairs or online applications.

### Quick start

Get started quickly using a template based on [Overleaf](https://www.overleaf.com/latex/templates/software-engineer-resume/gqxmqsvsbdjf).

### Build using Docker

```sh
  docker build -t latex .
  docker run --rm -i -v "$PWD":/data latex pdflatex thanh_duy_resume.tex
```

### Preview

![Resume Screenshot](/resume_preview.png)
