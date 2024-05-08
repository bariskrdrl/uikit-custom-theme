[![uikit banner](https://cloud.githubusercontent.com/assets/321047/21769911/474d7d9e-d681-11e6-9fe0-d95f8ccfd3a9.jpg)](http://getuikit.com/)

# UIkit Custom Theme

UIkit is a lightweight and modular front-end framework for developing fast and powerful web interfaces.

How to create a custom theme with UIkit is https://getuikit.com/docs/lesshere.

I gathered all less variables and hooks in UIkit.

---

## Getting started

You have the following options to get UIkit:

- Install with [pnpm](https://pnpm.io/) to get all source files as they are available on GitHub: ```pnpm add uikit```
- Uikit-custom-theme is cloned into the UIkit. https://github.com/bariskrdrl/uikit-custom-theme.git
---

## Examples Filex

    custom/

        <!-- entry file for Less compiler -->
        my-theme.less

        <!-- folder with single Less files -->
        my-theme/

            <!-- imports all components in this folder -->
            _import.less

            <!-- one file per customized component -->
            accordion.less
            alert.less
            ...

        <!-- custom icons -->
        icons/
            ...
    

---

## Compile

To compile UIkit and your custom theme into CSS, run the pnpm task compile
Run once to install all dependencies ```pnpm install```
Compile all source files including your theme ```pnpm compile```
Watch files and compile automatically everytime a file changes ```pnpm watch```

---

## Browser Support

![Chrome](https://raw.github.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png) | ![Firefox](https://raw.github.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png) | ![Edge](https://raw.github.com/alrra/browser-logos/master/src/edge/edge_48x48.png) | ![IE](https://raw.github.com/alrra/browser-logos/master/src/archive/internet-explorer_9-11/internet-explorer_9-11_48x48.png) | ![Safari](https://raw.github.com/alrra/browser-logos/master/src/safari/safari_48x48.png) | ![Opera](https://raw.github.com/alrra/browser-logos/master/src/opera/opera_48x48.png)
--- | --- | --- | --- | --- | --- |
Latest ✔ | Latest ✔ | Latest ✔ | 11+ ✔ | 9.1+ ✔ | Latest ✔ |

Tested With<br>[![BrowserStack](https://user-images.githubusercontent.com/355427/27389060-9f716c82-569d-11e7-923c-bd5fe7f1c55a.png)](https://www.browserstack.com)

## Copyright and License

Copyright [YOOtheme](https://yootheme.com) GmbH under the [MIT license](LICENSE.md).
