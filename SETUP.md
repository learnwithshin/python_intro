# Setup

## Install Anaconda

We will download Anaconda from this link:
https://www.anaconda.com/products/individual#windows

**Scroll all the way near to the bottom** to find the installer section and **select the one that meets your operating system**:

![Screen Shot](images/install_anaconda.png)

It may take a few minutes to downloand. Once downloaded, follow the instuctions to install to your PC or Mac.

After it's installed, you should be able to open up `Anaconca Navigator`.

![Screen Shot2](images/anaconda_navigator.png)

## Install Visual Studio Code

We are also going to install Visual Studio Code. Go to the link below and **downloand VSCode that meets your OS**.
https://code.visualstudio.com/download

![Screen Shot3](images/vscode.png)

Follow the instructions to install.

## Install Python Extension

Once installed, open Visual Studio Code. Then go to:

`View` -> `Extensions`

![Screen Shot3](images/vscode_extension.png)

In the search bar, type "python"

![Screen Shot3](images/vscode_search_extension.png)

Select the one that says "Python" and click on "Install"
![Screen Shot3](images/vscode_install_extension.png)

You should be all set for now!

### FAQ

#### Am I running 32-bit or 64-bit Windows?

Please refer to this link:
https://www.howtogeek.com/howto/21726/how-do-i-know-if-im-running-32-bit-or-64-bit-windows-answers/

#### Where do I find Anaconda-Navigator?

_Windows 7_

Type in "Anaconda" in search bar from Start button

![Screen Shot3](images/w7_find_anaconda.png)

_Windows 10_

Type in “Anaconda” in Search box

![Screen Shot3](images/win10_anaconda.png)

#### I still can't find Anaconda Navigator. What should I do?

If Anaconda Navigator is still not available, use https://jupyter.org/try

You will see a page like below:

![Screen Shot3](images/jupyter_cloud_home.png)

Click on "Try Classic Notebook".

Then you will see a page like this:
![Screen Shot3](images/binder.png)

Wait for a few, and then you should see a page like below.

![Screen Shot3](images/jupyter_notebook_1.png)

Click on the icon at the top left hand side that says "Jupyter".
![Screen Shot3](images/go_to_root.png)

It will pop up a message asking if you want to leave the site. Just click on "Yes".

It should then bring you to this page.
![Screen Shot3](images/jupyter_notebook_root.png)

Now drag and drop the files into this page.
![Screen Shot3](images/drag_files.png)

![Screen Shot3](images/drop_files.png)

Then click on "Upload" for those two files and you should be all set!

![Screen Shot3](images/uploaded.png)

#### I can't import pandas in my Vistual Studio Code. What should I do?

This could happen if you are using Mac becasue Mac already has python built in. We need to make sure that we are using the python interpreter from the Anaconda.

Go to `View` -> `Command Palette`

![Screen Shot3](images/command_palatte.png)

In the input bar, type in "Python Select Interpreter"

![Screen Shot3](images/search_select_interpreter.png)

It should show a list of differnt Pythons. Select the one that has **(anaconda3)**. In below example I will select "Python 3.76 64-bit 'anaconda3' virtualenv (You might be seeing different versions of Python but just make sure you pick the one that has "anaconda3" in it).

![Screen Shot3](images/select_anaconda.png)

Now you should be good to go!

#### How can I make the "OUTPUT" panel display my program output in VS Code?

You will need to install "Code Runner" extension.

Go to `View` -> `Extensions`

![Screen Shot3](images/vscode_extension.png)

In the search bar, type "Code Runner"

![Screen Shot3](images/code_runner.png)

Install the `Code Runner` exntension and you should be good to go!
