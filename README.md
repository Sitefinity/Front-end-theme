Front-end-theme
===============
Front-end-theme repo contains a new Front-end theme of Sitefinity. 

Source folder
--------------

Source folder contains the source of the theme in .less files. General folder contains all generic styling, Content folder contains styling for all Sitefinity front-end widgets, Images folder contains background images and Global folder contains Sitefinity.less which imports all other files in the correct order. 

The source can be used as a base to develop new Sitefinity themes quickly. For example, colors, font-sizes, font-family, etc. can be modified in variables.less which will change the look and feel of the theme in no time. Also, if some of the modules in Sitefinity are not used (for example Ecommerce) their corresponding imports in the main Sitefinity.less file can be commented out. This will prevent unused styles to be loaded on the front-end.

To compile the source of the theme you can use your preferred LESS compiler like Web Essentials, WinLess, etc. Also, you can try Sitefinity Less module which will enable you to use less files in a Sitefinity theme directly. 
We do not recommend to use Less module on live sites. It is meant for staging environments to ease development process. For live sites we recommend that CSS is used.

Theme folder
-------------
Theme folder contains the complied to CSS theme which can be used directly. Global folder contains Sitefinity.css which contains all imported and compiled styles and Images folder contains background images.

Questions?
-----------
If you have any questions, please feel free to ask on
