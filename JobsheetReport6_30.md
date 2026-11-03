# JOBSHEET 6 - CASE STUDY: SELECTION STRUCTURES WITH GIT AND GITHUB

## Student Identity

- Name: Wildan Arya Indradiansyah
- Student ID (NIM): 264107020257
- Class / No. Attendance : TI-1I / 30

---

# 1. Objectives

The objectives of this practicum are:

1. Students can solve case studies using basic and nested selection structures.
2. Students can save and submit their work using Git and GitHub through Visual Studio Code.
3. Students can collaborate with classmates using GitHub.

---

# 2. Labs Activities

## 2.1 Initial Setup (Git and GitHub)

This setup is done once on each laptop or PC. The work in this jobsheet is saved and submitted through GitHub. The Git steps (clone, add, commit, push, pull, sync) are done by clicking buttons in Visual Studio Code. Typing commands is only needed once, to set the Git identity.

### 2.1.1 Steps Done

1. Create a GitHub account at github.com, or sign in if the account already exists. The username and email of this account are used in step 4. (To be completed - write the GitHub username here.)
2. Download and install Git from git-scm.com/downloads. The default settings are used, so Git Credential Manager is included and no token is needed.
3. If Visual Studio Code was open before Git was installed, close it and open it again so Git is detected.
4. In Visual Studio Code, open the Terminal menu and choose New Terminal. Then type these two lines one at a time and press Enter after each line. The text in the quotation marks is replaced with my own GitHub username and email.

```text
git config --global user.name "your-github-username"
git config --global user.email "your-email@example.com"
```

(To be completed - the real username and email are not written here because they were not provided.) If no message appears after pressing Enter, the setup is successful. This step does not need to be repeated on the same laptop.

### 2.1.2 Running Results / Output Screenshot

> Insert the screenshot of the terminal after the two git config commands here. (To be completed - no screenshot has been provided yet.)

---

## 2.2 Experiment 1: Setting Up a Repository

This experiment creates a repository on GitHub, copies it to the computer (clone), and sends the first file to GitHub. The repository name follows the job sheet, PraktikumDaspro plus the attendance number, so the name is PraktikumDaspro30.

### 2.2.2 My repository link

> Insert the screenshots here: the repository creation page, the cloned folder in Visual Studio Code, the README.md file with status U, the commit, and the GitHub page showing README.md. (To be completed - no screenshots have been provided yet.)

Repository link: (https://github.com/wildanarya1209-collab/PraktikumDaspro30.git)

---

## 2.3 Experiment 2: Case Study 1 - Basic Selection

Kedai Kopi Senja sells Kopi Susu Gula Aren for Rp18,000 per cup. A purchase of at least Rp100,000 gets a 10% discount. The program reads the number of cups and the money paid, then calculates the total price, the discount, the total to pay, and the change. If the money is not enough, the program shows how much is still missing. The program follows the flowchart in the job sheet, so the variable names are the same as in the flowchart.

### 2.3.1 Java Program Code

The file is StudiKasus130.java, inside the repository PraktikumDaspro30. The job sheet did not come with a finished code, so this code was written from the flowchart.

```