# IS445
IS 445
{
  "$schema": "https://vega.github.io/schema/vega-lite/v4.json",
  "data": {
    "url": "https://raw.githubusercontent.com/UIUC-iSchool-DataViz/fall2023-acg-acu/main/data/building_inventory.csv"
  },
  "mark": "bar",
  "encoding": {
    "x": {"field": "Year Acquired"},
    "y": {"aggregate": "mean", "field": "Total Floors"}
  },
  "config": {}
}
