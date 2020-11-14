# Theme park website
A collaboration on creating a website for a theme park.

## Structure
1. Home page
2. Details page
3. Supporting features page

## Workflow

### Pull requests and approvals
* We will follow the [standard Github workflow](https://guides.github.com/introduction/flow/).
* Please create a **feature** branch from the **main** branch in order to develop features in this project.  
E.g. In the terminal, execute this command to create a feature branch called **logo** from the **main** branch:  

```
git checkout -b logo main
```

* The **main** branch is a protected branch; to make a contribution to the **main** branch branch, create a *pull request (PR)* from a **feature** branch.  
* Once a PR is created, another member will need to approve it before the code can be merged to the **main** branch.
* The reason for this is to control the code in the **main** branch and avoid conflicts for all other developers who are working on the project.  

### Rebasing
* Once a PR is merged to the **main** branch, all other **feature** branches will need to be rebased to the **main** branch to update with the latest code.  
E.g. If you are working on the **logo** feature branch, and another developer merged code to the **main** branch, to rebase your **logo** branch to **main** for the new code, in your terminal ensure that you are on your **logo** branch and execute execute:

```
git rebase main
```

* *Without rebasing, **code conflicts** will occur on your branch so please ensure you rebase your **feature** branch before continuing to work on your feature or making your own PR to the **main** branch.*  


## Collaborators
* Anoop Bains
* Gulshan Ara Nawshin
* Marianna Siembiot
* Preda Anu
* Ved Prakash Pandey