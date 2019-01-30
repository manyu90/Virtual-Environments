# Virtual-Environments
Virtual Environment .yml files:

For **Dragonn** also install genomelake-1,genomeflow,tf-dragonn from my forks
module load cuda
module load cudnn/5.1
For running tensorflow and keras with the environment parameters
For **modisco_cpu**, 
Activate modisco_cpu environment. On sherlock, the cudnn and cuda wont need to be loaded as this is tensorflow cpu. Install modisco from the cloned repo which I store in my softwares folder in /oak


For **tensorflow** environment on Sherlock:
after sourcing the env, also run:
module load cudnn/7.1.4
module load cuda/9.0.176
to load tensorflow-gpu==1.8.0,keras==2.0.8


