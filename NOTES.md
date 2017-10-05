# API

## refresh

Calls `updateWithOptions`

## updateWithOptions

Clears the directive element
set `scope.chart` to the nv chart model instance and applies options
Calls `updateWithData`

## update

If the chart already exists, re-applies the data and calls nv method to update. But does not update options.
If the chart doesn't exist calls the refresh method

## updateWithData

The entire svg element is removed from the DOM and recreated.

`scope.svg.datum(data).call(scope.chart);` is the sole call to nvd3.
