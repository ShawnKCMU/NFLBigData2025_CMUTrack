Overview: 
This repository contains our submission for the 2025 NFL Big Data Bowl competition hosted on Kaggle. The challenge focuses on analyzing pre-snap player tracking data to uncover patterns and make actionable predictions about team and player behavior post-snap. This year's theme encourages creativity and insight into player movements, formations, and tendencies before the snap to predict outcomes such as play type, scheme, or individual assignments.

Objective
Leverage the provided Next Gen Stats tracking data to:

Generate innovative metrics for player or team performance.
Predict offensive and defensive tendencies post-snap.
Create actionable insights for coaching, scouting, and strategic analysis.

Tracks and Submission
Our approach aligns with the Metric Track, where we use pre-snap data to evaluate team and player strategy and its relationship to post-snap outcomes. We aim to provide detailed analysis focusing on offensive and defensive schemes, player roles, and game-changing insights.

Join the Competition
For more information, visit the NFL Big Data Bowl 2025 on Kaggle.

Packages Used: 
(NFLBigData2025) koza@user1:~/Documents/NFL Big Data Bowl 2025$ conda list 

# packages in environment at anaconda3/envs/NFLBigData2025:
#
# Name                    Version                   Build  Channel
_libgcc_mutex             0.1                        main  
_openmp_mutex             5.1                       1_gnu  
asttokens                 3.0.0              pyhd8ed1ab_1    conda-forge
bzip2                     1.0.8                h5eee18b_6  
ca-certificates           2024.12.14           hbcca054_0    conda-forge
comm                      0.2.2              pyhd8ed1ab_1    conda-forge
dbus                      1.13.18              hb2f20db_0  
debugpy                   1.6.7           py310h6a678d5_0  
decorator                 5.1.1              pyhd8ed1ab_1    conda-forge
entrypoints               0.4                pyhd8ed1ab_1    conda-forge
exceptiongroup            1.2.2              pyhd8ed1ab_1    conda-forge
executing                 2.1.0              pyhd8ed1ab_1    conda-forge
expat                     2.6.4                h6a678d5_0  
filelock                  3.16.1                   pypi_0    pypi
findspark                 2.0.1              pyhd8ed1ab_0    conda-forge
freetype                  2.12.1               h4a9f257_0  
fsspec                    2024.12.0                pypi_0    pypi
glib                      2.78.4               h6a678d5_0  
glib-tools                2.78.4               h6a678d5_0  
ipykernel                 6.29.5             pyh3099207_0    conda-forge
ipython                   8.31.0             pyh707e725_0    conda-forge
jedi                      0.19.2             pyhd8ed1ab_1    conda-forge
jinja2                    3.1.5                    pypi_0    pypi
jupyter_client            7.3.4              pyhd8ed1ab_0    conda-forge
jupyter_core              5.7.2              pyh31011fe_1    conda-forge
ld_impl_linux-64          2.40                 h12ee557_0  
libffi                    3.4.4                h6a678d5_1  
libgcc-ng                 11.2.0               h1234567_1  
libglib                   2.78.4               hdc74915_0  
libgomp                   11.2.0               h1234567_1  
libiconv                  1.16                 h5eee18b_3  
libpng                    1.6.39               h5eee18b_0  
libsodium                 1.0.18               h36c2ea0_1    conda-forge
libstdcxx-ng              11.2.0               h1234567_1  
libuuid                   1.41.5               h5eee18b_0  
libxcb                    1.15                 h7f8727e_0  
markupsafe                3.0.2                    pypi_0    pypi
matplotlib-inline         0.1.7              pyhd8ed1ab_1    conda-forge
mpmath                    1.3.0                    pypi_0    pypi
ncurses                   6.4                  h6a678d5_0  
nest-asyncio              1.6.0              pyhd8ed1ab_1    conda-forge
networkx                  3.4.2                    pypi_0    pypi
nvidia-cublas-cu12        12.4.5.8                 pypi_0    pypi
nvidia-cuda-cupti-cu12    12.4.127                 pypi_0    pypi
nvidia-cuda-nvrtc-cu12    12.4.127                 pypi_0    pypi
nvidia-cuda-runtime-cu12  12.4.127                 pypi_0    pypi
nvidia-cudnn-cu12         9.1.0.70                 pypi_0    pypi
nvidia-cufft-cu12         11.2.1.3                 pypi_0    pypi
nvidia-curand-cu12        10.3.5.147               pypi_0    pypi
nvidia-cusolver-cu12      11.6.1.9                 pypi_0    pypi
nvidia-cusparse-cu12      12.3.1.170               pypi_0    pypi
nvidia-nccl-cu12          2.21.5                   pypi_0    pypi
nvidia-nvjitlink-cu12     12.4.127                 pypi_0    pypi
nvidia-nvtx-cu12          12.4.127                 pypi_0    pypi
openjdk                   11.0.13              h87a67e3_0  
openssl                   3.0.15               h5eee18b_0  
packaging                 24.2               pyhd8ed1ab_2    conda-forge
parso                     0.8.4              pyhd8ed1ab_1    conda-forge
pcre2                     10.42                hebb0a14_1  
pexpect                   4.9.0              pyhd8ed1ab_1    conda-forge
pickleshare               0.7.5           pyhd8ed1ab_1004    conda-forge
pip                       24.2            py310h06a4308_0  
platformdirs              4.3.6              pyhd8ed1ab_1    conda-forge
prompt-toolkit            3.0.48             pyha770c72_1    conda-forge
psutil                    5.9.0           py310h5eee18b_0  
ptyprocess                0.7.0              pyhd8ed1ab_1    conda-forge
pure_eval                 0.2.3              pyhd8ed1ab_1    conda-forge
py4j                      0.10.9.7                 pypi_0    pypi
pygments                  2.18.0             pyhd8ed1ab_1    conda-forge
pyspark                   3.5.4                    pypi_0    pypi
python                    3.10.16              he870216_1  
python-dateutil           2.9.0.post0        pyhff2d567_1    conda-forge
python_abi                3.10                    2_cp310    conda-forge
pyzmq                     26.2.0          py310h6a678d5_0  
readline                  8.2                  h5eee18b_0  
setuptools                75.1.0          py310h06a4308_0  
six                       1.17.0             pyhd8ed1ab_0    conda-forge
sqlite                    3.45.3               h5eee18b_0  
stack_data                0.6.3              pyhd8ed1ab_1    conda-forge
sympy                     1.13.1                   pypi_0    pypi
tk                        8.6.14               h39e8969_0  
torch                     2.5.1                    pypi_0    pypi
tornado                   6.1             py310h5764c6d_3    conda-forge
traitlets                 5.14.3             pyhd8ed1ab_1    conda-forge
triton                    3.1.0                    pypi_0    pypi
typing_extensions         4.12.2             pyha770c72_1    conda-forge
tzdata                    2024b                h04d1e81_0  
wcwidth                   0.2.13             pyhd8ed1ab_1    conda-forge
wheel                     0.44.0          py310h06a4308_0  
xz                        5.4.6                h5eee18b_1  
zeromq                    4.3.5                h6a678d5_0  
zlib                      1.2.13               h5eee18b_1  
