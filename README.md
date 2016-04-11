# VW Grid

[Bootstrap SASS](https://github.com/twbs/bootstrap-sass) grid consolidated into one partial file and adapted to work with VWs (specifically, with the [VW Starter Kit](https://github.com/hemminger8/vw-starter-kit)).

## Getting Started
Add your grid gutter width and the number of grid columns you would like to the top of _grid.scss. You will also need to set your responsive breakpoint variables (if using the VW Starter Kit, then the variables will likely be set there already). For example:

```
$grid-gutter-width: 40px;
$grid-columns: 12;

$tablet-max: 900px;
$mobile-max: 640px;
$mobile-layout: 320px;

```


## Output
The _grid.scss SASS partial outputs classes for:

* grid columns (e.g. col-xs-12, col-sm-12, col-md-12, col-lg-12)
* offset (e.g. col-md-offset-3)
* pull (e.g. col-md-pull-3)
* push (e.g. col-md-push-3)
* row (i.e. .row)
