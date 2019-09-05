<div align="center">
  <img src="https://gu-st.ru/st/img/logo_nobeta.0a1f5dfe6b.svg">
  <h1>
    Ant Design GosUslugi Theme
  </h1>
</div>


## Install
If use ```create-react-app```
```bash 
yarn add less less-loader @ant-design/gosuslugi-theme
```

## Usage 


```bash
yarn eject
```
```js
import gosuslugiTheme from '@ant-design/gosuslugi-theme';

// webpack.config.js: less-loader
{
  loader: 'less-loader',
  options: {
    modifyVars: gosuslugiTheme,
  },
},
```

# ant-design-gosuslugi-theme
Theme for https://gosuslugi.ru
