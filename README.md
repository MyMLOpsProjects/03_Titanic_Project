# 03_Titanic_Project
TITLE: Testing the Modules &amp; Packaging

Note:
To build packege, follow this:
> python -m  pip  install  --upgrade  build
then run this
>  python  -m  build

You will notice, two additional folders will be created:
1. dist: This contains the distributable ‘whl’ file and ‘gz tar’ file. The ‘whl’file is easy to install.
2. titanic_model.egg-info : This contains metadata and information of the packages along with the requirements information.
