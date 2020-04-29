# Change Log

All notable changes to the "betterfasto" extension will be documented in this file.

## [0.5] - 29-04-2020
### Added
- Keyword highlighting for ```if then else let in fun fn op```
- Operator highlighting for ``` => && not || ```
    - While the operators are  highlighted, some need to be implemented in the Fasto compiler in order to work.
- Single-line-comment highlighting
- Highlighting for built-in types and functions such as ```read```,  ```write```, ```iota```, ```map``` and ```reduce```
    - ```replicate```, ```filter``` and ```scan``` are also highlighted but need to be implemented in the Fasto compiler in order to work.
- String highlighting
- Escape-character highlighting, e.g. ```\n```