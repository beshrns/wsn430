IoT-LAB Git repository
======================

This repository contains the IoT-LAB source code to run experiments on the IoT-LAB sensor network platform.

Description
-----------

The code base contains:

* the wsn430 nodes drivers with examples using them
* a port of different RTOS for the wsn430 nodes:
    * ContikiOS
    * FreeRTOS
    * TinyOS
* Radio communication libraries


Getting updates
---------------

To get the last modifications from the git repository:

        ~/iot-lab$ git pull


Installation
------------

Run the `install.sh` script and copy its output to your `~/.bashrc` file

        ~/iot-lab$ ./install.sh | less
        ~/iot-lab$ ./install.sh >> ~/.bashrc

And reload the configuration

        ~/iot-lab$ source ~/.bashrc



Contributing
------------

The repository is read only, but you can send patches on
senslab-users mailing-list to fix bugs or suggest improvement.
Just remember to tell on which commit they are based.


License
-------

This is the source repository for the WSN430 drivers, and driver application examples.
All source code is provided under the CeCILL license [www.cecill.info] and can be copied, modified and redistributed under its terms.
If you got this archive, it means you have read and agreed with the licence.

All modification to the original source code written by:

- Guillaume Chelius <guillaume.chelius@inria.fr>
- Eric Fleury       <eric.fleury@inria.fr>
- Antoine Fraboulet <antoine.fraboulet@insa-lyon.fr>
- Colin Chaballier  <colin.chaballier@inria.fr>
- Clément Burin des Roziers <clement.burin-des-roziers@inria.fr>
- Gaëtan Harter     <gaetan.harter@inria.fr>

