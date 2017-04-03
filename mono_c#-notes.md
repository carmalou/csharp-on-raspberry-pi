1. ssh into raspberry pi
2. install mono
`sudo apt-get update`
`sudo apt-get install mono-runtime`
`sudo apt-get install mono-complete`

3. get a text editor
`sudo apt-get install emacs`
** usually I prefer atom or idk, something I can *see* but since I'm remoting into my raspberry pi via the terminal on my mac, I need something I can use in the terminal. don't @ me

** forget about this. I just ended up using nano instead because emacs was too much for me!

4. write your program

5. compile to .exe
`mcs HelloWorld.cs` --> `HelloWorld.exe`

6. Run that shizz
`mono HelloWorld.exe` --> "Hello Mono World"

** BOOM **



<!-- 1. install .net core
2. install VS code if dev'ing on mac
3.  -->
