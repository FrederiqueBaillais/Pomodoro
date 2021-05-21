# React: pomodoro

- Type of challenge: **learning**
- Repository : **`react-pomodoro`**

* * *
> A simple, static, [pomodoro timer](https://en.wikipedia.org/wiki/Pomodoro_Technique) with [React](https://reactjs.org).

## Introduction

You will use [React](https://reactjs.org) to create a simple Pomodoro timer.  
It will be *static*, without the need for a server.

You will also discover some build tools, with [Parcel](https://parceljs.org/), and will follow some code quality rules, with [Prettier](https://prettier.io) and [ESLint](https://eslint.org).

## Statement

Following these *beautiful [wireframes](./Assets/wireframes.jpg)*, you will code a pomodoro timer.

### Minimal requirements

- Display a big timer (minutes and seconds).
- Four buttons:
  - **plus (+)** and **minus (-)**, they will allow the user to adjust the *minutes counter* - **only when it's stopped**.
  - **start**, to run the timer (it will then change to **stop**), to serve as a *toggle* button
  - **reset**, to… reset the timer to its original value
- At the end of the timer, show a modal to invite user to *take a break*. The modal will have two buttons:
  - One to close the modal
  - Another to close the modal *and* start a new timer

### Optional additions

You can add anything to the timer, sky is the limit

You can add a sound at the end of the timer, add another timer in the modal to limitate the break time, add animations… feel free to try anything!

## Technical concerns

### Tooling

#### :warning: Learning first

We have seen some solutions to create your application. Like **Create React App**, which is a toolchain containing a set environment. We advise you to **do not use** this application for your Pomodoro.

Why ? Because this complete environment will not help you to learn all the basis about React. Later, when you'll have to build a more complex application, you could be stuck and encounter unexpected issues.

So we recommend to build your app using [Parcel](https://parceljs.org).

#### Build tool : Parcel

As you will see, React makes you create and handle many different files.
Keeping track of each of them and reference them in your html file can be a real _pain in the a$!%_.

We will need a build tool, a *bundler*, to create a final file from all our components.

There's many build tools around, the most popular (and complete) is [webpack](https://webpack.js.org) which is provided by default in the Create React App toolchain.
It's a really complex tool, so we will not use it for your first project (it will be for the next time).

We will use [Parcel](https://parceljs.org), which is a build tool "without configuration", which tries to guess your needs by looking at your code. It's magic :sparkles: !

Take a bit of your time to follow the [Parcel's documentation](https://parceljs.org/getting_started.html) and maybe you'll find some informations to create your React app with this bundler :innocent: .

#### Code Quality

Even if you're working alone on this project, we need you to enforce your *code quality*.

You will use [Prettier](https://prettier.io) to format your code, and [ESLint](https://eslint.org) to ensure your code following *good practices*.

You will use the [BeCode Presets](https://github.com/becodeorg/eslint-config). When your project's package.json file is created, execute the following command: `npx @becode/eslint-config --with-hook`.

It will install Prettier & ESLint and a *git hook* to run it before your commits.

> ⚠️ **NOTE:** if there's an ESLint error in your code, your commit will not be allowed. Correct the error and retry!
 
> 🧨 **WARNING:** disable ESLint **is not** an option!

### Hosting

We want you to publish your pomodoro online. There's many solutions to host a static website online for free, like [**github-pages**](https://pages.github.com) but we will use a new solution: [Netlify](https://www.netlify.com).  
It's free, easy to setup, and can observe your changes and publish automatically.

* * *

Good luck!