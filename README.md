# ⚡️SvelteKit-Portfolio⚡️

## A personal portfolio website made using `@sveltejs/kit`.

## Features

- Modern and Minimal UI Design
- Home, Projects, About and blog sections
- Blog made using `DEV.TO` API. (Medium WIP)
- Fully Responsive
- Performances and SEO optimizations

## Guide

- In order to add a new route (page) you need to add it in `src\lib\NavRoutes.js` and create a new file in the `routes` folder with the same name as the route `eg: about`.

In `src\lib\NavRoutes.js` you need to add in the `routes` an object with the following info for every route you want to add.

    {
    	href: '/globe', // route path
    	label: 'Globe', // name showed in the navbar
    	customColor: '#89a6fb' // OPTIONAL: a color that will be set when you switch route (for that specific route)
    }

# Dependencies

- svelte-icons
- @sveltejs/adapter-netlify

## Authors ❤️

- Rajeev - https://github.com/rajeevkrao
