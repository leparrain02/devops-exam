# Devops Team test
================

This is a test to evaluate base knowledge for a new candidate

## TEST 
------------
1. File and string manipulation
   
   In the folder /data/devops-exam/origin
   * List all file with a line starting with 3 followed by a digit and
     containing the word **DEVOPS**
   * Change all **NOTVALID** by **ANSIBLE** in all file content    
   * Make a copy of all file '*.txt' in /data/devops-exam/destination after
     renaming them to '<filename>_new.txt'
2. Shell scripting
   * Writing a new script to change text in file and copy the new file in another
     folder.
   * It should receive 3 parameters:searchstr, replacestr and destfolder.  If the number of parameter
     is invalid it should print the usager and exit
3. User creation and permission
   * Create a new user **devops**
   * User should be able to run any command as **root** without password (sudo)
   * User should be able to connect to **localhost** with ssh without having to enter his password
4. Git
   In the folder /data/devops-exam/TomcatRepo
   * Clone the repo [GitHub Testnouveau](https://github.com/leparrain02/testnouveau.git)
   * Create a new branch devel and make this branch active
   * Create a new file 'test.txt' containing 'THIS IS A TEST' and add it to git
   * Merge the branch devel to the master
5. Middleware ( Apache/Tomcat )
