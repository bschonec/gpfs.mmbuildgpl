# gpfs.mmbuildgpl

This RPM will ensure that GPFS is [re]compiled on system restart.  GPFS GPL binaries aren't built automatically on reboot and updating to a new kernel requires human interaction to rebuilt the GPFS GPL binaries.

With this RPM, 'mmbuildgpl' will execute just after file system mounts and before GPFS has a chance to start.

This works with only systemd and sysV variants.

This is tested only on RHEL6/RHEL7 on IBM SystemZ (s390/s390x).


I have *no* idea what I'm doing with rpmbuild so pull requests and suggestions are MOST welcome.


