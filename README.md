# Devops Team test
================

This is a test to evaluate base knowledge for a new candidate

## TEST 
------------
1. File and string manipulation
   
   In the folder /data/devops-exam/origin
   * List all file containing the word **DEVOPS**
   * List all file containing the word **DEVOPS** or **KUBE**
   * List all file with a line starting with **3** followed by a digit and
     containing the word **DEVOPS**
   * Change all **NOTVAL** by **ANSIBLE** in all file content    
   * Make a copy of all file '*.txt' in /data/devops-exam/destination after
     renaming them to '<filename>_new.txt'
2. Shell scripting
   * Writing a new script mytestdevops.sh
   * The script should be executable
   * It should receive 2 parameters: sourcefolder and destfolder.  If the number of parameter
     is invalid it should print the usager and exit
   * If the source folder doesn't exist, it should print and error and exit.
   * If the dest folder doesn't exist, it should create it.
   * It should include the lib /data/devops-exam/lib/testfunc.sh
   * For each file '*.txt' in the source folder, it should call the function 'devops_exam'.  The function needs 2 parameters: the file and the dest folder.
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
   Tomcat7 is already install on the server. You need to:
   * Copy /data/devops-exam/TomcatRepo/ROOT.war in the webapps folder of Tomcat
   * Install Apache
   * Make sure Apache will restart automatically after a reboot
   * Connect the path /devops-exam/ to the root folder of Tomcat with the protocol AJP.
