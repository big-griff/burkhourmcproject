# Problem Set 3½

Problem Set 3½ allows you to continue exploring your creating side. Having already designed and built your first website, we'll now be using CSS to make it look much cooler.

## Getting Started

To get started, you'll need to create a [GitHub](https://github.com/) repository to store your Problem Set 3½ code. After cloning my skeleton repository, you'll need to setup a remote to push your code to your repository instead of mine. Steps to accomplish this are outlined below.

### Setup

01. Login to your [GitHub](https://github.com/) account and create a new repository named `problem-set-3.5`.
02. In GitBash, navigate to your `APCSP` folder.
```
cd ~/Desktop/APCSP
```
03. Clone my skeleton repository from [GitHub](https://github.com/). This will make a copy of my repository and store it locally.
```
git clone git@github.com:rwilson-ucvts/principles-pset-3.5-skeleton.git
```
04. The cloning process will create a folder named `principles-pset-3.5-skeleton`. Rename this folder to `problem-set-3.5`.
```
mv principles-pset3-skeleton problem-set-3.5
```
05. Change directories to get into your `problem-set-3.5` folder.
```
cd problem-set-3.5
```
06. The cloning process will add a remote named `origin` that points at my skeleton repository. Rename `origin` to `upstream`.
```
git remote rename origin upstream
```
07. Add a new remote that points at the `problem-set-3.5` repository you created earlier. Make sure you replace `YOUR-USERNAME` with your actual [GitHub](https://github.com/) username.
```
git remote add origin git@github.com:YOUR-USERNAME/problem-set-3.5.git
```
08. Launch [Atom](https://atom.io/), select `File` and click `Add Project Folder...`.
09. Navigate to the `APCSP` folder on your `Desktop`, click the `problem-set-3.5` project folder, and click `Open`.

You should now see a folder named `problem-set-3` in the `Project` panel in [Atom](https://atom.io/).

10. Expand the `Project` folder. You should see a file named `README.md` (which is what you're reading right now!). That's all you get - no starter code this time! That's because you'll be copying over your existing files and folders from your `problem-set-3` repository.
11. To do that, add another remote that points at your previous `problem-set-3` repository. Again, make sure you replace `YOUR-USERNAME` with your actual [GitHub](https://github.com/) username.
```
git remote add pset3 git@github.com:YOUR-USERNAME/problem-set-3.git
```
12. Now, pull down all of the files and folders in your `problem-set-3` directory into your newly created `problem-set-3.5` directory.
```
git pull pset3 master
```

## Requirements

Modify the website you created for Problem Set 3. You'll be adding CSS to make it look a whole lot cooler. You're free to exercise creative expression and design, but must meet the minimum specifications below.

More specifically, your website must include and incorporate the following features and elements.

* At least 1 externally linked CSS file, which contains the vast majority of your styles.
   - Your CSS files should be in a folder named `styles`.
* At least 3 inline styles per page (for one-off styles that typically aren't replicated elsewhere).
* At least 3 different [type selectors](https://developer.mozilla.org/en-US/docs/Web/CSS/Type_selectors).
* At least 3 different [class selectors](https://developer.mozilla.org/en-US/docs/Web/CSS/Class_selectors).
* At least 3 different [ID selectors](https://developer.mozilla.org/en-US/docs/Web/CSS/ID_selectors).
* At least 3 different [attribute selectors](https://developer.mozilla.org/en-US/docs/Web/CSS/Attribute_selectors).
* At least 1 [universal selector](https://developer.mozilla.org/en-US/docs/Web/CSS/Universal_selectors).
* At least 3 different [combinators](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Selectors#Combinators).
* At least 3 different [pseudo-classes](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes).
* A `background-color` for each page.
* A `:hover` effect for each link (this does not count towards the [pseudo-classes](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes) requirement).
* Appropriate element spacing using `margin` and/or `padding`.
* A `border` around at least 1 image per page.
   - 1 of your `border`s must incorporate rounded corners.

To avoid confusion, your directory structure must match the following. If something is followed with a `/`, it is a folder; otherwise, it is a file.

```
problem-set-3/
   images/
      myimage1.png
      subfolder/
         myimage2.png
   index.html
   mysubtopic1.html
   mysubtopic2.html
   mysubtopic3.html
   README.md
   styles/
```

Of course, your filenames will be different than mine. They are alphabetized, so they will likely appear in a different order, too. The `subfolder` inside of the `images` folder is optional. You might find it useful to further categorize your pictures, but it is not required. The image files inside of the `images` and `subfolder` folders are examples. Yours, of course, will be named differently.

## Deadline

Your Canvas submission is due at or before 11:59pm on your section-specific due date.
* October 9, 2018 (A 3/4 & 7/8)
* October 10, 2018 (B 3/4 & 7/8)

### Submission Requirements

All that is required for submission is the top-level URL to your [GitHub](https://github.com/) repository for this problem set.