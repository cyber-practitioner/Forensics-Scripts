# Forensics-Scripts
<h4> script is now able to connect to a URL address,parse and download all the images files, and test each file for Exif metadata. Noticethat in the main function, we first fetch a list of all the images on the site. Then, for each image in the array,it will download the file and test it for GPS metadata.</h4>
  
  
<p> Syntax</p>

<p> python3 discover.py  website url. </p>


<p> required prerequisitres</p>


<li> argparse
<li> urllib.error
<li> urllib.parse
<li>urllib.request
<li>urllib.parse 
<li> os.path
<li> bs4 
<li>PIL 
<li> PIL.ExifTags 
</li>

**OR**
<p> run the command below</p>
<p> pip3 install -r requirements.txt </p>

