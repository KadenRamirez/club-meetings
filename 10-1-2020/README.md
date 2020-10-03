# CompSci Club Meeting 10/1/2020

---

## What you should know about Most Online CTFs

- Online CTFs can be found on [CTFtime.org](https://ctftime.org).
- Most CTFs than we will compete in will use [rCTF](https://rctf.redpwn.net), a capture the flag platform devloped by [redpwn](https://redpwn.net), for its scoreboard. 
  - Generally, the only rule is to not hack the scoreboard. 
  - For most online CTFs, there will not be a cap on the number of people we can have per team. However, we recommend that no more than 4 or 5 are on a team for the sake of coordination. 
  - There will only be one account per team for each CTF. Login details are typically shared through a unique login link, rather than a traditional username and password. 
- At some CTFs, the point value of challenges goes down as more teams solve it. This incentivises teams to solve challenges sooner rather than later. 
- In order to receive points for a solved challenge, you must provide its flag. This flag is typically in the format of _flag{coolflagname}_ or _competitionName{coolFlagName}_.

## Simple Linux Navigation Challenge

- A common challenge at CTFs requires one to navigate through a Linux machine in order to retrive a flag. 
- This requires two basic commands for navigation:
  - `ls` = list all of the files and folders in a directory.
  - `cd {directory}` = change the directory to the provided directory. 
- In addition, if you need to print out the contents of a text file, you can use the _cat_ command:
  - `cat {file}` = print out the contents of a text file. 
- Finally, here are some ways you can take advantage of _cd_ to more effectively move around a Linux filesystem:
  - `cd ~` = automatically navigate to the home directory.
  - `cd ../` = move backwards one directory. 
  - `cd ~{username}` = if you are hunting for the directory of a certain user, you can automatically navigate to the user's home directory. 
- If you wish to try a practice Linux navigation challenge, you can try [this](https://github.com/ASMSA-CompSci-Club/club-meetings/blob/master/10-1-2020/linux-ctf-practice.md) from DarkCTF. 
- We will continue to expand upon this Linux commands toolkit as we progress in the year. 
