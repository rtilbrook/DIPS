# DIPS : Detection Itinerary Planner for transiting Systems

A simple Jupyter notebook GUI for finding dates and times of primary and secondary transits. Outputs transit times in chronological order, organised into .csv files by night beginning.

Note: this is optimised for the specific observing runs that I'm involved in- this code has not been used by anyone except me yet. Feel free to suggest changes or edits if there are options which could be expanded for your needs!

------------

<h3>You will need: </h3>


- <h4>A txt file of your ephemerides with columns in the following order: </h4>

    - Target name
    - Epoch (JD)
    - Period (days)
    - Transit width (days)
    - RA (hr)
    - RA (min)
    - RA (sec)
    - Dec (deg)
    - Dec (min)
    - Dec (sec)


- <h4>The RA range over which you want to observe </h4>
- <h4>Sunset/ sunrise (or astronomical twilight start/ end) times </h4>
- <h4>Start/ end dates of run </h4>

    - NOTE: End date should be the date of the final morning when observations will be taken (i.e. NOT night beginning date)

- <h4>Longitude of observatory </h4>

    - NOTE: Positive values are in the Eastern hemisphere, negative values are in the Western hemisphere
    - e.g. La Silla: -70.738 (W)
    - e.g. SAAO 1m: 20.8101(E)
-------
