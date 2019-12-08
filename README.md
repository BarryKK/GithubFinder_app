# GithubFiner

>这是一个Github用户搜索器小项目, 使用了context API,useContext, useReducer hooks管理状态 <br>
>此项目用于学习基础React语法, JSX, Context和Hook的使用

## 项目结构

### 文件结构：
```
.
|-- .env.local
|-- netlify.toml
|-- package-lock.json
|-- package.json
|-- public
|   |-- favicon.ico
|   |-- index.html
|   |-- logo192.png
|   |-- logo512.png
|   |-- manifest.json
|   `-- robots.txt
`-- src                                //前端项目组件
    |-- App.css                        //样式
    |-- App.js                         //路由文件
    |-- components                     //组件
    |   |-- layout                     //布局组件
    |   |   |-- Alert.js
    |   |   |-- Navbar.js
    |   |   |-- Spinner.js
    |   |   `-- spinner.gif
    |   |-- pages                       //路由URL
    |   |   |-- About.js
    |   |   |-- Home.js
    |   |   `-- NotFound.js
    |   |-- repos                       //库展示
    |   |   |-- RepoItem.js
    |   |   `-- Repos.js
    |   `-- users                       //用户搜索
    |       |-- Search.js
    |       |-- User.js
    |       |-- UserItem.js
    |       `-- Users.js
    |-- context                          //context API
    |   |-- alert
    |   |   |-- AlertSate.js
    |   |   |-- alertContext.js
    |   |   `-- alertReducer.js
    |   |-- github
    |   |   |-- GithubState.js
    |   |   |-- gitHubContext.js
    |   |   `-- githubReducer.js
    |   `-- types.js
    `-- index.js                         //入口文件
```
