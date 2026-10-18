# 第三方组件

本应用自有部分未采用开源许可证。下列组件保留其各自版权与许可证；本应用的自有许可声明不会覆盖它们。

| 组件 | 用途 | 上游与许可证 |
| --- | --- | --- |
| Electron 44.8.0 | Windows运行时 | https://github.com/electron/electron · MIT及Chromium第三方许可 |
| electron-updater 6.8.9 | 安装版更新 | https://github.com/electron-userland/electron-builder · MIT |
| SheetJS CE 0.20.3 | Excel课表解析 | https://sheetjs.com/ · Apache-2.0 |
| Mammoth 1.13.0 | Word课表解析 | https://github.com/mwilliamson/mammoth.js · BSD-2-Clause |
| PDF.js / pdfjs-dist 6.4.299 | PDF文字与页面渲染 | https://github.com/mozilla/pdf.js · Apache-2.0 |
| Tesseract.js 7.0.0及其core | 本地OCR | https://github.com/naptha/tesseract.js · Apache-2.0 |
| Tesseract中英文语言模型 | 本地OCR语言数据 | https://github.com/tesseract-ocr/tessdata · Apache-2.0 |

完整许可文本位于随包的`third-party-licenses/`，以及运行时随附的`LICENSE`和`LICENSES.chromium.html`。浏览器依赖自带的版权注释／LICENSE文件也在应用资源中保留。

语言模型来自项目现有离线模型，文件校验值保存在构建工作区的模型清单。所有识别资源随发行包提供，运行时不从CDN下载。
