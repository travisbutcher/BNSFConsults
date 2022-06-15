# BNSFConsults
Sharing for BNSF

Python Question from Chris Kerzman to generate a buffered offline content around a subdivision. 6/15: Travis was unable to reproduce the issue, but is investigating further

OIDC + OAUTH https://developers.arcgis.com/documentation/mapping-apis-and-services/security/oauth-2.0/ 6/15: Have the same issue with another ESRI client. Tricky to substitute the OIDC token in the place of the OAuth token, but there may be a way to override the native ESRI OAuth Authorization handler. May need to take this up with the ESRI and BNSF security team together as a separate call. TB is trying a few code changes

Bluetooth pairing and increasing accuracy using secondary sources such as RTK https://developers.arcgis.com/ios/swift/sample-code/display-device-location-with-nmea-data-sources/ 6/15: No further information needed from ESRI/TB. Need to research if Trimble has an iOS SDK to include in the project to pull information from Trimble directly without having to install a second Trimble iOS application. Search for “Trimble Access”

Debug Legend display issue. 6/15: Vamsi sent code to Travis. TB will debug offline
Roadmap (Distance calculation, AI/ML) 6/15: TB looking for a sample to calculate distance along the track center line
Sample code/repo to calling multiple feature layers simultaneously to show content in a particular subdivision 6/15: TB sent example: https://gist.github.com/travisbutcher/cb455086a37f4d8d4e35b4a54f6ca2ec [gist.github.com]
Sample code/repo to create geometry objects 6/15: Search for CreateGeometriesViewController in the esri runtime samples repo
Sample code to fetch the geometry of a feature and display it (Ex: SubdivisionBuffer) 6/15: Search for FLQueryViewController, FeatureCollectionLayerQueryViewController, TimeBasedViewController in the esri runtime samples repo. Search for “QueryFeatures” in the samples repo
Sample code/repo to create spatial queries 6/15: Search for QueryMapImageSublayerViewController in the esri runtime samples repo
Sample code to switch between maps (US map and detailed Subdivision map) 6/15: Search for OpenMapURLViewController in the esri runtime samples repo
Is there a JS Extent equivalent in iOS 6/15: Most geometries have an extent object in them. You can however, you can create your own. TB to send a link to a sample repo
Is there a way to fetch the extent of a feature layer as a whole. 6/15: Yes, TB working on sending a sample repo
Administrative: We may save the consults on 6/20, 6/22 depending on how we progress on 6/17. If we decide to save the two consults, we will use them when Travis is back from vacation
