# Garmin_Helpers
Scripts to help manage data in and out of GPS devices.


## GPX_to_CSV.R
converts a multi-layer .gpx to a .csv. Only layers containing features are retained. Use this when you want to extract data from a GPS device.

## CSV_to_GPX.R
converts a flat .csv containing spatial data into .gpx format. Use this when you want to add data to a GPS device. See CSV_to_GPX_template.csv.

## CSV_to_GPX_template.csv
A GPS device expects specific field names to populate menu items like waypoint names. If you want your GPS device to, for instance, recognize your site names use this template to name your fields.
