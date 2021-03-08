# FTA Live Website

Website for FastTrack for Azure Live EMEA sessions. This is an MVP version to put up as soon as possible for customers.

## Updating Content

Assuming you've setup Jekyll, you can edit the content in the following ways.

- **Add/Update sessions**  
	Go to the `_sessions` folder and just add a new markdown file. Follow the existing naming conventions and use existing sessions as a template.

- **Add/Update Engineers**  
  Go to the `_data/engineers.yml` file and update as needed. Follow the existing YAML structure.

## Setup

Although there are other static site generators available, we chose to use Jekyll for its out of the box integration with [GitHub Pages](https://jekyllrb.com/docs/github-pages/), which means we have no need to setup CI/CD.

### Requirements

#### Ruby

This can be tricky to install especially on Windows. Please follow the [official installation for Windows directions](https://jekyllrb.com/docs/installation/windows/) and use Windows Subsystem for Linux.

### Installation

First, [Install Jekyll per official instructions](https://jekyllrb.com/docs/installation/)

Then, clone this repo

```
git clone https://github.com/azure/fta-live-emea-website
```

Then install dependencies

```
bundle install
```

Then start up dev server

```
bundle exec jekyll serve --livereload
```

### Publish?

Just push changes to the `main` branch and GitHub automatically re-publishes the website. Use a different branch if you are not ready for it to be published..

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
