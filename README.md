<div align="center">

<a href="https://github.com/gmtigrisva123/Mathematics-Methodology-on-Education">
  <img src="https://img.shields.io/badge/Math4Money-Inclusive%20Math%20Education-1f4b99?style=for-the-badge" alt="Math4Money" />
</a>

# Mathematics Methodology on Education

### Methods for Teaching Rational Numbers to Visually Impaired Students

<p>
  A research-driven educational framework for inclusive mathematics instruction,
  combining tactile learning, verbal reasoning, guided practice, and cognitive science.
</p>

<p>
  <a href="docs/ABSTRACT.md">Abstract</a>
  |
  <a href="docs/METHODOLOGY_OVERVIEW.md">Methodology Overview</a>
  |
  <a href="docs/REFERENCES.md">References</a>
  |
  <a href="src/index.html">Open Web Source</a>
</p>

<p>
  <img src="https://img.shields.io/badge/Research-Inclusive%20Education-4f4f4f?style=flat-square" alt="Research" />
  <img src="https://img.shields.io/badge/Applied%20Mathematics-Rational%20Numbers-5d8f2f?style=flat-square" alt="Applied Mathematics" />
  <img src="https://img.shields.io/badge/Accessibility-Visual%20Impairment-0f766e?style=flat-square" alt="Accessibility" />
  <img src="https://img.shields.io/badge/Pedagogy-Multi--Sensory-a16207?style=flat-square" alt="Pedagogy" />
  <img src="https://img.shields.io/badge/Format-Static%20Website-92400e?style=flat-square" alt="Format" />
  <img src="https://img.shields.io/badge/Status-Research%20Prototype-65a30d?style=flat-square" alt="Status" />
</p>

</div>

---

<div align="center">

## From tactile experience to mathematical understanding

<p>
  This project proposes a complete instructional model for helping visually impaired students
  understand rational numbers through structured non-visual learning pathways.
</p>

</div>

<table>
  <tr>
    <td width="50%" align="center">
      <a href="src/index.html">
        <img src="https://img.shields.io/badge/Web%20Presentation-Open%20the%20Framework-2563eb?style=for-the-badge" alt="Web Presentation" />
      </a>
      <br />
      <strong>Static pedagogical website</strong>
      <br />
      Full framework presentation in a clean, publishable web format
    </td>
    <td width="50%" align="center">
      <a href="docs/METHODOLOGY_OVERVIEW.md">
        <img src="https://img.shields.io/badge/Research%20Architecture-6%20Methods%20%2B%207%20Phases-7c3aed?style=for-the-badge" alt="Research Architecture" />
      </a>
      <br />
      <strong>Instructional architecture</strong>
      <br />
      Behavioral, cognitive, and pedagogical structure designed for replication
    </td>
  </tr>
</table>

<div align="center">

### [Research Showcase](#research-showcase) | [Instructional Pipeline](#instructional-pipeline) | [Theoretical Grounding](#theoretical-grounding) | [Impact](#why-it-matters) | [Roadmap](#roadmap)

</div>

---

## Research Showcase

This repository is not just a website. It is a documented pedagogical framework that translates modern educational theory into a practical model for teaching mathematics to students with visual impairments.

It is designed for:

- teachers and special educators
- inclusive education nonprofits
- curriculum designers
- researchers in mathematics education
- accessibility-focused learning initiatives

---

## Instructional Pipeline

The framework is built from six complementary methods:

| Code | Method | Core role |
| --- | --- | --- |
| `MSCM` | Multi-Sensory Conceptualisation Method | Build mathematical meaning through touch, sound, and guided language |
| `SWEM` | Structured Worked Example Method | Model procedure explicitly while reducing cognitive overload |
| `GIT` | Guided-to-Independent Transition | Shift responsibility from instructor support to learner autonomy |
| `VCE` | Verbalisation and Cognitive Encoding | Strengthen understanding through spoken reconstruction of reasoning |
| `EBLM` | Error-Based Learning Method | Use incorrect solutions to activate diagnosis and critical thinking |
| `CM` | Contextualisation Method | Embed abstract mathematics in meaningful real-life contexts |

These methods are delivered through a seven-phase lesson sequence:

1. Pre-Experience (Tactile)
2. Verbal Description
3. Generalisation
4. Worked Example
5. Guided Practice
6. Student Explanation
7. Multimedia Reinforcement

`Student Explanation` is the non-negotiable phase because it reveals whether the learner truly understands the concept instead of repeating procedure mechanically.

---

## Theoretical Grounding

The project is grounded in established work from cognitive science and educational psychology:

- Constructivism
- Cognitive Load Theory
- Dual Coding Theory
- Gradual Release of Responsibility
- Elaborative Interrogation
- Situated Cognition

Supporting references are collected in [docs/REFERENCES.md](docs/REFERENCES.md).

---

## Why It Matters

Most mathematics instruction still assumes that diagrams, symbols, and visual demonstrations are the default entry point to understanding. For many visually impaired students, that assumption creates unnecessary barriers.

This framework reframes mathematics learning around:

- tactile experience before symbolic abstraction
- language as a tool for reasoning, not just explanation
- carefully scaffolded independence
- concept formation instead of rote answer production
- mathematically meaningful contexts drawn from real life

The focus on rational numbers is deliberate because fractions and related concepts often determine whether later mathematical learning becomes accessible or difficult.

---

## Repository Structure

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

---

## Quick Start

```bash
git clone https://github.com/gmtigrisva123/Mathematics-Methodology-on-Education.git
cd Mathematics-Methodology-on-Education
```

Then open [src/index.html](src/index.html) in a modern browser.

There is no build step. The site is a static document-based presentation.

---

## Documentation Map

- [docs/ABSTRACT.md](docs/ABSTRACT.md): summary of the framework and its educational objective
- [docs/METHODOLOGY_OVERVIEW.md](docs/METHODOLOGY_OVERVIEW.md): quick-reference guide to all six methods and the seven-phase cycle
- [docs/REFERENCES.md](docs/REFERENCES.md): bibliography and theoretical foundation
- [src/index.html](src/index.html): main web presentation
- [.github/workflows/static.yml](.github/workflows/static.yml): GitHub Pages deployment workflow

---

## Contribution Direction

Contributions are valuable when they improve one of these areas:

- academic clarity
- accessibility and semantic HTML
- instructional precision
- responsive presentation
- proofreading and language quality
- translation and localization

Please preserve the educational purpose of the framework. This repository should read like a serious inclusive education project, not a generic product landing page.

---

## Roadmap

- fix encoding consistency across the repository
- strengthen semantic accessibility in the HTML source
- add formal citation metadata with `CITATION.cff`
- add screenshots or diagrams for the GitHub landing experience
- expand documentation for educators who want to adapt the model in practice

---

## Citation

If you use or adapt this work, cite it clearly:

```text
Minh, Le Tran Khanh, and Ho Viet Anh. Mathematics Methodology on Education:
Methods for Teaching Rational Numbers to Visually Impaired Students.
Math4Money Initiative, 2025. GitHub repository.
```

---

## Authors

- Le Tran Khanh Minh
- Ho Viet Anh
- Math4Money Initiative, Inclusive Mathematics Education, Vietnam

## License

This repository is distributed under the terms stated in [LICENSE](LICENSE).
