> :warning: **NOTE:** We develop OneDev at <a href="https://code.onedev.io/projects/160">code.onedev.io</a> for sake of dogfooding. All issues and pull requests should be created there

<div align="center">
<h1>All-In-One DevOps Platform</h1>

With Git Management, Issue Tracking, and CI/CD. Simple yet Powerful.

<div style="font-size: 18px;">
| <a href="https://code.onedev.io/projects/162/blob/main/pages/quickstart.md">5-minute Quickstart</a> 
| <a href="https://code.onedev.io/projects/162/blob/main/pages/installation-guide.md">Installation Guide</a> 
| <a href="https://code.onedev.io/projects/162/blob/main/pages/tutorials.md">Tutorials</a>
| <a href="https://code.onedev.io/projects/162/blob">All Documentations</a> |
</div>

<p style="margin-bottom: 20px;">
</div>

### Docker First Kubernetes Native Build Farm

Out-of-box CI/CD capability with docker. Trivial to scale up to run massive jobs as pods in Kubernetes. Transparent support for Linux and Windows containers.

![Job Executor](doc/images/job-executor.png)

### Effortless Agent Based Build Farm

In case you do not have Kubernetes clusters, or want to run CI/CD jobs  outside docker, agents can be installed on remote machines to set up your build farm. OneDev server will push updates to agents automatically to make agent maintenance effortless

![agents.png](doc/images/agents.png)

### Set up CI/CD in a Breeze

CI/CD configuration is defined in a yaml file together with your code, and OneDev provides a GUI to generate the file without any learning curve.

![Cispec](doc/images/build-spec.gif)

### Flexible Build Workflow and Pipeline

Conditional build parameters. Create matrix builds by combining different parameters. Connect jobs to create pipelines. Run jobs concurrently to speed up processing. Run jobs automatically upon certain events, or manually by authorized users

![Build Workflow](doc/images/build-workflow.gif)

### Code Annotation with Coverage and Problem 

Analyze various CI reports to annotate code/diff with test coverage information and found problems.

![code-annotation.png](doc/images/code-annotation.png)

### Custom Issue States and Fields

Add custom issue states, fields and links. Configure field dependencies. Transit issue state automatically upon certain events, or manually by authorized users 

![Custom Issue](doc/images/custom-issue.gif)

### Auto-Refreshing Issue Boards

Define issue boards to show issues in columns based on values of specified field. Perform issue operations without leaving the board. Refresh board automatically to reflect most recent issue state.

![Issue Boards](doc/images/issue-boards.gif)

### Code Intelligence

Symbol search and navigation in source code and diff. Outline display and search. Works for every commit. Currently supports Java, JavaScript, C, C++, CSharp, Go, PHP, Python, CSS, SCSS, LESS and R. 

![Symbol Search](doc/images/symbol-search.gif)

### Code Discussions and Comprehensions

Instant and lightweight code discussions on code and diff blocks without creating pull requests. Discussions stay with the code to help code comprehension even if file is changed or renamed. 

![Code Comments](doc/images/code-comments.gif)

### Flexible Pull Request Review Policies

Enforce pull request review with branch protections. Specify required reviewers and builds for desired file patterns. 

![Branch Protection](doc/images/branch-protection.gif)

### Painless Pull Request Review

Review pull request commits as a whole or one by one. Organize code discussions in threads to show changes since last review explicitly

![Increment Review](doc/images/increment-review.gif)

### Powerful Query Language

Perform sophisticated queries against projects, commits, builds, issues, pull requests or code comments with a powerful query language. Save query for quick access. Subscribe to saved query to get notified of interesting events.

![Powerful Query](doc/images/powerful-query.gif)

### Deep Integration of Code, Issue, Pull Request and Build

Configure issues to transit to desired state upon commit, build or pull request events. See commit and pull request events in issue activities. Query fixed issues between builds. Find builds or pull requests fixing particular issues or commits

![Issue Query](doc/images/issue-code-build-integration.gif)

### Service Desk to Work with Issues over Email

The ability to submit and discuss issues over email makes OneDev a perfect customer supporting system, with the ability to create tickets of different priorities for different customers, and assign to different support representatives. 

![service-desk-setting.png](doc/images/service-desk-setting.png)

### Fine Grained Permission Control

Define permission schemes best suiting your development workflow. For instance, you may specify who can change particular source folder, who can assign issues, who can run release builds, or who can access build log, etc.

![Role](doc/images/role.png)

### Project Hierarchy and Setting Inheritance

Projects can be organized in a tree structure, and settings of parent project can be inherited by children. This saves a lot of efforts when manage a lot of projects with some common settings.

![Child Projects](doc/images/child-projects.png)

----

# Special Thanks

![yourkit](https://www.yourkit.com/images/yklogo.png) 

[YourKit](https://yourkit.com) supports this project by providing a free open source license of YourKit Java profiler