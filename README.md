# HeroUI Components Failing in Nextra v4

Previously all HeroUI (formerly NextUI) components worked fine being used directly in MDX files in Nextra v3 and earlier. Now certain components, throw an error when used directly in MDX files. This is reproducible with the Table components.
Not all components fail like this, some like the Button or Card components are just fine (well their styling is not working but that's because HeroUI is still using tailwind 3, unrelated to this issue.)

### Steps to Reproduce
1. `npm i` to install depedencies
2. `npm run dev` and navigate to home page.