# Steins;Gate Archive Decompiler
___________________________________
|     NPA Archives Decompiler     |
|---------------------------------|
|   Italian Steins;Gate VN Team   |
|---------------------------------|
|     New Tool Made by Daviex     |
|---------------------------------|
|   Original Tool Made by Nagato  |
|---------------------------------|
|           Version 1.5           |
|---------------------------------|
|            CodeName:            |
|---------------------------------|
|         El Psy Congroo          |
|_________________________________|

This tool has been re-created from the original one made by Nagato to works with Just USA edition of the game.

This tool was made for the Italian Steins;Gate Project!

If you use it, just mention where you took it from!

# How it works?
At start, I tried to found every information useful to decrypt those files.
No info very useful was found until I took over my hand projects made by Nagato.
There I found his "documentation" about how steinsgate.exe works out.
From that, I found out that it used the same decrypt key on JUST USA Edition.
To write this tool, I based the code of the one made by Nagato. It tooks
the NPA file, and by inverting every bit of the decrypt key, and decrypting
all bytes of the file by using Exclusive OR on every byte. After that, 
I calculates Pointer and, by using a custom struct, I save all files.

# How to make it works?
Move your NPA file over the executable, it will decompile inside the same folder the file.

Enjoy

# Link to Project Forum
http://steinsgatevn.forumcommunity.net/

# Copyright

Copyright (c) 2015 Davide Iuffrida

License: Academic Free License ("AFL") v. 3.0

AFL License page: http://opensource.org/licenses/AFL-3.0
