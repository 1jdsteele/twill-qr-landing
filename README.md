# Twill the Messenger QR landing page

## Link to deployed page

https://www.twillthemessenger.com/blogs/woven-scripts

## Link to stretch goal: video gallery page

https://www.twillthemessenger.com/pages/highlights

## Link to scrapped page

https://www.twillthemessenger.com/pages/trademark-twill

## Project Description

The purpose of this repo is to show and describe the process I went through to meet the need of small business owner Julian Leon for his clothing brand, Twill the Messenger.

After many iterations of ideas, we agreed that his physical QR codes would link to a page that has links to all of his stories (think blog posts). I would make that page. 

That page was made by reworking Liquid in his Shopify shop via a developer account I created and Leon gave developer permissions to.

Now that this page has been created to his specifications, Leon can leave his clothing at viewings with the QR code so that people can find out more information about what he does without him there.

Leon then gave me another (stretch) goal: a video gallery page. This was completed with dummy data and not directly connected to his main shop page so that users cannot easily navigate to it. The video gallery code has a template I created with directions so Leon can add videos and descriptions as he sees fit.

## Screenshots

### After

#### Desktop QR Landing Page

<img width="1437" alt="Screen Shot 2022-04-14 at 3 33 41 PM" src="https://media.git.generalassemb.ly/user/41473/files/51379480-bc08-11ec-9701-45665e4a4631">

#### Mobile QR Landing Page

<img width="372" alt="Screen Shot 2022-04-15 at 2 38 24 PM" src="https://user-images.githubusercontent.com/97859358/163635158-a300aa86-415b-40b8-9599-dbe38c29542a.png">

#### Desktop Video Gallery

<img width="1436" alt="Screen Shot 2022-04-15 at 2 18 57 PM" src="https://user-images.githubusercontent.com/97859358/163633589-7d34bc68-b760-4412-9394-2aa80bfcab7b.png">

#### Mobile Video Gallery

<img width="362" alt="Screen Shot 2022-04-15 at 2 20 03 PM" src="https://user-images.githubusercontent.com/97859358/163633654-daef3289-f30b-491b-92b7-90a8af499b12.png">

### Before

#### Desktop QR Landing Page

<img width="1264" alt="Screen Shot 2022-04-13 at 4 36 46 PM" src="https://user-images.githubusercontent.com/97859358/163286765-0f2a1fe2-41bb-46d8-84f2-f5f6725967a1.png">

#### Mobile QR Landing Page

<img width="364" alt="Screen Shot 2022-04-13 at 4 40 00 PM" src="https://user-images.githubusercontent.com/97859358/163287022-e10c0aec-eee4-46a2-a0d9-39e714bdf7d9.png">

## Sample of Liquid within Shopify

<img width="753" alt="Screen Shot 2022-04-15 at 2 41 33 PM" src="https://user-images.githubusercontent.com/97859358/163635394-1d6f0f9e-2a29-4fa3-89cb-4e42140e5b3f.png">

Above creates the individual images and links for each post on the  QR  landing page. Note that Liquid uses {%%} for logic and {{}} to render dynamically. | is used as a filter. To note as well is the comment I left for the owner. I prefaced all of my comments to the owner with JUJU so that he can easily find all directed comments via search.

## Explanation of files in this repo

The files in this repo are copies of some of the files that I created or files that I added to or made major deletions to.

blog.liquid was the code that I deleted a whole bunch from and added a few classes, some other code and commented thoroughly to create the final blog page.

theme.scss.liquid contains the css that controls Leon's entire store. My additions start at the very bottom.

page.highlights.liquid is connects the menu to the video gallery page.

page.video-gallery.liquid was the stretch goal page, it displays videos and text. It has a template and directions for the owner to add more videos in the future.

All subsequent files were not used in the end for this project.

page-content.html was the html to the blog page I had started making from "scratch."

qr-landing-page.liquid is the code that renders page-content.html.

theme.css controls the themes to a duplicated generic store. Here I was looking for how it controls the whole store.

Also to note: I created what is called two themes. One theme, Debut Copy Trademark 2 dev theme to experiment in which was originally a copy of an empty store, and Spring 2022 April 13, 2022 w qr landing page which was a copy of Leon's entire store, to be used as a development branch.

## Tech Used

Shopify

Liquid

VS Code

Git

GitHub

CSS

HTML

## Link to GitHub repository

https://github.com/1jdsteele/twill-qr-landing

## Contribution Guidelines

This repository is not meant to be contributed to. If you have suggestions, would like to report a bug, or would like to work on the Twill the Messenger shop, please contact Julian Leon via https://www.twillthemessenger.com/

## MVP Goals

Page that links to all stories via images set up in a 3-across grid.
This page is accesible via a QR code.
Page has similar sytling to the rest of Twill the Messenger shop.

## User Stories

As a clothing browser, I want to easily find the story I'm looking for.
As the owner, I want the page to appear via a QR code.
As the owner, I want others to quickly find the story they are looking for.
As the owner, I want to know how to maintain this page.
As a developer working on this project on the future, I do not want to be distracted by code that isn't doing anything.
As a developer working on this project in the future, I want the comments to clearly guide and show me what is happening and why.

## Future Goals

Leon has given the full go ahead for publication and is very happy with the way this page has turned out. Future goals would include anything else Leon has in mind.

## Sources

Legacy code provided by Julian Leon's shopify store.

New code written by Jake Steele.

Danny Thompson helped with alignment.

Esin Saribudak helped with standardizing gap sizes.

## Original wireframes

### Desktop

The end product was instead a grid of 3 across, per request of the owner.

<img width="1027" alt="wireframe_twill_fullview" src="https://media.git.generalassemb.ly/user/41473/files/aa935580-b728-11ec-81e3-04a1c68fb511">

### Mobile

<img width="347" alt="wireframe_twill_full_mobile" src="https://media.git.generalassemb.ly/user/41473/files/b1ba6380-b728-11ec-910b-12cef4f9012a">


