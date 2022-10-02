# NASA Space Apps Challenge 2022: The Art In Our Worlds

### Team: Astro-Unite ###

### Team members: Eileen Lin, He(Barbie) Zhu, Kezhang(Tony) Chen ###


## File Description: ##

> ### Prototype: Basic Searching Algorithm Using IBM Watson ###

Using IBM Watson's default Natural Language Processing Model in conjunction with NASA's Image and Video Gallery API, images that are matched with the user's search prompt are returned to the user along with their respective descriptions. Using our prototype model, the user is directed to first input a phrase, similar to how a user will do so in our stART exploring app, which will then be run through the IBM Watson's natural language processing model to identify "entites" in the user's phrase, and it will be used to search the NASA Image and Video Gallery for any corresponding matches. All images on the first page(which can be expanded to all accessable pages, for the sake of time however, we have limited our prototype to only accessing results that come up to a maximum of 100 results) and their respective descriptions will be returned. If there are no matches, the user will be notified. The list of images and their respective descriptions can be altered to serve the role of displaying all matched images on the stART exploring app, where the user can review images, read their descriptions, edit the images, etc.

> ### Speech To Text Transcription ###

This program file is a sample implementation of speech to text transcription in python. Using the concept app stART exploring, all users can access the myriad of data offered by the NASA APIs. The Speech To Text function in our app is an integral part that allows even the illiterate or immobile to explore the possibilities enveloped in space, as such, we developed a speech to text implementation that puts this concept into action(code). Using the program, the user can record themselves talking, and the system will automatically convert the recording into a phrase. Some further developments that can be made in this program include adding multi-language support, to further the accessibility for all to make SPACE for everyone.

> ### Image Editor ###

Another integral part of our creative data display app is the capacity for image manipulation after selecting an image. We put this concept into implementation with the iamge editor program. Using the Python Imaging Library PIL, manipulations to the image can be made, as exemplified in our program. Some possible choices include image rotation, image blur, altering image sharpness, adding a gray filter, displaying the "edges" detected, image brightness, and image contrast. Some future developments include more options for image manipulation, or even the development of a machine learning model that dynmamically deepens the color within the image.

> ### Stable Diffusion  ###

#### Source Codes: ####
#### https://github.com/huggingface/diffusers #####
#### https://www.youtube.com/watch?v=124QcD3u0P8&t=0s #####
Using Machine Learning, both Stable Diffusion machine learning models offer promising results. Stable Diffusion Short allows users to input a phrase and a photo will be outputted in a short amount of time. Stable Diffusion Long allows users to enter in a phrase and a photo will be outputted in a specific style. Although Stable Diffusion Long takes a long time to train its machine learning model, the programmer can specify 
