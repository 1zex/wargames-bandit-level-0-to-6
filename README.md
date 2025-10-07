# wargames-bandit-level-0-to-6
Hi this is my second time doing that i finished networkchuck guide on linux and python and now i try something else that regroup almost everything i learned even more so pls if you have any advice so i can be better again and again feel free to share it with me!

---

 the site where i trained is very famous in this world because it's **[wargames](https://overthewire.org/wargames/bandit/bandit0.html)** 






**[LEVEL 0](https://overthewire.org/wargames/bandit/bandit0.html) :**


the first level **(the [level 0](https://overthewire.org/wargames/bandit/bandit0.html))** was pretty simple because you just had to connect into game by using `**ssh**`.


when you read the information that'd be given to you you could normally do it by yourself with no problem.


the command for doing that was : ssh bandit0@bandit.labs.overthewire.org -p 2220 after connecting it ask you the password and if you read you'll see that is the same as the username so bandit0.


Congratulations you finish the level 0 now let's go for level 1!





**[LEVEL 0 > 1](https://overthewire.org/wargames/bandit/bandit1.html) :**


the level 1 is also express. After being connected on the site they will ask you tu find a password inside a `**readme**`. The fist thing i did was typing `**ls**` after typing it i saw a readme file so i `**cat**` him (i do : `**cat readme**`)


and it texted me some congrats and give me the password. Because the game told me to store it in case the password change i opened a new terminal and create a new directory named wargamepasswd ( id did it by doing this command


mkdir wargamepasswd; echo `**(the password that'll be gave to you)**` > passwdlvl1.txt). 





**[LEVEL 1 > 2](https://overthewire.org/wargames/bandit/bandit2.html) :**


at this moment i asked for help because i couldn't find the - directory but i was dumb after finish 1 level you have to type exit to quit the game then enter to the next lvl by changing the ssh adress with the number of the lvl 


you currently achieve and by giving with that the password you just unlocked..


after realising it i change bandit 0 by 1 to reconnect again and it worked! it's asking me a password i put the one i just find and i'm in.


this lvl was very easy because i just learned it a day ago and it was to open/cat the file `**-**` yes the `**dash**` and to do that i just do : `**cat ./-**` yeah that's it i just got my second password in a second 





**[LEVEL 2 > 3](https://overthewire.org/wargames/bandit/bandit3.html) :**


for the third level i didn't know the anwser but i acted with my l ogic and it worked so i assume i have a great logic for cyber and i'm feeling grateful about that. but let's focus as the same as the previous level and for the 


next coming i exit the level 1>2 to reconnect but on the level 2>3 and i put my new unlocked password.


this level had spaces in his filename and dashes. at a first look it seems hard but just like the previous one i started by doing `**cat ./**` but right fater that if added  some `**coma "**` and looks like it worked very fine


because i just gained the password for the nxt level!





**[LEVEL 3 > 4](https://overthewire.org/wargames/bandit/bandit4.html) :**


for th is level you just have to remember the basics. the file was hidden from us in the dir inhere so to check all that i started enter in the i nhere dir by doing `**cd inhere/**` then when i was is i typed `**ls**` but nothing come out


so i did `**ld -a**` to show all the files and dir inside and there it is i find my due. the file was named `**...Hidden-From-You**` so you can see it has dot but no worries to cat him you just have to do as always because he also has text 


and no space so you do `**cat ...Hidden-From-You**` and there it is you have your code and you stok him in a file for later great job!





**[LEVEL 4 > 5](https://overthewire.org/wargames/bandit/bandit5.html) :**


well they said the passwd was on the only human-readable file in th inhere dir so i just logged in type `**ls**` saw the inhere dir the `**cd inhere/**` re type `**ls**` saw 9 file all of them started with a `**-**` so cat instantly cat them with 


this command `**cat ./-files00**` and so on i do all of them i find the only readable passwd in the seventh file i stock it but in case i'm loosing something else i do all of them but nothing happen so i was ok it was just a memory lesson


i think but it's always good to do some exercices like that to not loose the hand





**[LEVEL 5 > 6](https://overthewire.org/wargames/bandit/bandit6.html) :**


the last one but for today but the harder and i definitively search that up on [internet](https://manpages.ubuntu.com/manpages/noble/man1/find.1.html) but just how the find works i know i could use the command `**man**` but i just like


command `**ctrl+g**` it's way easier and to stop speaking about my life to find the directory because there were a loooooot of files i do this command with the help of the site but it's the same if you use man : `**find . -type f -size 1033c ! -executable**`


and it find me a file with the password.





Finally we reached the first part, there is 28 other to do but that was great. Thank's for reading that, the advices, and everything will find maybe next time! 
