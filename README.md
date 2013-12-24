NOT FOR NAVIGATION PURPOSES
===========================

Alaska Restricted Airspace
==========================


Extract provided by USAF Nov 2013

Converted to GeoJSON by Dayne Broderson

NOT FOR NAVIGATION PURPOSES

Please contact the FAA or JBER before you try and use this dataset.

http://www.jber.af.mil


Documents that might help context this:

Alaska Military Operations Areas (MOA) (april 2013 update): http://www.jber.af.mil/shared/media/document/AFD-130531-050.pdf


Convertion to GeoJSON
=====================

The dead simple conversion from WGS84 | UTM zone 6N to CRS:84 using ogr2ogr:

    ogr2ogr -f GeoJSON -t_srs crs:84 alaska_restricted_airspace.geojson alaska_restricted_airspace-sam_bushell-usaf/Alaska_airspace.shp

