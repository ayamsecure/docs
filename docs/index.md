# Welcome to Ayam Secure Docs

This is an open source, public knowledge base for everyone to learn how to use and even run software services that enables us to take ownership of our data.

Use the search box to do a full text search or navigate by the menu tabs in the header.

Learn more about Ayam Secure [here](/about/).

## How to contribute to the wiki

1. git clone the [repo](https://github.com/ayamsecure/docs) and from the `main` branch, checkout a new branch giving it an appropriate name
2. add your edits to markdown files in the `/docs` directory
3. if you're adding a new page, remember to add the page to the nav section in the `/mkdocs.yml` file
4. git add, commit, push, then open a PR from your branch to `main` and ping one of the repository maintainers to review your changes
5. once all build checks are passing (GitHub Actions will build your pushed branch), merge your PR into `main` and then Cloudflare Pages will build the production files and publish them
6. delete your branch to keep things tidy in this repository
7. [visit the site](https://docs.ayamsecure.com) to ensure your changes got published

## How to build the site locally

- run this docker command from the project root directory to build and run the site with hot reloading and the site will be available at `http://localhost:8000`, crtl + c to exit

```
docker run --rm -it -p 8000:8000 -v ${PWD}:/docs squidfunk/mkdocs-material
```

---

## Useful wiki resources

### Convert text and images to markdown

- [https://euangoddard.github.io/clipboard2markdown/](https://euangoddard.github.io/clipboard2markdown/)

### Markdown Syntax

- [https://www.markdownguide.org/basic-syntax](https://www.markdownguide.org/basic-syntax)

### Documentation for Material for MkDocs

- [https://squidfunk.github.io/mkdocs-material/reference/](https://squidfunk.github.io/mkdocs-material/reference/)
