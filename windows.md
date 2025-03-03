# Docker on Windows

## How to Install?
Docker on Windows is mostly used with Docker Desktop. The tutorial for install on requires WSL2.
Follow the instructions in the link to install.
- [Docker Install Instructions (Windows)](https://docs.docker.com/desktop/setup/install/windows-install/)

## How to Use?
**IMPORTANT**
On the Windows operational system, docker does not perform great when there is volums or shared files. When this is the scenario, the container becames very slow and can take many seconds to present a response to the user.

When this is the situation, you need to put your code inside the WSL. This means your code will run completle in Linux and this will improve performance.

This tutotial show how to config docker on windows AND run Docker(Windows) integrated with WSL.
- [Docker Desktop for Windows 10/11 Setup and Tips](https://www.youtube.com/watch?v=rATNU0Fr8zs)

This VSCode extensions allow to edit code inside the WSL container.
- [VSCode - Remote development in WSL](https://code.visualstudio.com/docs/remote/wsl-tutorial)
