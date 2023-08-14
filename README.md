# ESLint & Prettier Configuration Files

ESLint & Prettier configurations for quick starting different type of JavaScript projects.

## Table of contents

1. [General Info](#general-info)
2. [Instructions](#instructions)
3. [Base](#base)
4. [React](#react)
5. [Attributions](#attributions)
6. [Notes](#notes)

## General Info

> **Note**: All these configurations are based on the [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript/tree/master).

All the configuration files include Prettier in their `"extends"` key, this will disable all ESLint formatting rules that interfere with Prettier and leave the formatting responsibility **only** to Prettier.

We make use of the [`.prettierrc.json`](.prettierrc.json) file to enforce the default configuration of Prettier (among any other rules defined inside it), preventing any possible non-desired configuration variations inside the Visual Studio Code extension among developers.

It is highly recommended to install the official [Prettier extension for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) to have real-time Prettier formatting.

For more information about **Prettier**, follow [this link](https://prettier.io/) to the official site.

For more information about configuring **ESLint**, follow [this link](https://eslint.org/) to the official site.

⬆️ [Back to top](#table-of-contents)

## Instructions

1. Copy and paste the corresponding `.eslintrc.json` file inside your project's root directory.
2. Copy and paste the [`.prettierrc.json`](./.prettierrc.json) file in your project's root directory.
3. Install the required dependencies specified for your type of project on each section.

> **Note**: If you are not using ECMAScript modules (you don't have [`"type": "module"`](https://nodejs.org/api/packages.html#type) in your `package.json`), you'll need to remove [`"sourceType": "module"`](https://eslint.org/docs/latest/use/configure/language-options#specifying-parser-options) from `.eslintrc.json`

⬆️ [Back to top](#table-of-contents)

## Base

You can use this config if you just want to use JavaScript without any specific framework.

- ![JavaScript Logo](./img/javascript.png "JavaScript Logo") [.eslintrc.json](./base/.eslintrc.json "download")

- ![Prettier Logo](./img/prettier.png "Prettier Logo") [.prettierrc.json](./.prettierrc.json "download")

### Dependencies for Base

Make sure to install all the required dependencies:

```zsh
npm install eslint eslint-config-airbnb-base eslint-config-prettier -D
```

```zsh
npm install prettier -D -E
```

⬆️ [Back to top](#table-of-contents)

## React

You can use this config if you want to use React.

- ![React Logo](./img/react.png "React Logo") [.eslintrc.json](./react/.eslintrc.json "download")
- ![Prettier Logo](./img/prettier.png "Prettier Logo") [.prettierrc.json](./.prettierrc.json "download")

### Dependencies for React

Make sure to install all the required dependencies:

```zsh
npm install eslint eslint-config-airbnb eslint-config-prettier -D
```

```zsh
npm install prettier -D -E
```

⬆️ [Back to top](#table-of-contents)

## Attributions

- [JavaScript icons created by Freepik - Flaticon](https://www.flaticon.com/free-icons/javascript "javascript icons").

- [React icons created by Samat Odedara - Iconfinder](https://www.iconfinder.com/icons/1174949/js_react_js_logo_react_react_native_icon "react icons").

- [Prettier icons created by VSCode Icons - Icons For Free](https://icons-for-free.com/vscode+icons+type+prettier-1324451458122067730/ "prettier icons").

⬆️ [Back to top](#table-of-contents)

## Notes

- More project-specific configurations will be added in the future.

⬆️ [Back to top](#table-of-contents)
