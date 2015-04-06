# Editors

The first and foremost ingredient of any working environment is editors. Here by editors I means tools to edit files. People have different preferences and different groups of preferences often argue with their choices. Some people prefer IDEs, while other people likes text editors. Some people are GUI oriented [This has nothing to do with IDEs, though.]

# My criteria for editors

For me, editors are simply editors. I use editors to accomplish text editing part of the work. So my criteria for editors comes as follows:

1. Speed: how fast and convenient can I process text in them.
2. Availability: is the editor available on all platforms I use? Can I deploy it easily if not?
3. Extensibility: since my needs changes overtime, I need it to be extensible to cope with new needs.

The above criteria excludes most of the current IDEs. IDEs do some part of programming work efficiently but fail both on availability and extensibility. Among IDEs I tried, I want to discuss Eclipse and QtCreator. 

## About Eclipse

Eclipse is a comprehensive platform. It's omnipotent. By install the CDT plugin, it can be used as a C/C++ IDE. By installing the Egit plugin, It's integrated with git version control. One can even install plugins to make it manage computing clusters and do parallel computing.

The problem of Eclipse in my case is that It needs GUIs to function. So not avaliable on any of my clusters. It's also slow to start due to heavy JAVA dependency. JAVA availability used to be a problem but now we have OpenJDK on almost every Linux distribution. It does not support the edit-compile-run-edit programming cycle efficiently due to its slow startup.

So, although Eclipse is a nice platform, I pass over it.

## About QtCreator

QtCreator is a nimble IDE. It's mainly focused on C/C++ projects and is fast compared to Eclipse. It does not use JAVA but compiled directly to machine code. 





