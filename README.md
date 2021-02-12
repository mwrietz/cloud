# cloud

This script syncs files between local folders and cloud drive folders.

Primary motivation --- my cloud services do not provide a good syncing solution for linux and my preferred computing platform (raspberry pi).

## Dependencies
* rclone
* tree

## Example Usage
* cloud status  - display current status of local folder relative to cloud folder
* cloud pull    - sync local folder with cloud folder
* cloud push    - sync cloud folder with local folder

## Todo
* verify if sync_log exists on first cloud account
* create sync_log.txt if doesn't exist 
