If your cluster uses modules (lmod), you can put this package somewhere
accessible to your whole cluster and use the module file included here.

Just edit the file to set the correct root path, and add any python dependency
that you may have. Parts of this tool use pandas, so a python (probably
anaconda) distro that includes a fast numpy/pandas install would be handy.

This isn't essential for running pascal though, you can just run in 'single'
mode and no parsing will be done.
