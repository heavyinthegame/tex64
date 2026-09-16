# TeX64

A LaTeX editor for Windows and macOS, focused on writing and revising mathematics.

[Website](https://tex64.com) · [Download](https://tex64.com/download?ref=github&campaign=2026-09-launch) · [Documentation](https://tex64.com/docs) · [Editor comparison](https://tex64.com/latex-editor) · [FAQ](./FAQ.md)

TeX64 combines visual equation editing, on-device equation OCR, local PDF builds and SyncTeX. It works with ordinary `.tex` files and project folders. The core editor, equation input, OCR and local PDF workflow are free. Axiom is a separate online AI editing service with its own usage plans.

日本語: TeX64は、数式を見たまま入力・修正できるWindows・Mac用のTeXエディタです。通常の`.tex`ファイルを扱い、数式OCR、PDFビルド、SyncTeXなどの基本機能を無料で利用できます。オンラインのAI編集機能Axiomは別の機能です。[製品の説明](https://tex64.com/ja)・[TeXエディタの選び方](https://tex64.com/ja/latex-editor)。

## What it does

- **Visual equation editing:** edit rendered mathematics and apply the result to your LaTeX source.
- **On-device equation OCR:** import an equation image, inspect the recognized LaTeX, correct it and insert it into the document. Recognition needs checking against the original image.
- **Local PDF workflow:** build with a TeX distribution, preview the PDF and move between source and output with SyncTeX.
- **Axiom:** ask an online assistant to work with files in the active project, inspect the applied changes and PDF, and undo changes when necessary. AI output still needs review.
- **Ordinary project files:** keep `.tex`, images, bibliography files and styles in your project folder. Match the original engine and dependencies when migrating a project.

![TeX64 source editor and PDF preview](https://tex64.com/marketing/tex64-editor.png)

![Visual equation editing in TeX64](https://tex64.com/marketing/tex64-blocks-english.jpg)

## Platforms and setup

- Windows 10/11, x64: distributed through Microsoft Store and the official Store web installer.
- macOS 12 or later: Apple Silicon and Intel downloads.
- PDF builds require a TeX distribution. Use an existing compatible environment or approve TeX64's managed TeX Live installation. Initial installation and updates require internet access.
- Local editing, OCR and a prepared local TeX toolchain can be used offline. Axiom and account services require a network connection.

See [getting started](https://tex64.com/docs/getting-started) and [TeX environment setup](https://tex64.com/docs/tex-distribution) for current instructions. Download the [editable example pack](https://tex64.com/examples/tex64-starter-examples.zip), including a Japanese LuaLaTeX report and complete source/PDF reference examples.

## Choosing an editor

TeX64 is a candidate when visual equation editing and a local project workflow matter. Real-time coauthoring teams may prefer Overleaf; people already comfortable in VS Code may prefer LaTeX Workshop. The [comparison guide](https://tex64.com/latex-editor) describes requirements, alternatives and the scope of published interoperability evidence. It does not claim a measured performance ranking.

## This repository

This is the public product-information and feedback repository maintained by [Fermion Inc.](https://fermion.company). The desktop application's source is private. This repository is not an installer or an open-source release of the application.

[Support](https://tex64.com/support) · [Report an issue](https://github.com/heavyinthegame/tex64/issues/new/choose) · [Privacy](https://tex64.com/privacy)

Product information reviewed September 16, 2026. The website and official distribution channels carry current releases.
