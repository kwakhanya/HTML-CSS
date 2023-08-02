# HTML working with graphics.


## Images

Images improve the design and appearance of web pages. When we want to add images to our web page, we use image element which is written using img, images are not technically inserted in a web page, images are linked to the web pages. We have four attributes that we need to include for every image we use.

<img src="linda with her cat.webp" alt="Linda love her cat" width="400" height="300">

The source attribute (SRC) tells the browser which image to include.
ALT gives text description of the image which will be displayed if the image does not show, sometimes the ALT attribute help people who have visual problems by using screen reader(a software program that reads the HTML code, it allows the user to listen to the content) to read that ALT for them, then we have a width and height attribute which determines the size of the image, it important to always specify the width and height of image.

## Image Formats
We need to consider image file when putting image on a webpage, it must a file that a web browser understands. We have four types of Image format that are commonly used.
### JIF(Graphics Interchange Format)
### SVG(Scalable Vector Graphics)
### JPG()
are a popular one when compressing photographs, most digital cameras saves image in JPG format.
### PNG(Portable Graphic Networks) 
is a newer version that works well when you need transparency in a photograph.

## Responsive images

Responsive images will automatically be resized to fit your screen. When using images, you need to avoid using those with high resolution because using them will cause problem to users with network problem or low data. To solve that issue, you need to reduce the size of your image you need to keep your images physically small.
Responsive width

### Figcaption and Figures

It is important to match your caption with yoour image, your caption must have relationship with the image.The figure and figcaption elements are really useful for anything that serves as a visual illustration or a demonstration of a concept that needs a caption.

<figure>

<img src="linda with her cat.webp" alt="Linda love her cat" width="500" height="300">

<figcaption>Linda is enjoying her time with the cat
</figcaption>

</figure>

# Working with Audio
There are different audio format we can chose from.There are other attributes that can be used with the audio element too. For example, "loop" will make the file repeat from the beginning once it reaches the end. "Autoplay" can automatically play the audio as soon as the page loads, but be cautious with this one as most people dislike it when audio starts playing on a webpage without their consent. 

<audio controls src="NDIYAKHOLWA-KHOLEKA LIVE AT JOBURG THEATRE.MP3"></audio>

## Working with video
when putting a video on your webpage you need to consider the size of your video. The video element also have opening and closing tags.To display a video, use the source attribute to specify the video file. And if the controls attribute is added, the browser will automatically create a video player.

<video controls src="Baxolise.mp4" width="300" height="200" style="margin: right">


## Working with caption and subtitles
Sometime we add videos in our webpage but not eveybody can understand or hear it. when adding caption into a video we use track element and link it to text file, this element adds functionality to the video player.


## Embending media via iFrames
iFrame embend content from another sources into HTML document, Embedding refers to taking content from one site and placing it within the middle of another site's page. Lot of website have disabled the use of Iframes .While iframes are powerful, we need to consider security issues when pulling in code from other websites.When building a website, also consider security aspects related to the iframe element. Do not allow iFrames on your website unless you are the only one whose going to post videos