# task-mate
This is an application called task-mate. Basically this is application is in React + GraphQL with Next.js


Initialized a git repository. Click here to clone repository - [task-mate](https://github.com/saurabhshcs/task-mate.git)

Success! 
Inside that directory, you can run several commands:

- Starts the development server.
  `npm run dev`
- Builds the app for production.
  `npm run build`
- Runs the built app in production mode.   
  `npm start`
- We suggest that you begin by typing:
  'cd task-mate' and then `npm run dev`
  
> Configuration needed to install Next.js and TypeScript for the project.
  - Create any project folder where you need to run following commands: 
    `npx create-next-app --use-npm` (Why I use `--use-npm` because I have `yarn` installed on my system i.e. another build dependencies tool)
  - Above command will show a message as ` What is your project named? … my-app` here you need to give your application name for us this is `task-mate`.
  - Now, we need to install `TypeScript` so need to execute following command according to your node version. I'm using node `v14.17.6`
    `npm i -D typescript @types/react @types/node@14` and then create a file `tsconfig.json` in root directory i.e. inside `task-mate`
   ```yaml
       {
      "compilerOptions": {
        "target": "es5",
        "lib": [
          "dom",
          "dom.iterable",
          "esnext"
        ],
        "allowJs": true,
        "skipLibCheck": true,
        "strict": true,
        "forceConsistentCasingInFileNames": true,
        "noEmit": true,
        "esModuleInterop": true,
        "module": "esnext",
        "moduleResolution": "node",
        "resolveJsonModule": true,
        "isolatedModules": true,
        "jsx": "preserve"
      },
      "include": [
        "next-env.d.ts",
        "**/*.ts",
        "**/*.tsx"
      ],
      "exclude": [
        "node_modules"
      ]
    }```
  - [TypeScript](https://www.typescriptlang.org/tsconfig)  
  
  
