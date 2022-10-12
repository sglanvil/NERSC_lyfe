# NERSC_lyfe

https://docs.nersc.gov/jobs/

https://docs.nersc.gov/jobs/examples/

https://docs.nersc.gov/jobs/monitoring/

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

```
Case Directories
/project/projectdirs/ccsm1/people/sglanvil/cases/e3smv1-le/e3smv1.20TR_CMIP6.ne30_oECv3_ICG.LE-v1.0365.004
/project/projectdirs/ccsm1/people/sglanvil/cases/e3smv1-le/e3smv1.20TR_CMIP6.ne30_oECv3_ICG.LE-v1.0410.005
```
````
How to get ncdump on NERSC:
module load cray-netcdf
module load nco
````
