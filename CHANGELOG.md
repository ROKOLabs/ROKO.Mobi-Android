## Version 1.12.0.0 (June 21, 2017)
- Initial upload of ROKO Mobi SDK .aar on GitHub
- Updated InstaBot 2.0 UI
	- More polished outlines for multiple choice options and images
	- Standardized InstaBot icons to squares
	- Beautified the layout for the description and selection text for rich media cards 
	- Added grey borders around all images	
	- Descriptions accompanying rich media images will be overlayed on top of image
- Added support for ingesting a custom property from the user and immediately returning it back to the user in a prompt within the same conversation
- Added support for animated gifs

- **Bug Fixes**
- Fixed issue of InstaBot rich media images not appearing 
- Fixed crash when opening animated gif
- Fixed out of memory crash when opening InstaBot multiple times
- Fixed various minor UI issues
- Fixed format issue when displaying integers and dates
- Fixed issue of InstaBot background opacity not being set correctly as configured in the Mobi portal
- Fixed issue of the InstaBot launching for more times than configured in the Mobi portal
- Fixed issue of InstaBot conversations not scrolling all the way down under certain situations