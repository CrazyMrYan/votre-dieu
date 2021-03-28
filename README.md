# votre-dieu

## 下载依赖
```shell
npm install votre-dieu
```

## 引入注册
```js
# 全局注册
import VotreDieu from 'votre-dieu'
import 'votre-dieu/lib/votre-dieu.css'

Vue.use(VotreDieu)

# 按需引入
import { vdButton } from 'votre-dieu'
import 'votre-dieu/lib/votre-dieu.css'

Vue.use(vdButton)
```
## 简单使用
```html
<vd-button> default </vd-button>
```

## 组件
- [vd-button](./packages/vdButton/README.md)
- [vd-card](./packages/vdCard/README.md)
- [vd-input](./packages/vdInput/README.md)