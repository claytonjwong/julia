# Julia

# Grievances

* Integer division results in floating point values
* 1-based indexing and slicing from [1..n] inclusive
  * I prefer 0-based indexing and slicing from [0..n) non-inclusive, .ie from [0..n-1] inclusive
* Does *not* handle large integers well like Python3
  * See [Algorithms-Illuminated](https://github.com/claytonjwong/Algorithms-Illuminated) commit [8ccca8f](https://github.com/claytonjwong/Algorithms-Illuminated/commit/8ccca8f752edaac965b598c50c3381f3511edc8c)