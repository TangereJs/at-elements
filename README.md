at-elements
===========

This is the container project for all adenin TangereJS elements. All these components have the at- name prefix.

To contribute new elements the following steps are required:

prepare the development tree
--

The development tree is based on the https://github.com/TangereJs/designer repo. TangereJs/designer is the adenin MPS version of the Polymer Designer.

To setup your own development tree start with cloning the https://github.com/TangereJs/designer repo.

Then run 

**pull-all.sh** *user* *pass*

where *user* is your github user name and *pass* is your password.

This will first save any components/at- directories (which fails the first time, but this can savely be ignored), then uses bower to get all dependencies, restores the saved components/at- and then uses git to check out the full components/at- repos.

After the script is finished all at- components contain complete the git repos. So the files can be changed and then directly pushed to git.


add a new component
--

Add the new component to the components.list (https://github.com/TangereJs/designer/blob/master/components.list) and run **pull-all.sh** again

To add a new component add the component first to at-elements/bower.json and to at-elements/at-elements.html

If the components should be usable in the designer a metadata.html file needs to be created in the component directory and the metadata.html needs to be added to at-elements/metadata.html as well.

After adding the metadata.html the component should appear in the designer.

How to define a metadata.html file is explained at https://github.com/TangereJs/designer#metadatahtml 



