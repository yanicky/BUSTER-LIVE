# BUSTER-LIVE
Auto configuration files for creating Debian(Buster) [Live](https://live-team.pages.debian.net/live-manual/html/live-manual/about-project.en.html#76) Bootable System

### Requirement
* git
* live-build

``` sudo apt-get update;```

``` sudo apt-get install git live-build;```

### Installation methods

1. (recommended) ``` git clone https://github.com/yanicky/BUSTER-LIVE; cd BUSTER-LIVE;```
``` ```
2. (other) ``` mkdir BUSTER-LIVE; cd BUSTER-LIVE; lb config --config=https://github.com/yanicky/BUSTER-LIVE```

### Building the bootable ISO image
use the following commands in the base directory to build the iso

```sh auto/config; sudo lb clean; sudo lb build;```

Creating a iso file named live-image-amd64.hybrid.iso of about 346MB.

### Remastering
Optional configuration files are placed in opt/ just copy them in config/proper/subfolder before running the build command.
