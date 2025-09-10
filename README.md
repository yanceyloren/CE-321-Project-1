# Purpose
This repository is a place for students to test their answer submissions for Project 1 of Brigham Young University's CE 321, Structural Analysis, class.
Students should duplicate this repository (as a template, rather than forking it) and then use it to test their answer submissions.

# Setup
To interact with this toolset, you will need to create an account on GitHub if you do not already have one. To learn how to create an account, click [here](https://docs.github.com/en/get-started/start-your-journey/creating-an-account-on-github).
You may want to create this account using your BYU e-mail address, though that is not necessary.

After creating an account, navigate back to this repository. Then, near the top right of the webpage, click the button "**Use this template**" and select "Create new repository."
**Do NOT fork this repository.**
(If you do not see the "Use this template" button, try logging into your GitHub account before navigating to this repository.)
After selecting "Create new repository," you will then be asked to give the repository a name (e.g. CE_321_F25_Proj1)
You will also be asked whether to make your repository public or private. **Make your repository private.** If you accidentally make it public, you will need to start over with a private repository.

# Uploading Submission Results
After duplicating this repository as a private repository, you can interact with it in a number of ways.
The easiest way is simply to edit files online.
You will only need to edit one file to submit your assignment: project_1_submission.txt.
To do so, click on it and type in your answer for each question after the two colons.
In other words, if my answer for Question 1 were "T," I would find "Q1::" and type "Q1::T"
You may need to enable the editor to be able to modify this file, which is fine.
When you have finished inserting your answers, click on "Commit changes..."
You may either finish the entire answer submission document in one sitting or finish parts of it at a time, committing changes as you go.
Do not edit any other files.

Alternatively, anyone who is comfortable with command line and has used git repositories before may prefer downloading this to their machine, filling in data locally, and then uploading their submission.
Additional instructions on how to proceed in this manner will not be given, but you can look online to find out more.

The project_1_submission.txt file also includes a header "PartialCredit::" line at the top.
If you would like to see your results purely based on input answers (similar to Learning Suite), type "F" after the double colon.
If you would like to be graded using partial credit from your previous answers (some of which may or may not be correct), insert "T".
Your final grade will be based on the "T" setting for partial credit.

As an aside, there is no doubt that you will be able to break this testing software.
The purpose of this is to allow you to check your results prior to submitting your final answers.
The software will probably fail if you insert funny characters, use the "Enter" command in the middle of a question, put in words where a number is expected, etc.
If you treat it nicely, it should perform well for you.
If you believe that your submission should be performing correctly and it is not, please contact the instructor for assistance.

# Checking Submission Results
Once you have edited "project_1_submission.txt" and committed the changes, navigate to the "Actions" tab near the top left of the webpage.
The topmost workflow run is testing your submission against the grading software.
It should complete the testing within ~20 seconds of submitting your results.
If a green check mark is to the left of the workflow, you did not break the software. 
Otherwise, a red checkmark will indicate that something broke and that you should alter your submission file.
If it ran successfully, click on your most recent submission test, then click on "build" and then "Test Submission."
This is the output of the grader, and it will indicate whether your answers are correct or incorrect, how much partial credit you get on each quesiton, and what your total score is.
If you are happy with your score, please download your "project_1_submission.txt" file and submit it on Learning Suite with your handwritten and/or Excel document demonstrating your work.
Otherwise, please modify your "project_1_submission.txt" file as appropriate to correct your answers.

# A Note on Grading
As you may recall, the intent of the software is to give you as much partial credit as possible.
If you make a mistake on one problem (e.g. a load) and then that problem is used for subsequent calculations, you will be docked for missing the initial problem, but then your submitted result will be considered the correct
answer for subsequent problems.
This way, if you understand the material but make an error early on, you will still receive a high score (as opposed to getting every question wrong thereafter).
However, this means that if you make a typo on one question but have correct answers thereafter, all of these correct answers may be marked as incorrect.
If you want to fix your score or are confident that some of your answers that are marked incorrect are truly correct, please scroll to the first problem you missed on the grader and fix it before considering subsequent questions.
If you prefer using the program to give results only based on the current answer (rather than previous answers), ensure that your PartialCredit setting is set to "F".
However, your final grade will be evaluated using the "PartialCredit::T" setting.

Finally, remember that your final results will be submitted on Learning Suite.
If you try to game the system, your final results may be much lower than what is reported here.
Otherwise, if you use this tool properly and submit images where requested, your final score will likely be very similar to the score you see here.
