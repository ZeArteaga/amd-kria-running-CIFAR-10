# Instructions

1. Use docker to get this container https://hub.docker.com/r/xilinx/vitis-ai-tensorflow2-cpu 

should be:
```bash
docker pull xilinx/vitis-ai-tensorflow2-cpu
```


2. Once that is done:
```bash
git clone https://github.com/Xilinx/Vitis-AI
```


3. Copy the necessary files: **.h5 of the input model, notebook and cifar-10 dataset** to that directory. Or all of this repo for that matter. This is because once the container is running, they will be automatically mounted into the workspace folder (inside the container).


4. Run:
```bash
cd Vitis-AI
./docker_run.sh xilinx/vitis-ai-tensorflow2-cpu
```
(don't forget the 2, that's important)


5. once inside start a jupyter notebook:
```bash
jupyter notebook
```


6. Copy the provided link -> go to the code.ipynb (i know it is not the one inside the container but doesnt matter) -> select kernel -> jupyter -> paste the link -> give it a random name



**DONE!**