# Linux_Commands_Refresher_and_Projects
This Repo Tracks my Learning Progress for my Refresher on Linux Commands. The Repo collects learnings and projects from 'Linux Mastery: Master the Linux Command Line' Udemy Course

# First Commands
echo Hello                            To print on terminal
cal                                   Current Month Calender
    cal -y                            Current Year Calender
date                                  To print Date, Time, Date, Zone
clear                                 Clean up Terminal
Ctrl + L                              Shortcut for Cleanup
Up Arrow                              Cycle back to commands 
history                               All old commands shown numbered
    !1                                From History List Select 1st
!!                                    Run the most recent command
history -c; history -w                Clears the history and Writes it
exit                                  Terminal Close
CTRL + D                              Terminal Close Shortcut

# Command Structure 
1. Structure - commandName options inputs
2. cal          12      2017
3. date         -u               - Date in Universal Time - Short Name
4. date         --universal      - Date in Unversal Time - Long Name

5.  commandName options1 options2 input1 input2

6. To know where a command file recides, you can use the "which" command
which echo


# Linux Manual
Also Known as Man Pages.

Manual Structure:

1. Manual is divided into 8 Sections
    1. User Commands 
    2. System Calls
    3. C Library Functions
    4. Devices & Special Files
    5. File Formats & Conventions
    6. Games
    7. Misc
    8. System Admin

2. Reading the Man Pages of Linux
    1. man -k which  (-k for search the manual for term which)
        1. Result will give which doc and section number
        2. man 1 which (section 1 manual of which)
    2. Manual Strucutre:
        1. Synopsis
        2. Descriptions
        3. Options
        4. Exit Status
        5. Etc...

    3. Finding new commands:
        1. I want to find a command that list a directory. So search is done by this command:  " man -k "list directory" "
        2. man 1 ls or man ls to know more


