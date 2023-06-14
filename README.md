# Operating System (PennOS)
This repository implements PennOS, our own UNIX-like operating system. PennOS is designed around subsystems that model those of standard UNIX. This includes a basic priority scheduler (implemented in a round-robin fashion), FAT file system, and user shell interactions. Unlike a real operating system, this does not require to actually boot on hardware; rather, this PennOS runs as a guest OS within a single process running on a host OS.