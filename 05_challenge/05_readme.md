#!/bin/env python
#-*- encoding=utf8 -*-
```
import os,sys

if __name__=="__main__":

    print "__file__=%s" % __file__

    print "os.path.realpath(__file__)=%s" % os.path.realpath(__file__)

    print "os.path.dirname(os.path.realpath(__file__))=%s" % os.path.dirname(os.path.realpath(__file__))
　　
    print "os.path.split(os.path.realpath(__file__))=%s" % os.path.split(os.path.realpath(__file__))[0]　　

    print "os.path.abspath(__file__)=%s" % os.path.abspath(__file__)

    print "os.getcwd()=%s" % os.getcwd()

    print "sys.path[0]=%s" % sys.path[0]

    print "sys.argv[0]=%s" % sys.argv[0]
```
输出结果:

D:\>python ./python_test/test_path.py 

```
__file__=d:\workspace\wtfiswronghere\05_challenge\05_challenge.py
os.path.realpath(__file__)=d:\workspace\wtfiswronghere\05_challenge\05_challenge.py
os.path.dirname(os.path.realpath(__file__))=d:\workspace\wtfiswronghere\05_challenge
os.path.split(os.path.realpath(__file__))=d:\workspace\wtfiswronghere\05_challenge
os.path.abspath(__file__)=d:\workspace\wtfiswronghere\05_challenge\05_challenge.py
os.getcwd()=D:\workspace\wtfiswronghere
sys.path[0]=d:\workspace\wtfiswronghere\05_challenge
sys.argv[0]=d:\workspace\wtfiswronghere\05_challenge\05_challenge.py

```
