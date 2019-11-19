<p align="center">
  <a href="https://www.nextjs.org/">
    <img src="src/static/nextjs-black-logo.svg" width="80" height="28">
  </a>
</p>
<h1 align="center">
  Brevifolia
</h1>

## About

Brevifolia is a minimalist blog starter to get you going with [Next.js](https://nextjs.org/). 

This blog is statically generated by Next.js, a rendered combination of react components and markdown / json files. The styles were coded & designed by yours truly, using [styled-jsx](https://github.com/zeit/styled-jsx) (which is inherently supported by [Next.js](https://nextjs.org/docs#built-in-css-support)). The font used is [Work Sans](https://fonts.google.com/specimen/Work+Sans). 

##  Quick Setup

#### *Set-up Locally*
In your terminal, navigate to where you would like this blog to live, then run 
```bash
#clone the repo
git clone git@github.com:kendallstrautman/brevifolia-nextjs.git

#navigate to the directory
cd brevifolia-nextjs

#install dependencies & run dev server with yarn 
yarn install
yarn develop

```
This will start a dev server, navigate to localhost:3000 to check it out.

## Project Structure 

- Site-level configuration is stored in `data/config.json`. 
- Edit styles within each component or page file within the `<style jsx>` tags. 
- Global styles live in the `Meta` component. 
- `src/posts/`contains all your markdown blog posts.
- `src/static/` is where you images live and will get uploaded.
- `src/pages` is where you page components live. 
- The blog pages are dynamically generated with a `slug` parameter. See the template in `src/pages/blog/[slug].js`. 
- The pages & template are comprised of components from `src/components`.
- The routes are generated in `next.config.js` with `exportPathMap`

## Deploy Options

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/kendallstrautman/brevifolia-nextjs)
