# Welcome to lc_1st！
## Hello! Welcome to lc's first README file!

I'm not sure about how it might be used.

But, anyway, I will **try** it!!!

# Some **Important** Issue:
## 1. How to make the git bush run:

### - You should **modify configuration** as below:

- ***git config --global http.proxy 127.0.0.1:7897***

- ***git config --global https.proxy 127.0.0.1:7897***

*ATTENTION: Here the 7897 is **my port**.*

### - And when you would like to **cancel configuration**:

- ***git config --global --unset http.proxy***

- ***git config --global --unset https.proxy***

To **check** if you have already cancel configuration, you can do as below:

- ***git config --global http.proxy***

- ***git config --global https.proxy***

-> If nothing was output, then you have already reach your goal. 

-> Otherwise, please repeat the process until it passes your check.

## 2. How to **clone** and **push**

### - How to **clone**

You should firstly check the http of your targeted repository and copy the *HTTPS (reposity adress)* in the part of *code*.

- ***git clone REPOSITY_ADRESS***

### - How to **push**
- ***git add RILENAME.FORMAT***

- ***git commit -m "WHAT YOU WANT TO MARK"***

- ***git push***