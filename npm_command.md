## eslintの導入用
```bash
npm i --save-dev prettier eslint typescript-eslint @typescript-eslint/eslint-plugin @typescript-eslint/parser eslint-config-prettier eslint-plugin-prettier eslint-plugin-react eslint-plugin-react-hooks eslint-plugin-import
```

## Storybookの設定
```bash
# ルートディレクトリで生成
npx sb init

# プラグイン等のライブラリの導入
npm i --save-dev @storybook/addon-postcss tsconfig-paths-webpack-plugin @babel/plugin-proposal-class-properties @babel/plugin-proposal-private-methods @babel/plugin-proposal-private-property-in-object tsconfig-paths-webpack-plugin @mdx-js/react

npm install -g @storybook/cli
npm uninstall @storybook/react webpack
npm install @storybook/react webpack
npm install typescript@4.3
npm install react-docgen-typescript
```

# Storybookがnode18.xで動かないのでnvmを導入
 https://github.com/coreybutler/nvm-windows/releases
 setup.exeをインストール

# nvmでバージョンを変更
```
nvm install 16.13.0
nvm use 16.13.0
```

# react-hook-formを導入
```
npm i react-hook-form
```

# SWRの導入
```
npm i swr
```

# React Content Loaderの導入
```
npm i react-content-loader
npm i --save-dev @types/react-content-loader
```

# Material Iconsの導入
```
npm i @mui/material @mui/icons-material @emotion/react @emotion/styled
```