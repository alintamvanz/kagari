# kagari
Kagari adalah software di tullis dengan perl yang berfungsi untuk menemukan shell backdoor di suatu website
<pre>



root@kagari:~#  git clone https://github.com/alintamvanz/kagari.git
root@kagari:~# chmod 755 -R kagari
root@kagari:~# cd kagari
root@kagari:~/kagari # ./install

----------------------------------------------------------------------------------------------------------------------------------
This tool is created to help you find the file, a shell, a directory in a website.

instructions for use :

kagari run         : to run this tool
kagari -h/--help   : to see this
kagari --uninstall : to uninstall this tool on your system


the instructions for use "kagari run" :

kagari:WordlistTarget   >> YourWordlistTarget.txt

[*] Before you must create or write list of target separated by "," (comma) as the default wordlist of kagari.
[*] It should be considered also for its location directory wordlist

kagari:WordlistPassword >> wordlist.txt

[*] wordlist separated by "," (comma) as the default wordlist of Kagari, you can create your own wordlist
[*] It should be considered also for its location directory wordlist

kagari:SOShell  >> Home|shell|Files     

[*] It is a word or phrase that is in the shell, file, or directory you are looking for. This helps locate the file you're looking for using the Regular Expression
[*] Read more about regex : https://en.wikipedia.org/wiki/Regular_expression


----------------------------------------------------------------------------------------------------------------------------------
