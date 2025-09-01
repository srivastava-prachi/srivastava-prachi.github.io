

Prachi's website

## Documentation

The template is documented at https://pascalmichaillat.org/b/.

## Illustration

The website produced by the template can be viewed at https://pascalmichaillat.org/hugo-website/.


+ The first time that you push your repository to GitHub, you need to allow GitHub Actions and GitHub Pages so the website can be built and deployed to GitHub Pages.
+ The first step is to [ask GitHub to publish the website with a GitHub Action](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site#publishing-with-a-custom-github-actions-workflow). GitHub offers a ready-made action to publish a Hugo website, called `Deploy Hugo site to Pages`. This action must be enabled in the [Pages Settings](https://github.com/pmichaillat/hugo-website/settings/pages) of your GitHub repository. You can view the workflow triggered by the action in the `.github/workflows/hugo.yml` file.
+ Once the GitHub Actions are enabled, GitHub will build and publish the website as soon as the repository is updated. 
+ If you would like to update the deployment action (for instance because it became outdated and fails to deploy the site), you can find the [most recent action on GitHub]( https://github.com/actions/starter-workflows/blob/main/pages/hugo.yml). You can place this file directly in the `.github/workflows` folder to replace the old `hugo.yml` file—but make sure to set `push: branches` to `["main"]`.


## Software

+ The website is built with Hugo v0.147.2 via GitHub Actions.
+ The website was developed locally with Hugo v0.147.2 on macOS Sequoia. 
+ The website was tested on the following browsers:
	+ Safari 18.4 on macOS Sequoia
	+ Mobile Safari on iOS 18  
+ Other Hugo versions, operating systems, and web browsers may require minor adjustments. Please [report any issues](https://github.com/pmichaillat/hugo-website/issues) to help improve compatibility.

