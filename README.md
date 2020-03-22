# Operation System Design and Implementation Course 2020

[中文](讀我.md)

This repository is homework submission for students

## How to submit homework

1. Fork [this repository](https://github.com/GrassLab/osdi2020) on GitHub 
    ![](images/fork_button.png)
2. Write down following info in your `README.md`
    - GitHub account name
    - Student ID
    - Your name
3. Design and implement your kernel in forked repository
4. Create a GitHub pull request
    - Choose `GrassLab/osdi2020` as base repository and `{your student ID}` as base branch
    - Choose branch in your forked repository as compare branch
    ![](images/PR_branch.png)
    - Name it with student ID and which lab e.g. `0756110 lab0`
    ![](images/PR_name.png)
5. We will accept pull request when lab due date

repeat 3-5 to submit later homework/lab.

### Example

- forked repository: https://github.com/csielee/osdi2020
- pull request: https://github.com/GrassLab/osdi2020/pull/2

## How to demonstrate homework for TA

### Before the demonstrate
- Send pull request from your forked repository
- Fill one time slot in the demostrate schedule

### In the demonstrate

#### Prepare
1. Type `queue` in the TA's chat room on [gitter](https://gitter.im/GrassLab)
2. TA will send private message with url/link when your turn
3. Type your student id in private chat room
4. Click the url/link and then share your screen

#### Demonstrate and Explain
5. Demonstrate what you implement in `required` and `elective` with your test data
6. TA ask some details about implementation
7. TA ask `question` in the documentation
8. If you stuck in any step `5, 6, 7`, you can go back to setp `1` after you solve the issue (just like `context switch`)
    - No any penalty on your score

### After the demonstrate

- Check your result record in private chat room with TA. May like this:

| Lab0 | 李東霖 | 0756110 | 2020/01/01 11:11 | 
| --- | --- | --- | --- |
| R1 | Q1 | Q2 | E1 |
|Excellent|Yes|Yes|Yes|

- 4 state in your `required`
    - `Excellent`
    - `Good`
        - Can't run on real rpi3, but run on QEMU
    - `Poor`
        - Can't work at all or explain how you do and why
    - `Fail`
        - Can't demonstrate anything for TA
- 2 state in your `elective` and `question`
    - `Yes`
    - `No`
- If find any problem with record, please tell us as soon as possilbe

## Happy Coding ~