# react

## Table of Questions

| Sr. No. | Questions |
| --- | --------- |
| 1. | What is React  | 
| 2. | Installation  | 



## What is React
    React is a declarative, efficient, and flexible JavaScript library for building user interfaces. It lets you compose complex UIs from small and isolated pieces of code called “components”.

    class HelloWorld extends React.Component{
        render(){
            return(
                <h1>Hello World</h1>
            )
        }
    }


## Installation
by using tool chain "create-react-app my-app"

`There is lot of tool chain `

    #### Next.js
    Next.js is a popular and lightweight framework for static and server‑rendered applications built with React. It includes styling and routing solutions out of the box, and assumes that you’re using Node.js as the server environment.

    #### Gatsby
    Gatsby is the best way to create static websites with React. It lets you use React components, but outputs pre-rendered HTML and CSS to guarantee the fastest load time.

    Neutrino combines the power of webpack with the simplicity of presets, and includes a preset for React apps and React components.

    Nx is a toolkit for full-stack monorepo development, with built-in support for React, Next.js, Express, and more.

    Parcel is a fast, zero configuration web application bundler that works with React.

    Razzle is a server-rendering framework that doesn’t require any configuration, but offers more flexibility than Next.js.

### Creating a Toolchain from Scratch
A JavaScript build toolchain typically consists of:

    A package manager, such as Yarn or npm. It lets you take advantage of a vast ecosystem of third-party packages, and easily install or update them.

    A bundler, such as webpack or Parcel. It lets you write modular code and bundle it together into small packages to optimize load time.

    A compiler such as Babel. It lets you write modern JavaScript code that still works in older browsers.

## Installation using create-react app

    Run command : npx create-react-app app-name
    go to : cd app-name 
    run : npx start 