# hexo local admin

This is a hexo site admin tool(works only on your local machine.). You can use this tool to manage your posts, pages, drafts and trash, even can launch hexo server and deploy your site! Try it out!

![1](https://raw.githubusercontent.com/geekwen/hexo-local-admin/master/screenshot/1.jpg)

![2](https://raw.githubusercontent.com/geekwen/hexo-local-admin/master/screenshot/2.jpg)

**Requirement**

node version 4.x or later

**Support**

OS: windows and unix-like

Browser: highly recommend **latest** chrome and firefox. also support any other **latest** modern browsers.

## Before start 

0. **Please backup your `_source` directory, just for safety**

1. Front matter format **must** follow: https://github.com/dworthen/js-yaml-front-matter (otherwise, this APP may not work)

2. npm scripts:
    1. `npm run start`: start the APP
    2. `npm run build`: build js file

## HOW-TO-USE

1. install 
    ``` shell
    npm install -g hexo-local-admin
    ```

2. use command 

    ```
    hexo-admin -h
    ```
    will get:
    ```
    Usage: hexo-admin [options] [command]
    Commands:
      start   Start hexo local admin server
    Options:
        -h, --help                     output usage information
        -V, --version                  output the version number
        -r, --root-path [root_path]    view/set hexo root path
        -t, --theme-name [theme_name]  view/set hexo theme name

    ```

3. enjoy!

## Notice

1. The deploy button means run `hexo deploy -g` command. So before you use this feature, please make sure you can manually use this command to deploy your site. More info about hexo deploy: [hexo doc: deployment](https://hexo.io/docs/deployment.html)
 
2. (\*nix os) if you can't set root path or theme name, try add `sudo` before command. 

       
## License

MIT