nvmalloc library - Under development, cleanup, and restructuring phase 
---------------------------------------------------------------------

# How to build

To compile the library, you need the following libraries

     $ cd nvmalloc
     $ export NVMALLOC_HOME=$PWD
     $ sudo apt-get install libssl-dev

To build the object library, use sudo if required in your machine

    $ make clean
    $ make 
    $ make install	

Setup tmpfs with size in megabytes

    $ scripts/setuptmpfs.sh 4096


# How to run



# Provides pesistent allocation

# uses Intel's NVML for logging