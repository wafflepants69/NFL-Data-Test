# nflversedata 0.0.7

* `nflverse_upload()` uses `purrr::insistently()` to retry on failure because of random GitHub server issues. 

# nflversedata 0.0.5 

* Added file_types argument which takes a vector of file types and defaults to `c("csv","rds","qs","parquet")`

# nflversedata 0.0.4

* Added `nflverse_archive()` which automates archiving the rds version of every nflverse-data release asset and pushes it to https://github.com/nflverse/nflverse-data-archives

# nflversedata 0.0.3

* Added `nflverse_save()` which automates saving to the four main supported file formats (csv, rds, parquet, qs) and uploading to a specified release tag.

# nflversedata 0.0.2

* Added a `NEWS.md` file to track changes to the package.
* Added timestamp.json to experiment with shields.io badges

# nflversedata 0.0.1

* Added data upload wrapper function (`nflverse_upload()`) including timestamp updates.
