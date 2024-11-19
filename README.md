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


















