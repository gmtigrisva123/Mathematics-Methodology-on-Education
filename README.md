# Mathematics Methodology on Education

An open educational framework for teaching rational numbers to students with visual impairments through tactile, auditory, and language-based instruction.

## Overview

This repository documents a pedagogical framework developed for inclusive mathematics education in Vietnam. It combines six complementary teaching methodologies with a seven-phase instructional cycle designed to support conceptual understanding, verbal reasoning, and independent problem solving for learners with visual impairments.

The project is published as a lightweight static website and accompanying documentation. It is intended for educators, curriculum designers, accessibility advocates, nonprofit education teams, and researchers working at the intersection of mathematics education and disability inclusion.

## Why This Project Matters

Many mathematics resources still assume vision as the primary channel for explanation, practice, and assessment. This project takes a different stance: mathematical understanding can be built through structured tactile experience, explicit verbalisation, guided reasoning, and context-rich instruction.

The framework focuses especially on rational numbers, a topic that often becomes a barrier for later mathematical learning if conceptual foundations are weak.

## Framework at a Glance

The instructional model is built around six methods:

| Code | Method | Purpose |
| --- | --- | --- |
| `MSCM` | Multi-Sensory Conceptualisation Method | Build concepts through touch, sound, and guided language |
| `SWEM` | Structured Worked Example Method | Reduce overload through explicit step-by-step modelling |
| `GIT` | Guided-to-Independent Transition | Move learners from supported practice to autonomy |
| `VCE` | Verbalisation and Cognitive Encoding | Consolidate understanding through spoken explanation |
| `EBLM` | Error-Based Learning Method | Develop reasoning through diagnosing incorrect solutions |
| `CM` | Contextualisation Method | Anchor abstract mathematics in meaningful real-life situations |

These methods are delivered through a seven-phase Core Instructional Cycle:

1. Pre-Experience (Tactile)
2. Verbal Description
3. Generalisation
4. Worked Example
5. Guided Practice
6. Student Explanation
7. Multimedia Reinforcement

Phase 6, `Student Explanation`, is treated as essential because it surfaces actual understanding rather than passive imitation.

## Repository Contents

```text
Mathematics-Methodology-on-Education/
|-- .github/
|   `-- workflows/
|       `-- static.yml
|-- docs/
|   |-- ABSTRACT.md
|   |-- METHODOLOGY_OVERVIEW.md
|   `-- REFERENCES.md
|-- src/
|   |-- index.html
|   |-- js/
|   |   `-- main.js
|   |-- sections/
|   |   |-- abstract.html
|   |   |-- cover.html
|   |   |-- cycle.html
|   |   |-- footer.html
|   |   |-- methods.html
|   |   `-- theory.html
|   `-- styles/
|       |-- base.css
|       |-- components.css
|       |-- layout.css
|       `-- sections.css
|-- LICENSE
`-- README.md
```

## Documentation

- [Abstract](docs/ABSTRACT.md): concise summary of the framework and its instructional intent
- [Methodology Overview](docs/METHODOLOGY_OVERVIEW.md): quick reference for the six methods and the core teaching cycle
- [References](docs/REFERENCES.md): theoretical grounding in constructivism, cognitive load theory, dual coding, gradual release, elaborative interrogation, and situated cognition

## Website and Local Preview

This project does not require a build step.

To view it locally:

```bash
git clone https://github.com/gmtigrisva123/Mathematics-Methodology-on-Education.git
cd Mathematics-Methodology-on-Education
```

Then open [`src/index.html`](src/index.html) in a modern browser.

## Deployment

The repository includes a GitHub Actions workflow at [`.github/workflows/static.yml`](.github/workflows/static.yml) for static deployment to GitHub Pages on pushes to `main`.

If you want the site to publish correctly via GitHub Pages, confirm that:

- GitHub Pages is enabled for the repository
- the workflow has permission to deploy
- the published source is the GitHub Actions workflow

## Accessibility Intent

Although this repository presents content in a visual web format, the pedagogical model itself is built around non-visual learning pathways. The instructional design emphasises:

- tactile pre-experience before symbolic abstraction
- explicit oral explanation of reasoning
- reduced cognitive overload through structured examples
- repeated transfer from guided support to independent performance
- contextualised mathematics connected to everyday life

## Recommended Use Cases

This repository is most useful if you are:

- designing lesson plans for students with visual impairments
- building nonprofit or school-based inclusive mathematics programs
- adapting rational number instruction for tactile or oral delivery
- studying instructional design for disability-inclusive STEM education
- looking for a compact web-based presentation of a pedagogical framework

## Contribution Guidance

Contributions are welcome if they strengthen the educational value, clarity, accessibility, or scholarly quality of the project.

Good contributions include:

- improving wording, structure, and academic clarity
- refining accessibility and semantic HTML
- extending documentation or references
- improving responsive presentation of the static site
- translating or localising material for broader use

When contributing, try to preserve the core educational intent of the framework rather than treating the site as a generic landing page.

## Citation

If you use or adapt this framework in a program, report, or educational resource, cite the repository and its authors clearly. A simple citation format:

```text
Minh, Le Tran Khanh, and Ho Viet Anh. Mathematics Methodology on Education:
Methods for Teaching Rational Numbers to Visually Impaired Students.
Math4Money Initiative, 2025. GitHub repository.
```

If you want formal citation metadata later, add a `CITATION.cff` file to the repository.

## Authors and Initiative

- Le Tran Khanh Minh
- Ho Viet Anh
- Math4Money Initiative, Inclusive Mathematics Education, Vietnam

## License

This repository is distributed under the terms stated in [LICENSE](LICENSE).
