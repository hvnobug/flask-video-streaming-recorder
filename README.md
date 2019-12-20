> 在[Kr1s77/flask-video-streaming-recorder](https://github.com/Kr1s77/flask-video-streaming-recorder)的基础上修改

# Installing
### 🐍First you should install ``Python3.x`` on your Raspberry Pi

>   $ sudo  apt-get  update
>   $ sudo  apt-get  upgrade
	
    	
- Install python``dependent environment``
- install python ``Dependent environment``

>    $ sudo apt-get install build-essential libsqlite3-dev sqlite3 bzip2 libbz2-dev

    
- Download the python3.6 version source and extract it
- Download the python version 3.6 source code and decompress it

>    	$ wget https://www.python.org/ftp/python/3.6.1/Python-3.6.1.tgz
>    	$ tar zxvf Python-3.6.1.tgz
  	
- Compilation and installation

>	    $ cd Python-3.6.1
>	    $ sudo ./configure
>	    $ sudo make
>	    $ sudo make install
	    
- Check installation

> 	$ ls -al /usr/local/bin/python*


### Next install the module

- Install flask

> 	$ pip3 install flask==0.10.1
    	
- Install opencv
- install opencv

> $ pip3 install opencv_python
  
# Running the tests

- Download all files to run
- run main.py

> 	$ python3 main.py -p 0.0.0.0
> 当然你也可以使用Gunicorn来当做你的多线程服务器
    	
 - 2019.2.21 update

 - Increased login, a simple login interface, does not need a database
 
 - Test account
 ```
     Username:  admin
     Password:  admin
 ```
 - 2019.3.4 update
 - Add multi-threading and recording downloads
 - Support multi-device access, logout login is normal

 - 2019.3.14 update
 - 现在的目录结构是这个样子

 ![](./img/tree.png)
 
- 抽取了代码，进行了优化，就是这样目录看起来会很多
 
 - Added a beautiful login interface
 ![Alt text](./img/login.png)
 
 - Optimization homepage

 ![Alt text](./img/index.jpg)
 
 - Add video recording and download capabilities
 - Realized the ``high performance``, using the yield generator, and multi-threading, silky smooth!
 
# Author
- Crise LYJ
  
# Acknowledgments
- Thanks for all!

- Have a good time!

 ![Alt text](./img/hha.jpeg)
