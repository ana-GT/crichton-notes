Installing Dependencies
=======================

To run Crichton code you will need to install some 
dependent libraries. A good tutorial about how
to do this can be found `here <http://www.cs.rpi.edu/foswiki/bin/view/RoboticsWeb/PowerballGATech>`_. In short, 
the libraries you need to install are:

* *amino:* git clone http://thebrain.golems.org/git/lib/amino
* *ach:* git clone http://thebrain.golems.org/git/lib/sns
* *sns:* git clone http://thebrain.golems.org/git/lib/socanmatic
* *socanmatic:* git clone http://thebrain.golems.org/git/lib/socanmatic
* *netcanft:* git clone http://thebrain.golems.org/netcanft
* *reflex:* git clone http://thebrain.golems.org/git/lib/reflex


For some libraries, such as amino, you will need
to use autoconf. The general steps are:

.. code-block:: guess

   $ autoreconf -i
   $ ./configure
   $ make
   $ sudo make install

