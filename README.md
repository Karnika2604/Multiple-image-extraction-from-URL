# Multiple-image-extraction-from-URL


## Import all the necessary library as the image extraction uses beautifulsoup
from bs4 import *
import requests
import osfrom bs4 import *
import requests
import os

## create folder to download images
def folder_create(images):


## extract images from the given link and count them

def download_images(images, folder_name):

## create a Main function to extract the images from URL

def main(url):
   
    # content of URL
    r = requests.get(url)
 
    # Parse HTML Code
    soup = BeautifulSoup(r.text, 'html.parser')
 
    # find all images in URL
    images = soup.findAll('img')
 
    # Call folder create function
    folder_create(images)
    
## Create input to enter link 

### Call the Main function

### Store the images in their respective folder





