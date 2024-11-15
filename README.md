                   __/\__-______-__/\___
                 /    >-     _    -<     \
                 \_/ my-suckless-setup \_/

  Very minimal dwm setup. Cleaned up patches: full gaps, shift 
  tools, attach below, always center. To utilize more  
  functionality of shift-tools, read the shift-tools.c file and 
  add/remove/change bindings in config.h. This is meant to be a
  better "clean slate" for dwm, keeping it mostly vanilla. 
  Quality-of-life changes include: swapped modkey1 (alt) to 
  modkey4 (win), and better key binding optimizations.

  *NOTE* You need Nerd Font Symbols installed to see dwmblock 
  symbols. (go to https://www.nerdfonts.com, create .font 
  directory in "~/" and place the nerd symbol (or any font) files in 
  it.)

  *For Noobs* Compile with "sudo make install" or "sudo make clean install" 
  after downloading or making changes.

  *For Super Noobs* Ensure Dwm is executed at start (may be different if using
  a display manager) touch ~/xinitrc && echo "exec dwm" >> ~/xinitrc
