###Adding grunticons to json_resume
1. Download the svg(s) you would like to use from a site like [https://icomoon.io/app/](https://icomoon.io/app/)
2. Download the official json_resume svgs from [the json_resume_icon repo](http://github.com/NoahHines/json_resume_icons)
3. Drag all svgs onto the [grumpicon](http://www.grumpicon.com/) and then "downlode it"
4. Drag the files inside the grunticon folder into the json_resume's css folder, replacing existing files
5. Modify the default_html mustache script to include your icons. Edit the div class to include your new grunticon. ```<div class="icon-user icon-square">```, where "user" is the SVG name. Check grunticon's generated preview.html file to verify the icon class name.
6. run ```json_resume convert prateek.json``` and the updated icons should successfully be implemented.
