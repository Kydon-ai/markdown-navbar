
## [1.4.5](https://github.com/parksben/markdown-navbar/compare/v1.4.4...v1.4.5) (2026-04-01)

## [1.4.4](https://github.com/parksben/markdown-navbar/compare/8e4e2d92a2afb898067f616984e96efa79bd767d...v1.4.4) (2026-04-01)


### Bug Fixes

* 非标题行内出现#号导致的导航解析不正确 ([074cb10](https://github.com/parksben/markdown-navbar/commit/074cb1019e1d5008730e22bec2e02fea73460af9))
* 文档内容无标题时的页面滚动报错 ([a3353a6](https://github.com/parksben/markdown-navbar/commit/a3353a673ed7a26c0911087a8bec03ba44d28b39))
* anchor positioning fails when the page is initialized If there is a symbol or blank space in the title ([077a723](https://github.com/parksben/markdown-navbar/commit/077a7235eaaff0aa33fd76958fe852992656be11))
* Could not find dependency: core-js relative to dist/index.js ([c1659ed](https://github.com/parksben/markdown-navbar/commit/c1659edf8177d719576e39730eb1c3de9a93bcf8))
* decode the value of `location.hash` as event callback params ([9a284a0](https://github.com/parksben/markdown-navbar/commit/9a284a0b37ed1751422084071305dd0bf48b7607))
* fix some bugs for navigation and update README.md ([8e4e2d9](https://github.com/parksben/markdown-navbar/commit/8e4e2d92a2afb898067f616984e96efa79bd767d))
* serial number parse error when some content exists before level 1 title ([35a234f](https://github.com/parksben/markdown-navbar/commit/35a234f031a3eed1a1ee54b1a1457ec893cabd38))
* some data-id of heading elements not registered while two or multi same text of headings exist in one documentation ([cedf928](https://github.com/parksben/markdown-navbar/commit/cedf928d3280beabd521a16007138da93e79c1ee))
* the dataset.id of headings not be updated correctly after markdown source changed ([a175e73](https://github.com/parksben/markdown-navbar/commit/a175e73a0598f9139376bdd6df08a36934fbe290))
* the exception in Safari due to too many calls to the history.replacestate method ([2834372](https://github.com/parksben/markdown-navbar/commit/28343727cae29dcb48da6af38707b409410fe5dc))
* use location search for hash changing ([413e654](https://github.com/parksben/markdown-navbar/commit/413e6541584fbda77b2ca8875d92f681cdb84486))
* use new method to update the hash value of browser address without page scrolling ([1aae9fb](https://github.com/parksben/markdown-navbar/commit/1aae9fb8af416d8787613d7540aaf7a788368072))


### Features

* add a demo online at codesandbox.io && improve README ([7a8e419](https://github.com/parksben/markdown-navbar/commit/7a8e4198012a8f14d96a32bc48e646d6e8bbd3df))
* implement some event hooks ([1ab6712](https://github.com/parksben/markdown-navbar/commit/1ab671219adceccb274bae7f84ac679538318c45))
* scroll page to target heading when event `hashchange` has been triggered ([e76941d](https://github.com/parksben/markdown-navbar/commit/e76941de0c5a7d96a1317c5909610f20e2bba5bf))
* the function of automatically updating the hash value of browser address bar when the page scrolling ([bac0746](https://github.com/parksben/markdown-navbar/commit/bac0746966a2598007bb53513e6c7344b3716bd5))
