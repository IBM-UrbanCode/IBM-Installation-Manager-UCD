# IBM UrbanCode Deploy IBM Installation Manager Plugin [![Build Status](https://travis-ci.org/IBM-UrbanCode/IBM-Installation-Manager-UCD.svg?branch=master)](https://travis-ci.org/IBM-UrbanCode/IBM-Installation-Manager-UCD)
---
Note: This is not the plugin distributable! This is the source code. To find the installable plugin, go into the 'Releases' tab, and download a stable version.

### License
This plug-in is protected under the [Eclipse Public 1.0 License](http://www.eclipse.org/legal/epl-v10.html)

### Compatibility
	This plug-in requires version 6.1.1 or later of IBM UrbanCode Deploy.

### Installation
	The packaged zip is located in the releases folder. No special steps are required for installation.
	See Installing plug-ins in IBM UrbanCode Deploy. Download this zip file if you wish to skip the
	manual build step. Otherwise, download the entire IBM-Installation-Manager-UCD and
	run the "ant" command in the top level folder. This should compile the code and create
	a new distributable zip within the releases folder. Use this command if you wish to make
	your own changes to the plugin.

### Step List
- **Execute Response File**: Execute a `imcl` response file using IBM Installation Manager. This step can be used to install all products that use the IBM Installation Manager for installation.
- **Install or Upgrade IBM Installation Manager**: Install or Upgrade IBM Installation Manager from a IBM Installation Manager installer.
- **Uninstall IBM Installation Manager**: Uninstall the currently installed IBM Installation Manager.

### History
    Version 4
        Community GitHub Release

### How to build the plugin from eclipse client:

1. Expand the Groovy project that you checked-out from example template.
2. Open build.xml file and execute it as an Ant Build operation (Run As -> Ant Build)
3. The built plugin is located at releases/IBM-Installation-Manager-UCD-vdev.zip

### How to build the plugin from command line:

1. Navigate to the base folder of the project through command line.
2. Make sure that there is build.xml file there, and then execute 'ant' command.
3. The built plugin is located at releases/IBM-Installation-Manager-UCD-vdev.zip
