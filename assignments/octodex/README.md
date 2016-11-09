# Octodex

### Setup

- First, ensure you have the [`app-app` generator](https://github.com/tiy-tpa-fee/generator-app-app) installed. We will have done this in class.

- Open your Terminal and create and change into the project's directory:

  ```sh
  mkdir -p ~/tiy/week-1/day-3/octodex
  cd ~/tiy/week-1/day-3/octodex
  ```

- Run the generator to create a boilerplate project:

  ```sh
  yo app-app alpha
  ```

  This might take a minute to run, the generator is installing a handy development server and a tool to easily deploy our page to the web.

- Let's create our `git` repository now, and start tracking changes right away:

  ```sh
  git init
  git commit -am "Hello, App App"
  ```

  You can change the commit message to be anything you want.

- Open as a web site in Visual Studio

- Using the solution explorer in your editor, open the files `public/index.html` and `public/screen.css` and mark up and style your document (remember all content goes _inside_ the `<body>` tags). Don't worry about the other files in the directory for now, we'll talk about those later, right now, we're mostly concerned with the two files in `public`; `index.html` and `screen.css`.

## Description

GitHub has a great mascot called OctoCat. OctoCat even has it's own gallery of variations, created by GitHub itself and fans, called [Octodex](https://octodex.github.com).

Unfortunately, the Octodex is not responsive*! Today, your task is to recreate the layout of The Octodex as closely as possible, but make it responsive. You can use all the tools you have at your disposal to get the job done. Use your browser's Developer Tools to inspect their site to find the exact font sizes and padding amounts.

![Octodex](https://tiy-learn-content.s3.amazonaws.com/ec8b2d13-octodex.png)

\* Well, _actually_ it uses javascript set the number of columns on page load, but we want to see interactive responsiveness when we resize our window!

## Objectives

* Understand HTML/CSS Layout
* Be able to place elements on a page where you want them.
* Use flexbox techniques layout pages.

### Deliverables

- a git repo containing:
  - `index.html`
  - `styles` folder
    - `main.css`
  - `images` folder
    - with any images you used with your design
- a surge url

## Explorer Mode

Recreate the page as closely as you possibly can. Use the same fonts, sizes, and colors. Download some of your favorite Octocat images to use in your page (12-16 or so). Your layout should be flexible, but doesn't need to _perfectly_ responsive. Use flexbox styles to layout the header and the Octocats (hint: checkout the `flex-wrap` property).

## Adventure Mode

If you're feeling adventurous, use CSS _media queries_ to resize the Octocat containers to look great as a single full-width column on small screens, and a nice grid on bigger screens.

## Additional Resources

- [Google Fonts](http://google.com/fonts)
- [What the Flexbox?!](http://flexbox.io)
- [Learn CSS Layout](http://learnlayout.com/)
- [CSS Triangle Generator](http://apps.eky.hk/css-triangle-generator/)
- [Responsive Web Design](http://alistapart.com/article/responsive-web-design/)
