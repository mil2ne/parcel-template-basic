## parcel 번들러
- `npm init -y`
- `npm i -D parcel-bundler`

## ico converter
- https://www.icoconverter.com/

## parcel plugin static files copy
- https://www.npmjs.com/package/parcel-plugin-static-files-copy
- `npm i -D parcel-plugin-static-files-copy`
- `package.json` 파일로 이동 하여 추가

```json
"staticFiles": {
    "staticPath": "static"
  }

```

## autoprefixer
- `npm i -D postcss autoprefixer`
- PostCSS plugin autoprefixer requires PostCSS 8 관련에러 확인 시 
  - `npm i -D autoprefixer@9`

## babel
- `npm i -D @babel/core @babel/preset-env`
- `npm i -D @babel/plugin-transform-runtime`