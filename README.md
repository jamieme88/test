# 104f2e-monitorAdParm

## jsDoc

### Install

#### step 1：Install document this
可參考此網頁來安裝Document This：
https://marketplace.visualstudio.com/items?itemName=joelday.docthis

可參考此網頁來安裝VS Code Extension：
https://code.visualstudio.com/docs/editor/extension-gallery

#### step 2：cmd輸入：
    npm init
    npm i jsdoc --save-dev

#### step 3：修改package.json
 	"scripts": {
   	 	"js-doc": "./node_modules/.bin/jsdoc -d /src/js"
 	}

#### step 4：cmd輸入：
	npm run js-doc
