# Images and Viseos

In HTML, you can embed images and videos using the img and video elements, respectively. Here's how you can use these elements to include images and videos in your webpage:

# Images

To display an image on your webpage, use the img element and specify the src attribute to the image file's path.

```
<img src="image.jpg" alt="Description of the image">

```

The src attribute specifies the path to the image file.
The alt attribute provides alternative text for the image, which is useful for

# Videos

To embed a video on your webpage, use the video element and include one or more source elements within it to define different video formats for better browser

```
<video controls>
    <source src="video.mp4" type="video/mp4">
    <source src="video.webm" type="video/webm">
    Your browser does not support the video tag.
</video>

```

The controls attribute adds playback controls to the video player.
Each source element specifies a different video format (src) and its associated MIME type (type).
