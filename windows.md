# Windows Setup


### SSH X11 forwarding

Forwarding your x11 sesssion from a virtualbox session is usually smoother then trying to do everthing inside of virtualbox window.

* [Setting up x11 forwarding on windows](http://laptops.eng.uci.edu/software-installation/using-linux/how-to-configure-xming-putty)

After this you can then run any gui application by just running the command to start the application from the terminal

```bash 
#run Firefox
user@user:~$ firefox
```

*Software needed*
* [putty](https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html)
* [Xming](http://www.straightrunning.com/XmingNotes/) - you need to a log in, which you get after donating 10 dollars
* [VirtualBox](https://www.virtualbox.org)
