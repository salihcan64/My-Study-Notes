
# Creating Python Virtual Enviroment

### **Creating a virtual environment can be done using the command shown below:**

**python3 -m venv /path_to_new_virtual_environment**


mkdir <YOURPROJECT>: Create a new project

cd <YOURPROJECT>: Change directory to that project

virtualenv <NEWVIRTUALENV>: Creating a new virtualenv

source <NEWVIRTUALENV>/bin/activate: Activating that new virtualenv

Run this code. It will get activated if you are on a Windows machine:

source venv/Scripts/activate

Run this code. It will get activated if you are on a Linux or Mac machine:

. venv/bin/activate

  
  https://stackoverflow.com/questions/14604699/how-can-i-activate-a-virtualenv-in-linux

## How can I activate a virtualenv in Linux?: *workflow after creating a folder and cd'ing into it:*

### virtualenv venv --distribute



### source venv/bin/activate
### python
You can also do

### source ./python_env/bin/activate <br>
Or just go to the directory:

### cd /python_env/bin/  <br>
and then

### source ./activate
  
  ![Create Python Virtual Environment](https://user-images.githubusercontent.com/102698850/235342862-04b8be3e-6a55-42b5-943f-48e8b02eb2f1.png)
