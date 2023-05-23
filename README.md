
# Bitcoin Alps Website

This README file explains how to install and use Hugo, the Blowfish theme, and the Hugo Modules feature to manage themes and other dependencies for the Bitcoin Alps website. It also shows you how to start a local development server and generate a production-ready version of your site for deployment.

## Installation

1. Install Hugo:

    ```bash
    # on macOS
    brew install hugo

    # on Windows
    choco install hugo -confirm
    ```

2. Clone the github repository:

    ```bash
    git clone github.com/<username>/<repo-name>
    ```

## Development

1. Start a local development server:

    ```bash
    hugo server
    ```

2. Open your browser and go to [http://localhost:1313] to view your site.

3. As you make changes to your content and templates, the site will be automatically rebuilt and the changes will be reflected in the browser.

## Deployment

1. Generate a production-ready version of your site:

    ```bash
    hugo
    ````

2. The generated files will be placed in the public directory. You can then upload these files to a web server or hosting service.

## Update hugo template

Git submodules can be updated using the git command. Simply execute the following command and the latest version of the theme will be downloaded into your local repository:

```bash
git submodule update --remote --merge
```
