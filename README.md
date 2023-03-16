# <pre>     IT314 - Software Engineering    </pre> 

## Name : Pansuriya Viraj Dhirajbhai
## Id : 202001196
## Date : 16/03/2023


### Selected Tool : Mypy
### Selected Repo : https://github.com/davidsandberg/facenet/tree/master/test
From above Repo I have selected restore_test.py File


### Error: 

![Screenshot (28)](https://user-images.githubusercontent.com/75216559/225573992-616518cc-1c20-47e4-a924-c439fed43c5f.png)


### Justification : 
* This File is one of project file. As we can see in above screenshot it says that mysy is not able to find implementation or library
* Generally some tools does not have information about some library. Here "tensorflow" and "numpy" are not able to identify.
* These error occurs because mypy can not find that module that are trying to import.
* suggestion : use mypy --install -types
