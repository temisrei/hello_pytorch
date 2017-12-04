# 環境建立
<br>

Step 1. 建立 Pytorch 虛擬環境
```
$ conda create --name pytorch python=3.5
```
<br>


Step 2. 啟動 Pytorch 虛擬環境
```
$ source activate pytorch

# 若要結束環境
# $ source deactivate pytorch
```
<br>


Step 3. 參考 [官方網站 Get Started](http://pytorch.org/) 安裝 pytorch
```
$ conda install pytorch torchvision -c soumith
# macOS Binaries dont support CUDA, install from source if CUDA is needed
```
<br>


Step 4. 在 Jupyter 增加 Kernel: pytorch
```
python -m ipykernel install --user --name=pytorch

# 確認 Jupyter Kernel
# $ jupyter kernelspec list

# 如果增加 Kernel 過程中，發生 No module named ipykernel
# $ conda install ipykernel
```
<br>


Final. 啟用 jupyter notebook
```
$ juputer notebook
```
<br>