# Topographic Variables Derived from SRTM DEM for Thal Desert (Elevation, Slope, Aspect)

This repository contains topographic variables, including **elevation**, **slope**, and **aspect**, derived from the **Shuttle Radar Topography Mission (SRTM)** **Digital Elevation Model (DEM)**. The data was processed using **Google Earth Engine (GEE)** and analyzed in **ArcGIS** to assess the spatial distribution of topographic features in the **Thal Desert**. This dataset is useful for **landslide susceptibility modeling** and **climate change research**.

## Dataset Information:
- **Data Source**: Shuttle Radar Topography Mission (SRTM) DEM
  - **Website**: [EarthData - SRTM DEM](https://www.earthdata.nasa.gov/data/catalog)
- **Processed Using**:
  - **Google Earth Engine (GEE)** for data processing.
  - **ArcGIS** for analysis and visualization.
  
## Topographic Variables:
The following topographic variables were derived from the SRTM DEM:
1. **Elevation**: Represents the height above sea level for each point in the study area.
2. **Slope**: Represents the steepness of the terrain, calculated from the elevation data.
3. **Aspect**: Represents the orientation of the slope in terms of compass direction, derived from the DEM.

### Data Format:
- **GeoTIFF**: The processed outputs (elevation, slope, and aspect) are provided in **GeoTIFF** format, which is compatible with most GIS software like **ArcGIS** and **QGIS**.

## Geographical Coverage:
- **Latitude**: [31°10′N to 32°17′N]
- **Longitude**: [70°00′E to 71°40′E]
  
This dataset covers the **Thal Desert**, a semi-arid region located in the Punjab province of Pakistan.

## Methodology:
1. **Data Source**: The **SRTM DEM** dataset was obtained from NASA's EarthData platform.
2. **Processing**:
   - The **SRTM DEM** data was processed using **Google Earth Engine (GEE)** to extract topographic variables such as **elevation**, **slope**, and **aspect**.
   - The **elevation data** was used to compute **slope** and **aspect** values for each pixel in the study area.
3. **Analysis**: The derived topographic variables were analyzed in **ArcGIS** to assess the spatial distribution and potential implications for **landslide susceptibility** and **climate change**.

## License:
This dataset is made available under the **CC BY 4.0** (Creative Commons Attribution 4.0 International License), allowing reuse with proper attribution. You are free to use, modify, and distribute the data, provided you credit the source.

Alternatively, if you prefer to make the data freely available for reuse without any restrictions, you can use **CC0** (Public Domain Dedication).

## How to Use:
1. **Download the Data**: The data files are available in **GeoTIFF format**. You can download the files from this repository.
2. **Process the Data**: If you would like to replicate the analysis:
   - You can use **Google Earth Engine (GEE)** for processing SRTM DEM and computing **slope** and **aspect**.
   - Use **ArcGIS** for further analysis and visualization of the **topographic features**.
3. **Software**: The dataset can be visualized and analyzed in **ArcGIS**, **QGIS**, or other GIS software that supports **GeoTIFF files**.

## Citation:
If you use this dataset in your research or projects, please cite the source as follows:
