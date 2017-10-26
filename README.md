# AIX Configuration collector
1. listProcesses originaly taken from http://www.froebe.net/blog/2014/12/04/howto-determine-what-process-is-listening-on-a-port-aix-unix-specific/. It return porcesses listening to the network in nice format
--------------------------------------------------------------------------------------
| Process              | PID             | Protocol | Listening On                   |
--------------------------------------------------------------------------------------
| WEBAPL               |         4915396 |      UDP |                127.0.0.1.32807 |
| WEBAPL               |         4915396 |      UDP |                127.0.0.1.32808 |
| WEBAPL               |        12058770 |      UDP |                127.0.0.1.51714 |
| WEBAPL               |        12058770 |      UDP |                127.0.0.1.51715 |
| backupserver         |        19791994 |      TCP |              192.168.1.4.50021 |
--------------------------------------------------------------------------------------

