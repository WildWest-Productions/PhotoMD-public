# PhotoMD CHANGELOG

_**NOTES:**_
 1. Versions containing "alpha", "a", "beta", "b", or "rc" are pre-releases, and
subject to change.
 2. Pre-release versions are not available on the App Store.

## V2.1.1 - July 16, 2020

### SUMMARY
 - This update fixes the "Zoom in" issue
 - Minor updates to UI
 - Fixed issue when "Open with PhotoMD" for an image

### FIXED
 - Fixed issue when zooming in, with a fresh app install
 - Fixed word-correction in alert
 - Fixed menu item: "Star image" when not allowed to star images
 - Fixed issue when "Open with PhotoMD" for an image

## V2.1.0 - July 15, 2020

### SUMMARY
 - This update fixes several bugs, which effect the UI.
 - Added PhotoMD Preferences in menu.

### ADDED
 - Added button to cancel the "loading thumbnail..." prossess
 - Added PhotoMD Preferences
 - Added ability to "load low quality images over 20Mb"

### FIXED
 - Fixed issue when staring a large amount of images, when deleteing all but stared
 - Fixed alert when opening a lot of non-images
 - Fixed some typos in alerts

## V2.0.1 - July 12, 2020

### SUMMARY
 - This update fixes several bugs and crashes, and improves reliability. Specifically when removing an image during, or after processing the thumbnails.
 - Now uses a custom windows to display the help file PDFs (since Preview could edit the PDFs in the app).
 - Detect if the selected file(s) is an image before loading it, and don't load non-images.
 - Improved PhotoMD help PDF, and updated screenshots in App Store.

### ADDED
 - Added file check and alert for opening a file thats not an image
 - Added larger "?" (unknown image) for a missing image

### FIXED
 - Fixed crash when loading a folder, then deleting that folder while processing the image thumbnails
 - Fixed crash when "Deleting all except stared" when loading bar is almost complete

### CHANGED
 - If selecting more then one image, switching next/previous image will cancel multi-select
 - Changed from using Preview to show help file, and third-party licenses PDF, to using custom window. Since a user could edit the PDFs through Preview
 - Updated screenshots in App Store
 - Updated PhotoMD help to explain how to delete all image metadata
 - Disable zoom when selecting more then one file
 - Reset zoom when selecting more the one file


## V2.0.0 - July 10, 2020

### ADDED
 - Added support for dragNdrop (only for input images)
 - Added support for directories (can select whole directories with images)
 - Added tableView for related images, with thumbnails and names
 - Added support for zooming/magnifying an image
 - Added support for editing the image name
 - Added PhotoMD help PDF (can be accessed with Main Menu->Help->PhotoMD Help
 - Added ability to "star" an image
 - Added ability to "delete all exect stared" images (images deleted this way are moved to the users trash bin)

### CHANGED
 - New user inerface

### REMOVED
 - Removed support for undo/redo (may add this later)
 - Removed "Save as..." menu item (may be added back later)


## V1.2.0 - Jun 11, 2020

### ADDED
 - Support for undo and redo
 - Added "Revert all changes" menu item
 - Added menu checkbox to sort image metadata
 - Added new key "ImageDescription"
 - Added support for "Save as..."
 - Added warning if trying to open more then one file
 - Added new bug logo to some alert messages

### CHANGED
 - Select image will no longer be edited as data changes (will need to "Save..." before selected image gets updated)
 - If image is edited, closing the app will automaticly save the image
 - Updated app icon to use a bigger handle
 - Print the image res in X Y order


## V1.1.0 - Jun 4, 2020

### ADDED
 - Available to edit image metadata
 - Added delete selected row, to delete a selected row of data
 - Always will recompress image when editing data
 - Added image resolution label
 - Added "Delete all data" button to delete all image metadata
 - Added warning if trying to edit a unsupported image, eg. RAW images
 - Added warning if trying to add a tag on a image that does not support it
 - Added alert prompt to confirm that the user wants to edit the image (when editing data) (only popups one every app bootup)
 - Added alert prompt if the user wants to delete all image data
 - Reloads the "Image size label" after editing the image data
 - Added combo-box to select a data key to add
 - Added text-field to add a data value
 - Key, and value text fields are automaticly updated as the user selects rows of data from the table view
 - Added always-on checkbox to enable re-compressing image when editing data

### CHANGED
 - Fixed type: `Select a image` -> `Select an image`
 - Main window can no longer be resized

### REMOVED
 - Removed "PhotoMD help" from help menu (will add a help window soon)

## V1.0.0 - May 27, 2020

Init release.

