Installing Kinect libraries
===========================

To run my perception code you will need to grab online information from
the Kinect. I use the OpenNI/PrimeSense/PCL for this. 

There are tutorials to install OpenNI and PrimeSense. The most recent
thread at the moment of my writing this was `this <http://www.pcl-users.org/Can-t-use-Kinect-in-Ubuntu14-04-td4033666.html>`_.
However, I ended up using `this one <http://www.cimat.mx/~samota/blog/ubuntu/how-to-install-kinect-in-ubuntu-14.04.php>`_
to circumvent a strange error. The main take-home point is that you 
should use the unstable repositories for both OpenNI and PrimeSense.

Once you got OpenNI and PrimeSense, you might wish to reboot your
machine and only then try to run the sample.

After this, the only thing left is to install PCL with OpenNI support.
