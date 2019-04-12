# Synth-Pop Band Website

A static (front-end only) website for an 80s inspired cinematic synth-pop band from California.

To see working version please go to: [Live Preview](https://hopeful-bardeen-ef0513.netlify.com/)

## UX

The cinematic 80s inspired band website for the fans of synth-pop music, so they can listen to the latest tracks, view video clips, and check tour dates.

To learn more about the goals of the band, please read the [Project Brief](ux/Project_Brief.md) document.

### Objectives

- Increase online visibility
- Increase fanbase
- Promote music
- Share tour dates

#### Users

- Current and potential **Fans**

#### Stories

"As a fan, I want to listen to band music, so that I can hear the latest tracks."

"As a fan, I want to view video clips, so that I can see the footage of recent tours."

"As a fan, I want to view photos, so that I can see the cool moments of the band."

"As a fan, I want to purchase music tracks, so that I can listen to them whenever I want."

"As a fan, I want to check tour dates, so that I know when they are coming to town."

"As a fan, I want to follow them, so that I can receive important updates fast."

## Features

- Mobile-first
- Responsive
- Semantic
- Navigation
- Events
- Gallery
- Bandcamp
- SoundCloud
- YouTube

_Features to be implemented in the future:_

- Instagram feed

## Structure

To learn more about the information architecture and the flow of this application, please view the [Mindmap](ux/v1/Mindmap_v1.png).

## Skeleton

#### Wireframes

_Small:_ [Home](ux/v1/Wireframes/Small/Home.png), [Tour Dates](ux/v1/Wireframes/Small/Tour_Dates.png), [Music](ux/v1/Wireframes/Small/Music.png), [Videos](ux/v1/Wireframes/Small/Videos.png), [Photos](ux/v1/Wireframes/Small/Photos.png), [Biography](ux/v1/Wireframes/Small/Biography.png), [All in One](ux/v1/Wireframes/Small/Wireframe_Small_v1.pdf)

_Medium:_ [Home](ux/v1/Wireframes/Medium/Home.png), [Tour Dates](ux/v1/Wireframes/Medium/Tour_Dates.png), [Music](ux/v1/Wireframes/Medium/Music.png), [Videos](ux/v1/Wireframes/Medium/Videos.png), [Photos](ux/v1/Wireframes/Medium/Photos.png), [Biography](ux/v1/Wireframes/Medium/Biography.png), [All in One](ux/v1/Wireframes/Medium/Wireframe_Medium_v1.pdf)

## Surface

#### Fonts

Roboto - https://fonts.google.com/specimen/Roboto

Roboto Condensed - https://fonts.google.com/specimen/Roboto+Condensed

Share - https://fonts.google.com/specimen/Share

Racing Sans One - https://fonts.google.com/specimen/Racing+Sans+One

Josefin Sans - https://fonts.google.com/specimen/Josefin+Sans

#### Colours

![alt text](ux/v1/Designs/Colours.jpg)

#### Design Mockups

_Small:_ [Home](ux/v1/Designs/Small/Home.jpg), [Tour Dates](ux/v1/Designs/Small/Tour_Dates.jpg), [Music](ux/v1/Designs/Small/Music.jpg), [Videos](ux/v1/Designs/Small/Videos.jpg), [Photos](ux/v1/Designs/Small/Photos.jpg), [Biography](ux/v1/Designs/Small/Biography.jpg)

_Medium:_ [Home](ux/v1/Designs/Medium/Home.jpg), [Tour Dates](ux/v1/Designs/Medium/Tour_Dates.jpg), [Music](ux/v1/Designs/Medium/Music.jpg), [Videos](ux/v1/Designs/Medium/Videos.jpg), [Photos](ux/v1/Designs/Medium/Photos.jpg), [Biography](ux/v1/Designs/Medium/Biography.jpg)

## Tech

A list of all of the languages, frameworks and libraries used to construct this project.

- HTML & CSS
- Bootstrap CSS - https://getbootstrap.com
- Google Fonts - https://fonts.google.com
- Node - https://nodejs.org
- npm - https://www.npmjs.com
- Sass - https://sass-lang.com
- Font Awesome - https://fontawesome.com
- Prettier - https://prettier.io

## Testing

Checked the site with W3C [HTML](https://validator.w3.org/nu/?doc=https%3A%2F%2Fhopeful-bardeen-ef0513.netlify.com%2F) and [CSS](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fhopeful-bardeen-ef0513.netlify.com%2Fcss%2Fmain.css&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en) validators, and fixed the issues accordingly.

I've used [Google Lighthouse](https://developers.google.com/web/tools/lighthouse/) to run a series of audits against the page and generate a reports.

## Deployment

Before deploying the site to a hosting provider, you need to compile the "main.scss" file.

Install Node from: https://nodejs.org/en/download/ and then run:

```
$ npm install
$ npm run sass
```

Bootstrap will be imported and single stylesheet (main.css) will be generated at "css" directory.

Static files hosted on Netlify. To see working version please go to: [Live Preview](https://hopeful-bardeen-ef0513.netlify.com/)

## Credits

#### Media

The photos used in this site were obtained from:

- https://www.facebook.com/fm84music/

- https://www.instagram.com/fm84music

- https://www.goodfon.com/user/kipish_fon/

The soundtracks used in this site were obtained from:

- https://fm84.bandcamp.com/

- https://soundcloud.com/fm84

The videos used in this site were obtained from:

- https://www.youtube.com/user/NewRetroWave

- https://www.youtube.com/user/ViolentSuccess

- https://www.youtube.com/channel/UCQEOS714xK3pmvkvMyafPRQ

#### Acknowledgements

Inspiration for the style of this site:

- https://www.goodfon.com/wallpaper/synth-retrowave-synthwave-fon-new-retro-wave-sintveiv-ret-16.html

Help customising Bootstrap with Sass:

- https://itnext.io/setting-up-a-sass-build-process-aa9fd92fa585

- https://getbootstrap.com/docs/4.3/getting-started/theming/

- https://uxplanet.org/how-to-customize-bootstrap-b8078a011203
