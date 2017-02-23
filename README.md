# K nearest neighbor for objects

[![Build Status](https://travis-ci.org/kaiquewdev/knn.svg?branch=master)](https://travis-ci.org/kaiquewdev/knn)

## Description

    var k = require('./lib/index');

    var center = { a: 1, b: 2 },
        neighbor = { a: 1, c: 4 };

    k.neighbor( center, neighbor ); // return 2 for distance from center to neighbor

    neighbor = { a: 1, b: 2 };

    k.neighbor( center, neighbor ); // return 0 for distance from center to neighbor
