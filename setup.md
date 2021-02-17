In this setup I'm using [Oracle VM VirtualBox](https://www.virtualbox.org/) which can be downloaded [here](https://www.virtualbox.org/wiki/Linux_Downloads), feel free to use your own VM...

First of all open Oracle VM VirtualBox and click on the _New_ button:

<img width="551" alt="new-click" src="https://user-images.githubusercontent.com/61805754/88678038-b1199f00-d0f6-11ea-829b-06de28b5d501.png">

Then in the new window choose a _Name_ for the operating system, I will go with 'Rosehip' but you can choose anything,

and for the _Machine Folder_ I will choose 'C:\new' but you can choose anything (if you choose a folder which doesn't exists the VM will create it for you),

then tap on the _Type_ section to open a drop-down menu and choose _Linux_ and in the Version section choose _Other Linux (64-bit)_

<img width="309" alt="config" src="https://user-images.githubusercontent.com/61805754/88679859-8f211c00-d0f8-11ea-9756-cf192d301df8.png">

and click _Next_.

Choose how much RAM you want to allow Rosehip to use 2GB-4GB would be reasonable (it won't actually use all this RAM but if you give it high limit it will perform well) and press _Next_

Choose _create_. Choose _Next_. Choose _Next_.

Now you should see a window asking how much storage would you like to give to Rosehip, choose how much you want, (you need at least 300MB) and press _Create_

In the new window click on _Settings_:

<img width="550" alt="settings" src="https://user-images.githubusercontent.com/61805754/88681194-fbe8e600-d0f9-11ea-8d6b-4112ddac2691.png">

In the settings window choose _Storage_:

<img width="609" alt="storage" src="https://user-images.githubusercontent.com/61805754/88681460-45393580-d0fa-11ea-881d-ee28e90355da.png">

In the storage section delete _Empty_ by right-clicking it then pressing _Remove Attachment_ then pressing _Remove_.

Press _Controller: IDE_ and then on the little disk icon:

<img width="611" alt="add-disk" src="https://user-images.githubusercontent.com/61805754/88682123-fe980b00-d0fa-11ea-93f2-ac44c67ef677.png">

click on _Add_ and find the iso file you got from CITUR then press _Open_ then press _Choose_.

Go to _Display_ section:

<img width="613" alt="display" src="https://user-images.githubusercontent.com/61805754/88682696-a3b2e380-d0fb-11ea-8961-91c0d4b997c7.png">

And in the _Graphics Controller_ pick _VBoxVGA_:

<img width="611" alt="Graphics" src="https://user-images.githubusercontent.com/61805754/88683092-1a4fe100-d0fc-11ea-9f4b-24947f9ec8cf.png">

Press _Ok_ and press on the green right arrow _Start_

In the intrepreter just type the word "rosehip" to open the desktop
