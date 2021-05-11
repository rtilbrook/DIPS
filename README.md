# transit-times-code

A simple Jupyter notebook GUI for finding dates and times of primary and secondary transits.

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
