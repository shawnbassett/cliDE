# cliDE
A command line interface (cli) desktop environment(DE) all combined to gether to make cliDE!

cliDE was created so you can use a lightweight DE inside the console.  Now I am fully aware you can use the console for just about everything but I wanted to try to make it a little more stylish.
# How to install
First run 
`sudo apt-get install ncurses-dev lynx vim g++`
then run 
`g++ main.cpp -oa.out -lncurses && g++ clidemenu.cpp -oclide-menu -lncurses`
Eventually i will make it a make file.
