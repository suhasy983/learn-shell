We are going to learn Bash Shell Scripting

List of Shell Topics  
Printing  
Variables  
Conditions  
Functions  
Loops   

SED Editor  
SED  
Delete a line  
Add a line  
Change a line  
Search and replace a word  
Sed is available in two forms  

Display the changes on screen sed 'ACTION' FILE  
Edit the file sed -i 'ACTION' FILE  

Action Criteria can be picked in two ways.  
Line Number based  
String search based   
Example like, If we want to delete a line.

For line no criteria

sed '1 d' file

For search string criteria

sed '/root/ d' file

Both the above examples will be just displaying the output, However if we want to edit the file

sed -i '1d' file

sed -i '/root/ d' file

cd /tmp  
cp /etc/passwd .  
ls  
cat passwd  
sed '1d' passwd  
cat passwd  
sed -i '1d' passwd  
cat passwd  
sed -i '/nologin/ d' passwd  
cat passwd  
sed '1 i Hello World' passwd  
sed '/bash/ i Hello World' passwd  
sed '/bash/ a Hello World' passwd  
sed '/bash/ c Hello World' passwd  
cat passwd  
sed 's/halt/poweroff/' passwd  
sed 's/halt/poweroff/g' passwd  
sed 's/bash/BASH/' passwd  
sed 's/bash/ksh/' passwd  
sed '/roboshop/ s/bash/ksh/' passwd  

While we learn any coding, These 4 are kind of pillars to learn  
Variables  
Functions  
Conditions  
Loops  

