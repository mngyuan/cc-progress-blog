# cc-progress-blog

Progress Blog for Creative Computing Fa23

A progress blog documents work done on a regular basis i.e. weekly and helps document the process of building a project from start to finish in the moment. Sharing the process both helps yourself later when you need to document and display the project, and others who might want to undertake similar work or understand your work and you better.

# Structure

## `index.html`

This is the landing page people first see when they arrive at your blog, with a list of links to posts they can read and a brief introduction to the blog and maybe yourself. `index.html` is the default page loaded when you navigate to a URL, i.e. https://google.com and https://google.com/index.html are the same thing.

## `<nav>`

`<nav>` is a semantic element, meaning the name of the element is meant to convey its purpose. In this case, the contents of a `<nav>` element are meant to be a navigation bar or some element full of important links to pages that helps users quickly navigate your site.

## `<main>`

`<main>` is also a semantic element which signifies the main content of the page - from [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/main): "The main content area consists of content that is directly related to or expands upon the central topic of a document, or the central functionality of an application."

## `23-10-02.html`

Individual post pages are named after the date they're posted. When adding a new page, make sure to update the `<nav>`s on each page which has one and the listing of posts on `index.html`, so people can find your posts easily.

# Using this template for your own blog

To start your own blog with this template as a starting point, you can _fork_ this _repository_, which essentially creates a copy of the code but in a new repository that you control under your username. A _repository_ is just the word git & Github use to refer to a folder of code which is tracked by git's version control. You'll see that when you fork this repo, the history of what I've done to set it up comes with it. As you update this repo, that history diverges (_forks_) to create a fork in the "road" of the history of this repo.

```
Before              After forking and adding commit C

                         ( C )
                          /
    ( B )               ( B )
      |                   |
    ( A )               ( A )
```
