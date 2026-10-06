# Choosing a language/framework

The language and frameworks you should use in your project depend on how it will work. This page will help you decide what to use for your project.

## Websites

### Languages

Where possible, use [TypeScript](https://www.typescriptlang.org/) over JavaScript.

### Frameworks

For websites that can run entirely in the browser, but need some complex features, use [React](https://react.dev/) or [Next.js](https://nextjs.org/) with [static site generation](https://nextjs.org/docs/pages/guides/static-exports). (Example: [tangledwires.co.uk](https://github.com/TangledWiresOfficial/tangledwires.co.uk))

For a web app that needs a database or other server-side features, use [Ruby on Rails](https://rubyonrails.org/). If your Rails app has a frontend, use React for that too. (Example: [stationary-sync](https://github.com/TangledWiresOfficial/stationary-sync))

Use [Patternfly](https://www.patternfly.org/) for building your frontend. (Example: [Stationary](https://github.com/TangledWiresOfficial/Stationary))

If you need a package manager, prefer [`yarn`](https://yarnpkg.com/) over `npm`.

## Apps

### Frameworks

Use [Tauri](https://v2.tauri.app/) with a React frontend. (Example: [Stationary](https://github.com/TangledWiresOfficial/Stationary))
