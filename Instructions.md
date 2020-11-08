**Instructions**

_Setting up_



ALWAYS DO THIS:
Open Terminal
Type in:

--
cd website/website_production/
git pull 
--

Write articles etc 

If you make changes, go to Terminal
Type in:

--
git add .
git commit -m ""       		<- Add a message in between the quotation marks
git push -u origin master
--

Close Terminal



OTHER INFORMATION


_Adding Articles_ 
- To add an article, go to website_production > src > posts
- Copy an existing folder, then rename the folder
- Delete the images, add new images
- Rename the .md file and add information
- Keep the bit at the top, change the id to something unique, add a title, add the name of the image for the header in the "featuredImage" section, add a subtitle and any tags

_Writing Articles_
- add your text in the .md section
- use markdown
- add images using the following method <img src="{insert link here}" width="640"/>

For checking Markdown, press CTRL+K, then let go, then press V in "Visual Studio Code" (download)

_Uploading Articles_
To upload:
Follow the messages above (git add. ....)


_Hosting images_ 
- Should be done in: https://github.com/floraml/filehosting
- Add a new folder here if needed