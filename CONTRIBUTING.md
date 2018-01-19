Please provide as much information as possible when reporting a bug or filing an issue on the Visual C++ for Linux Development.
A well written bug will follow the template:

### 1) Issue Title

A title succinctly describing the issue. 

#### Example:

`Build not working with GCC 5.4.`

### 2) Brief description

A brief description of what you are attemping to do.

#### Example:

`I'm trying to use GCC 5.4 with the extension and it isn't working, description of my configuration below.`

### 3) VC++ version / Linux system / environment details

Your Visual Studio and VC++ version number.  This can be seen in the VS Help, About menu. Look for Visual C++ for Linux Development.

Additional information like GCC, GDB versions is also helpful, as are details of your hardware if running on an embedded system.

Here is an example on getting basic Linux system information.
```
uname -a
Linux jinx 4.4.13-v7+ #894 SMP Mon Jun 13 13:13:27 BST 2016 armv7l GNU/Linux
``` 

#### Example:
`Microsoft Visual Studio Community 2015`
`Version 14.0.25421.03 Update 3`
`Visual C++ for Linux Development 1.0.4`
`Linux jinx 4.4.13-v7+ #894 SMP Mon Jun 13 13:13:27 BST 2016 armv7l GNU/Linux`

### 4) Steps required to reproduce

Explanation of how to reproduce the problem, e.g. libraries needed, property page options set, sequence of build, debug steps, packages installed on Linux system, etc.

#### Example:

`On Linux box:`
`sudo add-apt-repository ppa:ubuntu-toolchain-r/test`
`sudo apt-get update`
`sudo apt-get install gcc-5 g++-5`
`In Visual Studio`
`Create console project`
`Set a breakpoint on entry to main and hit F5`

### 5) Copy of the build output window

#### Example:

```
1>------ Build started: Project: ConsoleApplication9, Configuration: Debug ARM ------
1>Build started 7/14/2016 2:19:58 PM.
1>     1>
1>Building with tools version "14.0".
1>     1>
```

### 6) Expected Behavior

What was the expected result of what you expected? Here for example, "It should have built and hit the break point" would be sufficient, other cases may require more explanation to help us understand.

### 8) Additional information

Some bugs require additional information such as scripts to reproduce.  Please add to this section.

If there are files required, email the files to vcpplinux-support@microsoft.com with:
Subject:  RE: github issue <issue #>
Body:  "Here are some supporting files for the issue I filed." and include your attachment.

### 9) Detailed Logs
Some bugs will require more detailed logs to help determine the cause. 

