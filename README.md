[html2canvas](https://github.com/niklasvh/html2canvas)
===========
- 1.基于 html2canvas V1.4.1 修改
- 2.添加对css属性的支持：`mix-blend-mode & -webkit-mask-box-image`

===========
事实上使用原生canvas 也无法达到我希望的效果，例子在example中
### Building ###

You can download ready builds [here](https://github.com/niklasvh/html2canvas/releases).

Clone git repository:

    $ git clone git://github.com/niklasvh/html2canvas.git

Install dependencies:

    $ npm install

Build browser bundle

    $ npm run build

### Examples ###

For more information and examples, please visit the [homepage](https://html2canvas.hertzen.com) or try the [test console](https://html2canvas.hertzen.com/tests/).

### Contributing ###

If you wish to contribute to the project, please send the pull requests to the develop branch. Before submitting any changes, try and test that the changes work with all the support browsers. If some CSS property isn't supported or is incomplete, please create appropriate tests for it as well before submitting any code changes.
