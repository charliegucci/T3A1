# T3A1 Workbook

## Submitted by: Wilson Esmundo

To view in GitHub <br/>
Please click [here](https://github.com/charliegucci/T3A1)

## Table of Contents

- [Provide an overview and description of a standard source control process for a large project](#Provide-an-overview-and-description-of-a-standard-source-control-process-for-a-large-project)<br/>

- [What are the most important aspects of quality software](#What-are-the-most-important-aspects-of-quality-software)<br/>

- [Outline a standard high level structure for a MERN stack application and explain the components](#Outline-a-standard-high-level-structure-for-a-MERN-stack-application-and-explain-the-components)<br/>

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

The following aspect will measure the quality of a software but depends upon the projects on which part they can prioritize more.

| #                 | Important Aspect of Quality Software                                                                                                                                                                                                                                                                                                                                                     |
| :---------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Reliability       | Software will be considered reliable if it behaves consistently. The functionality of a program should be predictable and repeatable. Errors should occur rarely or not at all. Errors that do occur should be handled gracefully and proactively. Users should never ask themselves whether the software will work correctly.                                                           |
| Understandability | Code, its component and structure must be clear, understandable and well organized. They must behave the way a developer would expect. Anything in the code that causes developers confusion reveals that the code is lacking in understandability. High-quality source code always appears simple and obvious.                                                                          |
| Modifiability     | It should be easy to add or change the behavior of a system. Flexible systems require changing very few lines of code to alter a behavior. For the expected dimensions of change, an application should have plugin points that allow the application to be used with different contextual elements. Tight coupling to an element that is expected to change is absolutely unacceptable. |
| Usability         | Software products must be simple and easy to use. The common use cases should be as obvious and clearly presented as possible. Software should not require excessive configuration. Users should feel empowered by your software. They should not need internet searches to discover core application functionality.                                                                     |
| Testability       | The functionality of software must be verifiable. The process of testing the software must be easy. Each business use case should be directly testable. Clear verification metrics must be available. Highly testable software will ship with a comprehensive automated test suite.                                                                                                      |
| Portability       | Portable software is usable in different environments and contexts. It is highly reusable. Portable software is decoupled from specific operating systems, types of hardware, and deployment contexts. Extremely portable software is reusable across projects and problem domains.                                                                                                      |
| Efficiency        | Efficient software uses as few physical resources as possible. It is fast. It is memory-efficient. It consumes few CPU cycles. It uses little battery life. It makes few external service calls. It minimizes the number of database calls. Efficient software accomplishes as much as possible with the least amount of resources.                                                      |

<br/>

## Outline a standard high level structure for a MERN stack application and explain the components

---

![mern](docs/mern.jpg) <br/>

MERN stack is the combination of technologies used to create a web application. Any web application will be made using multiple technologies (frameworks, libraries, databases etc).

The main advantage for developers using the MERN stack is that every line of code is written in JavaScript. This is a programming language that’s used everywhere, both for client-side code and server-side code. With one language across tiers, there’s no need for context switching.

The MERN stack is a JavaScript stack that’s designed to make the development process smoother. MERN includes four open-source components: MongoDB, Express, React, and Node.js. These components provide an end-to-end framework for developers to work in.<br/>

| #       | Components                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| :------ | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| MongoDB | A cross-platform document database. It is a NoSQL (non-relational) document-oriented database. While conventional relational databases have a typical schema design based on columns and tables, MongoDB is schema-less. Data is stored in flexible documents with a JSON (JavaScript Object Notation)-based query language. The content, size, and number of fields in the documents can differ from one to the next. This means that the data structure to be changed over time.                                                                                                                                                                                       |
| Express | A back-end web application framework. It is a web application framework for Node.js, another MERN component. Instead of writing full web server code by hand on Node.js directly, developers use Express to simplify the task of writing server code. There’s no need to repeat the same code over and over, as you would with the Node.js HTTP module. The Express framework is designed for building robust web applications and APIs. It’s known for its fast speed and minimalist structure, with many features available as plugins.                                                                                                                                |
| React   | A JavaScript library for building user interfaces. It was originally created by a software engineer at Facebook, and was later open-sourced. It is maintained by Facebook, as well as a community of development companies and individual developers. Its library can be used for creating views rendered in HTML. React views are declarative. This means that developers don’t have to worry about managing the effects of changes in the view’s state or changes in the data. Instead of relying on templates to automate the creation of repetitive HTML or DOM elements, React uses a full-featured Javascript to construct repetitive or conditional DOM elements. |
| Node.js | A cross-platform JavaScript runtime environment. It was initially built for Google Chrome, and later open-sourced by Google in 2008. It is built on Chrome’s V8 JavaScript engine. It’s designed to build scalable network applications, and can execute JavaScript code outside of a browser. Node.js works without an enclosing HTML page, instead using its own module system based on CommonJS, to put together multiple JavaScript files.                                                                                                                                                                                                                           |

<br/>

## Reference:

---

A Visual Guide to Version Control, Better Explained , https://betterexplained.com/articles/a-visual-guide-to-version-control/ <br/>

The Seven Aspects of Software Quality, Silas Reinagel, https://www.silasreinagel.com/blog/2016/11/15/the-seven-aspects-of-software-quality/ <br/>

Everything You Need to Know about the MERN Stack, Hyperion Development, https://blog.hyperiondev.com/index.php/2018/09/10/everything-need-know-mern-stack/ <br/>
