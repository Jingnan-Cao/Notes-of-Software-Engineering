# Version Control
## Why we need version control?


- Version Rollback

	Record the sequent evolution of software development.

	Revert selected files even entire project back to a previous state.

- Developers Cooperation
	
    Allow a number of clients check out files and merge changes.
    
    Compare change overtime.

- Version Dependency and Conflicts

	- [yang's block "why we need version control and virtual environment?"](http://blog.yangliu.online/2016/07/29/when-do-we-need-revision-managing-and-virtual-environment-md/)
    
    - rbenv for ruby

## How Git does version control?

Git, a distributed version control system.

- Data Repository

	Clients fully mirror project repository, get data from git, modify and copy back.

	Git is where Rails stored in.

- Version Record and Rollback

	I think the way Git records version evolution is kind of similar to how database work. In git, each record is a whole project repository including fully history. Each "git pull" inserts a record. The project version rollback is kind of just revert to a certain previous record.
    
- Developers Cooperation

	branch -> modify -> difference compare -> merge 


## How to use GitHub?







