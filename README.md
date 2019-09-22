NodeMCU-control
===============

integrate NodeMCU modules with home control

### About

### TO DO:
- [X] add system reboot button using "exec" node on System Menu page
- [X] update libraries 9/21/19
- [ ] split PWM configuration into a separate module
  - MAIN menu
  - make it wider to make frequency and pwn slider more control
- [ ] consider making MAIN module "shorter" to allow module to better fit screen

### Recent changes
- refreshed libraries 

### PROBLEMS
- git credentials don't work so a push does not work
  - CAUSE: git password was entered incorrectly
  - [git credential problems](https://discourse.nodered.org/t/unable-to-retry-username-password-for-remote-git-repository/14842)
  - restart node-red 
      - credentials are reset after reboot
