---
layout: post
title: Welcome to Sakariya's Data Science Blog
---








Have you ever tried to write a long report on your computer, and after making many changes, you realized that you have deleted important information and got things messed up? Or if you are a programmer, was there a time that you altered some lines in your code and you started getting more errors and your program wouldn't run anymore? In these critical situations, you probably ended up pressing Ctr + Z hoping to revert back to your previous correct version of your work. Even if you were the most careful person, you may start making a backup copy of your file before starting to edit. With this, you end up having a stack of filenames for the same document as shown below. You understand that this is a total mess. But the problem you are having is called Version Vontrol, and the solution is what Git is all about.
Without version control
Uday (2018) said:
“Developed by Linus Torvalds in 2005, Git is a distributed version control system. Using Git, many developers can make changes to the same code base at the same time without running into accidents like overriding someone else’s changes. Git will only update the differences made to a file”. https://bit.ly/2tkSa9d.
So, lets deep dive into what Git is and how it actually solves the above problem. Most of us have used at least one of the currently existing cloud storage services such as Google Drive, Dropbox, OneDrive, etc. We will use this as an analogy to explain how exactly Git works. Let’s say you are a graduate student at University of British Columbia (UBC), Vancouver campus and your supervisor asked for the submission of your thesis. In most situations, this is how you will go about it:
You will probably create a draft version of your thesis report.
Draft vs Final
Then change draft to a final version of your document, or sometimes end up making changes to your final version at the last minute and end up renaming it to “very final” with the current date.
Then if your document is very important, you start uploading a copy of it into Google Drive, Dropbox, etc. for safety in case something happens to your computer.
If you happen to be very familiar with all the above three steps, then that is amazing, Git is not far from what you were already doing.
Git Steps
Source: Blischak JD, Davenport ER, Wilson G (2016) A Quick Introduction to Version Control >with Git and GitHub. PLoS Comput Biol 12(1): e1004668. doi:10.1371/journal.pcbi.1004668
You had a “Draft” in your local computer, GIT uses a “Local Repository”
You had a “Final” document in your local computer, Git uses a “Staging Area”
You uploaded your report into “Dropbox”, git uses a “Remote Repository”, e.g. GitHub.
You could be surprised of the term “Repository”, that is totally fine and you are not alone. But a repository is just a folder residing inside Git, nothing more. Really! yes that is right. All we are doing is to switch the terminologies here as follows:
Version Control --> Git system
Draft --> Local Repository
Final --> Staging Area
Dropbox --> Remote Repository
In simple terms, the workflow you were used to before just changed from:
Draft --> Final --> Dropbox
to
Local Repository--> Staging Area --> Remote Repository
And if you have encountered the word Git before, you would have probably seen GitHub too. They appear similar but don’t be fooled, they are totally different things. It is a common mistake among many people who are new to Git, hence you are not the only one. In simple terms, Git is like the “undo” function in your Ms. Word document but has the additional capability to track changes in an entire project instead of a single file. On the other hand, GitHub is an online storage platform like Dropbox which hosts projects that multiple contributors can work on it at the same time. GitHub then creates a log for all the ‘undo’ processes and avails it to all the contributors.
So now that you have some idea about Git, it is simply a version control system (VCS) that keeps track and manages changes made to your project. For example, if you and your colleagues are designing a website and you both unknowingly start updating the same page, one of you will have their work overwritten, right? That is true under normal circumstances. Fortunately, Git doesn’t allow that to happen. Git will save two copies of the changes and show a message to let you view both changes and give you the option to reject or merge the changes. This is super amazing, right. This is what the version control of Git is all about. Git takes and stores snapshots of all the changes made to your project. Thus, you can revert back to any of your previous versions anytime.
You can now visualize how Git operates using the diagram below (Reshma, 2017). http://bit.ly/2msp9s7

Git add --> simply means, adding your file from Draft to Final as we indicated in the analogy above.
Git commit -m --> saves all the changes in the Final folder in your local computer.
Git push --> uploads your local folder to online repository, e.g. Dropbox (but would be GitHub in this case).
Git pull -- > downloads content from the remote online repository.
Congratulations for reading up to this point. Get started with using Git as your version control system for your future projects, I believe you will definitely appreciate its great benefits.



Below is my github repo, you may follow for regular updates on latest trends on the Data Science.
 [Sakariya's Blog Repo](https://github.com/eyrakas/eyrakas.github.io) on GitHub.