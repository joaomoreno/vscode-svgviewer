# vscode-svgviewer
SVG Viewer for Visual Studio Code
[Visual Studio Marketplace](https://marketplace.visualstudio.com/items/cssho.vscode-svgviewer)

[![](https://vsmarketplacebadge.apphb.com/version/cssho.vscode-svgviewer.svg)](https://marketplace.visualstudio.com/items?itemName=cssho.vscode-svgviewer)
[![](https://vsmarketplacebadge.apphb.com/installs/cssho.vscode-svgviewer.svg)](https://marketplace.visualstudio.com/items?itemName=cssho.vscode-svgviewer)
[![](https://vsmarketplacebadge.apphb.com/rating/cssho.vscode-svgviewer.svg)](https://marketplace.visualstudio.com/items?itemName=cssho.vscode-svgviewer)

## Usage 
0. コマンドパレットを表示し、入力欄に`ext install SVG Viewer`と入力
0. Enterを押下し、VSCodeを再起動
0. SVGファイルを開く
0. コマンドパレットかショートカットから処理を選択

![palette](img/palette.png)

### View SVG - `Alt+S O`
SVGをエディタ上で表示

### Export PNG - `Alt+S E`
SVGをPNGに変換

### Export PNG with explicitly size - `Alt+S X`
サイズを明示的に指定して、SVGをPNGに変換

### Copy data URI scheme - `Alt+S C`
SVGをdata URI schemeに変換し、クリップボードにコピー

![preview](img/preview.png)

### Options
SVG Viewerでは以下のVisual Studio Codeの設定が可能です。`User Settings`または`Workspace Settings`で設定できます。

```javascript
{
    // 透明グリッドを表示
	"svgviewer.transparencygrid": true
}
```
