# Important Points to know about Revisions and the Cloud 

* Version Control mainly used to record all the changes that happened to a document, so you can restore any time and any version you have made of your document 
* Local Version Control maintains track of files within the local system.
* Centralized Version Control is way for a developer team to collaborate on a single file or set of files and this system entails a single server storing all changes and file versions.
* Distributed Version Control The clients completely clone the repository including its full history. If any server dies, any of the client repositories can be copied on to the server which help restore the server.
* Git is a Distributed Version Control System 

# Setting up a Git Repository

* $ cd test (cd = change directory)
* $ git init
* $ git add *.c
* $ git add LICENSE
* $ git commit -m “any message here”
* Cloning $ git clone https://github.com/test


# The Life Cycle of File Status
![img for life cycle of file sratus](https://www.udemy.com/blog/wp-content/uploads/2015/08/image006.png)


# Local Repository Structure<br>
**The local Git repository has three components:** <br>

1. *Working Directory: The actual files reside here.*
2. *Index: The area used for staging*
3. *Head: Points to the most recent commit*

# Workflow
![img for workflow](https://www.udemy.com/blog/wp-content/uploads/2015/08/image036.png)

