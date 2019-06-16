<h1>zfs 0.8.1 on Ubuntu 19.04</h1>
Note: zfs 0.8+ provides encryption

&emsp;

## © 2019-present Harald Rudell <harald.rudell@gmail.com> (http://www.haraldrudell.com)

&emsp;

Because zfs 0.8 probably will not be in Ubuntu for months, here is a download source-build-install script runnable on Ubuntu 19.04. We can have <strong>encrypted zfs</strong> today

Note: 0.8.1 was released yesterday 6/14/2019

<h2>Just Run It!™</h2>
Execute <strong>buuld-zfs-0.8.1</strong> from a bash shell. In 20 minutes, this downloads, builds and installs zfs 0.8.1 on an Ubuntu system

<h2>Pesky Old Kernel Modules</h2>
Because Ubuntu includes 0.7.12 kernel modules for zfs, there is a need to run <strong>disable-zfs-kms-0.7.12</strong> to remove those and instead load the 0.8.1 kernel modules. Previous modules are backed up to the home directory. If that fails somehow, just manually get through the command in the script, it is not complicated

<h2>What if no work?</h2>
This worked for me on 6/15/2019. It is significantly easier to fix something that once worked than start from zero. This is unlikely to break Ubuntu. Google is your friend
&emsp;

## © 2019-present Harald Rudell <harald.rudell@gmail.com> (http://www.haraldrudell.com)

&emsp;
