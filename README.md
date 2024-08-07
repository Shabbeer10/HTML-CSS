# HTML-CSS Notes

ARIA Roles provide the necessary tools to make your site accessible to everyone.

Enhance readability by adding comments.

Best practice to use lowercase for html all elements.

The length of an element name indicates how old it is. back in the day, RAM was small, say space was prioritized.

Character entities come in handy when you need to type characters that are not available on your keyboard.
"&nbsp;" to keep 2 words together and avoid line break between them, or create more than one space betweeen words.

To create a link, we use the A element, which stands for anchor. Between the opening and closing A tags, we can place text or images, or both, to make them clickable.
HTTP/S stands for Hypertext Transport Protocol/Secure.
When linking to something within the same siteas the page containing the link, a relative URL can be used instead.
To create a relative URL, omit the domain name but include the initial slash at the beginning.
Relative URLs are based on the current file's location, while absolute URLs start from the root of the website.

example of adding images to website via html;
<img src="https://i.postimg.cc/j5hn1Th0/labrador-8554882-640.jpg" alt="a picture of a dog" width="" height="">

"alt=" is used for same purpose as aria. should add it even if blank, else screen reader will read the actual image name.
Inluding width and height attributes help with website rendering and enhances user experience.

GIFs for compressing illustrations that have mostly the same colours, but pixelates photographs.
SVGs are perfect for logos & icons. Scaled to size without losing quality, and the size remains small.SVG is actually a programming language for graphics.
JPGs are a good choice for compressing photographs. Important to resize else will slow loading speed
PNG is a newer format. It sometimes outperforms both GIF and JPG in compression of images.

To support different screen resolutions and device speeds, create copies of same image in different resolutions & add to HTML using srcset inside your <img> with varying pixels (1x, 2x, 3x etc)
instead of specifying pixels you may specify width aswell. The browser decides which image to show based on device density and viewport width.
Aim to send the smallest file possible while still delivering beautiful images.

The audio element also takes a source link like the picture element. it allows you to play music or sound effects and has attributes to control volume and autoplay and looping etc. This is a prebuilt audio player. MP3 formats are most popular.

Video element allows you to play videos on your website, and similiar to using audio files, you would want to optimise user experience by finding the right file sizes and resolutions, and making the content accessible to all in the form of sound and text (subtitles or captions).

Using the iframe tag it is possible to imbed an entire website into your own website. an example of using iframe tags is when we come accross videos that are playing straight from youtube, but you are on a different website.

Remember to set the language, text direction and charset of your website. This allows the browser to know which languages and character sets of those languages to use. Unicode, particularly UTF-8, is widely used as a character set. It encodes content to support a vast range of characters, scripts, and even emojis.

Prioritise simantic elements. div(block) and span(inline) work best when applying css or javascript

Common use of meta tags is to inform the browser that the layout has been adjusted to fit small screens, or to include a description of the site, which appears in search engine results, to design an attractive card that shows when a link is shared etc.

link tag is used to connet assets to the html file, like .css icons, fonts, audio, videos etc
scipt tag to load javascript, python etc
