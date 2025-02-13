Server Status Monitor
====================================

Overview
--------

This project is a Bash script that provides useful information about your server's performance and status. The script offers a multiple-choice menu allowing users to check various system metrics.

### Features:

*   **Current Disk Usage**
    
*   **Current CPU Usage**
    
*   **Current RAM Usage**
    
*   **Number of TCP Connections**
    
*   **Kernel Version**
    

Prerequisites
-------------

*   A Linux-based system
    
*   Bash installed (default on most Unix-like OS)
    

Installation
------------

1.  Clone the repository or download the script.
`https://github.com/02Manas-jha/status-menu`

1.  Give execution permission to the script.
 `chmod +x status.sh`

Usage
-----

Run the script using:
`./status.sh`

You will be presented with a menu to choose which server statistics you want to check:
`Menu  1) Memory usage  2) CPU load  3) Number of TCP connections  4) Kernel version  5) Check All  0) Exit  Choose an option:` 

Script Breakdown
----------------

The script includes the following functions:

*   memory_check(): Displays current memory usage.
    
*   cpu_check(): Displays CPU load.
    
*   tcp_check(): Shows the number of active TCP connections.
    
*   kernel_check(): Outputs the kernel version.
    
*   all_checks(): Runs all the above checks.
    

Additionally, the script features:

*   A color-coded interactive menu.
    
*   Error handling for invalid input.
    

Example Output
--------------
`   Memory usage on myserver is:                 total        used        free      shared  buff/cache   available  Mem:           7.7Gi       3.2Gi       1.9Gi       230Mi       2.6Gi       4.0Gi  Swap:          2.0Gi        0Mi       2.0Gi  CPU load on myserver is:   12:34:56 up 5 days,  4:20,  2 users,  load average: 0.15, 0.10, 0.08  TCP connections on myserver:   58  Kernel version on myserver is:   5.15.0-56-generic   `

Customization
-------------

You can modify the script to add more monitoring features, such as:

*   Disk usage statistics
    
*   Network bandwidth monitoring
    
*   Process monitoring
