## 如何使用？
- 下载、安装
  `yarn add params-translator` or `npm install params-translator`

- 使用
  ```
    import translator from 'params-translator'
    
    translator({
      name: 'hello',
      age: 'world',
      sex: undefined
    })
    // undefined将被过滤
  ```
  