
# Audio Explorer 


Audio Explorer 是一款数据可视化工具，来帮助研究人员分析特定位置的录音
           并可以随着时间的推移并验证其真实性。
挑战：Kasios Furniture（一家具公司）被指控在其工厂中使用违禁物质，并将废料倾倒在附近野生动植物保护区的东北地区。
           鸟类学家说，这直接导致了当地玫瑰凤冠蓝鸟的数量减少。 Kasios 驳斥了这一说法，并提供了 15 个记录在保护区内的音频文件，
           他们坚称这些文件证明了玫瑰冠蓝鸟鹭种群状况良好。 提供大量带有准确识别信息的记录鸟类叫声，
           我们的目标是检查 Kasios 声明的有效性，并表征保护区内所有物种随着时间的推移的模式。


### Prerequisites 依赖项

Install [Node.js](https://nodejs.org/en/) and [Yarn](https://yarnpkg.com) (if haven't already)

### Installing 安装

Clone the repository. Open terminal/commmand prompt and `cd` to root directory of the repo:
```
cd [repo directory]
```

Type `yarn install` to install dependencies:
```
yarn install
```
## Deployment 运行

To view a development build of Audio Explorer, run: 
```
yarn serve
```

Alternatively, to create a production build:
```
yarn build
```

The web app can then be viewed at http://localhost:8080/
## Built With

* [Vue.js](https://vuejs.org/) - Front-end framework
* [Vue CLI](https://cli.vuejs.org/) - Standard tooling for Vue.js development
* [D3.js](https://d3js.org/) - Data processing library
* [Vue2Leafet](https://rometools.github.io/rome/) - Vue wrapper for [Leaflet](https://leafletjs.com/) interactive map library
* [Leatlet.heat](https://github.com/Leaflet/Leaflet.heat) - Heatmap plugin for Leaflet maps
* [wavesurfer.js](https://wavesurfer-js.org/) - Audio visualization and playback plugin
* [vue-slider-component](https://nightcatsama.github.io/vue-slider-component/example/) - Vue slider components
* [vue-sweetalert2](https://github.com/avil13/vue-sweetalert2) - Vue wrapper for [SweetAlert2](https://sweetalert2.github.io/)

## Authors
孔启超 杨镐 二次开发

**Colin Scruggs** - [Github](https://github.com/colinscruggs)

**Cameron Henkel** - [Github](https://github.com/cameron-henkel)

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE.md](LICENSE.md) file for details.
