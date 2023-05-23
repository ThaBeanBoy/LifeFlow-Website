# LifeFlow Website

![Thumbnail](./thumnail.png)

## Table of Content

- [LifeFlow Website](#lifeflow-website)
  - [Table of Content](#table-of-content)
  - [Project overview](#project-overview)
    - [Tools](#tools)
    - [Design](#design)
    - [Responsive navigation](#responsive-navigation)
  - [Design](#design-1)
    - [Design Approach](#design-approach)
    - [Figma Tips](#figma-tips)
      - [Auto Layout](#auto-layout)
      - [Components](#components)

## Project overview

This project is meant to showcase the process from design to deployment of a static website. The first thing covered is

### Tools

Different tools are going to be used:

1. [Figma](https://www.figma.com/) - The edesign tool used to design the LifeFlow website. This is not necessary for those who just want to focus on the development cycle.
2. [VSCode](https://code.visualstudio.com/) - Text Editor, we will also use some extensions that make development easier.
3. HTML - The website is a static website, using HTML is going to be fine for this project.
4. [SCSS](https://sass-lang.com/) - Used for styling.
5. JS - Used to make the moile navigation open & closeable.
6. [Git](https://git-scm.com/) - Version control system. This will help us seperate implementation of different parts of the website, & merge it into 1 final project. Different branches will also represent different aspects of the website making it easy to follow the whole structure of the project.
7. [GitHub](https://github.com/) - GitHub will serve 2 functions here, we'll use it to store the repo inline, this way, we can make it accessible to anyone who wants to see the source code or follow along.

### Design

This is a quick overview of the design process, how LifeFlow's (a made-up company) website is designed, the typography decisions, colours & other elements of the design. The design is covered at [here](#design-1)

### Responsive navigation

We go over how to make the top bar of the website:

1. We'll see how to import the logo of the website.
2. How to make the navigation.
3. How to make the top bar responsive
4. How to make the mobile navigation
5. The javascript required to make the mobile navigation open & closeable.

## Design

**NB: This section is not necessary if you are just into the development protion**

The [designs](./design/) were made using [Figma Design](https://www.figma.com/file/OPFJjIl5HeKMCrzPVcTd6g/Untitled?type=design&node-id=0%3A1&t=dCN9IlLBl0GD6qK3-1).

### Design Approach

I didn't take the traditional approach when designing the website. Usually, I would

1. make a wireframes
2. make a design system/[style guide](./style-guide.md)
3. identify common components & design components
4. Design the UI

But this time, I just jumped into the design. This project was just to focus on the development cycle. I just jumped into Figma and started designing. As time went by, I started making the style guide on the fly.

### Figma Tips

#### Auto Layout

If you look at the pages that were designed, you will notice that it's not 1 frame, but instead an auto layout. This just makes it easier if you want to rearrange different sections of a design. It works well with a large design.

#### Components

If you go to the Thumbnails page on the Figma design project, you'll notice that there's a thumbnail component. Using components makes it easier to keep different thumbnails consistent with 1 design, but flexible enough to allow you to make changes.
