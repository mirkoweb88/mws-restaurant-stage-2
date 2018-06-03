# Mobile Web Specialist Certification Course
---
#### _Three Stage Course Material Project - Restaurant Reviews_

In the **Restaurant Reviews** projects, I converted a static webpage to a mobile-ready web application.

## Project Overview: Stage 2

In **Stage One**, you will take a static design that lacks accessibility and convert the design to be responsive on different sized displays and accessible for screen reader use. You will also add a service worker to begin the process of creating a seamless offline experience for your users.

---

### Install

1. Clone this repo `git clone https://github.com/mirkoweb88/mws-restaurant-stage-2/`
2. Go to the folder
3. Run `npm install`

_[ In my computer i have installed [ImageMagick](http://www.imagemagick.org/script/download.php "Go to Download page"), so if you are experiencing issues in `images-tasks` probably you'll need to install it. ]_

### Run && Watch

1. Development, with livereload: `npm run dev` or `npm run serve`
2. Staging, with livereload: `npm run staging` or `npm run serve:staging`
3. Production, with livereload: `npm run production` or `npm run serve:production`
4. Production, no livereload: `npm run production` or `npm run view:production`

_It watch files under the `dist/` folder, on port `4000`, to changing it check `var options` in the `gulpfile.js`*_

### Build

1. Production in the `dist/` folder: `npm run build`
2. Staging in the `dist/` folder: `npm run build:staging`
3. [Github Pages](https://pages.github.com/ "Github Pages") in the `docs/` folder: `npm run build:github:pages`

---


## Local Development API Server

### Usage

#### Get Restaurants

`curl "http://localhost:1337/restaurants/"`

#### Get Restaurants by id

`curl "http://localhost:1337/restaurants/{3}"`

### Architecture

Local server:

- Node.js
- Sails.js

--

#### Start only server

`npm run start`: development, Port: 1337

##### Start the server and the building process together

`npm run sailsjs`: production, Port: 1337, you manually have to go to url `http://localhost:1377`
_Served from `.tmp/public` folder_

