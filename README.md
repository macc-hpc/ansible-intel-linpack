# Ansible Scripts to install Intel Linpack and MPI on HPC cluster

## Requirements
* For communication between cluster nodes, in most cases Intel MPI Library uses the SSH protocol and it need to establish a passwordless SSH connection to ensure proper communication of MPI processes. 
* Download and copy Intel® Math Kernel Library Benchmarks 2017 zip to bin/l_mklb_p_2017.2.015.tgz 
* Download and copy ​Intel® MPI Library 2019 to bin/l_mpi_2019.3.199.tgz 
* Set PSET_INSTALL_DIR in bin/silent-mpi.cfg to the directory where you want to install Intel® MPI Library.

### Installation
ansible-playbook -i hosts linpack.yml

# Ansible Scripts to install Intel® Manycore Platform Software Stack (Intel® MPSS)

WIP

# Feedback

Updated source and an issue tracker are available at:

        https://github.com/macc-hpc/ansible-intel-linpack

Your feedback is welcome.

# Contact

Ricardo Vilaca (<rmvilaca@di.uminho.pt>)