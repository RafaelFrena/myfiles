# Decola Design System

This document has the purpose of establishing a reference for the implementation of new features in the project.
The especifications should always be considered, although there's always room for creativity.

> The platform is not the content, but the presentation of the content published by the content creators. That being said, it has to seek neutrality.

## Good UX Practices to follow (inspired by [this valuable text](https://www.usability.gov/what-and-why/user-interface-design.html)):

* Keep simple;
* Use common elements and conventions;
* Draw attention to the important pieces by using the UI elements;
* Use color, contrast and texture more as weapons than decoration;
* Use typography to create hierarchy;
* Constantly communicate the user of what is happening;
* Remove the burden from the user by setting defaults (ex.: autofill forms, give priority to the most used functionalities, et cetera).

## Layout

The whole aplication follows a simple and - as far as possible - immutable structure composed by 3 main components:

### Header
The header will always display an indication of where we are at the moment, such as further information about the page.

```css
.header {
  height: 64px;
  width: 100vh;
  background: #fafafa; /* cultured white */
  box-shadow: -2px 3px 4px rgba(0, 0, 0, 0.25);
}
```

### Sidebar
The sidebar displays the main pages of the app and copyright stuff at the bottom.

```css
.sidebar {
  height: 100vh;
  width: 60px;
  background: #00a6ff; /* blue jeans */
}
```

### Main
The main section is where the content will always show up. 

```css
.main {
  height: 100vh;
  width: 100vh;
  background: #dfe3e8; /* blueish gray */
}
```
#### Blocks
Inside the main section there are containers styled as white blocks in which there'll be displayed any sort of content.

```css
.blocks {
  background: #fafafa; /* cultured white */
  border-radius: 20px;
  box-shadow: -2px 3px 4px rgba(0, 0, 0, 0.25);
}
```

### Demos: 
![layout](https://github.com/RafaelFrena/myfiles/blob/main/layout.png?raw=true)

![layout-darkmode](https://github.com/RafaelFrena/myfiles/blob/main/layout-darkmode.png?raw=true)

## Color

#### Main color
Blue Jeans #5dadec

![bluejeans](https://github.com/RafaelFrena/myfiles/blob/main/bluejeans.PNG?raw=true)

Use: Sidebar background and possibly some other thing that require highlight.

#### Dark color
Jet #35353a

![bluejeans](https://github.com/RafaelFrena/myfiles/blob/main/jet.PNG?raw=true)

Use: icons, borders and text.

#### Bright color
Cultured #fafafa

![bluejeans](https://github.com/RafaelFrena/myfiles/blob/main/cultured.PNG?raw=true)

Use: main background for any sort of content.

#### Background color
Gainsboro #dfe3e8

![bluejeans](https://github.com/RafaelFrena/myfiles/blob/main/gainsboro.PNG?raw=true)

Use: Main section background.

#### Alt background color
Dark liver #47474b

![dark-liver](https://github.com/RafaelFrena/myfiles/blob/main/dark-liver.PNG?raw=true)

Use: Main section background.

## Typography

```css
* {
  font-family: 'Nunito', sans-serif;
  p: 18px; /* this is the most important guy, 18px for the sake of comfortable reading */
}

h1 {
  font-size: 36px;
}

h2 {
  font-size: 24px;
}
```

## Iconography

Description

## Accessibility

Description
