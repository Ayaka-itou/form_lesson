# 1st review
### HTML
* wrapper：divタグからsectionタグへの変更：登録フォームは基本的にサイトの一部のため、divではなくsectionタグで囲む
### CSS
* input-init：outline:none;の追加：ブラウザによってデフォルトのスタイル（枠線の色など）が適用されてしまうため、outline:none;で消して、input-area:focusでやりたいスタイルを指定する。*outlineの色は変えられない
* 出身：appearance:none;の追加：擬似要素（:after）で出した矢印と、デフォルトのものが重なっていたため
* 備考：resize:none;の追加：textareaの右下に、サイズ変更の三角が表示されていたため

# 2nd review
### CSS
* 送信ボタンの枠線：input-init[type="submit"] { border:none;}　*この時、クラス名とタイプの間にスペースを入れてしまうと、別の子要素のタイプということになってしまう（ホバーで確認できる！）