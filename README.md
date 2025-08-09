# Decoding Inequality 2025

This repository contains the materials for the course "Decoding Inequality: Kritische Perspektiven auf Machine Learning und gesellschaftliche Ungleichheit" held at the University of Bern in the spring semester 2025. The data in this repository is openly available to everyone and is intended to support reproducible research.

[![GitHub issues](https://img.shields.io/github/issues/DHBern/decoding-inequality-2025.svg)](https://github.com/DHBern/decoding-inequality-2025/issues)
[![GitHub forks](https://img.shields.io/github/forks/DHBern/decoding-inequality-2025.svg)](https://github.com/DHBern/decoding-inequality-2025/network)
[![GitHub stars](https://img.shields.io/github/stars/DHBern/decoding-inequality-2025.svg)](https://github.com/DHBern/decoding-inequality-2025/stargazers)
[![Code license](https://img.shields.io/github/license/DHBern/decoding-inequality-2025.svg)](https://github.com/DHBern/decoding-inequality-2025/blob/main/LICENSE-AGPL.md)
[![Data license](https://img.shields.io/github/license/DHBern/decoding-inequality-2025.svg)](https://github.com/DHBern/decoding-inequality-2025/blob/main/LICENSE-CCBYSA.md)
[![DOI](https://zenodo.org/badge/876239345.svg)](https://zenodo.org/badge/latestdoi/16785208)

## Repository Structure

The structure of this repository is organized as follows:

- `contents/`: Contains all the source material for the course website.
  - `sessions/`: Holds the Quarto markdown files for each of the 10 course sessions. Each file includes the session plan, learning objectives, and summaries of reading materials.
  - `posts/`: A directory for student-contributed blog posts.
  - `about.qmd`: The "About Us" page with information about the instructors.
  - `blog.qmd`: The page that lists and renders the student blog posts.
  - `home.qmd`: The main landing page for the course website.
  - `interesting-stuff.qmd`: A curated list of interesting links and resources.
  - `syllabus.qmd`: The complete course syllabus, including session dates and reading assignments.
  - `bibliography.bib`: The central bibliography file for all citations used in the project.
- `assets/`: Contains static assets like images, PDF files for readings, and CSS files.
- `.github/`: Houses GitHub-specific files, including Actions workflows for automation.
- `_site/`: The output directory for the rendered Quarto website. This directory is generated automatically.
- `_quarto.yml`: The main configuration file for the Quarto project, defining the website's structure and rendering options.
- `package.json`, `pnpm-lock.yaml`: Files defining project dependencies and scripts for Node.js.
- `README.md`: This file, providing an overview of the project.
- `CHANGELOG.md`: A log of all notable changes to the project.
- `LICENSE-*`: Files containing the licenses for the code and content.

## Data Description

The data in this repository consists of the course materials for "Decoding Inequality." This includes:

- Syllabus and session outlines in Quarto Markdown (`.qmd`).
- Reading materials and slides in PDF format, located in `assets/files/`.
- Bibliographic information in `contents/bibliography.bib`.
- Images and other web assets.

All materials are created and curated by the instructors unless otherwise noted. The content aims to provide a critical perspective on machine learning and its societal impact.

## Use

These data are openly available to everyone and can be used for any research or educational purpose. If you use this data in your research, please cite as specified in [CITATION.cff](CITATION.cff). The following citation formats are also available through _Zenodo_:

- [BibTeX](https://zenodo.org/record/16785208/export/hx)
- [CSL](https://zenodo.org/record/16785208/export/csl)
- [DataCite](https://zenodo.org/record/16785208/export/dcite4)
- [Dublin Core](https://zenodo.org/record/16785208/export/xd)
- [DCAT](https://zenodo.org/record/16785208/export/dcat)
- [JSON](https://zenodo.org/record/16785208/export/json)
- [JSON-LD](https://zenodo.org/record/16785208/export/schemaorg_jsonld)
- [GeoJSON](https://zenodo.org/record/16785208/export/geojson)
- [MARCXML](https://zenodo.org/record/16785208/export/xm)

_Zenodo_ provides an [API (REST & OAI-PMH)](https://developers.zenodo.org/) to access the data. For example, the following command will return the metadata for the most recent version of the data

```bash
curl -i https://zenodo.org/api/records/16785208
```

## Installation

Install [Node.js](https://nodejs.org/en/) and run the following commands in the root directory of the repository:

```bash
npm install
npm run prepare
```

## Use

Check that all files are properly formatted.

```bash
npm run check
```

Format all files.

```bash
npm run format
```

Run the wizard to write meaningful commit messages.

```bash
npm run commit
```

Run the wizard to create a CHANGELOG.md.

```bash
npm run changelog
```

Preview the documentation.

```bash
quarto preview
```

## Support

This project is maintained by [@DHBern](https://github.com/DHBern). Please understand that we can't provide individual support via email. We also believe that help is much more valuable when it's shared publicly, so more people can benefit from it.

| Type                                   | Platforms                                                                            |
| -------------------------------------- | ------------------------------------------------------------------------------------ |
| 🚨 **Bug Reports**                     | [GitHub Issue Tracker](https://github.com/DHBern/decoding-inequality-2025/issues)    |
| 📊 **Report bad data**                 | [GitHub Issue Tracker](https://github.com/DHBern/decoding-inequality-2025/issues)    |
| 📚 **Docs Issue**                      | [GitHub Issue Tracker](https://github.com/DHBern/decoding-inequality-2025/issues)    |
| 🎁 **Feature Requests**                | [GitHub Issue Tracker](https://github.com/DHBern/decoding-inequality-2025/issues)    |
| 🛡 **Report a security vulnerability** | See [SECURITY.md](SECURITY.md)                                                       |
| 💬 **General Questions**               | [GitHub Discussions](https://github.com/DHBern/decoding-inequality-2025/discussions) |

## Roadmap

- [x] Syllabus with reading list
- [x] Slides for lectures
- [x] Additional resources (e.g., links to papers, blog posts, etc.)
- [x] Blog posts, posters, or other materials produced by students

## Contributing

All contributions to this repository are welcome! If you find errors or problems with the data, or if you want to add new data or features, please open an issue or pull request. Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests.

## Versioning

We use [SemVer](http://semver.org/) for versioning. The available versions are listed in the [tags on this repository](https://github.com/DHBern/decoding-inequality-2025/tags).

## Authors and acknowledgment

- **Digital Humanities University of Bern** - _Initial work_ - [DHBern](https://github.com/DHBern)
- **Rachel Huber** - _Instructor_ - [HistoRaHub](https://github.com/HistoRaHub)
- **Moritz Mähr** - _Instructor_ - [maehr](https://github.com/maehr)

See also the list of [contributors](https://github.com/DHBern/decoding-inequality-2025/graphs/contributors) who contributed to this project.

## License

The data in this repository is released under the Creative Commons Attribution 4.0 International (CC BY 4.0) License - see the [LICENSE-CCBYSA](LICENSE-CCBYSA.md) file for details. By using this data, you agree to give appropriate credit to the original author(s) and to indicate if any modifications have been made.

The code in this repository is released under the GNU Affero General Public License v3.0 - see the [LICENSE-AGPL](LICENSE-AGPL.md) file for details. By using this code, you agree to make any modifications available under the same license.
