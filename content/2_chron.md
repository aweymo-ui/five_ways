---
title: Chronological
nav: Chronological
gallery: true
---


**Timeline.js**, like the majority of the tools and platforms we will be looking at today, is driven by a Google Sheet that is filled with metadata about your items. This metadata contains certain fields which need to be understood programmatically, such as the date field in this case, and some fields that can be used to provide your editorial create context, such as the text field here.

Going to the [Timeline.js site](https://timeline.knightlab.com/?_gl=1*1t78oyf*_ga*MTA3MDc3NjIwLjE3MjI2MjM0NDg.*_ga_8F4WPDMPL5*MTcyMjYyMzQ0Ny4xLjAuMTcyMjYyMzQ0Ny4wLjAuMA..#make), you can begin by making a copy of their [Google spreadsheet template](https://docs.google.com/spreadsheets/d/1pHBvXN7nmGkiG8uQSUB82eNlnL8xHu6kydzH_-eguHQ/copy) and replacing these metadata examples with your items and text. While Timeline.js is most easily suited for linking media directly from sites like Wikipedia, Flickr, Soundcloud and YouTube, we can also link media directly from Google Drive like we are doing here. 

{% include gallery-figure.html img="timeline_spread.jpg" width="100%" alt="multiple colored fields of a Google spreadsheet." caption="Timeline.js metadata template adjusted for our items." %}

**To use the right link for media you are storing on Google Drive**, select your item, select **Share** and change the status of General Access to **Anyone with the Link** can share and copy that link. When you are finished creating your metadata, share the entire document and select **Publish to Web**. 

<div class="symbol-container">
    <p class="symbol">&#10042;</p>
</div>

Then copy the URL of your document and paste into [the box at step three](https://timeline.knightlab.com/?_gl=1*1t78oyf*_ga*MTA3MDc3NjIwLjE3MjI2MjM0NDg.*_ga_8F4WPDMPL5*MTcyMjYyMzQ0Ny4xLjAuMTcyMjYyMzQ0Ny4wLjAuMA..#make) to generate the timeline. Here is [a link to the adjusted metadata](https://docs.google.com/spreadsheets/d/1NFeGhsb17uHzSdiU083yGKcwyXy-xgsufNWk88C68NI/edit?usp=sharing) and [the resulting output](https://cdn.knightlab.com/libs/timeline3/latest/embed/index.html?source=1NFeGhsb17uHzSdiU083yGKcwyXy-xgsufNWk88C68NI&font=Default&lang=en&initial_zoom=2&height=650):

<iframe src="https://cdn.knightlab.com/libs/timeline3/latest/embed/index.html?source=1NFeGhsb17uHzSdiU083yGKcwyXy-xgsufNWk88C68NI&font=Default&lang=en&initial_zoom=2&height=650" width="100%" height="600px"></iframe>

Some notes on Timeline.js:

- **Slides will default start at the earliest date provided**, not the order of rows in the template
- This format also works best for visualizing items with **overlapping time spans**, rather than specific times like we have here.
- The group field in the template acts a little like tagging and is displayed on the left of the timeline below as you can see the audio, pdf, images and video.
- Users have the option to select the media which will bring them to the link. This will kick them out to another site if that is linked, or to your personal cloud where the item is stored, which may be preferable for retaining users.

