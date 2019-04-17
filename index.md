# U.S. executions since 1977

{% include css.html %}

![Title Image]({{ site.baseurl }}/assets/images/America (3).PNG)

## Home

.

---

**[View the repository in GitHub](https://github.com/usf-portal/hacking-historical-texts-final)**

---

{% include nav.html %}

---

## Project Template

This is a starter template for final projects. When you have completed your final project, you should replace this message (README.md) with a short 1-2 paragraph description of your project.

See the [Course Workbook Project Page](https://theportus.github.io/hacking-historical-texts) for more information on the final project.

**REQUIREMENTS BEFORE STARTING**
+ [GitHub account](https://github.com) created
+ [Atom](https://atom.io) editor installed

---

## Getting a Copy and Renaming the Repository

To get started, you need to fork your own copy of this repository

1. Make sure you are on the homepage for [this repo](https://github.com/usf-portal/hacking-historical-texts-final)
2. Click the 'Fork' button, near the top right of the page, to the right of the repository title.
3. That's it, now you have your own copy. If you notice the title of the page, you are now at *your* version of the repo located at *your* account.
4. If you can't find it, your repo should be at `https://github.com/your-username/hacking-historical-texts-final`
5. You should change the name of the repository, to do this...
    1. Go to your repository homepage
    2. Click the `Settings` tab
    3. Under `Repository Name` put your project name. GitHub general ettiquite is to use lower case and name `your-repository-like-this`

---

## Launching the Site

To create the website from this repository, follow these steps...

1. Go to your repository homepage
2. Click the `Settings` tab
3. Change the name of the repository to represent your project
4. Scroll down to the `GitHub Pages` section
5. Under `Source` click the dropdown menu and choose `master branch`

**See your site at your-username.github.io/your-repo-name**

*(May take a few minutes)*

---

## Changing the Theme

To change the look of the website, follow these steps...

1. Go to your repository homepage
2. Click the `Settings` tab
3. Scroll down to the `GitHub Pages` section
4. Under `Theme Chooser` click the dropdown menu
5. Follow on-page instructions to preview and select your theme

---

## Files To Edit

Make sure you edit these files with your own data

```sh

# Intro pages, one for the repo, one for the site. You can make them identical
README.md # This file, which is displayed on the GitHub repository page
index.md # This is the homepage of your site

# Configuration and credit files. Edit with your team's info
_config.yml # Edit with your title/credit info, used when building site
CITATION.cff # A machine-readable citation file, edit with your info

# Where to put your own files
pages/*.md # The folder containing the rest of your pages (except index.md)
assets/images/ # Put your images here
assets/data/ # Put any data you want to include here (no files over 30mb)

```

---

## Images, Files, and Linking

*Putting in an image*

```sh

# Make sure to put your image in the assets/images folder (or subfolder)
![Example Image]({{ site.baseurl }}/assets/images/example-image.png)

```

*Linking to Sample Data*

```sh

# Make sure your data file is in the assets/data folder (or subfolder)
[Display text]({{ site.baseurl }}/assets/data/example-data.csv)

```

*Linking to index.md*

```sh

# Make sure the page you link to is in the pages/ folder
[Display text]({{ site.baseurl }}/index.md)

```

*Linking to another site page that isn't index.md*

```sh

# Make sure the page you link to is in the pages/ folder
[Display text goes here]({{ site.baseurl }}/pages/put-your-page-name-here.md)

```

*Linking to an external page*

```sh

[Display text](https://www.put-your-link-url-here.html)

```

---

## Past Project Examples

* [Confederate Memorials](http://confederate-memorials-project.readthedocs.io/)
* [The Slave Ledges](http://slave-ledger.readthedocs.io/en/latest/)
* [An Teanga Sean: The Celtic Languages](http://an-teanga-sean-the-celtic-languages.readthedocs.io/)

---
