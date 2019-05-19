
# Fork from Orange project
# Create single Spyder.app for Mac OS
# Usage: build-macos-app.sh <Path to spyder>.app
## build-macos-app.sh Spyder3.app
## have all basic packages: pandas, seaborn, scikit-learn. Can install other by using pip command inside the application bundle.



Orange macOS application (.app) build scripts
---------------------------------------------

Contents:

python-framework.sh
    Download, unpack and make relocatable the official python.org framework
    installers (used by build-macos-app.sh)

build-macos-app.sh
    Build an Orange.app application bundle from scratch

create-dmg-installer.sh
    Pack the Orange.app applicaiton into a .dmg installer disk image
