# Week 3 of DevOps with SpartaGlobal

### What is DevOps?
* A union of a *Developers* and *Operations*
* Enables the previously siloed teams to start working together in cooperation
### Why DevOps?
* Adds value and time cost saving measures
* Better coordination between tasks such as services and development
* Higher quality and consistent product output 
### 4 Pillars
* Continuous Planning
* Continuous Integration
* Continuous Delivery
* Continuous Operations


## Vagrant

*nginx location:* http://192.168.56.0/


### Usefull comands
```
vagrant up
vagrant reload
vagrant destroy  
```
#### Linux Commands

```
sudo apt-get upgrade -y
whoami
uname -a
pwd
cp /file/ /destination/location
mv /file/ /destination/location - Can change the
cd is for navingation
rm is for deletion

```
#### File Permissions

- read 'r' 
- Write 'w' 
- exec 'x'

- Change permision `chmod` + permision file/
- find out the processes running with `top` and `htop`
- to kill a processs `pkill` and then a process name
- another way is to use `kill` and then a process number

## Task

**Commands**

* head -2
* tail -2

*Pipping*

`cat sample.txt | head -4 | tail -2`

Pipping "|" carries the output to the commands following the |, for example,
in this command the cat will output the contents of sample.txt, it will 'pipe' into head,
meaning it will output only the first four files, after which it will carry or 'pipe' command into the tail.
the tail will then output from the first 4 the endings of the last two via the tail command.


## Development Environment



