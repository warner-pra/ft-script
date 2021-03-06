## Extension Development Logbook

1. Install node.js via installer package: https://nodejs.org/en/ (required for Yeoman install)
2. Installed Yeoman: `sudo npm install -g yo generator-code`
3. Run `yo code`
4. Fill in the fields per *abc* example: https://code.visualstudio.com/api/language-extensions/syntax-highlight-guide
5. Extension repo was created, but I hit a road block...not sure where to place the abc example or how to activate it to test it
6. Answer is in `vsc-extension-quickstart.md`: Can launch directly in vscode debugger (F5)
7. F5
8. Created test.abc and validated the default keywords were highlighted (e.g. for, if)