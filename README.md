# NERSC_lyfe

```
#!/bin/bash
#SBATCH --nodes=<nnodes>
#SBATCH --time=hh:mm:ss
#SBATCH --constraint=<architecture>
#SBATCH --qos=<QOS>
#SBATCH --account=<project_name>

srun -n <num_mpi_processes> -c <cpus_per_task> a.out
```

```
$ sbatch first-job.sh
```
