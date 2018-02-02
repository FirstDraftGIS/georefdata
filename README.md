# georefdata
Country Codes and other Miscellaneous Geo-Spatial Reference Data

# install
```
pip install georefdata
```

# usage
```
import georefdata

georefdata.get_country_codes()
# ['AF', 'AL', 'DZ', 'AS', 'AD', ... 'ZW']

georefdata.get_geonames_feature_classes()
# ['A', 'H', 'L', 'P', 'R', 'S', 'T', 'U', 'V', 'n']

georefdata.get_geonames_feature_codes()
# ['ADM1', 'ADM1H', 'ADM2', ... 'ZNF', 'ZOO', 'null]
```

# attribution
[GeoNames](https://geonames.org) uses [Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/), which requires attribution.  GeoNames Feature Classes and GeoNames Feature Codes come from GeoNames.
