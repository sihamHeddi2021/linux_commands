# linux_commands

## Ls command

* ls -l : long list (details)
* ls -a : list all (including hidden dir or files )
* ls -S : sort list depends on file size
* you can combine these options
* ls <name-dir>/*.html : get only html files
* ls <name-dir>/*.* : any type of files
* ls > out.txt : save command result inside out.txt 
* ls -R

## Cd command 

* cd ~ => move to home directory
* cd / => move to roo directory

## Cat command

* cat => to display the content of filw
* cat -s => squeeze space
* cat -b => set numbers for non empty lines
* cat -n => set numbers for all lines
* cat -e => set $ to the end of line
* cat > list.txt => create new file with name
 "list.txt" if doesnot exist than copy the content what 
you have wrote in terminal 
* cat list2.txt >> list3.txt => append 
* cat <filename1> <filename2>

## mkdir command

* mkdir <dir_name>
* mkdir -p <dir_name1>/<dir_name2> => if dir_name1 does not exist
* mkdir <dir_name>/{sub1,sub2,sub3} => to create multiple sub 
directories in same time


## rm & rmdir command

* rm -r => remove non empty directories
* rmdir => remove empty directories
* rmdir -p <dir1>/<dir2>/<dir3> => remove dir1 , dir2, dir3

## cp command

* cp h.txt f.txt
* cp -r dir1 dir2 
* cp -i dir1 dir2 => interactive mode to ask you 
if you would like to overwrite dir2 if exists

## mv command

* mv h.txt l.txt
* mv dir1 dir2
* mv -i s.txt dir1/s.txt

## less command

to show less content

* G => go to the end
* g => go to the top
* up => scroll up
* down => scroll down
* space => go to next page
* ? => search word , n => next word occurance
* q => to quit

## chmod command 

to change permissions

ls -l =>  <file_type>(r)ead(w)rite(x)exectuble 
u(user) g(group) o(other)

* chmod u+x <file_name> => add exectuble permission for user
* chmod u-x <file_name> => remove //    //          //
* chmod ugo=rwx
* chmod a=rw  
* chmod u-r,g+r,o=rwx

There is also numerical representation :

chmod 746 <file_name>

## adduser command 
sudo useradd -m <username> -s /bin/bash -g users

* -m => create home folder for this user
* -s => default shel
* -g => user groups

## userdel 

* sudo userdel -r <username>
* or remove user home directory

## add,assign user to group, delete group

* sudo groupadd <group_name>
* cat /etc/group 
* sudo groupdel <group_name>
* sudo gpasswd -a <user_name> <group_name>
* sudo gpasswd -d // //

## tar command

* to create tar file => tar -cvf  <out_file.tar> <dir_name>
* to extract tar file => tar -xvf // //

## top command

===== keys =====

* i => only active process
* s => change the duration
* k => to kill process

## kill

* kill <pid>


## pidof 

* pidof <name>

## ps 

* ps -aux => for all users
* ps -U <username>
* ps -C <name> => pid of instances

## df 

storage information for the whole system

* -h => more humanized result

## du 

storage for specific directory 

* -s => summary


## free 

* display the amount of free and used memory(also swap memory ) in the system
* -m => megabyte
* -k => kilobyte
* -g => gigabyte
and so on .....

## whatis

short descritption of command

## which 

the location of command

## watch

* to watch command every 2 seconds
* you can change the duration by typing "watch -n <number_of_seconds> <command>"

## head, tail 

* head => show top of file
* head -n3 => show first three lines 
* tail => show bottom of file
* tail -f => dont quit the command to append more new results if file has been changed 

## find 

* find <location> -name <pattern | file_name> 
* find <location> -mtime (+<number_of_days> => before specified number of days 
, - => after days, none => in specified day )

## grep 

to search patterns in specified file

* grep -i "pattern" => insensative
* grep -n => show number 
* grep -V => show lines those dont contain
 the specified pattern

 







