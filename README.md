# DEPI_EUI_GIT_BONUS
# Push a change to multiple repos with one command

reference: https://youtu.be/0v2HxBQ5gLg?si=KkyBPsP5M0To4Vcm


**Create a new repo (DEPI_EUI_GIT_BONUS)**
go to shell and clone the repo: 

- git clone git@github.com:rana-hesham/DEPI_EUI_GIT_BONUS.git
- vim DEPI_EUI_GIT_BONUS/.git/config

* Add the two other repos to it in [remote "origin"]**

```
[remote "origin"]
        url = git@github.com:rana-hesham/DEPI_EUI_GIT_BONUS.git
        fetch = +refs/heads/*:refs/remotes/origin/*
        url = git@github.com:rana-hesham/DEPI_EUI_GIT_TASK2.git
        url = git@github.com:rana-hesham/EUI_tasks.git

```

- git checkout -b multiplepush_branch
- touch multiplepush.txt
- git add --all
- git commit -m "Multi-repo push"
- git push origin multiplepush_branch

Results 

![image](https://github.com/user-attachments/assets/f5588e40-3ea6-479d-97be-a8a1b32fc56a)

![image](https://github.com/user-attachments/assets/a7da4e1a-cfe2-46f4-920b-01facd15da2d)

![image](https://github.com/user-attachments/assets/a4c3eabc-0d83-4610-aa09-ae6673971452)


