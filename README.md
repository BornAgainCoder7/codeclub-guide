# How to Start Your Own Code Club — Community Guide

Welcome to the SORTEE open guide to starting and running a Code Club. This guide was written by and for the SORTEE and broader coding community.

## What is this guide about?

This guide collects real experiences, tested strategies, and participant-contributed tips from the [SORTEE](https://sortee.org/) 2025 Unconference session "*How to Start Your Own Code Club*."

This guide provides:

- **Practical advice** on designing, launching, and running a Code Club  
- **Real tips from facilitators and participants** across universities, research groups, and online communities  
- **Session formats** (seminars, workshops, hacky hours) and how to choose what fits your group  
- **Solutions to common challenges** like balancing skill levels, finding session ideas, or sustaining motivation  
- **Resources and links** to existing materials, tutorials, and community examples  

It's a living document—contributions, adaptations, and improvements are always welcome.

## Related Resources

- **[SORTEE (Society for Open, Reliable, and Transparent Ecology and Evolutionary Biology)](https://sortee.org/)** — Organization dedicated to improving research practices in ecology and evolution  
- **[SORTEE Code Club](https://github.com/SORTEE/CodeClub)** — Repository with materials from past Code Club events  
- **[Slides Unconference Session](https://github.com/SORTEE/CodeClub/tree/main/20251016_SORTEE-Unconference5-CodeClub/slides)** from the October 2025 unconference 

## Repository Structure

```
start-your-codeclub-guide
│
├── index.qmd # Quarto Markdown source for the guide
├── styles.scss # custom SCSS styling
├── _quarto.yml # project configuration
├── docs/ # Rendered HTML site for GitHub Pages
│
├── README.md # This file
├── CONTRIBUTING.md # Guidelines for contributors
├── LICENSE # CC BY 4.0 License
```

## How to Contribute

We warmly welcome contributions! You can:

- **Fix typos or improve clarity** — open a pull request with your edits  
- **Add new tips, examples, or resources** — share what worked (or didn't) in your own Code Club  
- **Report issues or suggest topics** — open an issue to discuss ideas or missing sections  
- **Adapt for your institution** — fork this repo, customize for your community, and share back what you learn  

See [CONTRIBUTING.md](CONTRIBUTING.md) for detailed instructions on how to propose changes, render the site locally, and collaborate.

## Building the Guide Locally

This guide is built using [Quarto](https://quarto.org/).

### Prerequisites
- Install [Quarto](https://quarto.org/docs/get-started/)

### Steps

1. Clone this repository:
```
git clone https://github.com/SORTEE/start-your-codeclub-guide.git
cd start-your-codeclub-guide
```

2. Render the site:
`quarto render`

4. Preview locally:
`quarto preview`
The rendered site will appear in the `docs/` folder, ready to deploy via GitHub Pages.
