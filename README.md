doxygen-1.8.x-srpm
==================

SRPM building tools for doxygen 1.8.x for RHEL 8 beta. doxygen is needed
for building Samba libraries, but is not present in RHEL 8 beta.

The "make" command will do these steps.

	make build	# Build the package on the local OS
	make all	# Use "mock" to build the packages with the local
			# ../rhelbeta-8-x86_64.cfg configuration
	make install	# Actually install the RPM's in the designated
			# location for ../samba4repo/el/8/x86_64

		Nico Kadel-Garcia <nkadel@gmail.com>
