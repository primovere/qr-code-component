# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H).

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

## Overview

### Screenshot

<p align="center">
  <img src="./screenshots/qr-code-component-desktop.png" width="75%" alt="screenshot desktop version">
  <img src="./screenshots/qr-code-component-mobile.png" width="45%" alt="screenshot mobile version">
</p>

### Links

- Solution URL: [QR code component solution Page](https://www.frontendmentor.io/solutions/qr-code-component-XUAZV7y1kQ)
- Live Site URL: [QR code component](https://primovere.github.io/qr-code-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

- It's my first time to create a project with starter files.
  I learned how to push existing files to a GitHub repo.

1. Go to the project folder

   `cd Downloads/qr-code-component-main`

2. Start to track the folder's version change

   `git init`

3. Add all files to the stage for the following commit (version record)

   `git add .`

4. Commit the added files in the last step as the first version, like a snapshot, with a message.

   `git commit -m "first commit"`

5. Rename the current branch to main to ensure the local branch and GitHub's have the same name

   `git branch -M main`

6. Set the folder connect to the specified GitHub URL

   `git remote add origin git@github.com:username/qr-code-component.git`

7. Push the change you just made to GitHub

   `git push -u origin main`

- Estimate sizes of elements using transparency div in browser, Preview, and screenshot tool - Create a transparency div and make it overlap completely a specific element, and then check the div's size.

- Add horizontal padding to `.instruction` so the text doesn't touch the card's edges.

```css
.instruction {
  padding: 0 20px;
}
```

- Push footer to bottom using flex: 1 on `<main>`.

- The default browser font size is bound to root font size, so users who adjust their browser's default font size for accessibility can still control the site's text size — that's why the root font size (1rem) shouldn't be changed.

- The height of mobile design image is not the content requirement.

- `<h1>` can be identified as the main heading by screen readers in heading navigation, which help users find main messages quickly.
