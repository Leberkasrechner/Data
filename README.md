# Leberkasrechner Map Data
## Introduction

At Leberkasrechner, we prioritize user privacy and data efficiency. We understand the importance of having large datasets for our maps, and the challenges that come with creating vector tiles from these datasets. To address this, we self-host our tile-server and have decided to release ready-to-use ```.mbtiles``` files to the public.
## Methodology

Our process involves using OpenStreetMap (OSM) data in the form of .pbf files, which we source from [Geofabrik's OSM exports](https://download.geofabrik.de). We then convert these files into .mbtiles using Planetiler. The resulting .mbtiles files can be easily loaded into a tileserver like Tileserver-GL, providing a seamless experience for users.
## Download

Our download server is located in Vienna. This ensures fast and reliable access to the data files. Please note that due to the large size of the datasets, downloads may take some time. Nor can we guarantee that the data is up to date.

We hope this initiative will not only enhance the user experience but also contribute to the open-source community by providing valuable map data resources. We welcome feedback and contributions to improve this project.
## Disclaimer

Please ensure you comply with the terms of use and licensing requirements of the data sources and tools used in this project. Leberkasrechner is not responsible for any misuse or violations.
