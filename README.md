# The Android App Market on Google Play
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mariembencheikh/DataAnalysis_GooglePlay/main?filepath=notebook.ipynb)
Load, clean, and visualize scraped Google Play Store data to gain insights into the Android app market.
<img src="img/google_play_store.png">
* The data for this project was scraped from the Google Play website. While there are many popular datasets for Apple App Store. The data files are:
    * apps.csv: contains all the details of the apps on Google Play.
    * user_reviews.csv: contains 100 reviews for each app, most helpful first. 
#  :open_file_folder: apps.csv
|    |   Unnamed: 0 | App                                                | Category       |   Rating |   Reviews |   Size |   Installs | Type   |   Price | Content Rating   | Genres                    | Last Updated     | Current Ver        | Android Ver   |
|---:|-------------:|:---------------------------------------------------|:---------------|---------:|----------:|-------:|-----------:|:-------|--------:|:-----------------|:--------------------------|:-----------------|:-------------------|:--------------|
|  0 |            0 | Photo Editor & Candy Camera & Grid & ScrapBook     | ART_AND_DESIGN |      4.1 |       159 |   19   |  10000     | Free   |       0 | Everyone         | Art & Design              | January 7, 2018  | 1.0.0              | 4.0.3 and up  |
|  1 |            1 | Coloring book moana                                | ART_AND_DESIGN |      3.9 |       967 |   14   | 500000     | Free   |       0 | Everyone         | Art & Design;Pretend Play | January 15, 2018 | 2.0.0              | 4.0.3 and up  |
|  2 |            2 | U Launcher Lite – FREE Live Cool Themes, Hide Apps | ART_AND_DESIGN |      4.7 |     87510 |    8.7 |      5e+06 | Free   |       0 | Everyone         | Art & Design              | August 1, 2018   | 1.2.4              | 4.0.3 and up  |
|  3 |            3 | Sketch - Draw & Paint                              | ART_AND_DESIGN |      4.5 |    215644 |   25   |      5e+07 | Free   |       0 | Teen             | Art & Design              | June 8, 2018     | Varies with device | 4.2 and up    |
|  4 |            4 | Pixel Draw - Number Art Coloring Book              | ART_AND_DESIGN |      4.3 |       967 |    2.8 | 100000     | Free   |       0 | Everyone         | Art & Design;Creativity   | June 20, 2018    | 1.1                | 4.4 and up    |
