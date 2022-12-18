# Ayam Secure Open Source Documentation

## The Knowledge Base for Ayam Secure

[![Build Status](https://travis.ibm.com/IdentityEngineeringServices/ies-team-wiki.svg?token=VWgHY3qzsZpp8rWo1svi&branch=main)](https://travis.ibm.com/IdentityEngineeringServices/ies-team-wiki)

## How to contribute to the wiki

1. git clone this repo and from the `main` branch, checkout a new branch giving it an appropriate name
2. add your edits to markdown files in the `docs/` directory
3. if you're adding a new page, remember to add the page to the nav section in the `/mkdocs.yml` file
4. git add, commit, push, and then open a PR from your branch to `main` and ask at least one other dev to review your changes
5. once all checks are passing ([TravisCI](https://travis.ibm.com/IdentityEngineeringServices/ies-team-wiki) will build your pushed branch), merge your PR into `main` and then TravisCI will build the production files and push them to the `gh-pages` branch
6. delete your branch
7. [visit the site](https://pages.github.ibm.com/IdentityEngineeringServices/ies-team-wiki/) to ensure your changes got published

## To build the site locally

- run this docker command from the project root directory to build and run the site with hot reloading and the site will be available at `http://localhost:8000`, crtl+c to exit

```
docker run --rm -it -p 8000:8000 -v ${PWD}:/docs squidfunk/mkdocs-material:8.3.9
```

---

## Useful wiki resources

### Convert text and images to markdown

- https://euangoddard.github.io/clipboard2markdown/

### Markdown Syntax

- https://www.markdownguide.org/basic-syntax

### Documentation for Material for MkDocs

- https://squidfunk.github.io/mkdocs-material/setup/changing-the-colors/
