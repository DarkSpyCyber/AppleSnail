# AppleSnail
-=the easy file transfer=-

v0.2 2020.12.1

1. added customize port support
2. fixed bug of list file

v0.1 by DarkSpy

1. wrotten in Ruby
2. packed to windows exe file
3. compiled to native code

here's howto:

AppleSnail. the File Transfer Tool by DarkSpy v0.2<br>
2020/12/1 Options:<br>
server [P# port=9527 default]-> to run server<br>
send IP filename [P#] -> to send file to IP which was run server<br>
list IP [P#]          -> to list file what in AppleSnail's current folde<br>
recv IP filename [P#] -> to recv file from IP which was run server<br>
for example: ruby applesnail.rb server [P8081]<br>
             ruby applesnail.rb recv 111.222.244.34 pack.rar [P8081]<br>
             ruby applesnail.rb send 111.222.244.34 myfile.rar<br>
