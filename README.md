<<<<<<< HEAD
Manual for Ubuntu (16.04):
1) First of all we need to install "virtualenv", write in terminal:
sudo apt-get install virtualenv

2) Then after installation, to create virtual environment folder write in terminal:
virtualenv Jillerenv

3) Now, to activate environment, go to the new folder (in terminal write "cd Jillerenv") and write:
source bin/activate

4) Now your terminal is using your own virtual environment. Let's install packages for our django project. Download our project from github into Jillerenv folder. To install packages write in terminal:
pip install -r Jiller/requirements.txt 
=======
Manual for Ubuntu.
1) First of all we need to install "pip" and "virtualenv", write in terminal:

sudo apt-get install pip

sudo apt-get install virtualenv

2) Then after installation, to create virtual environment folder write in terminal:

virtualenv Jillerenv

3) Now, to activate environment, go to the new folder (in terminal write "cd Jillerenv") and write:

source bin/activate

4) Now your terminal is using your own virtual environment. Let's install packages for our django project. Download our project from github into Jillerenv folder. To install packages write in terminal:

pip install -r Jiller/requirements.txt 

note: after git your folder can have name "Jiller-master".
>>>>>>> 3712ee18b35117eab69b4709571c7170abea19b6
 
5) After installation you can check version of your Django by typing
django-admin.py --version

<<<<<<< HEAD
it should be 1.10.5
=======
In our environment it should be 1.10.5
>>>>>>> 3712ee18b35117eab69b4709571c7170abea19b6
