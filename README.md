# IllustGrid

日本語版は下の方にあります。

# What is IllustGrid?

"IllustGrid" was created to address the limitation of services like P\*\*terest that only allow you to organize images based on when you added them, making it difficult to rediscover older favorites.  
With IllustGrid, you can specify a folder, and it will randomly arrange and display the images (in png, jpg, jpeg formats) found within it.  
Use it for curating your favorite image collections, wallpapers, design inspiration, and more!

# Installation

As of now, IllustGrid requires you to set up Python environment. In the future, we aim to make it a standalone application.

### 1. Install Python 3.11.4

Please install Python 3.11.4 from the [official Python website](https://www.python.org/downloads/release/python-3114/).  
If you already have a different Python version installed, you can use tools like pyenv to ensure that Python 3.11.4 is available within the IllustGrid project folder.  
Windows users can use [pyenv-win](https://github.com/pyenv-win/pyenv-win).

### 2. Download the Project

- You can download the project by clicking on the "Code" button at the top-right and selecting "Download ZIP" from the dropdown. Extract the ZIP file to your preferred location.
- Alternatively, you can use Git to clone the project to a directory of your choice:

  ```bash
  git clone https://github.com/Yocchi3191/IllustGrid.git
  ```

If you're using pyenv, make sure that Python 3.11.4 is available in the folder where you've placed the project.

### 3. Add Images to the Images Folder

To display and arrange images randomly, simply place your images in the Images folder. You can also edit the `folder_path` in `illuist_grid.py` to specify a different folder containing the images you want to display.

---

# 日本語版

# IllustGrid って？

「P\*nterest は好みの画像をまとめることはできても、新しく登録した順でしか並べてくれないから、むかしに登録したものを偶然見つけて懐かしんだりできないんだよな」と思ってつくりました。  
フォルダを指定すると、その中の画像ファイル(png, jpg, jpeg)を取得してランダムに並べて表示します。
お気に入り画像集、壁紙、素材 etc... に使って懐かしんだり、アイデア出しの一助になればと思います。

# インストール

現状、IllustGrid の使用には Python 実行環境が必要です。ゆくゆくはソフト単体で動作するものにしたい...

### 1. python 3.11.4 をインストール

[Python の公式ページ](https://www.python.org/downloads/release/python-3114/) から、Python 3.11.4 をインストールしてください。
すでに別バージョンを入れている方は pyenv などのツールで、IllustGrid があるフォルダ内で Python 3.11.4 が動くようにしてください。  
windows ユーザーは[pyenv-win](https://github.com/pyenv-win/pyenv-win)、使おう！

### 2. プロジェクトをダウンロード

右上の Code からプロジェクトの zip ファイルをダウンロードして、好きなところで解凍してください  
または任意のディレクトリで

```bash
git clone https://github.com/Yocchi3191/IllustGrid.git
```

とすればプロジェクトをダウンロードできます  
pyenv を使っている場合であれば、Python 3.11.4 が動くフォルダに置けば OK です。(環境の作り方は素晴らしい先人の遺してくれたナレッジが web に転がってるので調べてください)

### 3. Images フォルダに並べたい画像を入れる

Images フォルダに画像を入れることで、その中の画像をランダムに並べ替えて表示させられます。  
illuist_grid.py の`folder_path`に渡すパスを編集すれば、好きなフォルダ内の画像を並べ替えて表示することもできます。
