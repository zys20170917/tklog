# tklog
a few handy log widgets based on tkinter

Log is just like a cup of Latte, and I like it anytime.

There are four classes in tklog.py:

* **tklog** class, which is the base component for all others. It can be
  packed into root or Toplevel window easily, and has a little power to
  log pictures (png and gif).

* **tklogHandler** class, which is inherited from logging.Handler and
  contains a tklog.

* **winlog** class, which is created in a Toplevel window, contains a
  tklog, and has the ability to withdraw or destroy root.

* **winlogHandler** class, which is inherited from logging.Handler and
  contains a winlog.

There are also four example code files for these classes.

Please run and check the example code before enjoying the classes from tklog, 
and don't forget to try **right click** on the log area. Maybe it's a surprise
for you. All the classes are **thread-safe**!

    $python3 example_tklog.py
    $python3 example_tklogHandler.py
    $python3 example_winlog.py
    $python3 example_winlogHandler.py

**中文参考： https://www.pynote.net/archives/1207**

Hope you like tklog and give me an encouraging **Star**. ^___^

