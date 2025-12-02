# GeoSurrogates

[![Build Status](https://github.com/joshday/GeoSurrogates.jl/actions/workflows/CI.yml/badge.svg?branch=main)](https://github.com/joshday/GeoSurrogates.jl/actions/workflows/CI.yml?query=branch%3Amain)

## Usage

```julia
using GeoSurrogates, Rasters

r = Raster(...)

f = GeoSurrogates.RasterSurrogate(r)

f(x, y)
```
