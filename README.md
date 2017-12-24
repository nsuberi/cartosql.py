# CartoPy

Simple utility library for interacting with the CARTO SQL API.

Example:

```
import cartopy

# CARTO_USER and CARTO_KEY read from environment if not specified
r = carto.get('select * from mytable', user=CARTO_USER, key=CARTO_KEY)

data = r.json()
```

Read more at:
http://carto.com/docs/carto-engine/sql-api/making-calls/

## Install

`pip install -e git+https://github.com/fgassert/cartopy.git#egg=cartopy`
`pip install -r cartopy/requirements.txt`
