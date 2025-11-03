<h1>Adding Images in react websites</h1>

images are stored, imported then this location is used in the source location of the image markup.
<hr>
 
STEP1:
first identify the location of your image in the file structure for your app. this address is used in the import url.

<code>import IMAGE_NAME from “../../LOCATION_OF_IMAGE.png"</code>

STEP2:
then the image is added to the code using the image name in place of the image source url

<code><img id="CHOOSE_ID" src={IMAGE_NAME} alt='ALT_DESC” width=“WIDTH” height=“HEIGHT/></code>

Task 1
Display an image on a page in a react app.

for more on importing images…
[follow this link](https://medium.com/@viditkumar.au/display-images-in-react-628e6cd4f4d8)
