Please start by downloading yahoo datasets from the link provided and run the file 'sample.py' which contains implementation of support sampling algorithm, with the downloaded datasets.
There is data file for synthetic datasets as well.
The rest three files are the implemntations of Frequent item mining, Survery Sampling and Heavy Hitter finding algorithms. 
We have hardcoded them with the synthetic datasets as they were taking a lot of time just for reading on the 2.2GB yahoo data.

Yahoo Dataset : https://webscope.sandbox.yahoo.com/myrequests.php?guccounter=1&guce_referrer=aHR0cHM6Ly9sb2dpbi55YWhvby5jb20v&guce_referrer_sig=AQAAAFMqEBzeM3ltJqQd0449YhkTV6Yv5SDa7bIHWu2g9xRLPhC8rBQsZDuDAZIcZaTh_VBlQw8L--zMom21gLFggyCo5N7-b-nM9CtJveEjuFGRYxLIj_bRdL5MFiAJBrp4vM2AU6h831hyfo_TaSWASyJYyXZhbhzqxPGHwPRMjuqQ




















Dataset: ydata-ymusic-user-artist-ratings-v1_0 

Yahoo! Music user ratings of musical artists, version 1.0

=====================================================================
This dataset is provided as part of the Yahoo! Research Alliance
Webscope program, to be used for approved non-commercial research
purposes by recipients who have signed a Data Sharing Agreement with
Yahoo!. This dataset is not to be redistributed. No personally
identifying information is available in this dataset. More information
about the Yahoo! Research Alliance Webscope program is available at
http://research.yahoo.com
=====================================================================

Full description:

This Yahoo! Music data represents a sample of (anonymized) Yahoo!
users' ratings of musical artists, gathered over a thirty-day period
sometime prior to March 2004.

Tab is used as a delimiter for all data files.

This dataset consists of two files:
1. ydata-ymusic-user-artist-ratings-v1_0.txt
2. ydata-ymusic-artist-names-v1_0.txt

The content of the two files are as follows:

=====================================================================

(1) "ydata-ymusic-user-artist-ratings-v1_0.txt" contains user ratings
    of music artists. It contains 11,557,943 ratings of 98,211 artists
    by 1,948,882 anonymous users. The format of each line of the file
    is: anonymous_user_id (TAB) artist_id (TAB) rating. The ratings
    are integers ranging from 0 to 100, except 255 (a special case
    that means "never play again").

Snippet:
1       1000125 90
1       1006373 100
1       1006978 90
1       1007035 100
1       1007098 100

====================================================================

(2) "ydata-ymusic-artist-names-v1_0.txt" contains the artist_id and
    name of each musical artist.

Snippet:
-100    Not Applicable
-99     Unknown Artist
1000001 Bobby "O"
1000002 Jimmy "Z"
1000003 '68 Comeback

