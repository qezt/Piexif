Changelog
=========

1.0.4
-----

- Fix APP1 matter.

1.0.3
-----

- Support SLong type.

1.0.2
-----

- Add some error detail to 'dump'.

1.0.1
-----

- Fix bug. 'load' and 'dump' InteroperabilityIFD was wrong.

1.0.0
-----

- Add handling InteroperabilityIFD, 1stIFD, and thumbnail image.
- *'load'* returns a dict that contains "0th", "Exif", "GPS", "Interop", "1st", and "thumbnail" keys.
- *'dump'* argument is changed from three dicts to a dict.
- *piexif.ZerothIFD* is renamed *piexif.ImageIFD* for 1stIFD support.

0.7.0c
------

- Rename project.
