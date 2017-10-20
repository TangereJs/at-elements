at-elements
===========

This is the container project for all adenin TangereJS elements. All these components have the at- name prefix.

To contribute new elements the following steps are required:



add a new component
--

Add the new component to the components.list (https://github.com/TangereJs/designer/blob/master/components.list) and run **pull-all.sh** again

To add a new component add the component first to at-elements/bower.json and to at-elements/at-elements.html

If the components should be usable in the designer a metadata.html file needs to be created in the component directory and the metadata.html needs to be added to at-elements/metadata.html as well.

After adding the metadata.html the component should appear in the designer.

How to define a metadata.html file is explained at https://github.com/TangereJs/designer#metadatahtml 



