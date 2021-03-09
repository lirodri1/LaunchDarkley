# LaunchDarkley Feature Flag Demo

Create a new feature flag and name it Luis Demo
The key should default to "luis-demo"
Update line 150 with the ldclient.variation("YOUR_FEATURE_KEY", false);

Run featureflag.html
Green Bubbles will appear as default
A new user will be created under the name of Luis Rodriguez
Enable the feature flag for Luis Rodriguez
Blue Bubles will start popping up on the screen as a representation of a new feature release
Disable the feature and the Blue Bubbles will disappear representing a roll back
