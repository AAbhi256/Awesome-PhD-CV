# Awesome PhD CV Templates

A curated collection of LaTeX CV/resume templates for PhD students, postdocs, and faculty applicants. Each format targets a different use case — pick the one that fits your needs.

## Templates

### 1. Awesome-CV Format (`research-cv/`)

A comprehensive, multi-page academic CV based on [posquit0/Awesome-CV](https://github.com/posquit0/Awesome-CV).
Best suited for **faculty applications and postdoc positions** where you need to present a full publication list, research statements, and detailed academic history.

**Includes:**
- `cv.tex` — Main CV with modular sections (education, publications, honors, etc.)
- `cv/` — Individual section files for easy editing
- `awesome-cv.cls` — The class file (XeLaTeX required)

**Key features:**
- Modular section files — edit each section independently
- Built-in support for publication lists with citation counts and GitHub stars
- Profile photo option
- Customizable accent colors
- BibTeX integration for references

**How to compile:**
```bash
cd awesome-cv-format
xelatex cv.tex
```

---

### 2. Jake's Format (`jakes-format/`)

A clean, single-page resume template by [Jake Gutierrez](https://github.com/sb2nov/resume).
The most popular LaTeX resume template on the internet — widely used for **industry software engineering positions** and internship applications.

**Includes:**
- `resume.tex` — Single self-contained file

**Key features:**
- ATS-friendly (machine-readable, no fancy formatting that breaks parsers)
- Single-page, single-column layout
- Clean section dividers with `\titlerule`
- Custom commands for consistent formatting (`\resumeSubheading`, `\resumeItem`, etc.)
- Easy to customize fonts (sans-serif and serif options commented out)
- Uses standard `pdflatex` — no special engine needed

**How to compile:**
```bash
cd jakes-format
pdflatex resume.tex
```

---

### 3. Deedy Format (`deedy-format/`)

A modern two-column resume template created by [Debarghya Das](https://github.com/deedy/Deedy-Resume). Popular among **experienced software engineers and tech professionals** who need to pack substantial experience into a single page with high information density. See also: [Deedy Resume Guide](https://www.sweresume.app/articles/deedy-resume/).

**Includes:**
- `resume.tex` — Single self-contained file

**Key features:**
- Distinctive two-column layout: narrow left (1/3) for education/skills, wide right (2/3) for experience/projects
- High information density while maintaining readability
- Clean typography with clear visual hierarchy
- `\runsubsection` and `\descript` commands for consistent entry formatting
- `\tightemize` environment for compact bullet points

**Note:** This template requires the `deedy-resume.cls` class file. Download it from the [original repository](https://github.com/deedy/Deedy-Resume).

**How to compile:**
```bash
cd deedy-format
xelatex resume.tex
```

---

## Which Template Should I Use?

| Template | Best For | Pages | Columns | Engine |
|----------|----------|-------|---------|--------|
| **Awesome-CV** | Faculty/postdoc applications, academic CV | Multi-page | 1 | XeLaTeX |
| **Jake's** | Industry SWE/internship applications | 1 | 1 | pdfLaTeX |
| **Deedy** | Experienced tech professionals | 1 | 2 | XeLaTeX |

## License

- Awesome-CV: [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) (original by Claud D. Park)
- Jake's Resume: [MIT License](https://opensource.org/licenses/MIT) (original by Jake Gutierrez, based on [sb2nov/resume](https://github.com/sb2nov/resume))
- Deedy Resume: [Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0) (original by Debarghya Das)
