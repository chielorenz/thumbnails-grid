##Thumbnails Grid: all css thumbails preview

####[Live Demo](https://www.lucalorenzini.org/thumbnailsGrid/demo/thumbnailsGridDemo.html)

##About:
The aim of the Thumbnails Grid is to create a simple grid of thumbnails with an image (inside an ancor), a description and some cool css transition. The adaptive layout of the thumbnails is not the purpose of this project.

####Elements:
It's build with polymer so is as simple as creating only one thumbnail and the magic of html5 element does the dirty job.

####Dependencies:
I've used the package manager bower so ther sholud not be dependency problem, you just need a

 
>$bower install


in the project's folder and you are ready to go.

##How it works:

####Structure:
There are three main files for this project:

* thumb-nail.html is the thumbnail itself.
* thumbnails-grid.html is the grid element thath wrap all the thumbnails.
* nails-services.html is a fake-service which read a .json file where all the thumbnails are listed. Normally this will be a server response.

####Workflow:
The thumbnailsGridDemo.html file import thumbnails-grid.html which call the sevices and build all the thumbnails with the response.

##Thanks
Hope you enjoy. 
