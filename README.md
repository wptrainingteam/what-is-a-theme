#  What is a Theme?

## Description

In this module, you'll learn how a theme interacts with WordPress and you will look at the role of CSS within that WordPress theme. You will also explore the definitions of both a framework and a child theme and see how they work.

## Prerequisite Skills

*   A basic knowledge of the names of web languages (HTML, [CSS](https://github.com/wptrainingteam/introduction-to-css), PHP)
*   Ability to edit files with a text editor
*   A desire to learn

## Assets

*   None needed

## Screening Questions

*   Do you want to begin to understand how WordPress sites are built?
*   Do you have basic knowledge of the names of web languages (HTML, CSS, PHP)?
*   Do you have the ability to edit files with a text editor?

## Teacher Notes

*   This lesson is meant to be a high-level overview of themes. You will find more details available in other lesson plans.

## Hands-on Walkthrough

### What is a Theme?

A theme is a collection of files that include HTML, CSS, JavaScript, and PHP code that controls how your site's information is displayed.

### How Does a Theme Interact with WordPress?

Themes are one of the three components that make up a WordPress website. WordPress itself provides the engine and database behind the site. Plugins provide functionality; such as forms and e-commerce. Themes give WordPress websites their look and feel. They are like the _skin_ of your site, or the layer you see on the outside, which is often referred to as the _front end_ of a website.

### What is a Theme Framework?

The term "Theme Framework" currently has three meanings:

*   A "drop-in" [code library](http://codex.wordpress.org/Theme_Frameworks#Code_Library "Codex: Code Library") that is used to facilitate development of a theme (e.g., Bootstrap or Foundation)
*   A stand-alone [base/starter Theme](http://codex.wordpress.org/Theme_Frameworks#Base.2FStarter_Theme "Codex: Base/Starter Theme") that is intended either to be forked into another theme (e.g. _s (Underscores) )
*   A parent theme template (e.g., Genesis, Thesis)

What these definitions have in common is that they provide code that serves as a base to build upon to create the theme that will actually be used to display the site.

### What is a Child Theme?

A child theme is a theme that builds upon another theme, called the parent theme. Child themes allow you to modify, or add to the code of a parent theme. **A child theme is the best, safest, and easiest way to modify an existing theme**, whether you want to make just one tiny change or completely overhaul it. When you use a child theme, you must also install a parent theme to make it work properly. Child themes are not meant to stand on their own. Instead of modifying the theme files directly, create a child theme and make your edits there. This will help prevent any updates to the parent theme from breaking your website.

## Exercises

*   None

## Quiz

**What must be installed in order to use a child theme?**

1. A starter theme
2. A framework
3. A parent theme

**Answer:** 3. A parent theme

* * *

**What is the best way to make modifications to an existing theme?**

1. Modify or add code to the parent theme
2. Create a child theme
3. Install a new theme

**Answer:** 2. Create a child theme

## Additional Resources

[Using Themes](https://codex.wordpress.org/Using_Themes) @ Codex
