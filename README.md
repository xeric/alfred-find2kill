# alfred-find2kill
***Alfred Quick Process Killer***

An Alfred Workflow provides ability to search and kill process by Port and Process Name

```
fport | fproc
```
----------------------------------------

## Command fport - Search Processes by Port Number

    fport {PortNumber}
<h>
By default, without provided Port Number, it will show up top 10 items, and with port number, it will find exact process which is using the port.

## Command fproc - Search Processes by Process Name

    fproc {Process Name keyword}
<h>
By default, without provided Process Name keyword, it will show up top 30 processes order by CPU usage.

With provided Process Name keyword, it will search processes with keyword, please notice that if you type multiple keywords and split by space, it will just treat it as single keyword which has whitespace characters.

For example, you search "Google Chrome", you find a process named "Google Chrome" and a process "Google Chrome Helper", but if you type "Chrome Google", nothing will show up.
 ***[keyword is case insensitive]***

## Download built version here:

https://github.com/xeric/alfred-find2kill/releases
