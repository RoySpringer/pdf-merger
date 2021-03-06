# Mergyfile

A small application that can merge multiple pdf files into one. It is a small open source project where you can merge your PDF files.

<img alt="mergyfile" src="./screenshots/Mergyfile.jpg" width="400">
<img alt="mergyfile2" src="./screenshots/Mergyfile2.jpg" width="400">

## Why I started this project

For most of the time when merging PDFs I use online tools to do that. But when I needed to merge some important files with personal information in it I didn't want to use a website for that. So I started with a small command-line NodeJS tool that can do it for me, which had an input folder and an output folder. In goes the files you want to merge and out goes the files merged together. A very easy tool when using the command-line and having NodeJS installed. I wanted to share my tool with other people arround me, but not everyone I know happens to have NodeJS installed on there computer, let alone use command-line tools😅.
It was a good time to convert this easy command-line tool to a desktop app and learn more about Electron.

## To Use - Developer

To clone and run this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
git clone https://github.com/RoySpringer/mergyfy.git
# Go into the repository
cd mergyfy
# Install dependencies
npm install
# Run the app
npm start
```

Build your own package:
```bash
npm package
```

Note: If you're using Linux Bash for Windows, [see this guide](https://www.howtogeek.com/261575/how-to-run-graphical-linux-desktop-applications-from-windows-10s-bash-shell/) or use `node` from the command prompt.

## Roadmap

- [x] Refactor to React - With TypeScript and webpack.
- [x] Add page selection per PDF to indicate which pages of a PDF you want to merge.
- [X] Add some sort of build proces to the project and create releases with installers voor all platforms.
- [ ] Add better documentation for the project.
- [ ] Add unit tests.

## License

Copyright (c) Roy Springer. All rights reserved.

Licensed under the [MIT](LICENSE) license.
