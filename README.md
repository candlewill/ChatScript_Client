# Simple Client for ChatScript

Here is an elementary python client. Perhaps would need to re-write using twisted if high performance is required, but should suffice for simple use cases.

## Run

$ python chatclient.py -u username -b botname -s 127.0.0.1 -p 1024

```
Options:
  -h, --help  show this help message and exit
  -u USER     user id, required
  -b BOTNAME  which bot to talk to, if not specified, will use default bot
  -s SERVER   chat server host name (default is 127.0.0.1)
  -p PORT     chat server listen port (default is 1024)
```

## Requirement

Python 3.5

