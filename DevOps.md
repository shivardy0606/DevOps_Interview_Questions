## Q1) what is DevOps?

By the name DevOps, it’s very clear that it’s a collaboration of Development as well as Operations. But one should know that DevOps is not a tool, or software or framework, DevOps is a Combination of Tools which helps for the automation of the whole infrastructure.
DevOps is basically an implementation of Agile methodology on the Development side as well as Operations side.

## Q2) why do we need DevOps?

To fulfil the need of delivering more and faster and better application to meet more and more demands of users, we need DevOps. DevOps helps deployment to happen really fast compared to any other traditional tools.
## Q3) Mention the key aspects or principle behind DevOps?

The key aspects or principle behind DevOps is:
•	Infrastructure as a Code
•	Continuous Integration
•	Continuous Deployment
•	Automation
•	Continuous Monitoring
•	Security
## Q4) List out some of the popular tools for DevOps?

•	Git
•	Jenkins
 

•	Ansible
•	Puppet
•	Nagios
•	Docker
•	ELK (Elasticsearch, Logstash, Kibana)
## Q5) what is a version control system?

Version Control System (VCS) is a software that helps software developers to work together and maintain a complete history of their work.
Some of the feature of VCS as follows:
•	Allow developers to wok simultaneously
•	Does not allow overwriting on each other changes.
•	Maintain the history of every version.

There are two types of Version Control Systems:
1.	Central Version Control System, Ex: Git, Bitbucket
2.	Distributed/Decentralized Version Control System, Ex: SVN
## Q6) What is Git and explain the difference between Git and SVN?

Git is a source code management (SCM) tool which handles small as well as large projects with efficiency. It is basically used to store our repositories in remote server such as GitHub.


GIT	
SVN

Git is a Decentralized Version Control Tool	
SVN is a Centralized Version Control Tool

Git contains the local repo as well as the full history of the whole project on all the	

SVN relies only on the central server to store
 

developers hard drive, so if there is a server outage , you can easily do recovery from your team mates local git repo.	
all the versions of the project file

Push and pull operations are fast	
Push and pull operations are slower compared to Git

It belongs to
3rd  generation Version Control Tool	
It belongs to
2nd  generation Version Control tools

Client nodes can share the entire repositories on their local system	
Version history is stored on server-side repository

Commits can be done offline too	
Commits can be done only online

Work are shared automatically by commit	
Nothing is shared automatically
## Q7) what language is used in Git?

Git is written in C language, and since its written in C language its very fast and reduces the overhead of runtimes.
 

## Q8) what is SubGit?

SubGit is a tool for migrating SVN to Git. It creates a writable Git mirror of a local or remote Subversion repository and uses both Subversion and Git if you like.
## Q9) how can you clone a Git repository via Jenkins?

First, we must enter the e-mail and user name for your Jenkins system, then switch into your job directory
and execute the “git config” command.
## Q10)What are the Advantages of Ansible?

•	Agentless, it doesn’t require any extra package/daemons to be installed
•	Very low overhead
•	Good performance
•	Idempotent
•	Very Easy to learn
•	Declarative not procedural
## Q11) what’s the use of Ansible?

Ansible is mainly used in IT infrastructure to manage or deploy applications to remote nodes. Let’s say we want to deploy one application in 100’s of nodes by just executing one command, then Ansible is the one actually coming into the picture but should have some knowledge on Ansible script to understand or execute the same.
## Q12) what’s the difference between Ansible Playbook and Roles?



Roles	
Playbooks

Roles are reusable subsets of a play.	

Playbooks contain Plays.

A set of tasks for accomplishing certain role.	

Mapps among hosts and roles.
 


Example: common, webservers.	
Example: site.yml, fooservers.yml, webservers.yml.
## Q13) How do I see a list of all the ansible_ variables?

Ansible by default gathers “facts” about the machines, and these facts can be accessed in Playbooks and in templates. To see a list of all the facts that are available about a machine, you can run the “setup” module as an ad-hoc action:
Ansible -m setup hostname
This will print out a dictionary of all the facts that are available for that particular host.
## Q14) what is Docker?

Docker is a containerization technology that packages your application and all its dependencies together in the form of Containers to ensure that your application works seamlessly in any environment.
## Q15) what is Docker image?

Docker image is the source of Docker container. Or in other words, Docker images are used to create containers.
## Q16) what is Docker Container?

Docker Container is the running instance of Docker Image.
## Q17) Can we consider DevOps as Agile methodology?

Of Course, we can!! The only difference between agile methodology and DevOps is that, agile methodology is implemented only for development section and DevOps implements agility on both development as well as operations section.
## Q18) what are the advantages of using Git?

1.	Data redundancy and replication
2.	High availability
3.	Only one. git directory per repository
4.	Superior disk utilization and network performance
5.	Collaboration friendly
 

6.	Git can use any sort of projects.
## Q19) what is kernel?

A kernel is the lowest level of easily replaceable software that interfaces with the hardware in your computer.
## Q20) what is difference between grep -i and grep -v?

I ignore alphabet difference V accept this value ex) ls | grep -i docker
Dockerfile docker.tar.gz
ls | grep -v docker Desktop Dockerfile Documents Downloads
You can’t see anything with name docker.tar.gz
Q21) How can you define particular space to the file

This feature is generally used to give the swap space to the server. Lets say in below machine I have to create swap space of 1GB then,
dd if=/dev/zero of=/swapfile1 bs=1G count=1
Q22) what is concept of sudo in linux?

Sudo(superuser do) is a utility for UNIX- and Linux-based systems that provides an	efficient way to give specific users permission to use specific system commands at the root (most powerful) level of the system.
Q23) what is a Jenkins Pipeline?

Jenkins Pipeline (or simply “Pipeline”) is a suite of plugins which supports implementing and integrating
continuous delivery pipelines into Jenkins.
 

Q24) How to stop and restart the Docker container?

To stop the container: docker stop container ID
Now to restart the Docker container: docker restart container ID
Q25) What platforms does Docker run on?

Docker runs on only Linux and Cloud platforms:
•	Ubuntu 12.04 LTS+
•	Fedora 20+
•	RHEL 6.5+
•	CentOS 6+
•	Gentoo
•	ArchLinux
•	openSUSE 12.3+
•	CRUX 3.0+

 
Cloud:
 

•	Amazon EC2
•	Google Compute Engine
•	Microsoft Azure
•	Rackspace
 

Note that Docker does not run on Windows or Mac for production as there is no support, yes you can use it for testing purpose even in windows
Q26) what are the tools used for docker networking?

For docker networking we generally use kubernets and docker swarm.
Q27) what is docker compose?

Lets say you want to run multiple docker container, at that time you have to create the docker compose file and type the command docker-compose up. It will run all the containers mentioned in docker compose file.
 

Q28) What is Scrum?

Scrum is basically used to divide your complex software and product development task into smaller chunks, using iterations and incremental practises. Each iteration is of two weeks. Scrum consists of three roles: Product owner, scrum master and Team
Q29) What does the commit object contain?

Commit object contain the following components:
It contains a set of files, representing the state of a project at a given point of time reference to parent commit objects
An SHAI name, a 40-character string that uniquely identifies the commit object (also called as hash).
Q30) Explain the difference between git pull and git fetch?

Git pull command basically pulls any new changes or commits from a branch from your central repository and updates your target branch in your local repository.
Git fetch is also used for the same purpose, but its slightly different form Git pull. When you trigger a git fetch, it pulls all new commits from the desired branch and stores it in a new branch in your local repository. If we want to reflect these changes in your target branch, git fetch must be followed with a git merge. Our target branch will only be updated after merging the target branch and fetched branch. Just to make it easy for us, remember the equation below:
Git pull = git fetch + git merge
Q31) How do we know in Git if a branch has already been merged into master?

git branch –merged
The above command lists the branches that have been merged into the current branch. git branch –no-merged
this command lists the branches that have not been merged.
Q32) What is ‘Staging Area’ or ‘Index’ in GIT?

Before committing a file, it must be formatted and reviewed in an intermediate area known as ‘Staging Area’ or ‘Indexing Area’.
#git add <file_name>
 

Q33) What is Git Stash?

Let’s say you’ve been working on part of your project, things are in a messy state and you want to switch branches for some time to work on something else. The problem is, you don’t want to do a commit of your half-done work just, so you can get back to this point later. The answer to this issue is Git stash.
Git Stashing takes your working directory that is, your modified tracked files and staged changes and saves it on a stack of unfinished changes that you can reapply at any time.
Q34) What is Git stash drop?

Git ‘stash drop’ command is basically used to remove the stashed item. It will basically remove the last
added stash item by default, and it can also remove a specific item if you include it as an argument. I have provided an example below:
If you want to remove any particular stash item from the list of stashed items you can use the below commands:
git stash list: It will display the list of stashed items as follows:
stash@{0}: WIP on master: 049d080 added the index file stash@{1}: WIP on master: c265351 Revert “added files” stash@{2}: WIP on master: 13d80a5 added number to log
Q35) What is the function of ‘git config’?

Git uses our username to associate commits with an identity. The git config command can be used to change our Git configuration, including your username.
Suppose you want to give a username and email id to associate commit with an identity so that you can know who has made a commit. For that I will use:
git config –global user.name “Your Name”: This command will add your username.
git config –global user.email “Your E-mail Address”: This command will add your email id.
Q36) How can you create a repository in Git?

To create a repository, you must create a directory for the project if it does not exist, then run command
“git init”. By running this command .git directory will be created inside the project directory.
Q37) Describe the branching strategies you have used?

Generally, they ask this question to understand your branching knowledge Feature branching
 

This model keeps all the changes for a feature inside of a branch. When the feature branch is fully tested and validated by automated tests, the branch is then merged into master.
Task branching
In this task branching model each task is implemented on its own branch with the task key included in the branch name. It is quite easy to see which code implements which task, just look for the task key in the branch name.
Release branching
Once the develop branch has acquired enough features for a release, then we can clone that branch to form a Release branch. Creating this release branch starts the next release cycle, so no new features can be added after this point, only bug fixes, documentation generation, and other release-oriented tasks should go in this branch. Once it’s ready to ship, the release gets merged into master and then tagged with a version number. In addition, it should be merged back into develop branch, which may have progressed since the release was initiated earlier.
Q38) What is Jenkins?

Jenkins is an open source continuous integration tool which is written in Java language. It keeps a track on version control system and to initiate and monitor a build system if any changes occur. It monitors the whole process and provides reports and notifications to alert the concern team.
Q39) What is the difference between Maven, Ant and Jenkins?

Maven and Ant are Build Technologies whereas Jenkins is a continuous integration(CI/CD) tool.
Q40) Explain what is continuous integration?

When multiple developers or teams are working on different segments of same web application, we need to perform integration test by integrating all the modules. To do that an automated process for each piece of code is performed on daily bases so that all your code gets tested. And this whole process is termed as continuous integration.
Q41) What is the relation between Hudson and Jenkins?

Hudson was the earlier name of current Jenkins. After some issue faced, the project name was changed from Hudson to Jenkins.
Q42) What are the advantages of Jenkins?

Advantage of using Jenkins
 

•	Bug tracking is easy at early stage in development environment.
•	Provides a very large numbers of plugin support.
•	Iterative improvement to the code, code is basically divided into small sprints.
•	Build failures are cached at integration stage.
•	For each code commit changes an automatic build report notification get generated.
•	To notify developers about build report success or failure, it can be integrated with LDAP mail server.
•	Achieves continuous integration agile development and test-driven development environment.
•	With simple steps, maven release project can also be automated.
Q43) Which SCM tools does Jenkins supports?

Source code management tools supported by Jenkins are below:
•	AccuRev
•	CVS
•	Subversion
•	Git
•	Mercurial
•	Perforce
•	Clearcase
•	RTC
Q44) What is Ansible?

Ansible is a software configuration management tool to deploy an application using ssh without	any downtime. It is also used for management and configuration of software applications. Ansible is developed in Python language.
Q45) How can your setup Jenkins jobs?

Steps to set up Jenkins job as follows:
Select new item from the menu.
After that enter a name for the job (it can be anything) and select free-style job.
 

Then click OK to create new job in Jenkins dashboard.
The next page enables you to configure your job, and it’s done.
Q46) What is your daily activities in your current role?

•	Working on JIRA Tickets
•	Builds and Deployments
•	Resolving issues when builds and deployments fails by coordinating and collaborating with the dev team
•	Infrastructure maintenance
•	Monitoring health of applications
Q47) What are the challenges you faced in recent times?

I need to implement trending technologies like Docker to automate the configuration management activities in my project by showing POC.
Q48) What are the build and deployment failures you got and how you resolved those?

I use to get most of the time out of memory issue. So I fixed this issue by restarting the server which is not best practice. I did the permanent fix by increase the Perm Gen Space and Heap Space.
Q49) I want a file that consists of last 10 lines of the some other file?

Tail -10 filename >filename
Q50) How to check the exit status of the commands?

echo $?
Become an DevOps Expert with Certification in 25hours
Q51) I want to get the information from file which consists of the word “GangBoard”

grep “GangBoard” filename
Q52) I want to search the files with the name of “GangBoard”

find / -type f -name “*GangBoard*”
Q53) Write a shell script to print only prime numbers?

 

 
Q54) How to pass the parameters to the script and how can I get those parameters?

Scriptname.sh parameter1 parameter2 I will use $* to get the parameters.
Q55) What is the default file permissions for the file and how can I modify it?

Default file permissions are : rw-r—r—
If I want to change the default file permissions I need to use umask command ex: umask 666
 

Q56) How you will do the releases?

There are some steps to follow.
•	Create a check list
•	Create a release branch
•	Bump the version
•	Merge release branch to master & tag it.
•	Use a Pull request to merge the release merge
•	Deploy master to Prod Environment
•	Merge back into develop & delete release branch
•	Change log generation
•	Communicating with stack holders
•	Grooming the issue tracker
Q57) How you automate the whole build and release process?

•	Check out a set of source code files.
•	Compile the code and report on progress along the way.
•	Run automated unit tests against successful compiles.
•	Create an installer.
•	Publish the installer to a download site, and notify teams that the installer is available.
•	Run the installer to create an installed executable.
•	Run automated tests against the executable.
•	Report the results of the tests.
•	Launch a subordinate project to update standard libraries.
•	Promote executables and other files to QA for further testing.
•	Deploy finished releases to production environments, such as Web servers or CD manufacturing.
The above process will be done by Jenkins by creating the jobs.
 

Q58) I have 50 jobs in the Jenkins dash board , I want to build at a time all the jobs

In Jenkins there is a plugin called build after other projects build. We can provide job names over there and If one parent job run then it will automatically run the all other jobs. Or we can use Pipe line jobs.
Q59) How can I integrate all the tools with Jenkins?

I have to navigate to the manage Jenkins and then global tool configurations there you have to provide all the details such as Git URL , Java version, Maven version , Path etc.
Q60) How to install Jenkins via Docker?

The steps are:
•	Open up a terminal window.
•	Download the jenkinsci/blueocean image & run it as a container in Docker using the following docker run command:( https://docs.docker.com/engine/reference/commandline/run/)
•	docker run \ -u root \ –rm \ -d \ -p 8080:8080 \ -p 50000:50000 \ -v jenkins- data:/var/jenkins_home \  -v /var/run/docker.sock:/var/run/docker.sock \  jenkinsci/blueocean
•	Proceed to the Post-installation setup wizard (https://jenkins.io/doc/book/installing/#setup- wizard)
•	Accessing the Jenkins/Blue Ocean Docker container docker exec -it jenkins-blueocean bash
•	Accessing the Jenkins console log through Docker logsdocker logs <docker-container- name>Accessing the Jenkins home directorydocker exec -it <docker-container-name> bash
Q61) Did you ever participated in Prod Deployments? If yes what is the procedure?

Yes I have participated, we need to follow the following steps in my point of view
•	Preparation & Planning : What kind of system/technology was supposed to run on what kind of machine
•	The specifications regarding the clustering of systems
•	How all these stand-alone boxes were going to talk to each other in a foolproof manner
•	Production setup should be documented to bits. It needs to be neat, foolproof, and understandable.
 

•	It should have all a system configurations, IP addresses, system specifications, & installation instructions.
•	It needs to be updated as & when any change is made to the production environment of the system
Q62) My application is not coming up for some reason? How can you bring it up?

We need to follow the steps
•	Network connection
•	The Web Server is not receiving users’s request
•	Checking the logs
•	Checking the process id’s whether services are running or not
•	The Application Server is not receiving user’s request(Check the Application Server Logs and
Processes)
•	A network level ‘connection reset’ is happening somewhere.
Q63) Did you automate anything in your project? Please explain

Yes I have automated couple of things such as
•	Password expiry automation
•	Deleting the older log files
•	Code quality threshold violations etc.
Q64) What is IaC? How you will achieve this?

Infrastructure as Code (IaC) is the management of infrastructure (networks, virtual machines, load balancers, and connection topology) in a descriptive model, using the same versioning as DevOps team uses for source code. This will be achieved by using the tools such as Chef, Puppet and Ansible etc.
Q65) What is multifactor authentication? What is the use of it?

Multifactor authentication (MFA) is a security system that requires more than one method of authentication from independent categories of credentials to verify the user’s identity for a login or other transaction.
•	Security for every enterprise user — end & privileged users, internal and external
 

•	Protect across enterprise resources — cloud & on-prem apps, VPNs, endpoints, servers, privilege elevation and more
•	Reduce cost & complexity with an integrated identity platform
Q66) I want to copy the artifacts from one location to another location in cloud. How?

Create two S3 buckets, one to use as the source, and the other to use as the destination and then create policies.
Q67) How can I modify the commit message in git?

I have to use following command and enter the required message. Git commit –amend
Q68) How can you avoid the waiting time for the triggered jobs in Jenkins.

First I will check the Slave nodes capacity, If it is fully loaded then I will add the slave node by doing the following process.
Go to the Jenkins dashboard -> Manage Jenkins ->Manage Nodes Create the new node a
By giving the all required fields and launch the slave machine as you want.
Q69) What are the Pros and Cons of Ansible?

Pros:
1.	Open Source
2.	Agent less
3.	Improved efficiency , reduce cost
4.	Less Maintenance
5.	Easy to understand yaml files Cons:
1.	Underdeveloped GUI with limited features
2.	Increased focus on orchestration over configuration management
3.	SSH communication slows down in scaled environments
 

Q70) How you handle the merge conflicts in git?

Follow the steps
1.	Create Pull request
2.	Modify according to the requirement by sitting with developers
3.	Commit the correct file to the branch
4.	Merge the current branch with master branch.
Q71) I want to delete 10 days older log files. How can I?

There is a command in unix to achieve this task find <directory_path> -mtime +10 -name “*.log” -exec rm
-f {} \; 2>/dev/null
What is the difference among chef, puppet and ansible?


	
Chef	
Puppet	
Ansible



Interoperability	

Works Only on Linux/Unix	

Works Only on Linux/Unix	
Supports Windows but server should be Linux/Unix

Conf. Language	
It uses Ruby	
Puppet DSL	
YAML
(Python)



Availability	
Primary Server and Backup Server	

Multi Master Architecture	

Single Active Node
 

Q72) How you get the Inventory variables defined for the host?

We need to use the following command
Ansible – m debug- a “var=hostvars[‘hostname’]” localhost(10.92.62.215)
Q73) How you will take backup for Jenkins?

Copy JENKINS_HOME directory and “jobs” directory to replicate it in another server
Q74) How to deploy docker container to aws?

Amazon provides the service called Amazon Elastic Container Service; By using this creating and configuring the task definition and services we will launch the applications.
Q75) I want to change the default port number of apache tomcat. How?

Go to the tomcat folder and navigate to the conf folder there you will find a server.xml file. You can change connector port tag as you want.
Q76) In how many ways you can install the Jenkins?

We can install Jenkins in 3 Ways
•	By downloading Jenkins archive file
•	By running as a service Java –jar Jenkins.war
•	By deploying Jenkins.war to the webapps folder in tomcat.
Q77) How you will run Jenkins job from command line?

We have a Jenkins CLI from there we need to use the curl command
curl -X POST -u YOUR_USER:YOUR_USER_PASSWORD http://YOUR_JENKINS_URL/job/YOUR_JOB/build
Q78) How you will do tagging in git?

We have following command to create tags in git Git tag v0.1
Q79) How can you connect a container to a network when it starts?

We need to use a following command
docker run -itd –network=multi-host-network busybox
Q80) How you will do code commit and code deploy in cloud?

•	Create a deployment environment
 

•	Get a copy of the sample code
•	Create your pipeline
•	Activate your pipeline
•	Commit a change and update the App.
Q81) How to access variable names in Ansible?

Using hostvars method we can access and add the variables like below
{{ hostvars[inventory_hostname][‘ansible_’ + which_interface][‘ipv4’][‘address’] }}
Q82) What is Infrastructure as Code?

Where the Configuration of any servers or tool chain or application stack required for an association can be made into progressively elucidating dimension of code and that can be utilized for provisioning and overseeing foundation components like Virtual Machine, Software, Network Elements, however it varies from contents utilizing any language, where they are a progression of static advances coded, where Version control can be utilized so as to follow condition changes .
Precedent Tools are Ansible, Terraform.
Q83) What are the zones the Version control can acquaint with get proficient DevOps practice?

A clearly fundamental region of Version Control is Source code the executives, Where each engineer code ought to be pushed to a typical storehouse for keeping up assemble and discharge in CI/CD pipelines.
Another territory can be Version control For Administrators when they use Infrastructure as A Code (IAC) apparatuses and rehearses for keeping up The Environment setup.
Another Area of Version Control framework Can be Artifactory Management Using Repositories like Nexus and DockerHub
Q84) Why Opensource apparatuses support DevOps?

Opensource devices dominatingly utilized by any association which is adjusting (or) embraced DevOps pipelines in light of the fact that devops accompanied an attention on robotization in different parts of association manufacture and discharge and change the executives and furthermore framework the board zones.
So creating or utilizing a solitary apparatus is unthinkable and furthermore everything is fundamentally an experimentation period of advancement and furthermore coordinated chops down the advantage of
 

building up a solitary device , so opensource devices were accessible available practically spares each reason and furthermore gives association a choice to assess the device dependent on their need.
Q85) What is the distinction among Ansible and chef(or) manikin?

Ansible is Agentless design the board device, where manikin or gourmet expert needs operator should be kept running on the specialist hub and culinary specialist or manikin depends on draw demonstrate, where your cookbook or show for gourmet expert and manikin separately from the ace will be pulled by the operator and ansible uses ssh to convey and it gives information driven guidelines to the hubs should be overseen , progressively like RPC execution, ansible utilizations YAML scripting, though manikin (or) culinary specialist is worked by ruby uses their own DSL .
Q86) What is Jinja2 templating in ansible playbooks and their utilization?

Jinja2 templating is the Python standard for templating , consider it like a sed editorial manager for Ansible , where it very well may be utilized is when there is a requirement for dynamic change of any config record to any application like consider mapping a MySQL application to the IP address of the machine, where it is running, it can’t be static , it needs modifying it progressively at runtime.
Arrangement
The vars inside the supports are supplanted by ansible while running utilizing layout module.
Q87) What is the requirement for sorting out playbooks as the job, is it vital?

Arranging playbooks as jobs , gives greater clarity and reusability to any plays , while consider an errand where MySQL establishment ought to be done after the evacuation of Oracle DB , and another prerequisite is expected to introduce MySQL after java establishment, in the two cases we have to introduce MySQL , yet without jobs need to compose playbooks independently for both use cases , yet utilizing jobs once the MySQL establishment job is made can be used any number of times by summoning utilizing rationale in site.yaml .
No, it isn’t important to make jobs for each situation, however making jobs is the best practice in Ansible.
Q88) What is the fundamental disservice of Docker holders?

As the lifetime of any compartments is while pursuing a holder is wrecked you can’t recover any information inside a compartment, the information inside a compartment is lost perpetually, however tenacious capacity for information inside compartments should be possible utilizing volumes mount to an outer source like host machine and any NFS drivers.
 

Q89) What are the docker motor and docker form?

Docker motor contacts the docker daemon inside the machine and makes the runtime condition and procedure for any compartment, docker make connects a few holders to shape as a stack utilized in making application stacks like LAMP, WAMP, XAMP
Q90) What are the Different modes does a holder can be run?

Docker holder can be kept running in two modes
Connected: Where it will be kept running in the forefront of the framework you are running, gives a terminal inside to compartment when – t choice is utilized with it, where each log will be diverted to stdout screen.
Isolates: This mode is typically kept running underway, where the holder is confined as a foundation procedure and each yield inside a compartment will be diverted log records inside/var/lib/docker/logs/<container-id>/<container-id.json> and which can be seen by docker logs order.
Q91) What the yield of docker assess order will be?

Docker examines <container-id> will give yield in JSON position, which contains subtleties like the IP address of the compartment inside the docker virtual scaffold and volume mount data and each other data identified with host (or) holder explicit like the basic document driver utilized, log driver utilized. docker investigate [OPTIONS] NAME|ID [NAME|ID…] Choices
•	Name, shorthand Default Description
•	group, – f Format the yield utilizing the given Go layout
•	measure, – s Display all out document sizes if the sort is the compartment
•	type Return JSON for a predefined type
Q92) What is the order can be utilized to check the asset usage by docker holders?

Docker details order can be utilized to check the asset usage of any docker holder, it gives the yield practically equivalent to Top direction in Linux, it shapes the base for compartment asset observing instruments like a counsel, which gets yield from docker details order.
docker details [OPTIONS] [CONTAINER…] Choices Name, shorthand Default Description
•	all, – a Show all holders (default demonstrates simply running)
 

•	group Pretty-print pictures utilizing a Go layout
•	no-stream Disable spilling details and just draw the main outcome
•	no-trunc Do not truncate yield
Q93) How to execute some errand (or) play on localhost just while executing playbooks on various has on an ansible?
In ansible, there is a module called delegate_to, in this module area give the specific host (or) has where your errands (or) assignment should be run.
undertakings:
name: ” Elasticsearch Hitting”
uri: url=’_search?q=status:new’ headers='{“Content-type”:”application/json”}’ method=GET
return_content=yes register: yield delegate_to: 127.0.0.1
Q94) What is the distinction among set_fact and vars in ansible?

Where a set_fact sets the incentive for a factor at one time and stays static, despite the fact that the esteem is very powerful and vars continue changing according to the esteem continues changing for the variable.
assignments:
set_fact:
fact_time: “Truth: ” troubleshoot: var=fact_time order: rest 2
troubleshoot: var=fact_time assignments:
name: queries in factors versus queries in realities has: localhost
vars:
var_time: “Var: ”
Despite the fact that the query for the date has been utilized in both the cases, wherein the vars are
 

utilized it modifies dependent on an opportunity to time each time executed inside the playbook lifetime. Be that as it may, Fact dependably continues as before once query is finished
Q95) What is a query in ansible and what are query modules bolstered by ansible?

Query modules enable access to information in Ansible from outside sources. These modules are assessed on the Ansible control machine and can incorporate perusing the filesystem yet in addition reaching outside information stores and administrations.
Organization is {lookup{‘<plugin>’,'<source(or)connection_string>’}}
A portion of the query modules upheld by ansible are Document
pipe redis
jinja layouts etcd kv store
Q96) How might you erase the docker pictures put away at your nearby machine and how
might you do it for every one of the pictures without a moment’s delay?

The direction docker RMI <image-id> can be utilized to erase the docker picture from nearby machine, though a few pictures may should be constrained in light of the fact that the picture might be utilized by some other holder (or) another picture , to erase pictures you can utilize the mix of directions by docker RMI $(docker pictures – q), where docker pictures will give the docker picture names, to get just the ID of docker pictures just , we are utilizing – q switch with docker pictures order.
Q97) What are the organizers in the Jenkins establishment and their employments?

JENKINS_HOME – which will be/$JENKINS_USER/.jenkins it is the root envelope of any Jenkins establishment and it contains subfolders each for various purposes.
employments/ – Folder contains all the data pretty much every one of the occupations arranged in the Jenkins example.
Inside employments/, you will have the envelope made for each activity and inside those organizers, you will have fabricate organizers as indicated by each form numbers each form will have its log records, which we see in Jenkins web support.
Modules/ – where all your modules will be recorded.
 

Workspace/ – this will be available to hold all the workspace documents like your source code pulled from SCM.
Q98) What are the approaches to design Jenkins framework?

Jenkins can be designed in two different ways
Web: Where there is a choice called design a framework, in their area, you can make all setup changes. Manual on filesystem: Where each change should likewise be possible straightforwardly on the Jenkins config.xml document under the Jenkins establishment catalog, after you make changes on the filesystem, you have to restart your Jenkins, either can do it specifically from terminal (or) you can utilize Reload setup from plate under oversee Jenkins menu or you can hit/restart endpoint straightforwardly.
Q99) What is the job Of HTTP REST API in DevOps?

As DevOps is absolutely centers around Automating your framework and gives changes over the pipeline to various stages like an every CI/CD pipeline will have stages like form, test, mental soundness test, UAT, Deployment to Prod condition similarly as with each phase there are diverse devices is utilized and distinctive innovation stack is displayed and there should be an approach to incorporate with various instrument for finishing an arrangement toolchain, there comes a requirement for HTTP API , where each apparatus speaks with various devices utilizing API , and even client can likewise utilize SDK to interface with various devices like BOTOX for Python to contact AWS API’s for robotization dependent on occasions
, these days its not cluster handling any longer , it is generally occasion driven pipelines
Q100) What are Micro services, and how they control proficient DevOps rehearses?

Where In conventional engineering , each application is stone monument application implies that anything is created by a gathering of designers, where it has been sent as a solitary application in numerous machines and presented to external world utilizing load balances, where the micro services implies separating your application into little pieces, where each piece serves the distinctive capacities expected to finish a solitary exchange and by separating , designers can likewise be shaped to gatherings and each bit of utilization may pursue diverse rules for proficient advancement stage, as a result of spry improvement ought to be staged up a bit and each administration utilizes REST API (or) Message lines to convey between another administration.
So manufacture and arrival of a non-strong form may not influence entire design, rather, some usefulness
is lost, that gives the confirmation to productive and quicker CI/CD pipelines and DevOps Practices.
Get DevOps Online Training
 

Q101) What are the manners in which that a pipeline can be made in Jenkins?

There are two different ways of a pipeline can be made in Jenkins Scripted Pipelines:
Progressively like a programming approach Explanatory pipelines:
DSL approach explicitly to make Jenkins pipelines.
The pipeline ought to be made in Jenkins document and the area can either be in SCM or nearby framework.
Definitive and Scripted Pipelines are developed on a very basic level in an unexpected way. Definitive Pipeline is a later element of Jenkins Pipeline which:
gives more extravagant grammatical highlights over Scripted Pipeline language structure, and is intended to make composing and perusing Pipeline code less demanding.
Q102) What are the Labels in Jenkins and where it tends to be used?

Similarly as with CI/CD arrangement should be concentrated , where each application in the association can be worked by a solitary CI/CD server , so in association there might be various types of utilization like java, c#,.NET and so forth, likewise with microservices approach your programming stack is inexactly coupled for the task , so you can have Labeled in every hub and select the choice Only assembled employments while name coordinating this hub, so when a manufacture is planned with the mark of the hub present in it, it hangs tight for next agent in that hub to be accessible, despite the fact that there are different agents in hubs.
Q103) What is the utilization of Blueocean in Jenkins?

Blue Ocean reconsiders the client experience of Jenkins. Planned from the beginning for Jenkins Pipeline, yet at the same time good with free-form occupations, Blue Ocean diminishes mess and builds lucidity for each individual from the group.
It gives complex UI to recognize each phase of the pipeline and better pinpointing for issues and extremely rich Pipeline editorial manager for apprentices.
Q104) What is the callback modules in Ansible, give a few instances of some callback modules?
Callback modules empower adding new practices to Ansible when reacting to occasions. Of course, callback modules control a large portion of the yield you see when running the direction line programs,
 

however can likewise be utilized to include an extra yield, coordinate with different apparatuses and marshall the occasions to a capacity backend. So at whatever point a play is executed and after it creates a few occasions, that occasions are imprinted onto Stdout screen, so callback module can be put into any capacity backend for log preparing.
Model callback modules are ansible-logstash, where each playbook execution is brought by logstash in the JSON group and can be incorporated some other backend source like elasticsearch.
Q105) What are the scripting dialects can be utilized in DevOps?

As with scripting dialects, the fundamental shell scripting is utilized to construct ventures in Jenkins pipelines and python contents can be utilized with some other devices like Ansible , terraform as a wrapper content for some other complex choice unraveling undertakings in any mechanization as python is more unrivaled in complex rationale deduction than shell contents and ruby contents can likewise be utilized as fabricate ventures in Jenkins.
Q106) What is Continuous Monitoring and why checking is basic in DevOps?

DevOps draws out each association capacity of fabricate and discharge cycle to be a lot shorter with an idea of CI/CD, where each change is reflected into generation conditions fastly, so it should be firmly observed to get client input. So the idea of constant checking has been utilized to assess every application execution progressively (at any rate Near Real Time) , where every application is produced with application execution screen specialists perfect and the granular dimension of measurements are taken out like JVM details and even practical savvy measurements inside the application can likewise be spilled out progressively to Agents , which thusly provides for any backend stockpiling and that can be utilized by observing groups in dashboards and cautions to get persistently screen the application.
Q107) Give a few instances of persistent observing instruments?

Where numerous persistent observing instruments are accessible in the market, where utilized for an alternate sort of use and sending model
Docker compartments can be checked by consultant operator, which can be utilized by Elasticsearch to store measurements (or) you can utilize TICK stack (Telegraph, influxdb, Chronograph, Capacitor) for each framework observing in NRT(Near Real Time) and You can utilize Logstash (or) Beats to gather Logs from framework , which thusly can utilize Elasticsearch as Storage Backend can utilize Kibana (or) Grafana as visualizer.
The framework observing should be possible by Nagios and Icinga.
 

Q108) What is docker swarm?

Gathering of Virtual machines with Docker Engine can be grouped and kept up as a solitary framework and the assets likewise being shared by the compartments and docker swarm ace calendars the docker holder in any of the machines under the bunch as indicated by asset accessibility
Docker swarm init can be utilized to start docker swarm bunch and docker swarm joins with the ace IP from customer joins the hub into the swarm group.
Q109) What are Microservices, and how they control productive DevOps rehearses?

Where In conventional engineering , each application is stone monument application implies that anything is created by a gathering of designers, where it has been conveyed as a solitary application in numerous machines and presented to external world utilizing load balancers, where the microservices implies separating your application into little pieces, where each piece serves the diverse capacities expected to finish a solitary exchange and by separating , engineers can likewise be shaped to gatherings and each bit of utilization may pursue distinctive rules for proficient advancement stage, on account of light-footed improvement ought to be staged up a bit and each administration utilizes REST API (or) Message lines to impart between another administration.
So manufacture and arrival of a non-hearty variant may not influence entire design, rather, some usefulness is lost, that gives the affirmation to proficient and quicker CI/CD pipelines and DevOps Practices.
Q110) What are the manners in which that a pipeline can be made in Jenkins?

There are two different ways of a pipeline can be made in Jenkins Scripted Pipelines:
Progressively like a programming approach Explanatory pipelines:
DSL approach explicitly to make Jenkins pipelines.
The pipeline ought to be made in Jenkins record and the area can either be in SCM or neighborhood framework.
Definitive and Scripted Pipelines are developed in a general sense in an unexpected way. Explanatory Pipeline is a later element of Jenkins Pipeline which:
gives more extravagant linguistic highlights over Scripted Pipeline sentence structure, and is intended to make composing and perusing Pipeline code simpler.
 

Q111) What are the Labels in Jenkins and where it very well may be used?

Likewise with CI/CD arrangement should be incorporated , where each application in the association can be worked by a solitary CI/CD server , so in association there might be various types of use like java, c#,.NET and so forth, similarly as with microservices approach your programming stack is inexactly coupled for the undertaking , so you can have Labeled in every hub and select the alternative Only assembled occupations while mark coordinating this hub, so when a fabricate is booked with the name of the hub present in it, it sits tight for next agent in that hub to be accessible, despite the fact that there are different agents in hubs.
Q112) What is the utilization of Blueocean in Jenkins?

Blue Ocean reexamines the client experience of Jenkins. Planned starting from the earliest stage for Jenkins Pipeline, yet at the same time good with free-form occupations, Blue Ocean lessens mess and expands clearness for each individual from the group.
It gives modern UI to recognize each phase of the pipeline and better pinpointing for issues and rich Pipeline proofreader for fledglings.
Q113) What is the callback modules in ansible, give a few instances of some callback modules?

Callback modules empower adding new practices to Ansible when reacting to occasions. As a matter of course, callback modules control the greater part of the yield you see when running the direction line programs, yet can likewise be utilized to include an extra yield, coordinate with different instruments and marshall the occasions to a capacity backend. So at whatever point a play is executed and after it delivers a few occasions, that occasions are imprinted onto Stdout screen, so callback module can be put into any capacity backend for log handling.
Precedent callback modules are ansible-logstash, where each playbook execution is gotten by logstash in the JSON position and can be incorporated some other backend source like elasticsearch.
Q114) What are the scripting dialects can be utilized in DevOps?

As with scripting dialects, the fundamental shell scripting is utilized to assemble ventures in Jenkins pipelines and python contents can be utilized with some other instruments like Ansible.
Q115) For what reason is each instrument in DevOps is generally has some DSL (Domain Specific Language)?
Devops is a culture created to address the necessities of lithe procedure, where the advancement rate is quicker ,so sending should coordinate its speed and that needs activities group to arrange and work with
 

dev group, where everything can computerize utilizing content based , however it feels more like tasks group than , it gives chaotic association of any pipelines, more the utilization cases , more the contents should be composed , so there are a few use cases, which will be sufficient to cover the requirements of light-footed are taken and apparatuses are made by that and customization can occur over the device utilizing DSL to mechanize the DevOps practice and Infra the board.
Q116) What are the mists can be incorporated with Jenkins and what are the utilization cases?

Jenkins can be coordinated with various cloud suppliers for various use cases like dynamic Jenkins slaves, Deploy to cloud conditions.
A portion of the cloud can be incorporated are
•	AWS
•	Purplish blue
•	Google Cloud
•	OpenStack
Q117) What are Docker volumes and what sort of volume ought to be utilized to accomplish relentless capacity?
Docker volumes are the filesystem mount focuses made by client for a compartment or a volume can be utilized by numerous holders, and there are distinctive sorts of volume mount accessible void dir, Post mount, AWS upheld lbs volume, Azure volume, Google Cloud (or) even NFS, CIFS filesystems, so a volume ought to be mounted to any of the outer drives to accomplish determined capacity, in light of the fact that a lifetime of records inside compartment, is as yet the holder is available and if holder is erased, the information would be lost.
Q118) What are the Artifacts store can be incorporated with Jenkins?

Any sort of Artifacts vault can be coordinated with Jenkins, utilizing either shell directions (or) devoted modules, some of them are Nexus, Jfrog.
Q119) What are a portion of the testing apparatuses that can be coordinated with Jenkins and notice their modules?
Sonar module – can be utilized to incorporate testing of Code quality in your source code. Execution module – this can be utilized to incorporate JMeter execution testing.
 

Junit – to distribute unit test reports.
Selenium module – can be utilized to incorporate with selenium for computerization testing.
Q120) What are the manufacture triggers accessible in Jenkins?

Fabricates can be run physically (or) either can naturally be activated by various sources like
Webhooks- The webhooks are API calls from SCM, at whatever point a code is submitted into a vault (or) should be possible for explicit occasions into explicit branches.
Gerrit code survey trigger-Gerrit is an opensource code audit instrument, at whatever point a code change is endorsed after audit construct can be activated.
Trigger Build Remotely – You can have remote contents in any machine (or) even AWS lambda capacities (or) make a post demand to trigger forms in Jenkins.
Calendar Jobs-Jobs can likewise be booked like Cron occupations.
Survey SCM for changes – Where your Jenkins searches for any progressions in SCM for the given interim, if there is a change, a manufacture can be activated.
Upstream and Downstream Jobs-Where a construct can be activated by another activity that is executed already.
Q121) How to Version control Docker pictures?

Docker pictures can be form controlled utilizing Tags, where you can relegate the tag to any picture utilizing docker tag <image-id> order. Furthermore, on the off chance that you are pushing any docker center library without labeling the default label would be doled out which is most recent, regardless of whether a picture with the most recent is available, it indicates that picture without the tag and reassign that to the most recent push picture.
Q122) What is the utilization of Timestamper module in Jenkins?

It adds Timestamp to each line to the comfort yield of the assemble.
Q123) Why you ought not execute an expand on ace?

You can run an expand on ace in Jenkins , yet it isn’t prudent, in light of the fact that the ace as of now has the duty of planning assembles and getting incorporate yields with JENKINS_HOME index, so on the off chance that we run an expand on Jenkins ace, at that point it furthermore needs to manufacture apparatuses, and workspace for source code, so it puts execution over-burden in the framework, if the Jenkins ace accidents, it expands the downtime of your fabricate and discharge cycle.
 

Q124) What do the main benefits of DevOps?

With a single team composed of cross-functional comments simply working in collaboration, DevOps organizations container produce including maximum speed, functionality, including innovation. Where continue special benefits: Continuous software control. Shorter complexity to manage.
Q125) What are the uses of DevOps tools?

•	Gradle. Your DevOps device stack will need a reliable build tool.
•	Git. Git is one from the most successful DevOps tools, widely applied across the specific software industry.
•	Jenkins. Jenkins is that go-to DevOps automation tool for many software community teams.
•	Bamboo.
•	Docker.
•	Kubernetes.
•	Puppet Enterprise.
•	Ansible.
Q126) What is DevOps beginner?

DevOps is a society which supports collaboration between Development including Operations Team to deploy key to increase faster in an automated & repeatable way. In innocent words, DevOps backside is established as an association of development and IT operations including excellent communication and collaboration.
Q127) What is the roles and responsibilities of the DevOps engineer?

DevOps Engineer manages with developers including the IT system to manage the code releases. They are both developers cases become interested in deployment including practice settings or sysadmins who convert a passion for scripting and coding more move toward the development front where all can improve that planning from test and deployment.
Q128) Which is the top DevOps tools? and it’s Which tools have you worked on?

Discover about the trending Top DevOps Tools including Git. Well, if you live considering DevOps being a tool when, you are wrong! DevOps does not a tool or software, it’s an appreciation that you can adopt for continuous growth. file and, by practicing it you can simply coordinate this work among your team.
 

Q129) Explain the typical characters involved in DevOps?

•	Commitment to the superior level in the organization.
•	Need for silver to be delivered across the organization.
•	Version check software.
•	Automated tools to compliance to process.
•	Automated Testing
•	Automated Deployment
Q130) What are your expectations from a career perspective of DevOps?

To be involved in the end to end delivery method and the most important phase of helping to change the manner so as to allow that development and operations teams to go together also understand each other’s point of view.
Q131) What does configuration management under terms like infrastructure further review some popular tools used?
In Software Engineering Software Configuration Management is a unique task about tracking to make the setting configuration during the infrastructure with one change. It is done for deploying, configuring and maintaining servers.
Q132) How will you approach when each design must to implement DevOps?

As the application is generated and deployed, we do need to control its performance. Monitoring means also really important because it might further to uncover some defects which might not have been detected earlier.
Q133) Explain about from Continuous Testing

From the above goal of Continuous Integration which is to take this application excuse to close users are primarily providing continuous delivery. This backside is completed out any adequate number about unit testing and automation testing. Hence, we must validate that this system created and integrated with all the developers that work as required.
Q134) Explain about from Continuous Delivery.

Continuous Delivery means an extension of Constant Integration which primarily serves to make the features which some developers continue developing out on some end users because soon as possible.
 

During this process, it passes through several stages of QA, Staging etc., and before for delivery to the PRODUCTION system.
Q135) What are the tasks also responsibilities of DevOps engineer?

In this role, you’ll work collaboratively including software engineering to use and operate our systems. Help automate also streamline our procedures and processes. Build also maintain tools for deployment, monitoring, including operations. And troubleshoot and resolve problems in our dev, search and production environments.
Q136) What is defined DevOps engineer should know?

DevOps Engineer goes including developers and that IT staff to manage this code releases. They live both developers who become involved through deployment including web services or sysadmins that become a passion for scripting and coding more move into the development design where only can develop this planning from search also deployment.
Q137) How much makes any DevOps engineer make?

A lead DevOps engineer can get between $137,000 including $180,000, according to April 2018 job data of Glassdoor. The common salary from any lead DevOps engineer based at the Big Apple is $141,452.
Q138) What mean the specific skills required for a DevOps engineer?

While tech abilities are a must, strong DevOps engineers further possess this ability to collaborate, multi- task, also always place that customer first. critical skills that all DevOps engineer requirements for success.
Q139) What is DevOps also why is it important?

Implementing the new approach would take in many advantages on an organization. A seamless collection up can be performed in the teams of developers, test managers, and operational executives also hence they can work in collaboration including each other to achieve a greater output on a project.
Q140) What is means by DevOps lifecycle?

DevOps means an agile connection between development including operations. It means any process followed by this development because well because of help drivers clean of this starting of this design to production support. Understanding DevOps means incomplete excuse estimated DevOps lifecycle.
Tools for an efficient DevOps workflow. A daily workflow based at DevOps thoughts allows team
 

members to achieve content faster, be flexible just to both experiments also deliver value, also help each part from this organization use a learning mentality.
Q142) Can you make DevOps without agile?

DevOps is one about some key elements to assist you to achieve this. Can you do agile software evolution without doing DevOps But managing agile software development and being agile are a couple really different things.
Q143) What exactly defined is DevOps?

DevOps is all of bringing commonly the structure also process of traditional operations, so being support deployment, including any tools, also practices of traditional construction methods so as source control also versioning.
Q144) Need for Continuous Integration:

•	Improves the quality of software.
•	Reduction in time taken to delivery
•	Allows dev team to detect and locate problems early
Q145) Success factor for the Continuous Integration

•	Maintain Code Repository
•	Automate the build
•	Perform daily checkin and commits to baseline
•	Test in clone environment
•	Keep the build fast
•	Make it easy to get the newest deliverables
Q146) Can we copy Jenkins job from one server to other server?

Yes, we can do that using one of the following ways
•	We can copy the Jenkins jobs from one server to other server by copying the corresponding jobs folder.
•	We can make a copy of the existing job by making clone of a job directory with different names
•	Rename the existing job by renaming the directory
 

Q147) How can we create the backup and copy in Jenkins?

We can copy or backup, we need to backup JENKINS_HOME directory which contains the details of all the job configurations, build details etc.
Q148) Difference between “poll scm” and “build periodically”

Poll SCM will trigger the build only if it detects the change in SCM, whereas Build Periodically will trigger the build once the given time period is elapsed.
Q149) What is difference between docker image and docker container?

Docker image is a readonly template that contains the instructions for a container to start. Docker container is a runnable instance of a docker image
Q150) What is Application Containerization?
It is a process of OS Level virtualization technique used to deploy the application without launching the entire VM for each application where multiple isolated applications or services can access the same Host and run on the same OS.
Get Devops 100% Practical Training
Q151) syntax for building docker image

docker build –f <filename> -t imagename:version
Q152) running docker image

docker run –dt –restart=always –p <hostport>:<containerport> -h <hostname> -v
<hostvolume>:<containervolume> imagename:version
Q153) How to log into a container

docker exec –it <containerID> /bin/bash
Q154) What is Puppet?

Puppet is a Configuration Management tool, Puppet is used to automate administration tasks.
Q155) What is Configuration Management?

Configuration Management is the System engineering process. Configuration Management applied over the life cycle of a system provides visibility and control of its performance, functional, and physical attributesrecording their status and in support of Change Management.
 

Q156) List the Software Configuration Management Features.

•	Enforcement
•	Cooperating Enablement
•	Version Control Friendly
•	Enable Change Control Processes
Q157) List out the 5 Best Software Configuration Management Tools.

•	CFEngine Configuration Tool.
•	CHEF Configuration Tool
•	Ansible Configuration Tool
•	Puppet Configuration Tool.
•	SALTSTACK Configuration Tool.
Q158) Why should Puppet be chosen?

•	It has good community support
•	Easy to Learn Programming Language DSL
•	It is open source
Q159) What is Saltstack?

SaltStack is based on Python programming & Scripiting language. Its also a configuration tool.Saltstack works on a non-centralized model or a master-client setup model. it provides a push and SSH methods to communicate with clients.
Q160) Why should Puppet to be chosen?

There are Some Reason puppet to be chosen.
•	Puppet is open source
•	Easy to Learn Programming Language DSL
•	Puppet has good community support
Q161) Advantages of VCS

1.	Multiple people can work on the same project and it helps us to keep track of the files and documents and their changes.
 

2.	We can merge the changes from multiple developers to single stream.
3.	Helps us to revert to the earlier version if the current version is broke.
4.	Helps us to maintain multiple version of the software at the same location without rewriting.
Q162) Advantages of DevOps

Below are the major advantages
Technical:
1.	Continuous software delivery
2.	Less Complexity
3.	Faster Resolution
Business:
1.	Faster delivery of the features
2.	More stable operating environment
3.	Improved communication and collaboration between various teams
Q163) Use cases where we can use DevOps

1.	Explain the legacy / old procedures that are followed to develop and deploy software
2.	Problems of that approach
3.	How can we solve the above issues using DevOps.
For the 1st and 2nd  points, development of the application, problems in build and deployment, problems in operations, problems in debugging and fixing the issues
For 3rd  point explain various technologies we can use to ease the deployments, for development, explain about taking small features and development, how it helps for testing and issue fixing.
Q164) Major difference between Agile and DevOps

Agile is the set of rules/principles and guidelines about how to develop a software. There are chances that this developed software works only on developer’s environment. But to release that software to public consumption and deploy in production environment, we will use the DevOps tools and Techniques for the operation of that software.
In a nutshell, Agile is the set of rules for the development of a software, but DevOps focus more on Development as well as Operation of the Developed software in various environments.
 

Q165) What Are the Benefits Of Nosql?

•	Non-relationals and schema-less data models
•	Low latency and high performance
•	Highly scalable
Q166) What Are Adoptions Of Devops In Industry?

•	Use of the agile and other development processes and methods.
•	Demand for an increased rate of the production releases from application and business.
•	Wide availability of virtuals and cloud infrastructure from both internal and external providers;
•	Increased usage of the data center ,automation and configuration management tools;
•	Increased focus on the test automation and continuous integration methods;
•	Best practices on the critical issues.
Q167) How Is the Chef Used As a Cm Tool ?

Chef is the considered to be one of the preferred industry-wide CM tools. Facebook migrated its an infrastructure and backend IT to the Chef platform, for example. Explain how to the Chef helps you to avoid delays by automating processes. The scripts are written in Ruby. It can integrate with a cloud-based platforms and configure new systems. It provides many libraries for the infrastructure development that can later to be deployed within a software. Thanks to its centralized management system, one of the Chef server is enough to be used as the center for deploying various policies.
Q168) Why Are the Configuration Management Processes And Tools Important ?

Talk about to multiple software builds, releases, revisions, and versions for each other software or testware that is being developed. Move on to explain the need for storing and maintaining data, keeping track of the development builds and simplified troubleshooting. Don’t forget to mention that key CM tools that can be used to the achieve these objectives. Talk about how to tools like Puppet, Ansible, and Chef help in automating software deployment and configuration on several servers.
Q169) Which Are the Some Of the Most Popular Devops Tools ? The most popular DevOps tools included`
•	Selenium
•	Puppet
 

•	Chef
•	Git
•	Jenkins
•	Ansible
Q170) What Are the Vagrant And Its Uses?

Vagrant used to virtual box as the hypervisor for virtual environments and in current scenario it is also supporting the KVM. Kernel-based Virtual Machine.
Vagrant is a tool that can created and managed environments for the testing and developing software. Devops Training Free Demo
Q171) How to Devops Is Helpful To Developers ?

To fix the bug and implements new features of the quickly. It provides to the clarity of communications among team members.
Q172) Name of The Popular Scripting Language Of the Devops ?

Python
Q173) List of The Agile Methodology Of the Devops?

•	DevOps is a process
•	Agile is the same as DevOps.
•	Separate group are framed.
•	It is problem solving.
•	Developers managing production
•	DevOps is the development-driven release management
Q174) Which Are The Areas of Devops Are Implemented?

•	Production Development
•	Creation of the productions feedback and its development
•	IT Operations development
 

Q175) The Scope For SSH ?

•	SSH is a Secure Shell which provides users with a secure, encrypted mechanism to log into systems and transfer files.
•	To log out the remote machine and worked on command line.
•	To secure encrypted of the communications between two hosts over an insecure network.
Q176) What Are The Advantages Of Devops With Respect To the Technical And Business Perspective?
Technical benefits
•	Software delivery is continuous.
•	Reduces Complexity in problems.
•	Faster approach to resolve problems
•	Manpower is reduced.

Business benefits
•	High rate of delivering its features
•	Stable operating environments
•	More time gained to Add values.
•	Enabling faster feature time to market
Q177) What Are The Core Operations Of the Devops In Terms Of the Development And Infrastructure ?
The core operations of DevOps
•	Application development
•	Code developing
•	Code coverage
•	Unit testing
•	Packaging
•	Deployment With infrastructure
•	Provisioning
 

•	Configuration
•	Orchestration
•	Deployment
Q178) What Are The Anti-patterns Of Devops?

A pattern is common usage usually followed. If a pattern of thecommonly adopted by others does not work for your organization and you continue to blindly follow it, you are essentially adopting an anti- pattern. There are myths about DevOps.
Some of them include
•	DevOps is a process
•	Agile equals DevOps
•	We need a separate DevOps group
•	Devops will solve all our problems
•	DevOps means Developers Managing Production
•	DevOps is Development-driven release management
•	DevOps is not development driven.
•	DevOps is not IT Operations driven.
•	We can’t do DevOps – We’re Unique
•	We can’t do DevOps – We’re got the wrong people
Q179) What are The Most Important Thing Devops Helps Us Achieve?

The most important thing that the DevOps helps us achieve is to get the changes into production as quickly as possible while that minimizing risks in software quality assurance and compliance. This is the primary objective of DevOps.
For example clear communication and better working relationships between teams i.e. both of the Ops team and Dev team collaborate together to deliver good quality software which in turn leads to higher customer satisfaction.
Q180) How Can Make a Sure New Service Is Ready For The Products Launched?

•	Backup System
•	Recovery plans
 

•	Load Balancing
•	Monitoring
•	Centralized logging
Are You Interested in DevOps Course ? Click here
Q181) How to All These Tools Work for Together?

•	Given below is a generic logical of the flow where everything gets are automated for seamless delivery. However, its flow may vary from organization to the organization as per the requirement.
•	Developers develop the code and this source code is managed by Version Control System of the tools like Git etc.
•	Developers send to this code of the Git repository and any changes made in the code is committed to this Repository.
•	Jenkins pulls this code from the repository using the Git plugin and build it using tools like Ant or Maven.
•	Configuration managements tools like puppet deploys & provisions testing environment and then Jenkins releases this code on the test to environment on which testing is done using tools like selenium.
•	Once the code are tested, Jenkins send it for the deployment on production to the server (even production server are provisioned & maintained by tools like puppet).
•	After deployment Its continuously monitored by tools like Nagios.
•	Docker containers provides testing environment to the test the build features.
Q182) Which Are The Top Devops Tools?

The most popular DevOps tools are mentioned below
•	Git Version Control System tool
•	Jenkins Continuous Integration tool
•	Selenium Continuous Testing tool
•	Puppet, Chef, Ansible are Configuration Management and Deployment tools
•	Nagios Continuous Monitoring tool
 

•	Docker Containerization tool
Q183) How to Devops Different From the Agile / Sdlc?

Agile are the set of the values and principles about how to produce i.e. develop software.
Example if you have some ideas and you want to the turn those ideas into the working software, you can use the Agile values are principles as a way to do that. But, that software might only be working
on developer’s laptop or in a test environment. You want a way to quickly, easily and repeatably move that software into the production infrastructure, in a safe and simple way. To do that you needs are DevOps tools and techniques.
You can summarize by saying Agile of the software development methodology focuses on the development for software but DevOps on the other hand is responsible for the development as well as deployment of the software to the safest and most reliable way to the possible. Here’s a blog that will give you more information of the evolutions of the DevOps.
Q184) What Is The Need For Devops?

According to me, this should start by explaining the general market trend. Instead of the releasing big sets of the features, companies are trying to see if small features can be transported to their customers through a series of the release trains. This have many advantages like quick feedback from the customers, better quality of the software etc. which in turn leads to the high customer satisfaction.
To achieve this, companies are required to
•	Increase deployment frequency
•	Lower failure rate of new releases
•	Shortened lead time between fixes
•	Faster mean time to recovery of the event of new release crashing
Q185) What is meant by Continuous Integration?

It’s the development practice that requires developers to integrate code into a shared repository several times a day. Each check-in then verified by an automated build, allowing teams to the detect problems early.
Q186) Mention some of the useful plugins in Jenkins.

Below, I have mentioned some important are Plugins:
•	Maven 2 project
 

•	Amazon EC2
•	HTML publisher
•	Copy artifact
•	Join
•	Green Balls
Q187) What is Version control?

Its the system that records changes are the file or set of the files over time so that you can recall specific versions later.
Q188) What are the uses of Version control ?

Revert files back to a previous state. Revert to the entire project back to a previous state. Compare changes over time.
See who last modified the something that might to be causing a problem. Who introduced an issue and when.
Q189) What are the containers?

Containers are the of lightweight virtualization, heavier than ‘chroot’ but lighter than ‘hypervisors’. They
provide isolation among processes
Q190) What is meant by Continuous Integration?

It is a development practice that requires are developers to integrate code into the shared repository several times a day.
Q191) What’s a PTR in DNS?

Pointer (PTR) record to used for the revers DNS (Domain Name System) lookup.
Q192) What testing is necessary to insure a new service is ready for production?

Continuous testing
Q193) What is Continuous Testing?

It is the process of executing on tests as part of the software delivery pipelines to obtain can immediate for feedback is the business of the risks associated with in the latest build.
 

Q194) What is Automation Testing?

Automation testing or Test Automation is a process of the automating that manual process to test the application/system under test.
Q195) What are the key elements of continuous testing?

Risk assessments, policy analysis, requirements traceabilities, advanced analysis, test optimisation, and service virtualisations
Q196) What are the Testing types supported by Selenium?

Regression testing and functional testing
Also Read>> Top Selenium Interview Questions & Answers
Q197) What is Puppet?

It is a Configuration Management tool which is used to the automate administration of the tasks.
Q198) How does HTTP work?

The HTTP protocol are works in a client and server model like most other protocols. A web browser using which a request is initiated is called as a client and a web servers software which are the responds to that request is called a server. World Wide Web Consortium of the Internet Engineering Task Force are two importants spokes are the standardization of the HTTP protocol.
Q199) Describe two-factor authentication?

Two-factors authentication are the security process in which the user to provides two means of the identification from separate categories of credentials.
Q200) What is git add?

adds the file changes to the staging area
Become an DevOpsCertified Expert in 25Hours
Q201) What is git commit?

Commits the changes to the HEAD (staging area)
Q202) What is git push?

Sends the changes to the remote repository
 

Q203) What is git checkout?

Switch branch or restore working files
Q204) What is git branch?

Creates a branch
Q205) What is git fetch?

Fetch the latest history from the remote server and updates the local repo
Q206) What is git merge?

Joins two or more branches together
Q207) What is git pull?

Fetch from and integrate with another repository or a local branch (git fetch + git merge)
Q208) What is git rebase?

Process of moving or combining a sequence of commits to a new base commit
Q209) What is git revert?

To revert a commit that has already been published and made public
Q210 What is git clone?

Ans: clones the git repository and creates a working copy in the local machine
Q211) What is the difference between the Annie Playbook book and the characters?

Roles
The characters are a restructured entity of a play. Plays are on playbooks.
A set of functions to accomplish the specific role. Maps between hosts and roles. Example: Common, Winners. Example: site.yml, fooservers.yml, webservers.yml.
Q212) How do I see all the ansible_ variables list?

By naturally collecting “facts” about the machines, these facts can be accessed in Playbooks and in templates. To see a list of all the facts about a computer, you can run a “setup” block as an ad hoc activity: Ansible -m system hostname
It will print a dictionary of all the facts available for that particular host.
 

Q213) What is Doctor?

Docax is a container technology that connects your application and all its functions into the form of containers to ensure that you are running uninterrupted in any situation of your use.
Q214) What is the Tagore film?

Tucker is the source of the dagger container. Or in other words, dagger pictures are used to create containers.
Q215) What is the tooger container?

Dogger Container is a phenomenon of the film.
Q216) Do we consider Dev Devils as a smart way?

Of course, we !! The only difference between dynamic algorithms and DevObs is that the dynamic process is implemented for the development section and activates both DevOps development and functionality.
Q217) What are the benefits of using Git?

Data personality and copy Get high
only one. A directory directory in the repository High disk usage and network performance Joint friendship
Git can use any kind of projects.
Q218) What is kernel?

A kernel, the software that can easily change the hardware interfaces of your computer.
Q219) What is the difference between grep -i and grep -v?

I accept this value
L) ls | grep -i docker Dockerfile docker.tar.gz
ls | grep -v docker Desktop Dockerfile
 

Documents Downloads
You can not find anything with name docker.tar.gz
Q220) You can define a specific location for the file

This feature is generally used to give the server a replacement location. Let me tell you on the computer below and I want to create 1GB swap space,
dd if = / dev / zero = = / swapfile1 bs = 1G count = 1
Get DevOps Training with 100% practical Classes
Q221) What is the concept of sudo in Linux?

Pseudo is an application for Unix-and Linux-based systems that provide the ability to allow specific users
to use specific system commands in the system’s root level.
Q222) What is Jenkins pipe?

Jenkins pipeline (or simply “tube”) is an additional package that supports and activates continuous delivery tube in Jenkins.
Q223) How to stop and restart the toxin container?

Stop container: stop container container ID
Reboot the Tucker Container now: Docer Re-container ID
Q224) Which sites are running by Tagore?

Docax is running on Linux and Cloud platforms only: Ubuntu 12.04 LTS +
Fedora 20+
RHEL 6.5+
CentOS 6+ Gentoo ArchLinux openSUSE 12.3+
CRUX 3.0+
Cloud: Amazon EC2
 

Google Compute Engine Microsoft Asur Rackspace
Since support is not supported, do not work on Windows or Mac for token production, yes, even on windows you can use it for testing purposes
Q225) What are the tools used for taxi networking?

We usually use karfs and taxi bear to do taxi networking.
Q226) What does Tucker write?

You would like to have a number of taxiers containers, and at that time you need to create a file that creates a docer and type the command to make a taxi-up. It runs all containers mentioned in the docer compose file.
Q227) What is a scrum?

Using scrime based on your complex software and product development task as small particles, it uses reboots and additional procedures. Each replay is two weeks. Scrum has three characters: product owner, scrum master and team
Q228) Purpose for SSH?

SSH is a secure shell that allows users to login to a secure, encrypted mechanism into computers and transmitting files.Exit the remote machine and work on the command line.
Protect encrypted communications between the two hosts on an unsafe network.
Q229) Are DevOps implemented?

Product development
Creating product feedback and its development IT Activities Development.
Q230) Do you want to list the active modes of DevOps?

DevOps is a process Like the active DevOps.
A separate group is configured. This will solve the problem.
 

Manufacturers manufacturing production
DevOps is a development-driven output management
Q231) Do you list the main difference between active and DevOffice?

Agile:
There is something about dynamic software development Devops:
DevOps is about software deployment and management.
DevOps does not replace the active or lean. By removing waste, by removing gloves and improving regulations, it allows the production of rapid and continuous products.
Q232) For the popular scripting language of DevOps?

Python
Q233) How does DevOps help developers?

To correct the defect and immediately make innovative attributes.
This is the accuracy of the coordination between the members of the group.
Q234) What is Vegand and its Uses?

Virtual virtual box has been used as a hyperversion for virtual environments and in the current scenario it supports KVM. Kernel-based virtual machine
Vegant is a tool for creating and managing the environment for making software and experiments. Tutorials Tutorial Free Demo
Q235) What is the main difference between Linux and Unix operating systems?

Unix:
It belongs to the multitasking, multiuser operating system family. These are often used on web servers and workstations.
It was originally derived from AT & T Unix, which was started by the Bell Labs Research Center in the 1970s by Ken Thompson, Dennis Ritchie, and many others.
Operating systems are both open source, but the comparison is relatively similar to Unix Linux. Linux:
Linux may be familiar to each programming language.
 

These personal computers are used.
The Unix operating system is based on the kernel.
Q236) How can we ensure how to prepare a new service for the products launched?

Backup system Recovery plans Load balance Tracking Centralized record
Q237) What is the benefit of NoSQL?

Independent and schema-less data model Low latency and high performance
Very scalable
Q238) What is the adoption of Devokos in the profession

1.	Use of active and other developmental processes and methods.
2.	An increased ratio of production output is required from use and business.
3.	Virtual and Cloud Infrastructure Transfers from Internal and Outdoor Providers;
4.	Increased use of data center, automation and configuration management tools;
5.	Focusing on testing automation and serial coordination systems;
6.	Best Practices in Important Problems
Q239) What are the benefits of NoSQL database on RDBMS?

Benefits:
1.	ETL is very low
2.	Support for structured text is provided
3.	Changes in periods are handled
4.	Key Objectives Function.
5.	The ability to measure horizontally
6.	Many data structures are provided.
7.	Vendors may be selected.
 

Q240) The first 10 capabilities of a person in the position of DevOp should be.

The best in system administration Virtualization experience
Good technical skills Great script
Good development skills
Chef in the automation tool experience People management
Customer service
Real-time cloud movements
Who’s worried about who
Q241) What is PTR in DNS?

The PNS (PTR) registration is used to turn the search DNS (Domain Name System).
Q242) What do you know about DevOps?

Your answer should be simple and straightforward. Start by explaining the growing importance of DevOps in information technology. Considering that the efforts of the developments and activities to accelerate the delivery of software products should be integrated, the minimum failure rate. DevOps is a value-practical procedure in which the design and performance engineers are able to capture the product level or service life cycle across the design, from design and to the design level
Q243) Why was Dev’s so important in the past few years?

Before discussing the growing reputation of DevOps, discuss the current industry scenario. The big players like Netflix and Facebook begin with some examples of how this business can help to develop and use unwanted applications. Facebook’s continuous use and coding license models, and how to measure it, while using Facebook to ensure the quality of the experience. Hundreds of lines are implemented without affecting ranking, stability and security. Dipops Training Course
Your next application must be Netflix. This streaming and on-the-video video company follows similar procedures with complete automated processes and systems. Specify user base of these two companies: Facebook has 2 billion users, Netflix provides online content for more than 100 million users worldwide. Reduced lead time between the best examples of bugs, bug fixes, runtime and continuous supplies and the overall reduction of human costs.
 

Q244) What are some of the most popular DevOps tools?

The most popular DevOps tools include:
Selenium Puppet Chef
Git information Jenkins
Ansible
Tucker Tipps Online Training
Q245) What is Version Control, and why should VCS use?

Define the control bar and talk about any changes to one or more files and store them in a centralized repository. VCS Tools remembers previous versions and helps to:
Make sure you do not go through changes over time.
Turn on specific files or specific projects to the older version. Explore the problems or errors of a particular change.
Using VCS, developers provide flexibility to work simultaneously on a particular file, and all changes are logically connected.
Q246) Is There a Difference Between Active and DevOps? If yes, please explain

As a DevOps Engineer, interview questions like this are very much expected. Start by explaining the clear overlap between DevOps and Agile. Although the function of DevOps is always synonymous with dynamic algorithms, there is a clear difference between the two. Agile theories are related to the soft product or development of the software. On the other hand, DevOps is handled with development, ensuring quick turnaround times, minimal errors and reliability by installing the software continuously.
Q247) Why are structural management processes and tools important?

Talk about many software developments, releases, edits and versions for each software or testware. Describe the need for data storage and maintenance, development of developments and tracking errors easily. Do not forget to mention key CM tools that can be used to achieve these goals. Talk about how the tools, such as buffet, aseat, and chef are useful in automating software deployment and configuration on multiple servers.
 

Q248) How is the chef used as a CM tool?

Chef is considered one of the preferred professional CM Tools. Facebook has changed its infrastructure and the Shef platform keeps track of IT, for example. Explain how the chef helps to avoid delays by automating processes. The scripts are written in ruby. It can be integrated into cloud-based platforms and configures new settings. It provides many libraries for infrastructure development, which will then be installed in a software. Thanks to its centralized management system, a chef server is sufficient to use various policies as the center of ordering.
Q249) How do you explain the concept of “Infrastructure Index” (IAC)?

This is a good idea to talk about IAC as a concept, sometimes referred to as a programming program, where the infrastructure is similar to any other code. The traditional approach to managing infrastructure is how to take a back seat and how to handle manual structures, unusual tools and custom scripts
Q250) List the essential DevOps tools.

Git information Jenkins Selenium Puppet
Chef Ansible Nagios Laborer Monit
El-Elistorsch, Lestastash, Gibbon Collectd / Collect
Git Information (Gitwidia)
Q251) What are the main characters of DevOps engineers based on growth and infrastructure?

DevOps Engineer’s major work roles Application Development Developing code
Code coverage Unit testing
 

Packaging
Preparing with infrastructure Continuous integration Continuous test
Continuous sorting Provisioning Configuration Orchestration Deployment
Q252) What are the advantages of DevOps regarding technical and business perspective?

Technical Advantages:
Software delivery continues. Problems reduce austerity.
Fast approach to solving problems Humans are falling.
Business Benefits:
The higher the rate for its features Fixed operating systems
It took too long to add values. Run fast time for the market
Learn more about DevOps benefits from this information blog.
Q253) Purpose for SSH?

SSH is a secure shell that allows users to login to a secure, encrypted mechanism into computers and transmitting files.
Exit the remote machine and work on the command line.
Protect encrypted communications between the two hosts on an unsafe network.
Q254) Which part of DevOps is implemented?

Product development
Creating product feedback and its development IT Activities Development
 

Q255) List the DevOps’s active algorithm.

DevOps is a process Like the active DevOps.
A separate group is configured. This will solve the problem.
Manufacturers manufacturing production
DevOps is a development-driven output management
Q256) List the main difference between active and devOps.

Agile:
There is something about dynamic software development Devops:
DevOps is about software deployment and management.
DevOps does not replace the active or lean. By removing waste, by removing gloves and improving regulations, it allows the production of rapid and continuous products.
Q257) For the popular scripting language of DevOps.

Python
Q258) How does DevOps help developers?

Correct the error and activate new features quickly.
It provides clarity of clarity between the members of the group.
Q259) What are the speed and its benefits?

Virtual box has been used as a hyper version for virtual environments and in the current scenario, it supports KVM. Kernel-based virtual machine
Vegant is a tool for creating and managing the environment for making software and experiments.
Q260) What is the use of Anuj?

It is mainly used for information technology infrastructure to manage or use applications for remote applications. We want to sort an app on the nodes of 100 by executing one command, then the animation is actually in the picture, but you need to know or run some knowledge on the animated script.
 

Q261) Provide a Deployment Use Cases in Kubernetes

Deployment Use Cases in Kubernetes are given below:
Use Case 1- Create a Deployment: On the creation of deployment, Pods are created automatically by ReplicaSet in the background.
Use Case 2- Update Deployment: Creation of new ReplicaSet happens and now the deployment is updated. Deployment revisions are updated through these new ReplicaSet.
Use Case 3- Rollback Deployment: If the current deployment state is not steady, rollback of deployment happens. But we can see the container images are updated.
Use Case 4- Scale a Deployment: Based on the requirement, scaling up or scaling down can be performed on each and every deployment.
Use Case 5- Pause the Deployment: To apply various fixes, deployment can be paused and later resumed.
Q262) Give the different methods of pipelines made in Jenkins

Explanatory Pipelines and Scripted Pipelines are the two methods of pipelines made in Jenkins.
Q263) Can you list out some of the core operations of DevOps?

Unit Testing, Deployment, Code Building, Packaging, and Code coverage are the core operations of DevOps.
 

Q264) For a DevOps Engineer, which is the most important scripting language?

Any simple and user-friendly scripting language would suite for a DevOps Engineer. For example, Python is becoming popular while working on DevOps.





















Q266) What are the checks to be done when a Linux build server become slow suddenly?

Perform a check on the following items:
1.	System Level Troubleshooting: You need to make checks on various factors like application server log file, WebLogic logs, Web Server Log, Application Log file, HTTP to find if there are any issues in server receive or response time for deliberateness. Check for any memory leakage of applications.
2.	Application Level Troubleshooting: Perform a check on Disk space, RAM and I/O read-write issues.
3.	Dependent Services Troubleshooting: Check if there is any issues on Network, Antivirus, Firewall, and SMTP server response time.
Q267) In Ubuntu, how will you enable startup sound?

Follow the below steps to enable startup sound in Ubuntu:
1.	In Ubuntu, click on “Control Gear” and click on “Startup Applications”.
 

2.	Startup Application Preference window appears. To add an entry, click on “Add”
3.	Provide the information in the fields such as Command, Name, and Comment. Once the processes are done, logout and login again.
Q268) Provide the steps to create launchers on an Ubuntu desktop

Below are the steps to create launchers on an Ubuntu Desktop:
In Ubuntu system, press Alt+F2.
Type “gnome-desktop-item-edit –create-new~/desktop”. You will get a GUI dialog box which will create a
launcher on Ubuntu desktop.
Q269) Mention some of the top rated DevOps tools

Nagios, Jenkins, Docker, Git, Puppet, Chef, and Selenium are some of the topmost DevOps Tools.
Q270) Write a shell script to add two numbers

Below is the shell script to add two numbers




Q271) What are the technical benefits of DevOps?

With DevOps, you can deliver the features quickly, possible to add values as we have more time and create firm operating environments.
Q272) Give some benefits of Git

Below are some of the useful benefits of Git:
1.	As Git is one of the best-distributed version control system, you will be able to track changes made to a file.
2.	You can revert the changes whenever it is required
 

3.	Central cloud repository is available where the users can commit changes and share with others in the team.
Q273) What is the Git command to add one or more files to staging?

To add one or more files to staging, use the command “git add <filename.> git add**”
Q274) Provide the Git command to send the modifications to the master branch of your remote repository
When you need to send the modifications to the master branch, use the command “git push origin master”
Q275) What is Maven?
Maven is a DevOps tool used for building Java applications which helps the developer with the entire process of a software project. Using Maven, you can compile the course code, perform functionals and unit testing, and upload packages to remote repositories.
Get DevOps Online Training with Real Time Projects
Q276) What is the command to install Maven in Ubuntu system?

To install Maven in Ubuntu system, use the command “sudo apt-get install mvn” or “sudo apt-get install
maven”.
Q277) How will you validate whether the maven is done correctly?

To confirm the installation of Maven, use the command “mvn -version”.
Q278) Provide few differences between DevOps and Agile:

The below tables provides a very few differences between DevOps and Agile:


S. No	Parameters	DevOps	Agile

1.	
Purpose	DevOps to manage the overall engineering process	Agile to manage complex projects

2.	
Team Size	A huge team is required to involve with the work and
communicate with the	
A smaller team is well enough
 
		stakeholders to resolve the issues	


3.	

Implementation	DevOps mainly focus on collaboration and hence there are no frequently permitted framework	

There are few frameworks in Agile which are safe and fray

4.	
Feedback	Feedback is received from internal team	Feedback is received from customers

5.	
Automation	DevOps has a primary goal as Automation.	Agile do no focus on automation though it is helpful

6.	
Tools used	Chef, Puppet, AWS are some of the popular DevOps tools	Kanboard, Jira, Bugzilla are some of the popular Agile tools


Q279) What is JFrog Artifactory in DevOps?

JFrog Artifactory is a binary repository manager which is useful to store the build process outcomes. JFrog afford replication, high availability, disaster recovery, and scalability which works with many cloud storages.
Q280) Write a script in Python for DevOps learners to find palindrome of a sequence

Below is the script in Python for DevOps learners to find palindrome of a sequence




Q281) Give an example for Fibonacci series

Below is an example for Fibonacci series:
 

 


Q282) Explain NumPy in DevOps

There are many packages in Python and NumPy- Numerical Python is one among them. This is useful for scientific computing containing powerful n-dimensional array object. We can get tools from NumPy to integrate C, C++ and so on.
Q283) What are the available cloud computing platforms in DevOps?

Microsoft Azure, Google Cloud, and Amazon Web Services are the top three cloud computing platforms in DevOps.
Q284) Describe Ansible

Ansible is a very simple automation engine which is useful in automating tasks like configuration management, intra-service orchestration, cloud provisioning, and application deployment. Ansible does not use any additional custom security infrastructure or agents and hence this becomes very simple for deployment. By connecting to nodes and pushing out Ansible modules (small programs), you can see the working of Ansible.
Q285) Provide an example of how a simple Ansible playbook appears

Below is an example of simple ansible-playbook:
#Simple Ansible Playbook
 


•	Run command1 on server1
•	Run command2 on server2
•	Run command3 on server3
•	Run command4 on server4
•	Restarting Server1
•	Restarting Server2
•	Restarting Server3
•	Restarting Server4
Q286) Provide an example of how a complex ansible-playbook appears

Below is an example of complex ansible-playbook:
#Complex Ansible Playbook
•	Deploy 50 VMs on Public Cloud
•	Deploy 50 VMs on Private Cloud
•	Provision Storage to all VMs
•	Setup Monitoring Components
•	Setup Cluster Configuration
•	Install and Configure backup clients on VMs
Q287) Can you provide a sample YAML format?

Refer to the below sample YAML format:
#Simple Ansible Playbook1.yml
–
name: Play 1 host: localhost
tasks:

•	name: Execute command ‘date’

command: date
•	name: Execute script on server
 


script: mytest_script.sh
•	name: install httpd service

yum:
name: httpd state: present
•	name: Start web server

service:
name: httpd state: started
Q288) Explain Docker

An open source that automates the application deployment is called a Docker. You can see the Docker container can be seen running in both Windows and Linux systems. Docker technology is promoted to work with vendors like cloud, windows, Linux and Microsoft. Containers are deployed by Docker at all layers of the hybrid cloud.
Q289) Is it possible to consider DevOps as Agile Methodology?

Yes, it is possible to consider DevOps as Agile Methodology, still we have differences between these two. Implementation of DevOps is possible on both development and operations section whereas Agile methodology implementation is possible only on development section.
Q290) List out the tools helpful for docker networking

Docker swarm and Kubernetes are the tools helpful for docker networking.
Q291) Provide the difference between git pull and git fetch

If there are any changes or commits done in the central repository branch, Git pull command performs a pull of those changes and update the local repository targeted branch. Git fetch is little similar to git pull but has a slight difference. When using the git fetch command, all the new commits are pulled from the desired branch and those get stored in the new branch of your local repository. You can make use of git merge once git fetch is done to see the changes in your target branch. Once the merging is done between fetched branch and target branch, the target branch gets updated. Just remember the equation “git merge + git fetch = git pull”.
 

Q292) Explain Git stash drop

To remove the stashed items, use the Git command “stash drop”. By default, it will remove eradicate the
last added stash and also when a specific item is added as an argument, it will be removed.
Q293) Provide few branching strategies

Task Branching, Feature branching and Release branching are the three branching strategies.
1.	Task Branching: Along with the task key comprised in the branch name, each task is employed on its own branch.
2.	Feature branching: The whole changes for a feature is placed inside a branch. Once the feature branch is completely tested and evaluated using automated tests, a merge happens between the branch and master.
3.	Release branching: When the develop branch has acquired enough features for a release, it is possible to clone that specific branch and form a release branch. Once the release branch is formed, we cannot add any new features and the next release cycle starts.
Q294) Define Jenkins

Jenkins, a continuous integration tool is an open source written in Java language. When we experience changes, tracking the version control system, initiating and monitoring a build system are some of the process carried out by Jenkins. On successful tracking and monitoring, notifications and reports are provided to alert the respective squad.
Q295) Can you give me an example of simple Jenkins pipeline?

Below is the best example of simple Jenkins pipeline:


 

 


Q296) Give me the procedure to create Jenkins jobs

Let us have an example to create simple WelcomeGuys application.
1.	Open the Jenkins dashboard and click on “New Item”.
2.	Now enter the item name, for example, WelcomeGuys.
•	Select “Freestyle project” and click “Ok”
1.	You will get a different screen where you need to enter few more details of the job like project name, description, Advanced project options, source code management, branches to build, and repository browser.
2.	Click “Save” to apply the changes made.
3.	Click on Build Now option once the job details are saved.
4.	When the build is scheduled, the build starts to run and the build history section indicates the progress of build.
Q297) What are the points to check when an application is not coming up?

Perform the following checks when an application is not coming up:
1.	Validate all the file logs
2.	Check whether the web server is receiving the user’s request or not
3.	Check the status of process id
4.	Analyse the network connection
 

Q298) What are the tasks performed by Puppet Slave and Puppet Master?

The below image shows the task details performed by Puppet Slave and Puppet Master:









Q299) What are pre-requisites to install and configure Puppet Master server on Linux?

Both client node and master node must be accessible. Make sure you have internet access to both the nodes so that you can install packages from puppet labs repositories. Better to disable the firewalls if enabled just to avoid few issues at the time of configurations.
Q300) In puppet, where you can find codedir?

In windows, you can find in the location “%PROGRAMDATA%\PuppetLabs\code”. In Linux/Unix, you can
find in the location “/etc/puppetlabs/code”.
Q301) Define IaC

IaC stands for Infrastructure as Code. This indicates the automation of IT operations like building, deploying, and managing with the help of code, instead of handling with manual process. Below is a diagrammatic representation of IaC.
 

Q302) Can you provide a diagrammatic explanation on Chef Architecture?

Below is the diagrammatic explanation of chef architecture





























Q303) Give a solution when a resource action is not specified in Chef

Chef applied the default action when a resource action is not specified in Chef. Below is the best example:


 

Q304) Explain NRPE available in Nagios

NRPE stands for Nagios Remote Plugin Executor. This is an addon intended to permit the users to execute Nagios plugins. The vital reason for using this addon is to monitor local resources such as memory usage, CPU load and so on.
Q305) Through SDLC, how Docker provides steady computing environment?

Below are the steps on how Docker provides steady computing environment:
1.	A Docker image is created is built by a Docker file and all the project codes are contained in that image.
2.	You can create many Docker containers by running that image.
3.	Now, you can upload the image on Docker Hub and anyone can pull the image from Docker Hub to build a container.









Q306) Explain Docker Compose

To configure and run applications easily that are made up of multiple containers, you can use Docker Compose. Let us have the below example for Docker Compose:
Three different containers where on running on web app, second on postgres and third container running on redis. All these three are in one single YAML file. Now to run all three connected containers with a single command, Docker Compose is used.
Q307) What is the command in git to modify the commit message?

Use the command “amend” to modify the commit message.
Q308) Give us two methods to install Jenkins

Below are the top two methods to install Jenkins:
1. Download Jenkins archive file
 
 
