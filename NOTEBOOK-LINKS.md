## Delete this file after you use the template to create another workshop.

## Datahub

This link only works for people with access to the Berkeley Datahub. This method is easy -- it just requires you to put the link together manually.

Steps:
1. https://datahub.berkeley.edu/hub/user-redirect/interact?account=ds-peer-consulting&repo=
2. Name of repository, i.e. if the URL is https://github.com/ds-peer-consulting/workshop-template, the name is workshop-template
3. &branch=main&subpath=
4. Name of notebook, i.e. sample-notebook-structure(ANSWERS).ipynb

Concatenate 1-4 and you have your url.

[Example](http://datahub.berkeley.edu/user-redirect/interact?account=ds-peer-consulting&repo=fa20-intro-to-python-dataviz-workshop&branch=master&subpath=)
- note that if you don't provide a subpath, it just opens the folder

## Binder

This link works for anyone! This requires you to go to https://mybinder.org/ and filling in the information. You may run into some environment building problems, which will require you to write a .yml file that describes the packages you are using.

- Git ref is usually `main`
- Please insert the path to the attendee notebook.

**Note** Please make sure to test these links before the actual workshop! You can use the ANSWERS notebook for the dry run as a temporary substitute.
