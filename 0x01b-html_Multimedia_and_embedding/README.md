# HTML Multimedia & Embedding
In this project, I learned that text alone would make the web a boring place. So we inject life into it with some interesting content by exploring how to use multimedia in web pages, including the different ways that images can be included, and how to enbed video and audio.

## Images in HTML
Eventhough there may be other types of multimedia to consider, we take a logical look and explore the `<img>` element to understand how it can be used to embed a simple image in more depth in a webpage.

    * The `<img>` element is a void element (meaning, it cannot have any child content and cannot have an end tag) that requires two attributes to be useful: `src` and `alt`. 
        - The `src` attribute contains a URL pointing to the image you want to embed in the page. As with the `href` attritube for `<a>` elements, the `src` attribute can be a relative URL or an absolute URL. Without a `src` attribute, an `img` element has no image to load. 

        - The `alt` attibute has a value which is supposed to be a textual description of the image, for use in situations where the image cannot be seen/displayed or takes a long time to render because of a slow internet connection.


## Video and Audio Content
Next, we looked at how to use the HTML `<video>` and `<audio>` elements to embed video and audio on webpages, including basics, providing access to different file formats to diferent browers, adding captions and subtitltes, and how to add fallbacks for older browers.

