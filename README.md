# package_host
Repository for hosting python zips and files for use in some of my other programs. 
I did not create any of the files inside of these zip files. 

The main purpose of the files is for a program (currently unreleased) that I am working on called slave.py. What it does is it runs on a machine and takes specifically formatted commands that tell it how to run provided code. As such, it allows for scripts to break their workload up and distribute them to many different machines on a network. Upon starting the script, it will try to import several modules. Should it find itself unable to import these modules because they are not installed, it will download the zip files provided here to extract and import directly. 

Currently provided modules:
perf (all versions):
  https://github.com/TheElementalOfCreation/package_host/raw/master/perf.zip

six (all versions):
  https://raw.githubusercontent.com/TheElementalOfCreation/package_host/master/six.py
