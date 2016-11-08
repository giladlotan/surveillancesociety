# Technical Setup

Open up terminal.
First thing, let’s make sure we have pip installed. This will help us easily install python packages into our machine.

```
sudo easy_install pip
```

If this worked, when we type ‘pip’ into the command line we should see command options.

**Virtualenv**

Virtualenv is an absolute must when working with Python. It creates a folder that stores a private copy of python, pip, and other Python packages. We can then enable this private folder while working on a project. By using the virtual environment, we can use different versions of Python and a different combination of Python packages on a per-project basis. Virtualenvwrapper is a wrapper that helps us navigate across the virtual environments.

```
sudo pip install virtualenv
```

Let’s check that it installed properly:

```
virtualenv
```

And it should come back with a lot of output.

**Virtualenvwrapper**

Now let’s install virtualenvwrapper:

```
sudo pip install virtualenvwrapper
```

You may run into issues with an existing installation of a library called - six. In that case try installing this way:

```
sudo pip install virtualenvwrapper --ignore-installed six
```

Here’s where we have to do something a little different. In our home directory let’s make a folder called .virtualenvs:

```
cd
mkdir .virtualenvs
```

Now we need to have our shell load the virtualenvwrapper.sh script. To do this we’re going to add a line to our .bash_login file. You may use vi or any other file editing tool.

```
vi .bash_login
```

Now let’s add the following line (remember to press ‘i’ to get into insert mode) into the bottom of the file. Once the line is added, we can write and quit (escape, colon, w, q, return).

```
source /usr/local/bin/virtualenvwrapper.sh
```

Now close the terminal, and open up a new one. Let’s check it:

```
mkvirtualenv
```

If that spits out a whole bunch of information… success!

Let’s create a new project

```
mkvirtualenv itp
```

If we close our terminal window, we can always get back to our project’s virtual environment by typing:

```
workon itp
```

**Jupyter Notebook**

```
pip install jupyter
```

Let’s first create a folder for the class (I’m calling mine ‘ssoc’):

```
mkdir ssoc
cd ssoc
```

And then run the notebook:

```
jupyter notebook --no-browser &
```


**Github**

Make sure git is installed on your computer. There are many ways to do this. On a mac you can install via Xcode.
When you type ‘git’ into the command line, you should see the git help tutorial. If that’s not coming up, you need to install it (lots tutorials online).

Next let’s clone our class repo into the current class directory:

```
git clone https://github.com/giladlotan/surveillancesociety
```

When we navigate to: localhost:8888/ - in our browser, we should be able to see the class materials and notebooks.


**Google API**

Go to the Google API Console - https://console.developers.google.com/
You will need to create an API key and enable various APIs that you may want to use (Google Maps Javascript API, Google Places API...)

First create a new project. Then click into the 'Library' tab on the left, and navigate to 'Google Maps JavaScript API'. On the top of that page click 'ENABLE'. This gives our api key access to that service. Finally, grab your API key from the 'Credentials' tab on the left:

credentials -> create API key -> copy the key and paste it in the right place within your ipython notebook.

Next we just need to run a few things in the terminal (make sure you are in the right virtual environment).

Enable widgets extensions to Jupyter:

```
jupyter nbextension enable --py --sys-prefix widgetsnbextension

```

Install gmaps python component and tell Jupyter to load the extension:

```
pip install gmaps
jupyter nbextension enable --py gmaps
```

**Links**
- Virtualenvwrapper documentation: http://virtualenvwrapper.readthedocs.io/en/latest/
- Jupyter Notebook documentation: http://jupyter.org/
- Thanks Jamie: http://jamie.curle.io/posts/installing-pip-virtualenv-and-virtualenvwrapper-on-os-x/

