# setup_labs
_Extract zip submissions from RIT's MyCourses mass download_

## Requirements

* Python 3 must be installed and callable from `/usr/bin/python3`.
  * If this behavior is not desirable, 

## Usage

Place in `/usr/bin/` to call from anywhere.

```
Usage: setup_labs ZIP DEST

  ZIP     name of zip file (with sub zips) to extract from
  DEST    name of destination directory to place extracted files from    
```

## Todo

* Use argparser...
  * ...optionally define regex for part of name to strip
  * ...extract directory (e.g. default is `./DEST/extract/`)
