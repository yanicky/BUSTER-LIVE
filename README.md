# BUSTER-LIVE
Auto configuration files for creating Debian(Buster) Live-Build Bootable System

### Requirement
* git
* live-build

``` sudo apt-get update;```

``` sudo apt-get install git live-build;```

### Installation

``` git clone https://github.com/yanicky/BUSTER-LIVE;```

### Building the bootable ISO image
use the following commands in the base directory to build the iso

``` cd BUSTER-LIVE;```

```sh auto/config; sudo lb clean; sudo lb build;```

Creating a iso file named live-image-amd64.hybrid.iso of about 346MB.

Optional configuration files are placed in opt/
