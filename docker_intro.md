What is Docker ?

Docker us an open-source platform that allows you to build, ship and run applications inside containers.
Containers are like lightweight, isolated boxes that contain everything your application needs to run: code, libs, dependencies and settings.
Why Docker ?

Before Docker developers often faced the classic “works on my machine” problem, Moving an app from one env to another was painful.
Docker solves :Packaging apps and dependencies together.
Running the same container images anywhere (laptop, cloud , server)
Speeding up testing and deployement.
How Does Docker Work ?

Docker uses the host operating system’s kernel to run containers (not a full vm).
A docker engine runs on your machine.
You build a docker image (template with your app + dependencies).
You start a container from that image ( a running instance).
Example : docker run hello-world — this downloads a image and runs it in a container.
Advantages :

Lightweight : uses less resources than VMs.
Portable : runs anywhere.
Fast : containers start in seconds.
Version-controlled : images can be tagged and rolled back.
Ecosystems : thousands of ready-to-use images on docker hub.
Disadvantages :

Requires learning curve (commands, images, containers).
Windows support historically weaker than linux (but improving) mostly not an issue for devs.
Conclusion :

Docker has become a must-known tool for devs and DevOps engineers.

In this post. we learned what Docker is, why it is used, how it works at a high level, and its adv&disadv.

In the next post, we’ll install docker and our very first container step by step.