# dan's portfolio

This is my (dan jacobson) portfolio website. It's designed to be mostly professional, but also a bit fun. I use it to muck around with different tech and silly ideas.

Currently, the website is a Jekyll static site, using the [cvless theme](https://github.com/piazzai/cvless) from Michele Piazzai (and others).  

## Features

The site offers some fun stuff. Links to my email, linkedin, and github. My CV, which can be easily downloaded in digestible resume form. A `particle.js`-based cute little broccoli emoji background.

I'm also working on adding additional functionality. Namely:
- A blog (lol),
- A projects page (it's in the works I promise),
- Interactivity via emoji-reacts to some of the pages on the site.

## Installation

Clone the repo locally. The repo depends on `ruby`. If you don't have it, [install ruby](https://www.ruby-lang.org/en/documentation/installation/), for example via `brew install ruby` on macOS.

Next, use `bundler` (which should come preinstalled with your ruby version), and run `bundle install` in the project directory.

## Running the site locally

After cloning, and installing dependencies, run the repo with `bundle exec jekyll serve`.