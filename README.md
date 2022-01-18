# UD170_Lesson02
Intro to Data Analysis lesson 2 resources and code

https://www.udacity.com/course/intro-to-data-analysis--ud170

Turnstile and Weather Variables

     + UNIT -> Remote unit that collects turnstile information. Can collect from multiple banks of turnstiles.
     + Large -> subway stations can have more than one unit.
     + DATEn -> Date in “yyyy­mm­dd” (2011­05­21) format.
     + TIMEn -> Time in “hh:mm:ss” (08:05:02) format.
     + ENTRIESn -> Raw reading of cummulative turnstile entries from the remote unit. Occasionally resets to 0.
     + EXITSn -> Raw reading of cummulative turnstile exits from the remote unit. Occasionally resets to 0.
     + ENTRIESn_hourly -> Difference in ENTRIES from the previous REGULAR reading.
     + EXITSn_hourly -> Difference in EXITS from the previous REGULAR reading.
     + datetime -> Date and time in “yyyy­mm­dd hh:mm:ss” format (2011­05­01 00:00:00). Can be parsed into a
     + Pandas -> datetime object without modifications.
     + hour -> Hour of the timestamp from TIMEn. Truncated rather than rounded.
     + day_week -> Integer (0 ­ 6 Mon ­ Sun) corresponding to the day of the week.
     + weekday -> Indicator (0 or 1) if the date is a weekday (Mon ­ Fri).
     + station -> Subway station corresponding to the remote unit.
     + latitude -> Latitude of the subway station corresponding to the remote unit.
     + longitude -> Longitude of the subway station corresponding to the remote unit.
     + conds -> Categorical variable of the weather conditions (Clear, Cloudy etc.) for the time and location.
     + fog -> Indicator (0 or 1) if there was fog at the time and location.
     + precipi -> Precipitation in inches at the time and location.
     + pressurei -> Barometric pressure in inches Hg at the time and location.
     + rain -> Indicator (0 or 1) if rain occurred within the calendar day at the location.
     + tempi -> Temperature in ℉ at the time and location.
     + wspdi -> Wind speed in mph at the time and location.
     + meanprecipi -> Daily average of precipi for the location.
     + meanpressurei -> Daily average of pressurei for the location.
     + meantempi -> Daily average of tempi for the location.
     + meanwspdi -> Daily average of wspdi for the location.
     + weather_lat -> Latitude of the weather station the weather data is from.
     + weather_lon -> Longitude of the weather station the weather data is from.
