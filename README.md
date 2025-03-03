# NOAA Storm Data Analysis

## Introduction
Storms and other severe weather events can cause significant public health and economic challenges for communities and municipalities. Many severe events result in fatalities, injuries, and property damage. Understanding these events and their impacts is crucial for mitigating risks and improving preparedness.

This project explores the U.S. National Oceanic and Atmospheric Administration's (NOAA) storm database. This database tracks characteristics of major storms and weather events in the United States, including the timing, location, and estimates of fatalities, injuries, and property damage.

## Data
The dataset used in this analysis is provided in a comma-separated value (CSV) format and compressed using the bzip2 algorithm to reduce its size. The data can be downloaded from the following link:

- [Storm Data (47MB)](https://d396qusza40orc.cloudfront.net/repdata%2Fdata%2FStormData.csv.bz2)

Additional documentation regarding the dataset is available at:

- [National Weather Service - Storm Data Documentation](https://www.ncdc.noaa.gov/stormevents/pd01016005curr.pdf)
- [National Climatic Data Center - Storm Events FAQ](https://www.ncdc.noaa.gov/stormevents/faq.jsp)

The dataset contains records from 1950 to November 2011. In the early years, fewer events were recorded, likely due to limited record-keeping. More recent years contain more comprehensive and reliable data.

## Assignment
The objective of this analysis is to explore the NOAA Storm Database and address fundamental questions regarding severe weather events. The dataset is used to generate insights through tables, figures, and other summaries. Any R package may be used to support the analysis.

### Questions
This data analysis focuses on answering the following questions:

1. Across the United States, which types of events (as indicated in the `EVTYPE` variable) are most harmful with respect to population health?
2. Across the United States, which types of events have the greatest economic consequences?

This report is designed to be informative for government or municipal managers who are responsible for preparing for severe weather events and prioritizing resource allocation. However, no specific recommendations are required.

### Requirements
The following tools are needed for this analysis:

- **RStudio**: Required for publishing the completed analysis document to RPubs and editing/writing the analysis.
- **knitr**: Necessary for compiling the R Markdown document and converting it to HTML.

### Document Layout
- **Language**: The document is written in English.
- **Title**: A brief summary of the data analysis.
- **Synopsis**: A concise summary (maximum of 10 sentences) of the analysis.
- **Data Processing**: Describes (in words and code) how the data were loaded into R and processed for analysis. The analysis starts from the raw CSV file containing the data, and no preprocessing is performed outside the document. If preprocessing is time-consuming, the `cache = TRUE` option may be used for certain code chunks.
- **Results**: A section presenting the findings of the analysis.
- Additional sections may be included, but **Data Processing** and **Results** are mandatory.

### Figures and Code
- The analysis must include **at least one figure containing a plot**.
- A maximum of **three figures** is allowed, with multiple plots per figure permitted (e.g., panel plots).
- All code used in the analysis must be shown. While this may increase verbosity, it ensures transparency. The `echo = TRUE` setting should be used for every code chunk (default in knitr).
