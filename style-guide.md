# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Primary

- Dark Blue (intro and email sign up background): hsl(217, 28%, 15%)
- Dark Blue (main background): hsl(218, 28%, 13%)
- Dark Blue (footer background): hsl(216, 53%, 9%)
- Dark Blue (testimonials background): hsl(219, 30%, 18%)

### Accent

- Cyan (inside call-to-action gradient): hsl(176, 68%, 64%)
- Blue (inside call-to-action gradient): hsl(198, 60%, 50%)

### Neutral

- White: hsl(0, 0%, 100%)

## Typography

### Body Copy

- Font size: 14px

### Headings, Call-to-actions, Header Navigation

- Family: [Raleway](https://fonts.google.com/specimen/Raleway)
- Weights: 400, 700

### Body

- Family: [Open Sans](https://fonts.google.com/specimen/Open+Sans)
- Weights: 400, 700

## Icons

For the social icons, you can use a font icon library. Some suggestions can be found below:

- [Font Awesome](https://fontawesome.com/)
- [IcoMoon](https://icomoon.io/)
- [Ionicons](https://ionicons.com/)


body
  background-color: hsl(218, 28%, 13%)
  margin: 0
  padding: 0
  box-sizing: border-box
  color: hsl(0, 0%, 100%)
  font-size: 14px
  font-family: 'Raleway', sans-serif

.container
  display: flex
  flex-direction: column
  justify-content: center

a
  text-decoration: none
  color: white
  cursor: pointer

#intro
  background: url('images/bg-curvy-desktop.svg') bottom center no-repeat hsl(217, 28%, 15%)
  min-height: 500px
  display: flex
  flex-direction: column
  align-items: center
  justify-content: center
  width: 100vw
  #introImage
    width: 100%
    height: auto
  header
    padding: 40px 40px
    justify-self: flex-start
    align-self: flex-start
    display: flex
    justify-content: space-between
    width: calc(100% - 80px)
    span
      margin: 0px 15px
      padding: 15px

.intro
  display: flex
  flex-direction: column
  justify-content: center
  align-items: center
  text-align: center
  min-width: 200px
  width: 100%
  max-width: 1000px
  h1
    margin-top: 40px
    text-rendering: optimizeLegibility
    font-size: 3em
    font-weight: 700
    font-family: 'Raleway', sans-serif
  p
    font-size: 2em
    font-weight: 400
    margin-bottom: 60px


.button
  background-color: hsl(176, 68%, 64%)
  min-width: 150px
  width: 40%
  max-width: 300px
  color: white
  font-size: 2em
  padding: 10px
  border: 0
  border-radius: 25px
  margin-bottom: 100px

.main
  background-color: hsl(218, 28%, 13%)
  display: grid
  grid-template-columns: 32.5% 32.5%
  align-items: center
  justify-content: center
  margin: 0
  width: 100vw

.services
  display: flex
  flex-direction: column
  justify-content: center
  align-items: center
  margin-bottom: 100px
  width: 100%
  text-align: center
  h2
    font-size: 2em
    font-weight: 700
    margin: 30px 0 10px 0
  p
    font-size: 16px
    font-weight: 100
    width: 90%

.works
  width: 100%
  display: flex
  flex-direction: column
  justify-content: center
  h1
