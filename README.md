# Ikarus Visual SPS project
_The full SPS project of Ikarus_

This package provides several templates to be extended into your custom SPS project.
## Usage
````bin
$ composer create-project ikarus/sps-project -sdev ./my-sps-project
````
Start the SPS on your device:
````bin
$ cd ./my-sps-project
$ php ikarus.php &
// OR
$ sudo php ikarus.php &
````
Then if the SPS is running, you can launch the visualizer webserver:
````bin
$ cd ./my-sps-project
$ php -S localhost:8080 Public/skyline.php
````
Of course you can choose another port, but update the Skyline's project xml files.
    