# EpubRename2Title
## 概要
epubファイルのファイル名をメタデータに保存されている書籍名(タイトル)にリネームします．  
引数で渡したディレクトリにあるepubファイルをすべてリネームします．  
Python 3系で使用してください．  
例：epubFile001.epub => 新世紀エヴァンゲリオン(1).epub
## 使用方法
python epubRename2Title [epubファイルを配置したパス]  
例：python ./epubRename2Title ./epubDir

## Summary
This program renames epub file to original book title that on metadata.  
This program renames all epub files in a directory that selected as argument.  
Please use this program with Python 3.  
Example: epubFile001.epub => Neon Genesis EVANGELION(1).epub
## How to use
python epubRename2Title [epub files directory path]  
Example: python ./epubRename2Title ./epubDir
