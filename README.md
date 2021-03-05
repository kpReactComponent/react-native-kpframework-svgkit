# react-native-kpframework-svgkit

在[react-native-svg-uri](https://github.com/vault-development/react-native-svg-uri)基础上进行修改


Install library from `npm`

```bash
npm install react-native-kpframework-svgkit --save
npm install react-native-svg --save
// or
yarn add react-native-kpframework-svgkit
yarn add react-native-svg
```

## 目录
- [SvgImage](#svgimage)


## SvgImage
svg组件，使用方式类似于图片
  
```jsx
import { SvgImage } from 'react-native-kpframework-svgkit';

<SvgImage width={200} height={200} source={require('./img/homer.svg')} />
<SvgImage
  width={200}
  height={200}
  source={{uri:'http://thenewcode.com/assets/images/thumbnails/homer-simpson.svg'}}
/>
```
  
**Props**

| Prop | Type | Default | Note |
|---|---|---|---|
| `style` | `ViewStyle` |  | 样式
| `width` | `number` |  | 宽度
| `height` | `number` |  | 高度
| `source` | `ImageSource` |  | Same kind of `source` prop that `<Image />` component has
| `svgXmlData` | `String` |  | You can pass the SVG as String directly
| `fill` | `Color` |  | Overrides all fill attributes of the svg file
| `fillAll` | `Boolean` |  Adds the fill color to the entire svg object

## 开源库的原生文档

[文档](./doc/README.md)