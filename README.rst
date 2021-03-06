PyOpenCL lets you access GPUs and other massively parallel compute
devices from Python. It tries to offer computing goodness in the
spirit of its sister project `PyCUDA <http://mathema.tician.de/software/pycuda>`_:

* Object cleanup tied to lifetime of objects. This idiom, often
  called
  `RAII <http://en.wikipedia.org/wiki/Resource_Acquisition_Is_Initialization>`_
  in C++, makes it much easier to write correct, leak- and
  crash-free code.

* Completeness. PyOpenCL puts the full power of OpenCL's API at
  your disposal, if you wish.  Every obscure `get_info()` query and 
  all CL calls are accessible.

* Automatic Error Checking. All CL errors are automatically
  translated into Python exceptions.

* Speed. PyOpenCL's base layer is written in C++, so all the niceties
  above are virtually free.

* Helpful and complete `Documentation <http://documen.tician.de/pyopencl>`_
  as well as a `Wiki <http://wiki.tiker.net/PyOpenCL>`_.

* Liberal license. PyOpenCL is open-source under the 
  `MIT license <http://en.wikipedia.org/wiki/MIT_License>`_
  and free for commercial, academic, and private use.

* Broad support. PyOpenCL was tested and works with Apple's, AMD's, and Nvidia's 
  CL implementations.

Like PyOpenCL? (And perhaps use it for `bitcoin
<http://bitcoin.org>`_ mining?) Leave a (bitcoin) tip:
1AwrFPb8sR6h9czi8qj68CxC9pwUKvMGfB

