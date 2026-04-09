# 📊 Exploratory Data Analysis in R

Two EDA projects using R's base plotting system and ggplot2, covering household energy consumption and US air pollution trends.

---

## Project 1 — Household Power Consumption

Explores the [UCI Individual Household Electric Power Consumption](https://archive.ics.uci.edu/ml/datasets/Individual+household+electric+power+consumption) dataset, visualizing energy usage patterns over a 2-day window (Feb 1–2, 2007).

| Plot | Script | Description |
|------|--------|-------------|
| ![plot1](plot1.png) | `plot 1.R` | Histogram of Global Active Power |
| ![plot2](plot2.png) | `plot 2.R` | Global Active Power over time |
| ![plot3](plot3.png) | `plot 3.R` | Energy sub-metering (3 channels) over time |
| ![plot4](plot4.png) | `plot 4.R` | 2×2 composite: active power, voltage, sub-metering, reactive power |

**Plotting system:** R base graphics

---

## Project 2 — US PM₂.₅ Emissions (1999–2008)

Analyzes fine particulate matter (PM₂.₅) emissions data from the EPA National Emissions Inventory, answering six questions about pollution trends across the US, Baltimore City, and Los Angeles County.

| Plot | Script | Question |
|------|--------|----------|
| `plot1.R` | `project2code.R` | Have total US emissions decreased? |
| `plot2.R` | `project2code.R` | Have Baltimore City emissions decreased? |
| `plot3.R` | `plot3.R` | Which source types decreased/increased in Baltimore? |
| `plot4.R` | `plot64.R` | How have coal combustion emissions changed nationwide? |
| `plot5.R` | `plot5.R` | Motor vehicle emissions in Baltimore? |
| `plot6.R` | `plot6.R` | Baltimore vs. Los Angeles motor vehicle emissions? |

**Plotting system:** ggplot2 with `ggthemes`, `RColorBrewer`

**Report:** `projec_2.Rmd` — full R Markdown write-up with code and outputs

---

## 🛠️ Tech Stack

<p>
  <img src="https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white" />
  <img src="https://img.shields.io/badge/ggplot2-FC8D62?style=flat-square" />
  <img src="https://img.shields.io/badge/dplyr-EE6A50?style=flat-square" />
  <img src="https://img.shields.io/badge/RColorBrewer-Palettes-green?style=flat-square" />
  <img src="https://img.shields.io/badge/ggthemes-Themes-blueviolet?style=flat-square" />
</p>

---

## 🚀 Getting Started

```r
# Project 1 — place household_power_consumption.txt in root, then:
source("plot 1.R")  # generates plot1.png
source("plot 2.R")  # generates plot2.png
source("plot 3.R")  # generates plot3.png
source("plot 4.R")  # generates plot4.png

# Project 2 — downloads data automatically:
source("project2code.R")
```

---

## 👤 Author

**Ali Trabelsi Karoui** — [LinkedIn](https://www.linkedin.com/in/ali-trabelsi-karoui-226990151/) · [Email](mailto:alitrabelsikaroui2293@gmail.com)
