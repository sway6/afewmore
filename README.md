# afewmore command

![Shurnim icon](https://codemaxx.github.io/assets/images/emoji/terminal.png)

## Directory
* [Project Introduction](#项目介绍)
* [Instructions For Use](#使用说明)
  * [get the source code](#获取代码)
  * [Synopsis](#开发插件)
* [Others](#其他)

<a name="项目介绍"></a>
## Projecte Introduction
*"afewmore"* -- duplicate EC2 instances with their data directory<br>

The *"afewmore tool"* can be used to duplicate a given EC2 instance.  When doing so, it creates multiple new instances and populates their data directory by copying the data from the original.
  
I have a course to learn system administration. Including run different command line on different systems such as **netBSD**, **sunSolar**, **linux** and so on. Some times I need to create the same type of instance for multiple times, so i decide to develop a command tool to create several same type of instances at one time.

This command tool really save my time.

I developed this command tool using **shell script**

<a name="使用说明"></a>
## Instructions For Use

<a name="获取代码"></a>
### Get the source code

* github:<https://github.com/sway6/afewmore/blob/master/afewmore.txt>

   
<a name="开发插件"></a>
### Synopsis
afewmore [-hv] [-d dir] [-n num] instance

    -d dir:   
    
    Copy the contents of this data directory                from the orignal source instance to all the new instances.  If not specified, defaults to /data.

    -h  :       
    Print a usage statement and exit.

    -n num:   
    Create this many new instances.  If not specified,   defaults to 10.

    -v:
    Be verbose.

<a name="其他"></a>
## Others
It's my pleasure to share my opinion and receive suggestions from you.

By the way, I am a new graduate student major in computer science. Now looking for an entry level Software Engineer position.

if you have suggestions about my code or working chance, please contact me

* Email: <bxrbaixinrui@gmail.com>
