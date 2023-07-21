# s3-tree

Print an S3 bucket as a hierarchical tree.

# Runtime Dependencies

`tree` (brew install tree)

# Usage

```
$ python s3-tree --help

Usage: s3-tree [OPTIONS] PROFILE_NAME BUCKET_NAME PREFIX [MAX_DEPTH]
               [SHOW_FILES] [MAX_FILES_TO_SHOW] [VERBOSE]

  Prints all files in a S3 bucket as a tree.

Arguments:
  PROFILE_NAME         AWS profile name  [required]
  BUCKET_NAME          Bucket name  [required]
  PREFIX               Prefix to filter  [required]
  [MAX_DEPTH]          Max depth to traverse  [default: 3]
  [SHOW_FILES]         Show files or not  [default: False]
  [MAX_FILES_TO_SHOW]  If show, how many files to show  [default: 10]
  [VERBOSE]            Verbose or not  [default: False]
```

