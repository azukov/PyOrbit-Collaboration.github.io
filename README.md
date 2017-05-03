# Particle Accelerator Simulation Code PyORBIT

The PyORBIT code is an implementation and extension of algorithms of the original ORBIT code that was developed for the Spallation Neutron Source accelerator at the Oak Ridge National Laboratory. The PyORBIT code has a two level structure. The upper level uses the Python programming language to control the flow of intensive calculations performed by the lower level code implemented in the C + + language. The parallel capabilities are based on MPI communications. The PyORBIT is an open source code hosted at [github](https://github.com/PyORBIT-Collaboration/py-orbit).

[The Particle Accelerator Simulation Code PyORBIT](http://ac.els-cdn.com/S1877050915011205/1-s2.0-S1877050915011205-main.pdf?_tid=6585b486-302f-11e7-a56d-00000aab0f26&acdnat=1493836758_f97df43faf4dde6f7fe2cb63067448a9) paper provides detailed description of code internals and capabilities. 

Benchmarking with [PARMILA](http://laacg.lanl.gov/laacg/services/download_PMI.phtml) for MEBT of SNS accelerator gives quite consistent results.

![ParmilaX](images/ParmilaX.png)
![ParmilaY](images/ParmilaX.png)
![ParmilaZ](images/ParmilaX.png)
