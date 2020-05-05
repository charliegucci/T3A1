# T3A1 Workbook

## Submitted by: Wilson Esmundo

To view in GitHub <br/>
Please click [here](https://github.com/charliegucci/T3A1)

## Table of Contents

- [Provide an overview and description of a standard source control process for a large project](#Provide-an-overview-and-description-of-a-standard-source-control-process-for-a-large-project)
- [What are the most important aspects of quality software](#What-are-the-most-important-aspects-of-quality-software)

## Provide an overview and description of a standard source control process for a large project

---

Version Control or Source Control lets you track your files over time. So when you mess up we can easily get back to a previous working version.
| # | Functions of Version Control |
| :------- | :-------------- |
| Backup and Restore | Files are saved as they are edited, and we can jump to any moment in time. |
| Synchronization | Lets people share files and stay up-to-date with the latest version.|
| Short-term undo | We can throw away changes and go back to the “last known good” version in the database.|
| Long-term undo | We can jump back to the old version, and see what change was made that day.|
| Track Changes | As files were updated, we can leave messages explaining why the change happened. This makes it easy to see how a file is evolving over time.|
| Track Ownership | We can every change with the name of the person who made it.|
| Sandboxing | We can make temporary changes in an isolated area, test and work out the kinks before “checking in” your changes.|
| Branching and merging | Its like a larger sandbox were we can branch a copy of your code into a separate area and modify it in isolation tracking changes separately. Later, you can merge your work back into the common area.|
<br>

| #                        | Basic Setup                                                                                             |
| :----------------------- | :------------------------------------------------------------------------------------------------------ |
| Repository (repo)        | The database storing the files.                                                                         |
| Server                   | The computer storing the repo.                                                                          |
| Client                   | The computer connecting to the repo.                                                                    |
| Working Set/Working Copy | Your local directory of files, where you make changes.                                                  |
| Trunk/Main               | The primary location for code in the repo. Think of code as a family tree — the trunk is the main line. |

<br>

### Examples:

#### Checkins

![checkins](docs/basic_checkin.png) <br/>
\*\*\* Each time we check in a new version, we get a new revision (r1, r2, r3, etc.) <br>

#### Checkouts And Editing

![checkout_edit](docs/checkout_edit.png) <br/>
\*\*\* If you don’t like your changes and want to start over, you can revert to the previous version and start again (or stop). When checking out, you get the latest revision by default. If you want, you can specify a particular revision.<br/>

#### Difference

![diffs](docs/basic_diffs.png) <br/>
\*\*\* The trunk has a history of changes as a file evolves. Diffs are the changes you made while editing: imagine you can “peel” them off and apply them to a file <br/>

#### Branching

![branch](docs/first_branch.png) <br/>
\*\*\* let us copy code into a separate folder so we can edit it separately.<br/>

#### Merging

![merge](docs/merging.png) <br/>
\*\*\* adds the changes we made from the branch to the main trunk<br/>

#### Conflict

![conflict](docs/conflict.png) <br/>
\*\*\* When changes overlap and contradict <br/>

#### Tagging

![tagging](docs/tagging.png) <br/>
\*\*\* lets us tag revision for easy references.<br>

## What are the most important aspects of quality software

---

## Reference:

---

A Visual Guide to Version Control, Better Explained , https://betterexplained.com/articles/a-visual-guide-to-version-control/ <br/>
