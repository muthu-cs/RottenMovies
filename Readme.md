RottenTomatoesDemo
==================

IOS demo application did as part of my IOS course here in Yahoo! for displaying the latest box office and Top DVD's movies using the [RottenTomatoes API](http://www.rottentomatoes.com/).

Time spent: 15 hours spent in total

Completed user stories:

 * [x] Required: User can view a list of movies from Rotten Tomatoes.  Thumbnail images are loaded asynchronously.
 * [x] Required: User can view movie details by tapping on a cell
 * [x] Required: User sees loading state while waiting for movies API. Third party library used: MBProgressHUD
 * [x] Required: User sees error message when there's a networking error. Third party library used: tonymillion/Reachability
 * [x] Required: User can pull to refresh the movie list. Third party library used: ODRefresh
 * [x] Optional: All images fade in
 * [] Optional: All images should be cached in memory and disk.
 * [x] Optional: Customize the highlight and selection effect of the cell
 * [x] Optional: Add a tab bar for Box Office and DVD
 * [] Optional: Add a search bar
 * [x] Optional: Customize the navigation bar
 * [] Optional: For the large poster, load the low-res image first, switch to high-res when complete
 * [] Optional: All images should be cached in memory and disk. In other words, images load immediately upon cold start

Walkthrough of all user stories:


![Video Walkthrough](RottenTomatto.gif)
===================================================================================
When there is a network error, we show an error message:
Note: I have modified the api to get the network error.

![Video Walkthrough](RottenTomatto-2.gif)


Acknowledgements:

 Licecap - GIF created with [LiceCap](http://www.cockos.com/licecap/).
 
 MBProgressHUD - Copyright (c) 2013 Matej Bukovinski
 
 AFNetworking - Copyright (c) 2013-2014 AFNetworking (http://afnetworking.com/)
 
 ODRefreshControl - The MIT License. Copyright (c) 2012 Fabio Ritrovato. All rights reserved.
 
 Reachability - Copyright (c) 2011, Tony Million. All rights reserved.
 

