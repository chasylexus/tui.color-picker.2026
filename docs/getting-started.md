## Install

``` sh
$ npm install --save @techie_doubts/tui.color-picker.2026 # Latest version
$ npm install --save @techie_doubts/tui.color-picker.2026@<version> # Specific version
```

It can also be installed by using bower or downloaded by CDN. Please refer to the [💾 Install](https://github.com/nhn/tui.color-picker#-install).

## Usage

```javascript
import colorPicker from '@techie_doubts/tui.color-picker.2026';
import '@techie_doubts/tui.color-picker.2026/dist/tui-color-picker.css';

const colorpicker = colorPicker.create({
  container: document.getElementById('color-picker-container'),
  color: '#f9f9f9',
  preset: ['#181818', '#292929', '#393939'],
  ...
});
```

It can also be used by namespace or CommonJS module. Please refer to the [🔨 Usage](https://github.com/nhn/tui.color-picker#-usage).

For more information about the API, please see [here](https://nhn.github.io/tui.color-picker/latest/ColorPicker).