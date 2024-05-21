# efsExplorer

[EFS Explorer](https://github.com/pgaljan/efsExplorer/blob/main/efsExplorer.xlsx) is concept for OLAP analysis of cloud storage pricing data, leveraging the AWS Bulk Pricing API.

To refresh, navigate to Data>Refresh All.  If you are prompted for an authentication type, select "Anonymous".

Data provided as-is with no warranty.

### EFS Calculator
![image](https://github.com/pgaljan/efsExplorer/assets/11296072/991f447e-a4d4-40d9-ac71-6660c5afb34a)
Leverages filters to get full term price, adjusting for throughput consumption model, and handling all current EFS storage types.  This could also be achieved with cube functions, but is unnecessary for a such a small data set

### EFS Explorer
![image](https://github.com/pgaljan/efsExplorer/assets/11296072/6faf7772-5c08-4776-aa38-6f37c18863ed)

The Explorer tab leverages a Power Pivot data model to help evaluate cost elements across different locations and areas.  Calculates median, but is effectively the same as a raw value in this charts.
