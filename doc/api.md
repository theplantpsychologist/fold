# FOLD API

The FOLD API consists of several modules under the `fold` namespace:

* `fold.filter`: Selecting existing parts of, or computing new features of,
  a given FOLD object.
* `fold.convert`: Augment an existing FOLD object with additional fields,
  and convert between FOLD and other file formats.
* `fold.geom`: Basic geometry tools (manipulation of vectors, angles,
  lines, segments, etc.).  Basically whatever we needed to implement other
  features, but which you might find helpful too.

## fold.filter

See [source code](https://github.com/edemaine/fold/blob/master/src/filter.coffee)
for details.

## fold.convert

See [source code](https://github.com/edemaine/fold/blob/master/src/convert.coffee)
for details.

## fold.geom

See [source code](https://github.com/edemaine/fold/blob/master/src/geom.coffee)
for details.