### to Add screenshot to shortcuts 
1 - create file and add 
 
  #!/bin/bash

  maim -s --noopengl | xclip -selection clipboard -t image/png

>>>>

2 - write in terminal 

  sudo chmod +x /path/to/file

>>>>

add the file path to the shortcut 

### for the screenshot with save 
 
#!/bin/bash

maim -s --noopengl > /home/zyad/screenshots/screenshot.$(date +%F.%R:%S).png

>>>>



###  to install st terminal 

go to st folder follow instructions but first run 

  sudo apt-get install build-essential libfontconfig1-dev libfreetype-dev x11proto-dev libx11-dev libxft-dev


>>>>>>

### install BTOP for TASK MANAGEER 

### install asdf for node , npm , elixir 
