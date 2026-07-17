For 2026 VANTAGE, we have moved to [AprilTags](https://april.eecs.umich.edu/media/pdfs/olson2011tags.pdf)  [Fiducial Tags](https://april.eecs.umich.edu/media/pdfs/krogius2019iros.pdf)


| Boundary Markers and Inner panel markers | Distance between markers (using iPhone) |
| :---: | :---: |
| ![2 Panels](AT01-Two-Panels.jpg) | ![Distance](AT01-Distance.jpg) |

|pair|distance|||||||
|-|-|-|-|-|-|-|-|
|1,2|4'7"||1,13|3'8"||1,12|2'2"|
|2,3|5'1"|
|3,4|4'6"|
|4,1|5'2"|

|Detecting the Tags|Clipped tag (not detected 2 and 4)
| :---: |:---: |
| ![Detected](AprilTag-detection-AT01-closest-R3-L4.jpg_screenshot_16.07.2026.png) | ![Detected](AprilTag-detection-AT01-closest-R1-L2.jpg_screenshot_16.07.2026.png)|

|Detecting all the Tags|
|:---: |
| ![Detected-All](AprilTag-detection-AT01-Two-Panels.jpg_screenshot_16.07.2026.png)|

```
  "boundary_marker_ids": [1, 2, 3, 4],
  "inner_marker_ids": [12, 13]
```

| Inner Marker | Distances to Boundary Markers </p> ` {"ids": [1, 2], "feet": 4, "inches": 7}`| Added </p>`{"ids": [2, 3], "feet": 5, "inches": 1}`|Added </p>{"ids": [3, 4], "feet": 4, "inches": 6}|Added </p>{"ids": [1, 4], "feet": 5, "inches": 2}|
|---|---|---|---|---|
| 12 | [<ul><li>Marker 1: 1 ft 3.6 in (15.61 in total, 132.7px)</li></ul><br> <ul><li>Marker 2: 4 ft 2.9 in (50.88 in total, 432.7px)</li></ul><br> <ul><li>Marker 3: 6 ft 4.2 in (76.16 in total, 647.8px)</li></ul><br> <ul><li>Marker 4: 4 ft 2.5 in (50.49 in total, 429.4px)</li></ul>] | [<ul><li>Marker 1: 1 ft 3.9 in (15.92 in total, 132.7px)</li></ul><br> <ul><li>Marker 2: 4 ft 3.9 in (51.90 in total, 432.7px)</li></ul><br> <ul><li>Marker 3: 6 ft 5.7 in (77.68 in total, 647.8px)</li></ul><br> <ul><li>Marker 4: 4 ft 3.5 in (51.50 in total, 429.4px)</li></ul>] | [<ul><li>Marker 1: 1 ft 0.4 in (12.35 in total, 132.7px)</li></ul><br> <ul><li>Marker 2: 3 ft 4.3 in (40.27 in total, 432.7px)</li></ul><br> <ul><li>Marker 3: 5 ft 0.3 in (60.28 in total, 647.8px)</li></ul><br> <ul><li>Marker 4: 3 ft 4.0 in (39.97 in total, 429.4px)</li></ul>] |[<ul><li>Marker 1: 1 ft 1.1 in (13.08 in total, 132.7px)</li></ul><br> <ul><li>Marker 2: 3 ft 6.6 in (42.63 in total, 432.7px)</li></ul><br> <ul><li>Marker 3: 5 ft 3.8 in (63.81 in total, 647.8px)</li></ul><br> <ul><li>Marker 4: 3 ft 6.3 in (42.31 in total, 429.4px)</li></ul>] |
| 13 | [<ul><li>Marker 1: 3 ft 7.2 in (43.24 in total, 367.7px)</li></ul><br> <ul><li>Marker 2: 1 ft 0.5 in (12.47 in total, 106.1px)</li></ul><br> <ul><li>Marker 3: 4 ft 11.4 in (59.43 in total, 505.5px)</li></ul><br> <ul><li>Marker 4: 6 ft 10.9 in (82.91 in total, 705.1px)</li></ul>] | [<ul><li>Marker 1: 3 ft 8.1 in (44.10 in total, 367.7px)</li></ul><br> <ul><li>Marker 2: 1 ft 0.7 in (12.72 in total, 106.1px)</li></ul><br> <ul><li>Marker 3: 5 ft 0.6 in (60.62 in total, 505.5px)</li></ul><br> <ul><li>Marker 4: 7 ft 0.6 in (84.56 in total, 705.1px)</li></ul>] |  [<ul><li>Marker 1: 2 ft 10.2 in (34.22 in total, 367.7px)</li></ul><br> <ul><li>Marker 2: 0 ft 9.9 in (9.87 in total, 106.1px)</li></ul><br> <ul><li>Marker 3: 3 ft 11.0 in (47.04 in total, 505.5px)</li></ul><br> <ul><li>Marker 4: 5 ft 5.6 in (65.63 in total, 705.1px)</li></ul>] | [<ul><li>Marker 1: 3 ft 0.2 in (36.23 in total, 367.7px)</li></ul><br> <ul><li>Marker 2: 0 ft 10.5 in (10.45 in total, 106.1px)</li></ul><br> <ul><li>Marker 3: 4 ft 1.8 in (49.79 in total, 505.5px)</li></ul><br> <ul><li>Marker 4: 5 ft 9.5 in (69.46 in total, 705.1px)</li></ul>] |



| Inner Marker | Distances to Boundary Markers |
|---|---|
| 12 | [<ul><li>Marker 1: 1 ft 1.1 in (13.08 in total, 132.7px)</li></ul><br> <ul><li>Marker 2: 3 ft 6.6 in (42.63 in total, 432.7px)</li></ul><br> <ul><li>Marker 3: 5 ft 3.8 in (63.81 in total, 647.8px)</li></ul><br> <ul><li>Marker 4: 3 ft 6.3 in (42.31 in total, 429.4px)</li></ul>] |
| 13 | [<ul><li>Marker 1: 3 ft 0.2 in (36.23 in total, 367.7px)</li></ul><br> <ul><li>Marker 2: 0 ft 10.5 in (10.45 in total, 106.1px)</li></ul><br> <ul><li>Marker 3: 4 ft 1.8 in (49.79 in total, 505.5px)</li></ul><br> <ul><li>Marker 4: 5 ft 9.5 in (69.46 in total, 705.1px)</li></ul>] |

| Inner Marker | 1 pair: (1,2) | 2 pairs: (1,2), (2,3) | 3 pairs: (1,2), (2,3), (3,4) | 4 pairs: (1,2), (2,3), (3,4), (1,4) |
|---|---|---|---|---|
| 12 | [<ul><li>Marker 1: 15.61in / 132.7px</li></ul><br> <ul><li>Marker 2: 50.88in / 432.7px</li></ul><br> <ul><li>Marker 3: 76.16in / 647.8px</li></ul><br> <ul><li>Marker 4: 50.49in / 429.4px</li></ul>] | [<ul><li>Marker 1: 15.92in / 132.7px</li></ul><br> <ul><li>Marker 2: 51.90in / 432.7px</li></ul><br> <ul><li>Marker 3: 77.68in / 647.8px</li></ul><br> <ul><li>Marker 4: 51.50in / 429.4px</li></ul>] | [<ul><li>Marker 1: 12.35in / 132.7px</li></ul><br> <ul><li>Marker 2: 40.27in / 432.7px</li></ul><br> <ul><li>Marker 3: 60.28in / 647.8px</li></ul><br> <ul><li>Marker 4: 39.97in / 429.4px</li></ul>] | [<ul><li>Marker 1: 13.08in / 132.7px</li></ul><br> <ul><li>Marker 2: 42.63in / 432.7px</li></ul><br> <ul><li>Marker 3: 63.81in / 647.8px</li></ul><br> <ul><li>Marker 4: 42.31in / 429.4px</li></ul>] |
| 13 | [<ul><li>Marker 1: 43.24in / 367.7px</li></ul><br> <ul><li>Marker 2: 12.47in / 106.1px</li></ul><br> <ul><li>Marker 3: 59.43in / 505.5px</li></ul><br> <ul><li>Marker 4: 82.91in / 705.1px</li></ul>] | [<ul><li>Marker 1: 44.10in / 367.7px</li></ul><br> <ul><li>Marker 2: 12.72in / 106.1px</li></ul><br> <ul><li>Marker 3: 60.62in / 505.5px</li></ul><br> <ul><li>Marker 4: 84.56in / 705.1px</li></ul>] | [<ul><li>Marker 1: 34.22in / 367.7px</li></ul><br> <ul><li>Marker 2: 9.87in / 106.1px</li></ul><br> <ul><li>Marker 3: 47.04in / 505.5px</li></ul><br> <ul><li>Marker 4: 65.63in / 705.1px</li></ul>] | [<ul><li>Marker 1: 36.23in / 367.7px</li></ul><br> <ul><li>Marker 2: 10.45in / 106.1px</li></ul><br> <ul><li>Marker 3: 49.79in / 505.5px</li></ul><br> <ul><li>Marker 4: 69.46in / 705.1px</li></ul>] |
