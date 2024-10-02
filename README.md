# Azure-Dynamics-DMOC-X45

a repository information regarding Azure Dynamic's DMOC 445 and 645 motor
controllers.

## ccShell

ccShell is the application used to communicate with Azure Dynamic's motor
controllers. Each motor controller has a different `.ccs` file corresponding
with its build number, which contained information used by ccShell to determine
how to communicate with the hardware.

### known build files

`./ccs/` contains all non-custom files I have. If you have any others, please
open a pull request to add them, as they are becoming quite rare!
