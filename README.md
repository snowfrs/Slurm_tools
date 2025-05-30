# Slurm tools

This project is licensed under the GNU General Public License v3.0.
The DOI link to these tools is https://doi.org/10.5281/zenodo.15261429

These [Slurm](https://slurm.schedmd.com/overview.html)
tools have been developed for management and monitoring of our cluster:

1. [pestat](pestat/) Print Slurm nodes status with 1 line per node including job info.

2. [slurmreportmonth](slurmreportmonth/) Generate monthly accounting statistics from Slurm using the sreport command.

3. [slurmacct](slurmacct/) Generate accounting statistics from Slurm as an alternative to the sreport command

4. [showuserjobs](showuserjobs/) Print the current node status and batch jobs status broken down into userids.

5. [showuserlimits](showuserlimits/) Print Slurm resource user limits and usage.

6. [showpartitions](partitions/) Print a Slurm cluster partition status overview with 1 line per partition, and other tools.

7. [slurmibtopology](slurmibtopology/) Infiniband topology tool for Slurm.

8. Slurm [triggers](triggers/) scripts.

9. Scripts for managing [nodes](nodes/).

10. Scripts for managing [jobs](jobs/).

11. Scripts for managing [Slurm accounts and users](slurmaccounts/).

12. Scripts for managing [power_save](power_save/) of nodes.

13. Slurm [plugins](plugins/) for job_submit.

14. Tools for managing [InfiniBand and Omni-Path](InfiniBand/) network fabrics.

Slurm deployment HOWTO
----------------------

Our [Slurm HOWTO guide](https://wiki.fysik.dtu.dk/niflheim/SLURM) for setting up a Slurm installation.
It's based on RHEL 7/8 Linux (and clones), but much of the information should be relevant on other Linuxes as well.

Download
--------

Use the above ```Clone or download``` button,
or go to the individual tool page,
click on the desired file, and then click the ```Raw``` button
to get a link which you can use for download.
