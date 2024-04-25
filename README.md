![header](https://capsule-render.vercel.app/api?type=Cylinder&color=auto&height=200&section=header&text=Study%20RAPIDS&fontSize=50&animation=fadeIn)



<center>
<a href="https://rapids.ai/">
<img  src="https://img.shields.io/badge/RAPIDS-512BD4" />
</a>
<a href="https://www.dask.org/">
<img  src="https://img.shields.io/badge/DASK-FC6E6B?style=flat-square&logo=dask&logoColor=FFFFFF" />
</a>
<a href="https://www.nvidia.com">
<img  src="https://img.shields.io/badge/NVIDIA-76B900?style=flat-square&logo=NVIDIA&logoColor=FFFFFF" />
</a>
<a href="https://www.python.org/">
<img  src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=FFFFFF" />
</a>
<a href="https://numpy.org/">
<img  src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=FFFFFF" />
</a>
<a href="https://pandas.pydata.org/">
<img  src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=FFFFFF" />
</a>
<a href="https://numpy.org/">
<img  src="https://img.shields.io/badge/scikit-learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=FFFFFF" />
</a>
</center>
<hr/>
This Repository For NVIDIA 기술랩 - Data Engineering with RAPIDS

<br/><br/>

## What is RAPIDS?

The RAPIDS data science framework is a collection of libraries for running end-to-end data science pipelines completely on the GPU. The interaction is designed to have a familiar look and feel to working in Python, but utilizes optimized NVIDIA® CUDA® primitives and high-bandwidth GPU memory under the hood. Below are some links to help getting started with each of the individual RAPIDS libraries.
If you want to see more information follow links: 
[Hompage](https://rapids.ai/),
[Documentation](https://docs.rapids.ai/user-guide?_gl=1*10rgyfz*_ga*MjEzMTA2MTQxNy4xNzA0OTUyNzQ4*_ga_RKXFW6CM42*MTcxNDAzMTU2My4xNS4wLjE3MTQwMzE1NjMuNjAuMC4w)


<br/><br/>


## File Sturcture

📦STUDY_RAPIDS<br/>
┣ 📂[Kaggle](./Kaggle)<br/>
┃ ┣ 📂[AML](./Kaggle/AML)<br/>
┃ ┗ 📂[Titanic](./Kaggle/Titanic)<br/>
┃ ┃ ┣ 📂[data](./Kaggle/Titanic/data)<br/>
┃ ┃ ┃ ┣ 📜gender_submission.csv<br/>
┃ ┃ ┃ ┣ 📜test.csv<br/>
┃ ┃ ┃ ┣ 📜test.parquet<br/>
┃ ┃ ┃ ┣ 📜train.csv<br/>
┃ ┃ ┃ ┗ 📜train.parquet<br/>
┃ ┃ ┣ 📜01_Titanic Random Forest.ipynb<br/>
┃ ┃ ┣ 📜02_Titanic Random Forest with Dask.ipynb<br/>
┃ ┃ ┣ 📜03_Titanic XGB.ipynb<br/>
┃ ┃ ┣ 📜README.md<br/>
┃ ┃ ┣ 📜cufile.log<br/>
┃ ┃ ┣ 📜mydask.html<br/>
┃ ┃ ┣ 📜requirements.txt<br/>
┃ ┃ ┣ 📜submission.csv<br/>
┃ ┃ ┣ 📜submission_RF_cpu.csv<br/>
┃ ┃ ┣ 📜submission_RF_dask.csv<br/>
┃ ┃ ┣ 📜submission_RF_gpu.csv<br/>
┃ ┃ ┗ 📜submission_xgb.csv<br/>
┗ 📜README.md<br/>