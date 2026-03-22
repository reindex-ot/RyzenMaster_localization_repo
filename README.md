# Ryzen Master Localization Repository

## English
## What is this repository?
This repository is dedicated to simplifying the multi-language localization of **AMD Ryzen Master**, AMD's official overclocking utility. Currently, Ryzen Master officially supports only English, German, French, and Simplified Chinese, which can be a barrier for many users.

This project is for those who want to take localization into their own hands and enjoy using the tool comfortably in their native language.

## About the repository files
The files in this repository are primarily targeted at **Ryzen 5000 series and newer** processors. However, by following the methods described below, anyone can create custom language files for various versions.

## Editing and Compiling Language Files
Since AMD applications are built using the **Qt framework**, their language assets can be modified using compatible editors.

* **Editing:** You can use [Qt Linguist](https://github.com/lelegard/qtlinguist-installers) to edit translations or export source files. Since **.ts** files are XML-based, you can also use tools like XML Notepad or any text editor.
* **Compiling:** To make your translations usable in Ryzen Master, the edited **.ts** file must be compiled into a **.qm** file. In Qt Linguist, simply select **File > Release** to automatically generate the required **.qm** file.

### How to convert QM files back to TS
If you need to revert a compiled file, you can open a **.qm** file directly in **Qt Linguist**. By selecting **Save As**, you can save it in the **.ts** format, making it editable once again.

## 日本語
### このリポジトリはなに?
このリポジトリは AMD が公開しているオーバークロックツール、**Ryzen Master** の多言語対応を容易にするためのリポジトリです。現在の Ryzen Master は英語、ドイツ語、フランス語、中国語 (簡体字) のみ対応となっており、ユーザーフレンドリーとは言えない状態です。

それならば、自前でローカライズを行い、母国の言語で気軽に使える状態にしてしまおうと思う方向けのリポジトリです。

### リポジトリのファイルについて
**Ryzen 5000 シリーズ以降**のプロセッサ向けのものが対象です。
ですが、下記の方法を使用すれば誰でも言語ファイルの作成が行えます。

### 言語ファイルの編集とコンパイルについて
AMD のアプリケーションは **Qt** を使用しているため、対応したエディタを使えば編集可能です。

* **編集:** [Qt Linguist](https://github.com/lelegard/qtlinguist-installers) を使用することで編集やソースとなるファイルを出力できます。TS ファイルは XML ベースのテキストなので、XML Notepad などのエディタでも編集できます。
* **コンパイル:** 言語ファイルとして使うには、編集した **.ts** ファイルを **.qm** ファイルにコンパイルする必要があります。Qt Linguist の「ファイル」から「リリース」を選択することで、自動的に .qm ファイルが生成されます。

#### QM ファイルから TS ファイルに戻すには
Qt Linguist にそのまま .qm ファイルを読み込ませることができます。読み込んだ後、「名前を付けて保存」を選択し、ファイル形式で **.ts** を指定することで、再度編集可能な状態になります。
