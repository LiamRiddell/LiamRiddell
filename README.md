### Liam Riddell

Full-stack developer based in the United Kingdom. Most of what is here is
small, focused tools rather than one large product: a note-taking plugin, the
expression engine underneath it, and a handful of ports and utilities built
because something needed to exist and did not yet.

More at [liamriddell.co.uk](https://www.liamriddell.co.uk).

### Building now

**[solve-engine](https://github.com/LiamRiddell/solve-engine)**
An expression engine for natural language calculations. Give it a line of
text such as `100 cm + 2 m` or `15% of 2400` and it works out what the line
means: units, currencies, percentages, dates, matrices and a fair amount of
plain English, evaluated through a lexer, a parser and a bytecode virtual
machine. Runs in Node, a browser or a worker, with no DOM and no framework
to satisfy.

**[obsidian-solve](https://github.com/LiamRiddell/obsidian-solve)**
The editor integration built on top of solve-engine. Type an expression on
any line of an Obsidian note and the answer appears next to it as you type.
The engine does the calculation, this plugin wires it into the editor and
exposes the settings that make sense for a note-taking app.

### Other projects

**[NoteMaster](https://github.com/LiamRiddell/NoteMaster)**
A minimalistic, persistent note-taking app. Its Smart Mode feature, which
evaluated expressions written directly into notes, was the starting idea
that later became Solve.

**[MJML.NET](https://github.com/LiamRiddell/MJML.NET)**
An unofficial port of MJML, the responsive email markup language, to .NET.
[mjml-net-app](https://github.com/LiamRiddell/mjml-net-app) is a desktop app
built on top of it.

**[vscode-plainly](https://github.com/LiamRiddell/vscode-plainly)**
A VS Code extension that flags likely-unclear writing while you type:
passive voice, weasel words, and sentences that have grown too complex.

**[Stremio-Server-Raspberry-PI](https://github.com/LiamRiddell/Stremio-Server-Raspberry-PI)**
A guide for running stremio-server on a Raspberry Pi under Docker.
