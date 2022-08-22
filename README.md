# practice-go
To practice Go programming language which is fast and easy to learn.

# Installation
Install Go using homebrew.
```shell
> brew install go
```

Creates pkg, bin, and src directories.
```shell
> mkdir pkg bin src
```

Install Visual Studio Code ([Link](https://code.visualstudio.com)).  
Install Visual Studio Go Plugin in market.
![image](https://user-images.githubusercontent.com/33278794/185820482-c6631c80-7ffa-4eb3-95b3-e5442b1ba0a0.png)

Update Go Plugin
Cmd + Shift + P, then Select All.
![image](https://user-images.githubusercontent.com/33278794/185820495-519f0657-c850-428c-80b7-62a0acd93ff0.png)

# Add environment
It doesn't work when run Go script in Visual Studio Code at first.
Let's update Go environment using `env`command
```shell
> go env -w GO111MODULE
```
Then run the script again. It should work :D



