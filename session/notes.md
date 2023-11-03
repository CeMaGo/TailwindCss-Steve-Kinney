# Session notes

-[Workshop]('https://tailwind-workshop.vercel.app/introduction')

-[Tailwind]('https://tailwindcss.com/')


utility first CSS, templating lang, 


> Link collection
> - [MUI]('https://mui.com/')
> - [Steve Kinney Git]('https://github.com/stevekinney/tailwind-workshop')
> - [Tailwind]('https://tailwindcss.com/')
> - [Workshop]('https://tailwind-workshop.vercel.app/introduction')
> - [UI.Colors]('https://uicolors.app/create')



possible to extend figma pallet to config theme


`conig`

```
/** @type {import('tailwindcss').Config} */
export default {
  theme: {
    extend: {
      colors: {
    
    },
  },
  plugins: [],
}
```

`CSS`
```
@tailwind base;
@tailwind components;
@tailwind utilities;

body {
  @apply m-8;
}

@layer base {
  button {
    @apply bg-primary-light rounded px-4 py-2 text-white shadow-sm;
  }
}
```
[2nd challenge]('https://tailwind-workshop.vercel.app/space')
