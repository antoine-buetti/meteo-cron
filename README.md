# meteo-cron
Uses GitHub Actions to regularly pull data from MeteoSuisse

Usage: Modify the file "cap_location.txt" with the CAP of interest. This will trigger an automated workflow that pulls information from MeteoSuisse and summarizes it in the output file "info_meteo.txt". The workflow is also triggered by a schedule defined in "./.github/workflows/actions.yml"

Antoine

