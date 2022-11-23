
# Stream

> stream

## 如何使用ReadStream

```javascript   title='demo.js'
import fs from "fs";
const rs = fs.createReadStream('demo.zip')
rs.on('data',function(chunk){
    console.log(chunk.length)
})
```