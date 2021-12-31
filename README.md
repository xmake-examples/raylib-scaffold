# 🌱 Raylib Scaffold

A minimal raylib project template

## 🦄 Usage

Simply click the button below to get started:

[![Use this template](https://img.shields.io/badge/use%20this%20template-brightgreen.svg?longCache=true&style=for-the-badge)](https://github.com/xmake-examples/raylib-scaffold/generate)

## 🔨 Development

###  📋 Requirements

To setup and use the project you will need to have the following tools installed:
 - [Xmake](https://xmake.io/)

###  ⬇️ Installation

Clone the repository

```bash
$ git clone https://github.com/xmake-examples/raylib-scaffold.git
```

Change the working directory to the newly cloned repository:

```bash
$ cd raylib-scaffold
```

Run xmake to install the dependencies & build the project:

```bash
$ xmake
note: install or modify (m) these packages (pass -y to skip confirm)?
in xmake-repo:
  -> raylib 4.0.0
please input: y (y/n/m)

  => download https://github.com/raysan5/raylib/releases/download/4.0.0/raylib-4.0.0_macos.tar.gz .. ok
  => install raylib 4.0.0 .. ok
[ 25%]: ccache compiling.release src/main.cpp
[ 50%]: linking.release raylib-scaffold
[100%]: build ok!
```

Run the project after it has been built:

```bash
$ xmake run
```

![](/res/example.png)
