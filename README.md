# tsviz
This simple tool creates a UML diagram from typescript modules.

![diagram](samples/diagram.png)

## Installation

```bash
npm install -g tsviz-cli
```
You also need to install [GraphViz](http://www.graphviz.org/download/), including correctly added it to your PATH.

## Usage
```
tsviz-cli <switches> <sources filename/directory> <output.png>

Available switches:
  -d, dependencies: produces the modules dependencies diagram
  -r, recursive: include files in subdirectories (must be non-cyclic)

```

In order to create a diagram for an entire project you simply type:

```bash
tsviz-cli samples/ diagram.png
```
