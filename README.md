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







