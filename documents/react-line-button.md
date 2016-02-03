# react-line-button
Simple React components for LINE Button.

[日本語ドキュメント/website](http://uraway.hatenablog.com/entry/2016/02/02/000000)

- **This component is aimed for smart phone users.** It does not work for PC users.

## Install
```
npm install --save react-social-sharebutton
```

## Example
```javascript
import { LINEButton } from 'react-social-sharebutton';

class App extends React.Component {
  render() {
    let text = "LINEで送る";
    let image = "36x60";
    return (
      <LINEButton text={text} image={image} />
    );
  }
}
```

## props

#### text

The text you want to share. You can only specify the page title and page URL.

- [ガイドライン](https://media.line.me/guideline/ja/)
- [Guideline](https://media.line.me/guideline/en/)

#### image

Specify size of the image you want to use as LINE button.

##### 20x20
![20x20](../images/linebutton_20x20.png)

##### 30x30
![30x30](../images/linebutton_30x30.png)

##### 36x60
![36x60](../images/linebutton_36x60.png)

##### 40x40
![40x40](../images/linebutton_40x40.png)

##### 82x20
![82x20](../images/linebutton_82x20.png)

---
MIT licensed