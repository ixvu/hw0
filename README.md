# HW 0

* Assigned:
* Due: 





## Development Environment

For this lab, we've partnered with [Instabase](https://www.instabase.com/) to provide you with a hosted IPython environment. 
To get started, create an account on the [website](https://www.instabase.com/account/register?use_token=true) (note that this URL is special for this class). 
The service is still in beta, so:

* Use the following token: `token-prof-wu-columbia`
* Make sure you sign up with your columbia email. 

After you've signed up, login and follow the steps below - 


1. Create a new repository. Give it a name / description of your liking and set the visibility to private.
1. Once the repo is created, click on the "collaborators" button on the sidebar and add `w4111` as a collaborator.
1. go to [https://www.instabase.com/ewu/w4111/fs/Instabase%20Drive/](https://www.instabase.com/ewu/w4111/fs/Instabase%20Drive/)
1. Select the `HW0` folder, click on "more", then "Copy", then pick your repository, and copy to `Instabase Drive`
   * `HW0` should now be in the `fs/Instabase Drive/` folder of your repository.
1. Navigate to the `HW0` folder in your repository, right click `hw0.ipynb` and open the file with `Jupyter`.  This will open the file using [Jupyter (used to be IPython) Notebook](http://jupyter.org/).
1. Follow the instructions in the notebook to complete and submit homework 0
   * There are [numerous resources](https://www.google.com/search?q=jupyter%20tutorial) that can introduce you to Jupyter Notebook.


**Installing packages**

The instabase platform already comes installed with the popular data-science and machine learning packages. To get the complete list, you can interact with the `bash` like so in your IPython notebook
```
%%bash
pip freeze
```
If you want to install a certain package that doesn't exist, you can install it on your own
```
%%bash
pip install requests
```

