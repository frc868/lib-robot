# FRC 868 Robot Library

This repository contains a variety of standard robot utilities and functions for the FIRST Robotics Competition.

## Usage

This repository is designed to be used as a `git submodule`. To add it to your existing Eclipse project, simply run:

```
git submodule add https://github.com/frc868/lib-robot src/lib
```

This will add all of this repository's source files to your `src/lib` directory.

## Making Changes

Of course, since this repository isn't an Eclipse project (doesn't play well with submodules) we created a separate repo (`frc868/lib-robot-project`) which allows you to edit these files & run unit tests, all from the comfort of your IDE.
