# GPU_Windows11
1. install Visual Studio 2022: https://visualstudio.microsoft.com/vs...
2. install NVIDIA CUDA: https://developer.nvidia.com/cuda-too...
3. Copy the file and paste in CUDA: NVIDIA CUDNN:  https://developer.nvidia.com/rdp/cudn...
4. install PyTorch: https://pytorch.org/get-started/locally/
5. install https://www.tensorflow.org/install/pip
6. pip install "tensorflow<2.11"

# command for installation process
1. install VsCode community
2. Install Nvidia Cuda tooltkits
3. Copy all files from Nvidia cuDNN like bin, include, x64, and paste in CUDA file location
4. Install Miniconda
5. Create a conda environment
6. Check the python version
7. Install TensorFlow below version 11
8. conda install -c conda-forge cudatoolkit=11.2 cudnn=8.1.0
9. Verify the installation CPU and GPU
10. pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
this is CLI command
# git documents

https://git-scm.com/
# github-cli-test

1. …or create a new repository on the command line
```
echo "# git_cli_test" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:hossain-sanowar/git_cli_test.git
git push -u origin main
```
2. …or push an existing repository from the command line

```
git remote add origin git@github.com:hossain-sanowar/git_cli_test.git
git branch -M main
git push -u origin main
```

## push branch to main
```
git branch --move master main
git push --set-upstream origin main
```
## remove branch 
```
git push origin --delete master
```
# git status
```
git init
git log
git branch
git brach -D <file_name> #delete branch file
git pull <repository>
git push origin main
git commit -m "salary prediction"
git add .
git push --force origin main
git push -u origin main
```
## get commit 1 command ahead, then what should we do?
```
git pull origin main
```
## current change and incoming change
`remove conflict message, then push again`

### check the branch
```
git checkout branch
git branch stage
git checkout stage
git status
git add .
git commit -m "message"
git push origin stage #here stage is branch name



