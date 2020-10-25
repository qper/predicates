# predicates

- CGI scripts to run properly on Unix-like operating systems, the +x bit needs to be set. Using chmod a+x your_script.py may solve this problem. All CGI scripts has to be named with prefix or sufix CGI and executable bit has to be checked by CI. [Source](https://docs.python.org/2/howto/webservers.html)

- On a Unix-like system, The line endings in the program file must be Unix style line endings. It has to be checked by CI. [Source](https://docs.python.org/2/howto/webservers.html)


