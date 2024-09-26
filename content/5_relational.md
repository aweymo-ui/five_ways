---
title: Relational
nav: Relational
gallery: true
---

**In both this section and the next one** we will be working with different iterations of a platform called [CollectionBuilder](https://collectionbuilder.github.io/) that was created here by the [Center for Digital Inquiry and Learning](https://cdil.lib.uidaho.edu/) at the U of I library. Going from most lightweight to more technically advanced, there is **CollectionBuilder Sheets**, **CollectionBuilder-GH** (which stands for GitHub) and **CollectionBuilder CSV**, like the file type. To view our items relationally, letting the reader compare and contrast the differences between items and their varying metadata, we are going to build a simple database using Sheets.

- First, you will need to create an account with **GitHub**, a cloud-based platform that allows developers to store, share and collaborate on code (but don’t worry, this doesn’t require doing any coding). 

- Next visit the [cb-sheets repository page](https://github.com/CollectionBuilder/collectionbuilder-sheets) and select `Use this Template` and then the `Create a New Repository` dropdown option.

{% include gallery-figure.html img="create-sheets-repo.gif" width="100%" alt="Gif of the action to create a new repository within the GitHub browser interface." %} 

- Leave the repository as `Public`. Enter a repository name (use a lowercase name without spaces or odd characters, e.g. watkins-demo) and click the `Create repository` button.

{% include gallery-figure.html img="generate-sheets-repo.gif" width="100%" alt="Gif of the action to create a new repository within the GitHub browser interface." %} 

- Then we will add the media to the **Objects** folder and commit the changes. “Commits” are how GitHub saves changes that you make to your site either individually or in batches.

- Next, in our **config.yml** file, we can either link to our published Google Sheet containing our metadata if this is an ongoing, collaborative project, or we can add our metadata CSV file to our **Assets** folder if it is complete.

{% include gallery-figure.html img="edit-file-sheets.gif" width="100%" alt="Gif of the action to adjust config.yml file within the GitHub browser interface." %} 

For example, linking a Google sheet of an ongoing project:

```
metadata-csv: https://docs.google.com/spreadsheets/d/e/2PACX-1vRJhe6UcNZXItEtHlxQFOaHBBD2SDU8nyNOAROtcLWLrl83sYaCNBNYHOvhM_xZ7SVnnOrjCzo6U5_o/pub?output=csv
```

or a CSV of a finished project named "hist320" (note the .csv filename is omitted)

```
metadata-csv: hist320
```

{% include gallery-figure.html img="download-sheets-csv.gif" width="100%" alt="Gif of the action to download a csv from Google Sheets." caption="How to download a CSV from Google Sheets" %} 

{% include gallery-figure.html img="add-file-sheets.gif" width="100%" alt="Gif of the action to add exported CSV file to the Assets folder of your Git Repository." caption="How to add exported CSV file to the Assets folder of your Git Repository" %} 

- Then change the style formatting of the site in the **theme.yml** file, add a banner image and customize navigation as I have here

<div class="symbol-container">
    <p class="symbol">&#10042;</p>
</div>

- **Finally**, go to the repository settings in Git, deploy from the main branch and your site should be live. Moving forward, with every new commit that you make, the site will rebuild itself to incorporate those changes.

{% include gallery-figure.html img="settings-pages-sheets.gif" width="100%" alt="Gif of the action to access the Settings and Pages sections of your repository from the GitHub browser" caption="How to access the Settings and Pages sections of your repository from the GitHub browser" %} 

## Output

Using our four media items, these actions produce the [following site](https://aweymo-ui.github.io/hist320_sheets_approach/):

<iframe src="https://aweymo-ui.github.io/hist320_sheets_approach/" width="100%" height="600px"></iframe>


{% include feature/alert.html text="Note that all CollectionBuilder templates also feature a timeline and map interface, but they function in slightly different ways to the Knightlabs Timeline.js and Storymaps. Also note that there is a way to embed the Timeline.js feature in a CollectionBuilder site if you prefer it." color="light" align="center" %}

Find the complete walkthrough for creating a site with Sheets [here](https://collectionbuilder.github.io/cb-docs/docs/walkthroughs/sheets-walkthrough/#sheets-walkthrough-part-2) (start with part two)