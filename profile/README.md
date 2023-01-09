## overview

| platform         | low                     | mid    | high        | runtime        | wrapper  | framework    |
|------------------|-------------------------|--------|-------------|----------------|----------|--------------|
| web              | js / ts                 | -      | js / ts     | browser        | -        | angular      |
| web              | js / ts                 | -      | js / ts     | browser        | -        | react        |
| web              | js / ts                 | -      | js / ts     | browser        | -        | vue          |
| web              | wasm                    | -      | cpp         | browser        | -        | [asm-dom](https://github.com/mbasso/asm-dom) |
| web              | wasm                    | -      | rust        | browser        | -        | [yew](https://github.com/yewstack/yew) / [dioxus](https://github.com/DioxusLabs/dioxus) |
| web              | wasm                    | -      | golang      | browser        | -        | [golang wasm wiki](https://github.com/golang/go/wiki/WebAssembly) |
| desktop          | cpp                     | -      | cpp         | os             | -        | ?            |
| desktop          | rust                    | -      | rust        | os             | -        | ?            |
| desktop          | golang                  | -      | golang      | os             | -        | [fyne](https://github.com/fyne-io/fyne) |
| desktop          | cpp / rust / golang     | -      | js / ts     | os             | -        | react-native |
| desktop          | js / ts                 | cpp    | js / ts     | browser on os  | electron | *            |
| desktop          | js / ts                 | rust   | js / ts     | browser on os  | tauri    | *            |
| desktop          | js / ts                 | golang | js / ts     | browser on os  | *        | *            |
| mobile (android) | java                    | -      | java        | mobile os      | -        | ?           |
| mobile (ios)     | object-c                | -      | object-c    | mobile os      | -        | ?           |
| mobile (ios)     | swift                   | -      | swift       | mobile os      | -        | ?           |
| mobile           | java / object-c / swift | -      | cpp         | mobile os      | -        | ?            |
| mobile           | java / object-c / swift | -      | rust        | mobile os      | -        | ?            |
| mobile           | java / object-c / swift | -      | golang      | mobile os      | -        | [Mobile](https://github.com/golang/go/wiki/Mobile) / [mobile](https://github.com/golang/mobile) / [fyne](https://github.com/fyne-io/fyne) |
| mobile           | java / object-c / swift | -      | js / ts     | mobile os      | -        | react-native |
| mobile           | js / ts                 | *      | js / ts     | browser on os  | *        | [Top 10 Vue Mobile UI Frameworks for Developing Mobile Apps](https://www.cmarix.com/blog/top-10-vue-mobile-ui-frameworks-for-developing-mobile-apps/) / [12 Frameworks for Hybrid Mobile Apps](https://medium.com/@Jscrambler/12-frameworks-for-hybrid-mobile-apps-9cee8a91105e) / [Comparing Vue.js mobile app development frameworks](https://blog.logrocket.com/comparing-vue-js-mobile-app-development-frameworks/) / [15 Best Vue Mobile UI Frameworks for Developing Apps](https://superdevresources.com/vuejs-mobile-frameworks/) |
| wechat           | js / ts                 | -      | js / ts     | browser on app | wechat   | *            |

## framework

### mvvm

- event -> state -> view
- detect change: event -> state 
  - angular: zone.js
- render: state -> view 
  - angular: shadow dom + incremental dom
  - react / vue: virtual dom
    - https://www.zhihu.com/search?type=content&q=virtual%20dom
    - https://www.google.com/search?q=virtual+dom+%E5%AE%9E%E7%8E%B0

### 组件化 

- 父组件数据流向子组件
- 子组件数据流向父组件

### 其他

- dynamic template
- route
