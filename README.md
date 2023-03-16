# <pre>     IT314 - Software Engineering    </pre> 

## Name : Pansuriya Viraj Dhirajbhai
## Id : 202001196
## Date : 16/03/2023

# File 1
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


# File 2

### Selected Tool : Mypy
### Selected Repo : https://github.com/davidsandberg/facenet/blob/master/tmp/mnist_center_loss.py

# Error:

![image](https://user-images.githubusercontent.com/75216559/225578160-07bf7b43-3ac1-4129-ba06-78cf8ee00069.png)

### Justification : 

* As we have seen in File 1 , here also same kind error has and apart from that there are sae kind of hints that i have mentioned in File 1 suggestion section. 

