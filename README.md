#
# cloud
#

This script syncs files between local folders and cloud drive folders.

My primary motivation --- there is currently not a good syncing solution provided by my cloud service providers for linux and my preferred computing platform (raspberry pi).

Dependencies:
* rclone

Example Usage:
* cloud status  - display current status of local folder relative to cloud folder
* cloud pull    - sync local folder with cloud folder
* cloud push    - sync cloud folder with local folder

Todo:
* move configuration file to ./config/cloud/
* move log file to ./config/cloud/
* change local data root folder to ./Cloud/
