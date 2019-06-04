# firessh

## Important!
After 13 years and 25 million downloads later, Firefox has officially removed FireFTP and FireSSH support from the browser. Thus, I've ended support / development of the addons. I recommend switching to [Waterfox](http://www.waterfoxproject.org) to continue using the addons.

## Setting up the repository

`FireSSH` has a dependency on the [paramikojs](https://github.com/mimecuvalo/paramikojs) library so it's a couple more steps than just cloning.

    git clone git://github.com/mimecuvalo/firessh.git
    git submodule init
    git submodule update

## Roadmap

- explore webassembly for core logic. previously had tried workers but had trouble since transferring data arrays across
  the boundary was expensive.
- look at using https://github.com/Yomguithereal/react-blessed instead of the current CLI code.