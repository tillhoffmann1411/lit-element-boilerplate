# Lit-Element Boilerplate
This is a boilerplate to quickly start frontend projects. This repo ist based on this [Guide](https://upbeat-cowbell-ee1.notion.site/Setup-typescript-Project-320ae0a82fdb4d4298e9f549bc8f23f0).
It contains:

- [x] [TypeScript](https://www.typescriptlang.org/)
- [x] [lit-Element](https://lit-element.polymer-project.org/guide)
- [x] [Redux](https://redux.js.org/)
- [x] [ESLint](https://eslint.org/)
- [x] [Webpack](https://webpack.js.org/)
- [x] .env support
- [ ] Testing
- [ ] [Firebase](https://firebase.google.com/)


## 🚀 Setup
1. Clone this repo
2. Run `npm install`
3. Add a .env file which looks like the .env.example file
4. Start development with `npm start`
5. Get files for production with `npm run build`. Your files are now in the /public folder.

## 🔨 Features
### Accessing environment variables
You can access variables which are defined in the .env file with `process.env.[variable-name]`