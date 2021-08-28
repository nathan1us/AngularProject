# Moview - an exam project built using Angular and Firebase.

Moview is a lightweight blogging platform that allows people to voice their opinions on all sorts of things.

# Tech stack

- Angular - Front-end framework
  - Used to build the entire front-end part of the application
- Firebase - NoSQL service by google
  - Used as a database service for the application

# Sitemap

## Public pages

- Home / Register page
  - Implemented validation for registrations
- Login page
  - Implemented validation

## Pages with required authorization

- Dashboard / Profile
  - Including a page to edit your profile
- Different home page displaying all posted blogs
- Blog post page
  - Each blog post has it's own page where you can read the entire contents of the post and leave a comment

## Every registered user can do the following:
- Create blog posts
- Comment on blog posts
- Customize their profile
  - Bio
  - Interests
  - Hobbies
  - Picture
  - Name & Email

# Getting started

## Prerequisites

- Angular
- Node.JS
- NPM

*Internet connection is required to use the application properly.*

*The application in it's current state is meant to be ran and viewed in a development environment. <br>
The provided instructions are NOT meant for deploying a production version of the application.*

## Installing

1. Clone the repository
2. Navigate to the cloned project via CLI of your choice
3. Run `npm install` to install all required NPM packages
4. Configure your Firebase "Firestore" database inside `src/app/app.module.ts`

## Starting the application

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

# Authors

- Georgi Slaveykov <github.com/nathan1us>

# License

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/nathan1us/Moview/blob/main/LICENSE) file for details