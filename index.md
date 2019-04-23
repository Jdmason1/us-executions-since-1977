# Year by year number of executions

{% include css.html %}

![Title Image]({{ site.baseurl }}/assets/images/year value (2).PNG)


---

{% include nav.html %}

---

## Home

My project is set up to examine and analyze data through visualizes retaining to United States executions since 1977.  I am working from 1977 onward because for a short time the death penalty was suspended and called unconstitutional by the United States Supreme Cour. That changed however in 1976 with a new death penalty statute, reinstating it as constitutional.  This is a very controversial subject among citizens today as it has been for year and I want to look to see if I can find any patterns or trends in location, race, age and more. While doing so I will be comparing Florida with the rest of the nation on our own executions.  I will be doing this all by using Webscraper for my data gathering and Tableau for all my visualizations.   

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
