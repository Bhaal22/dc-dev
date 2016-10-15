# dc-dev: Dreamcast Environment inside Docker containers

![alt text][dc-logo]

[dc-logo]: https://github.com/Bhaal22/dc-dev/blob/master/resources/Dreamcast.png "Dreamcast Logo"

# Container Creation
 * 1st intermediate container : Build the gcc toolchains for sh-elf and arm
 * 2nd intermediate container : Build KallistiOS / KOS Ports and dcload-tool
 * 3rd container: Contain all binaries to compile dreamcast binaries and upload tools
 
 

