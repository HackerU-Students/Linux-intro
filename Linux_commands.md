| Command  |                          Description                                      |              Example                  |                        Flag                 | 
| ---------|---------------------------------------------------------------------------|---------------------------------------|---------------------------------------------|
| ssh      | Used for secure remote access to a system                                 | ssh username@192.168.1.50             |-l,-i,-p,-X,-L,-R,-C,-f,-N,-T,-o,-v          |
| ls       | List directory contents                                                   | ls -l                                 |-l,-a,-lh,-R,-t,-lr,-S,-i,-F,--color=auto,-G |
| pwd      | Print the current working directory                                       | pwd                                   |-L,-P                                        |
| cd       | Change directory to a different folder                                    | cd /home/username                     |
| touch    | Create an empty file or update the modified timestamp of an existing file | touch newfile.txt                     |
| echo     | Print a message or the value of a variable                                | echo "Hello, World!"                  |
| nano     | A simple text editor                                                      | nano example.txt                      |
| vim      | A more advanced text editor with many features                            | vim example.txt                       |
| cat      | Print the contents of a file to the console                               | cat file.txt                          |
| shred    | Securely delete a file by overwriting its contents                        | shred -u sensitive.txt                |
| mkdir    | Create a new directory                                                    | mkdir newdirectory                    |
| cp       | Copy a file from one location to another                                  | cp file1.txt /path/to/destination/    |
| mv       | Move a file from one location to another, or rename a file                | mv oldname.txt newname.txt            |
| rm       | Remove a file                                                             | rm unwantedfile.txt                   |
| rmdir    | Remove a directory if it is empty                                         | rmdir emptydirectory                  |
| ln       | Create a link to a file or directory                                      | ln -s /path/to/original /path/to/link |
| clear    | Clear the console                                                         | clear                                 |
| useradd  | Add a new user to the system                                              | sudo useradd newusername              |
| sudo     | Run a command with administrative privileges                              | sudo apt-get update                   |
| adduser  | Add a new user to the system with more options than useradd               | sudo adduser newusername              |
| su       | Switch to another user account                                            | su - username                         |
| exit     | Close the current terminal or log out of the current user account         | exit                                  |
| passwd   | Change the password for the current user                                  | sudo passwd                           |
| apt      | A package manager used to install, update and remove software packages    | sudo apt update                       |
| finger   | Display information about a user                                          | finger username                       |
| man      | Display the manual page of a command                                      | man ls                                |
| whatis   | Display a brief description of a command                                  | whatis ls                             |
| which    | Locate a command and display its path                                     | which python                          |
| whereis  | Locate the binary, source, and manual page files for a command            | whereis ls                            |
| wget     | Download files from the web                                               | wget http://example.com/file.zip      |
| curl     | Transfer data to or from a server                                         | curl -O http://example.com/file.zip   |
| zip      | Compress files into a zip archive                                         | zip archive.zip file1 file2           |
| unzip    | Extract files from a zip archive                                          | unzip archive.zip                     |
| less     | View a file one page at a time                                            | less file.txt                         |
| head     | Display the first lines of a file                                         | head -n 10 file.txt                   |
| tail     | Display the last lines of a file                                          | tail -n 10 file.txt                   |
| cmp      | Compare two files byte by byte                                            | cmp file1 file2                       |
| diff     | Display the differences between two files                                 | diff file1 file2                      |
| sort     | Sort the lines of a file                                                  | sort file.txt                         |
| find     | Search for files in a directory hierarchy                                 | find /path -name filename             |
| chmod    | Change the permissions of a file or directory                             | chmod 755 script.sh                   |
| chown    | Change the owner of a file or directory                                   | chown user:group file.txt             |
| ifconfig | Configure network interfaces                                              | ifconfig eth0 up                      |
| ping     | Test network connectivity by sending packets to a host                    | ping google.com                       |
| netstat  | Display network connections, routing tables, and interface statistics     | netstat -an                           |
| -tulpn   | Display active listening ports and associated programs                    | netstat -tulpn                        |
| ss       | Display socket statistics                                                 | ss -tuln                              |
| iptables | Configure and administer the netfilter firewall                           | sudo iptables -L                      |
| ufw      | A user-friendly interface to manage iptables firewall rules               | sudo ufw enable                       |
| uname    | Print  kernel name, network node hostname,kernel release, kernel version  |                                       | 
| neofetch | Display system information in a colorful and visually appealing way       | neofetch                              |
| cal      | Display a calendar of the current month or year                           | cal                                   |
| free     | Display the amount of free and used system memory                         | free -h                               |
| df       | Display disk usage statistics for a file system                           | df -h                                 |
| ps       | Report a snapshot of current processes                                    | ps aux                                |
| top      | Display dynamic real-time information about running processes             | top                                   | 
| kill     | Send a signal to terminate a process                                      | kill -9 1234                          |
| pkill    | Send a signal to terminate one or more processes based on their name      | pkill firefox                         |
| systemctl| Control the systemd system and service manager                            | sudo systemctl start apache2          |
| history  | Display previously executed commands                                      | history                               |
| reboot   | Reboot the system with administrative privileges                          | sudo reboot                           |
| shutdown | Shutdown or reboot the system                                             | sudo shutdown -h now                  |