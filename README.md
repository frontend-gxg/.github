# frontend-gxg

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
| desktop          | golang                  | -      | golang      | os             | -        | ?            |
| desktop          | cpp / rust / golang     | -      | js / ts     | os             | -        | react-native |
| desktop          | js / ts                 | cpp    | js / ts     | browser on os  | electron | *            |
| desktop          | js / ts                 | rust   | js / ts     | browser on os  | tauri    | *            |
| desktop          | js / ts                 | golang | js / ts     | browser on os  | *        | *            |
| mobile (android) | java                    | -      | java        | mobile os      | -        | ？           |
| mobile (ios)     | object-c                | -      | object-c    | mobile os      | -        | ？           |
| mobile (ios)     | swift                   | -      | swift       | mobile os      | -        | ？           |
| desktop          | cpp                     | -      | cpp         | mobile os      | -        | ?            |
| desktop          | rust                    | -      | rust        | mobile os      | -        | ?            |
| desktop          | golang                  | -      | golang      | mobile os      | -        | ?            |
| mobile           | java / object-c / swift | -      | js / ts     | mobile os      | -        | react-native |
| mobile           | js / ts                 | *      | js / ts     | browser on os  | *        |              |
| wechat           | js / ts                 | -      | js / ts     | browser on app | wechat   | *            |
