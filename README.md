Most of Ruby on Rails developers have a problem to install therubyracer gem in windows environment.
The "therubyracer_for_windows" package provides all the necessary gems and v8.dll to solve this issue. 

Installation steps:

1. Download the package

2. Open the windows command prompt and brows the "therubyracer_windows\" directory

eg:- 

If you download the package in to c:\downloads\, then the path in command prompt should be "c:\downloads\therubyracer_windows\"
you can do it by typing "cd c:\downloads\therubyracer_windows\"

3. Install the ruby gem "therubyracer-0.11.0beta1-x86-mingw32.gem"

This can be done by typing gem install therubyracer-0.11.0beta1-x86-mingw32.gem
eg:-

c:\downloads\therubyracer_windows> gem install therubyracer-0.11.0beta1-x86-mingw32.gem

4. Copy v8.dll & v8preparser.dll in to ruby\bin folder


done...


Enjoy ruby developments more :-)