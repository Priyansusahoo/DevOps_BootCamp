# Linux Commands
  - ls         :     List information about the files.

  - mkdir      :     Creating new directory.

  - cd         :     Changing the directory.

  - touch      :     Create an empty file.

  - vi         :     Text-Editor.

  - cat        :     Reading the files sequentially.

  - cp         :     Copy command.

  - mv         :     Move command.

  - chmod      :     Changing file permission.

  - kill       :     Killing the process.

  - env        :     Getting the list of environment variables.

                    E.g: // To create a new env:

                              $export demo=training

                         // View the specific variable by:

                              $echo $demo

  - export     :     Exporting the variables.

  - curl       :     Transfer data from or to a server.

  - tar        :     Archive utility. 

                     E.g: // Extract a file:

                             $tar -xvf <file-name>.

  - du         :     - Disk usage command.

                     e.g: // summary in human readable format.

                             $du -sh 

                          // view in human readable format.

                             $du -h  

  - ping       :     Network Connectivity.
                     
                     E.g: // for only 1 packet :

                           $ping -c 1 www.google.com

  - netstat    :     Network statistics to monitor network connections.

                     E.g:
                          // All the Connections:

                             $netstat -a

                          // For TCP Connections:

                             $netstat -at

                          // For UDP Connections:

                             $netstat -au

  - nslookup   :     Name server lookup.
                     
                     E.g: $nslookup www.google.com

  - ps         :     process status.

  - tail       :     Prints last N lines of a file.
                     
                     E.g: // Last 5 lines

                             $tail -n 5 <file_name>

  - systemctl  :     To Control services.
                     
                     E.g: // status of a service, let's say Docker:

                             $systemctl  status docker

                          // start a service:

                             $systemctl start docker

                          // Enable a service (start at boot):

                             $systemctl enable docker

  - journalctl :     View systemd logs.

                    E.g: // view systemd logs(important to see logs of kublet,etc,.):
                     
                             $journalctl

  - top        :     Memory and cpu utilisation view.
