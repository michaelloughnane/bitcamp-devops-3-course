# Welcome

A quick note of caution!

This course requires your name to not contain any capital letters! It causes an error down the line. If your username contains a capital letter, it's recommended to change it now.

### Setting up CI Workflow

#### What is CI?

First, take a moment to examine the image below. It shows the relationship between **continuous integration**, **continuous delivery** and **continuous deployment**.

![](https://i.imgur.com/xZCkjmU.png)

**Continuous integration** (CI) is a practice where developers  integrate code into a shared branch several times per day.  The shared branch is sometimes referred to as **trunk**, but on Git, it's named **master**. To integrate code, developers **commit** on other Git branches, **push** their changes, and **merge** to master through **pull requests**. 

Automated events take place throughout this process. These events can range from running tests or deployments to cross-linking to relevant threads. Here's an example that we will use:

- Source code goes through an automated build process if necessary
- Automated testing of the software takes place
- Reports are generated and sent back to the developers with the status of their changes

**GOAL:** Regular code integration enables faster and easier error detection.

### Why do we need this?

**Continuous delivery** (CD) is the natural "next phase" of **continuous integration** (CI). Setting up a CI workflow will show us the entire picture of our workflow.

