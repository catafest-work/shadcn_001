## ... working in progress , see the next image , no source code with these update:

![]()

This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started - default start project for nextjs.

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.

## First steps :

- create the project and first run , is a default nextjs default page:
  ```
  shadcn_001>cd ..

  c:\>npx shadcn@latest init
  √ The path c:\ does not contain a package.json file. Would you like to start a new Next.js project? ... yes
  √ What is your project named? ... shadcn_001
  √ Creating a new Next.js project.
  √ Which style would you like to use? » Default
  √ Which color would you like to use as the base color? » Neutral
  √ Would you like to use CSS variables for theming? ... no / yes
  √ Writing components.json.
  √ Checking registry.
  √ Updating tailwind.config.ts
  √ Updating app\globals.css
  √ Installing dependencies.
  √ Created 1 file:
    - lib\utils.ts
  
  Success! Project initialization completed.
  You may now add components.
  
  
  c:\>cd shadcn_001
  
  c:\shadcn_001>npm run dev
  
  > shadcn_001@0.1.0 dev
  > next dev
  
   ⚠ Port 3000 is in use, trying 3001 instead.
    ▲ Next.js 14.2.16
    - Local:        http://localhost:3001
  
   ✓ Starting...
   ✓ Ready in 2.1s
   ○ Compiling / ...
   ✓ Compiled / in 6.1s (546 modules)
   GET / 200 in 6656ms
   ✓ Compiled in 427ms (254 modules)
  <w> [webpack.cache.PackFileCacheStrategy/webpack.FileSystemInfo] Resolving '../../../typescript/lib/typescript' in c:\shadcn_001\node_modules\next\dist\build for build dependencies doesn't lead to expected result 'C:\shadcn_001\node_modules\typescript\lib\typescript.js', but to 'c:\shadcn_001\node_modules\typescript\lib\typescript.js' instead. Resolving dependencies are ignored for this path.
  <w>  at resolve commonjs file ...
  ```

- fix warnings , check the lastest version amd update them:

  ```
    shadcn_001>npm outdated
    shadcn_001>npm install next@latest webpack@latest
  ```
- run again and ... works:
  
  ```
  shadcn_001>npm run dev

  > shadcn_001@0.1.0 dev
  > next dev
  
   ⚠ Port 3000 is in use, trying 3001 instead.
     ▲ Next.js 15.1.2
     - Local:        http://localhost:3001
     - Network:      http://10.13.13.2:3001
  
   ✓ Starting...
  
     We detected TypeScript in your project and reconfigured your tsconfig.json file for you.
     The following suggested values were added to your tsconfig.json. These values can be changed to fit your project's needs:
  
          - target was set to ES2017 (For top-level `await`. Note: Next.js only polyfills for the esmodules target.)
  
   ✓ Ready in 2.1s
   ○ Compiling / ...
   ✓ Compiled / in 4.5s (662 modules)
   GET / 200 in 4994ms
   ✓ Compiled in 230ms (306 modules)
   ✓ Compiled /favicon.ico in 242ms (353 modules)
   GET /favicon.ico 200 in 339ms
  ```
