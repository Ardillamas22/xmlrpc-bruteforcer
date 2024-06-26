# xmlrpc-bruteforcer
XMLRPC Brute Forcer and User Enumerator for Wordpress
#xmlrpc.php Brute-Forcer & User Enumerator
<!---
Lenguaje: Bash
-->     
![Logo](imagenes/logo.png)



## Bruteforce passwords via xmlrpc 


Exposing the XML-RPC interface in a WordPress site can pose significant security risks. This interface allows for remote procedure calls, which, if not properly secured, can be exploited by attackers. Script takes advantage of this error by sending a large number of requests to the XML-RPC interface. This allows for rapid testing of user credentials, effectively enabling password cracking. This script employs multithreading, executing many tasks in parallel on the processor. This parallel execution significantly enhances the speed of the script, making it much more efficient. By distributing the workload across multiple threads, the script can send a large number of requests to the XML-RPC interface simultaneously. This allows for rapid testing of user credentials and drastically reduces the overall execution time. It's crucial to understand that this tool can only be used for security testing.

## User Enumeration

The tool also includes a user enumeration feature. This is due to a particular behavior of WordPress: when a valid username is provided, regardless of the password, WordPress returns a distinct response compared to when an invalid username is provided. This tool capitalizes on this behavior to enumerate existing users, which can be invaluable for security testing purposes.
Moreover, the script’s multithreading capability allows it to perform this user enumeration in parallel, significantly speeding up the process. By executing multiple enumeration tasks simultaneously, the script can quickly and efficiently identify valid usernames.


## Installation

```bash
git clone https://github.com/Ardillamas22/xmlrpc-bruteforcer
cd xmlrpc-bruteforcer
chmod +x ./xmlrpc-bruteforcer

```

## Usage

![helPanel](imagenes/panel.png)




In terms of usage, the tool provides a straightforward 'helpPanel' message that explains how to use it. This message details all the necessary parameters and how to specify them. It serves as a guide, making the tool accessible and easy to use. This 'helpPanel' ensures that users can effectively utilize the tool for testing the security of WordPress sites.

## Interactive Mode

![helPanel](imagenes/interactive.png)







The tool also features an interactive mode. In this mode, users are first prompted to select the mode they wish to enter.


![helPanel](imagenes/interactive2.png)





Once a mode has been selected in the interactive mode, the tool will then prompt the user for all the necessary parameters. This step-by-step process ensures that all required information is gathered 


![finish](imagenes/finish.png)
