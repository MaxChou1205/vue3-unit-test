## 測試程式碼：
```js
import { describe, it } from 'vitest'

describe('add()', () => {
  it(`add(1, 1)，應該為 2`, () => {})
  it(`add('1','1') 應該為 2`, () => {})
  it(`add(0.1, 0.2) 應該為 0.3`, () => {})
  it(`add('1','1') 不應該為 '11'`, () => {})
})

```
## 實作程式碼：

> 可參考 `Math.js` 等工具庫實作。