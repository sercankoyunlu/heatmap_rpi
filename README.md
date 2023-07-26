Geospatial Visualization of Turkish Housing Market Data

This script performs geospatial visualization and data analysis of the Turkish housing market data. It explores price disparities across different regions in the housing market, focusing on the data from the last month.

The script leverages the evdsAPI to retrieve the necessary data and utilizes Pandas for data manipulation. Geopandas is used for geospatial mapping, allowing visualization of the housing market data on the map. Thefuzz library is employed for text matching to ensure accurate mapping.

The script first fetches the housing market data using the evdsAPI and calculates the annual percentage change. It then prepares the data for geospatial mapping by merging and transforming it accordingly.

After processing the data, the script creates a choropleth map using Matplotlib. The map represents the annual percentage change in the Turkish housing market index (Konut Fiyat Endeksi Yıllık Değişim) across different regions. The map is saved as an image named 'konut_fiyat.png' and as a PDF file named 'konut_fiyat.pdf'.

Subsequently, the script exports the processed data to an Excel file named 'kfe_fiyat.xlsx'. The data is saved on a sheet named 'Sheet1', and the choropleth map image is inserted into cell D3 of the same sheet.


