# PhotoMD CHANGELOG

_**NOTES:**_
 1. Versions containing "alpha", "a", "beta", "b", or "rc" are pre-releases, and
subject to change.
 2. Pre-release versions are not available on the App Store.

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

