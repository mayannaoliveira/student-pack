## What's in the folder

* This folder contains all of the files necessary for your extension.
* `package.json` - this is the manifest file that defines the location of the snippet file and specifies the language of the snippets.
* `snippets/snippets.json` - the file containing all snippets.
* `vscode-setting.json` - the file with my Visual Studio Code settings, check it on Github repository: [mayannaoliveira/student-pack].

## How to install?

1. Select extensions (ctrl+shift+X) or click it in sidebar.
2. Extensions > click in ... > install VSIX.
3. Select .vsix file to install it.
* The other way to install it is looking in marketplace.

#### Steps to make your own extension pack

1. Install some NPM: `npm install -g yo` and `npm install -g yo generator-code`.
2. Create a new folder.
3. Open terminal and type `yo code`.
4. Select the option extension pack.
5. To generate a vsix to install as extension type `vsce package` in terminal.
6. `vsce --help` to check other options.

#### Icon

Icon created by Yanti from [Noun Project](https://thenounproject.com/search/?q=plant&i=2754744).


**Best Regards!**

**[Mayanna Oliveira]**

[Mayanna Oliveira]: https://beacons.ai/mayannaoliveira
[mayannaoliveira/student-pack]: https://github.com/mayannaoliveira/student-pack