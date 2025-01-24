+++
title = "PolyCat's Project Management System"
date = "2024-01-23"
description = "A general overview for a Git based project management system"
tags = ["organisation" ,"system", "git"]
+++
# The Core 
- The core system will center around a git host ( Example: [GitTea](https://about.gitea.com/)) and [Markdown](https://www.markdownguide.org/).
- The idea is to keep everything as decentralized as possible with minimal hierarchy and a focus on documentation.

> [!Note]
> To fully understand the system, a basic understanding of [git](https://git-scm.com/) and how git hosts operate is recommended.

# Organization
Each project will have it's own repository with these core elements enabled:
- #### Issues
    - For reporting issues and tasks.
- #### Pull Request
    - For merging changes with a review process.
- #### Wiki
    - Most things in the project should be documented to reduce confusion.
    - Ideally, if someone has a question about the project they should be able to easily figure out an answer based on the wiki.
    - If not, that's what Issues are for.
   
> [!Note]
>More features can be enabled based on the project but these are the core elements of this system

# The Wiki Structure
The wiki should contain:
- #### Quick rundown of what the project is and it's structure
    - Any new person coming to the project should ideally be able to start contributing just based on these instructions.
- #### Docs
    - A constantly evolving wiki of what's going on in the project.
    - This should keep everyone on the same page about the project's state.

# Special Thanks
- [No Boilerplate](https://noboilerplate.org/) for [his great video](https://www.youtube.com/watch?v=WgV6M1LyfNY) on this subject.
- This system is heavily inspired by his if not almost a one to one copy.