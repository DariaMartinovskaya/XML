## GIT Homework 1

## XML
#### 21. Create external repository named XML
Web Git Hub => "Repositories" Tab => [New] Button => Repository Name "XML" => Click "Add a REDMI file" => [Create repository"] Button
#### 22. Clone XML repository to local computer
git clone https://github.com/DariaMartinovskaya/XML.git
#### 23. Create file “new.xml” inside XML repository
touch new.xml
#### 24. Add the file to git
git add new.xml
#### 25. Commit the file
git commit -m new.xml
#### 26. Send the file to external GitHub repository
git push
#### 27. Edit content of “new.xml” file- add the information about yourself (Full name, age, amount of pets, future desired salary). To be written in XML format
vim new.xml => i (edit mode) => {Input data} => "esc" + ":wq" + "Enter" 
#### 28. Send changes to external repository
git add new.xml + git commit -m new.xml + git push
#### 29. Create preferences.xml file
touch preferences.xml
#### 30. Add information about your preferences (favorite film, favorite series, favorite food, favorite season, country you would like to visit) into preferences.xml file in XML format
vim preferences.xml => i (edit mode) => {Input data} => "esc" + ":wq" + "Enter"
#### 31. Create sklls.xml file and add information about skills to be learnt during the course in XML format
touch skills.xml => vim skills.xml => i (edit mode) => {Input data} => "esc" + ":wq" + "Enter" 
#### 32. Make a commit in one line
git add . && git commit -m "comment" 
#### 33. Send 2 files to external repository at the same time
git push
#### 34. Create bug_report.xml file on the web interface
Web Git Hub => Repositories => "XML" => Click [Add file] Button => Choose "Create new file" => Name of the file: "bug_report.xml"
#### 35. Commit changes (save) on the web interface
[Commit changes...] Button => [Commit changes] Button
#### 36. Modify bug_report.xml file on the web interface, add bug report in XML format
Choose bug_report.xml => Edit this file button
#### 37. Commit changes (save) on the web interface
[Commit changes...] Button => [Commit changes] Button
#### 38. Synchronize external and local XML repositories
git pull
