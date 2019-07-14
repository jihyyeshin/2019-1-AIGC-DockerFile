# DockerFile
> tensorflow+jupyter_notebook+python docker file

## Build Setup

```bash
sudo docker build -t rd .
sudo docker run --name final -p 8888:8888 -p 6006:6006: -v notebooks -it rd bash
cd ..
/run_jupyter.sh --ip 0.0.0.0 --allow-root -NotebookApp.token=''
```
