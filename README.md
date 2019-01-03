# Installing Sublime Text's command line tool 'subl' in terminal for Mac
In the “Terminal” app of Mac, you can type:

    ln -s "/Applications/Sublime Text 2.app/Contents/SharedSupport/bin/subl" ~/bin/subl

ln -s will create a alias of the subl file in your bin directory and you will be able to run the command.

I keep getting permission denied : ~/bin/subl: Permission Denied
Try the following:
     sudo ln -s "/Applications/Sublime Text 2.app/Contents/SharedSupport/bin/subl" ~/bin/subl
 or  
     sudo ln -s /Applications/Sublime\ Text\ 2.app/Contents/SharedSupport/bin/subl /usr/local/bin/subl

You will have to provide a password for the sudo command, but it will work
