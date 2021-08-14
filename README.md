# Dancing Button
### typescript implementation of [liquid button v2](https://codepen.io/Zaku/pen/eRmRxz)
### Above app is [Intuiter](https://github.com/seonglae/intuiter)
![asd](https://img.shields.io/lgtm/grade/javascript/g/seonglae/dancing-button.svg?logo=lgtm&logoWidth=18)

<br/>

# Install
```bash
npm i dancing-button
yarn add dancing-button
pnpm add dancing-button
```

# example
```html
<svg class="dancing-button"/>
```

```typescript
const button: <SVGElement> = document.querySelector('.dancing-button')
const btn = new LiquidButton(button)
```
