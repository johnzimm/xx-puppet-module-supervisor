#rentabiliweb-supervisor

####Table of Contents

1. [Overview](#overview)
2. [Module Description](#module-description)
3. [Setup](#setup)
4. [Usage](#usage)
5. [Development](#development)

##Overview

The rentabiliweb-apticron module  enables you to install,  deploy, and configure
supervisor.

##Module Description

Supervisor  is a  client/server  system that  allows its  users  to monitor  and
control a number of processes on UNIX-like operating systems.

It shares  some of  the same  goals of programs  like launchd,  daemontools, and
runit. Unlike some of these programs, it is  not meant to be run as a substitute
for init as “process id 1”. Instead it  is meant to be used to control processes
related to a project or a customer, and is meant to start like any other program
at boot time.

http://supervisord.org/

##Setup

```puppet
class { 'supervisor':
}
```

##Usage

##Development

Rentabiliweb  modules on  the  Puppet  Forge are  open  projects, and  community
contributions are  essential for keeping  them great.  We can’t access  the huge
number  of   platforms  and  myriad   of  hardware,  software,   and  deployment
configurations that  Puppet is intended to  serve so feel free  to contribute on
GitHub.

Thanks https://github.com/puppetlabs/ for help to write this README :)


