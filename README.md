# foss-test

## install conda: 
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
bash Miniconda3-latest-Linux-x86_64.sh -b -p /opt/conda

## link path
ln -s /opt/conda/pkgs/*/bin/* /bin
ln -s /opt/conda/pkgs/*/lib/* /usr/lib
ln -s /opt/conda/pkgs/*/lib/* /usr/lib

   15  conda search ptyhon
   16  conda search python
   17  /opt/conda/bin/conda install -c conda-forge -y jupyterlab=1.2.3
   18  conda search jupyterlab
   19  /opt/conda/bin/conda search jupyterlab
   20  /opt/conda/bin/conda install -c conda-forge -y nodejs=10.13.0
   21  /opt/conda/bin/pip install bash_kernel
   22  /opt/conda/bin/pip install ipykernel
   23  /opt/conda/bin/python3 -m bash_kernel.install
   24  /opt/conda/bin/conda install -y ipykernel
   25  /opt/conda/bin/conda search -c bioconda fastx


   27  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'
   
   28  ls
   29  mkdir reproducibility
   30  ls
   31  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'
   32  mkdir reproducibility-tutorial
   33  ls
   34  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'mkdir 
   35  ls
   36  cd reproducibility-tutorial/
   37  ls
   38  cd ..
   39  ls
   40  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'
   41  ls
   42  git clone https://github.com/Javi-RS/INFO8000.git
   43  ls
   44  cd INFO8000/
   45  ls
   46  cd final_project/
   47  ls
   48  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/INFO8000/final_project/'
   49  /opt/bin/conda/pkgs/pip numpy
   50  /opt/conda/bin/pip install numpy
   51  /opt/conda/bin/pip install pandas
   52  docker --version
   53  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/INFO8000/final_project/'
   54  /opt/conda/bin/pip install PIL math cv2 os
   55  cd..
   56  cd ..
   57  cd ..
   58  ls
   59  sudo apt-get update
   60  sudo apt-get install -y apt-transport-https ca-certificates curl gnupg-agent software-properties-common
   61  docker run hello-world
   62  history
   63  df -h
   64  ls
   65  cd reproducibility-tutorial/
   66  ls
   67  nano README.md
   68  ls
   69  cd ..
   70  ls
   71  cd INFO8000/
   72  ls
   73  history >>README.md 
   74  nano README.md 
   75  nano README.md 
   76  nano README.md 
   77  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/INFO8000/final_project/'
   78  git commit -am "document install instruction"
   79  git config --global --edit
   80  git commit -am "document install instruction"
   81  git push
   82  cd ..
   83  ls
   84  git clone https://github.com/charlie-BSAIL/foss-test.git
   85  ls
   86  cd foss-test/
   87  history >>README.md 
