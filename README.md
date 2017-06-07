# 104f2e-monitorAdParm

jsDoc
====

##document this安裝與用法

### 1. 安裝套件： 
Document This網站：
https://marketplace.visualstudio.com/items?itemName=joelday.docthis

### 2. 在終端機輸入：
    npm init
接著輸入
    npm i jsdoc --save-dev

### 3. 修改package.json
 	"scripts": {
   	 	"js-doc": "./node_modules/.bin/jsdoc -d /src/js"
 	}

### 4. 在終端機中輸入：
	npm run js-doc
