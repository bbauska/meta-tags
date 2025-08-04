<!-- bbauska/meta-tags/essential-meta-tags.md -->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>Essential HTML Meta Tags</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->

```
<meta charset="UTF-8">
```

	- <p>Specifies the character encoding for the HTML document.</p>
	- <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/meta#attr-charset">MDN Web Docs</a>

```
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

	- <p>Controls the viewport's size and scale, essential for responsive design.</p>
	- <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Viewport_meta_tag">MDN Web Docs</a>

```
<meta http-equiv="X-UA-Compatible" content="IE=edge">
```

	- <p>Advises Internet Explorer to use the latest rendering engine.</p>
	- <p>No longer broadly relevant as IE reaches end-of-life.</p>

```
<meta name="description" content="Free Web tutorials">
```

	- <p>Provides a brief description of the page. Important for SEO and when sharing links on social platforms.</p>
	- <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/meta/name">MDN Web Docs</a>

```
<meta name="keywords" content="HTML, CSS, JavaScript">
```

	- Specifies keywords for search engines. Its importance for SEO has diminished over time due to overuse and spamming.

```
<meta name="author" content="John Doe">
```

	- Defines the author of the webpage.

```
<meta http-equiv="refresh" content="30">
```

	- Refreshes the page after a specified number of seconds.
	- <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/meta/http-equiv#attr-refresh">MDN Web Docs</a>

```
<meta name="robots" content="noindex, nofollow">
```

	- Instructs search engines not to index or follow the links on the page.
	- <a href="https://developers.google.com/search/docs/advanced/robots/robots_meta_tag">Google Developers</a>

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>Security-Related Meta Tags</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->

```
<meta http-equiv="Content-Security-Policy" content="default-src 'self'">
```

	- Controls resources the user agent is allowed to load, enhancing security.
	- <a href="https://developer.mozilla.org/en-US/docs/Web/HTTP/CSP">MDN Web Docs</a>

```
<meta http-equiv="X-Content-Type-Options" content="nosniff">
```

	- Prevents the browser from MIME-sniffing a response away from the declared content-type.
	- <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/meta/http-equiv#x-content-type-options">MDN Web Docs</a>

```
<meta name="referrer" content="no-referrer">
```

	- Controls the amount of referrer information sent along with requests.
	- <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/meta/name">MDN Web Docs</a>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>Social Media Integration Meta Tags</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h4>Open Graph (Facebook)</h4>

```
<meta property="og:title" content="Title Here">
```

The title of your content.

```
<meta property="og:description" content="Description Here">
```

A brief description.

```
<meta property="og:image" content="https://example.com/image.jpg">
```

An image URL which should represent your content.

```
<a href="https://ogp.me/">Open Graph Protocol</a>
```

<h4>Twitter Cards</h4>

```
<meta name="twitter:card" content="summary_large_image">: 
```

Determines the card type.

```
<meta name="twitter:title" content="Title Here">
<meta name="twitter:description" content="Description Here">
<meta name="twitter:image" content="https://example.com/image.jpg">
```

<a href="https://developer.twitter.com/en/docs/twitter-for-websites/cards/overview/markup">Twitter Developer Docs</a>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>Other Meta Tags</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->

```
<meta name="format-detection" content="telephone=no">
```

	- Instructs browsers not to detect and format telephone numbers automatically.
	- Useful for preventing unintended UI modifications, especially on mobile devices.

```
<meta name="theme-color" content="#ffffff">
```

	- Suggests a color that browsers should use to customize the display of the page or of the surrounding user interface.
	- <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/meta/name/theme-color">MDN Web Docs</a>

	- Particularly useful for mobile browsers to match the address bar color with the site’s theme color.

```
<meta name="application-name" content="Application Name">
```

	- Specifies the name of the web application.
	- Not widely used for SEO but can be useful in web app manifests and when the website is pinned to a screen, like on mobile devices or desktops.

```
<meta name="generator" content="WordPress 5.8">
```

	- Indicates the software or platform used to generate the page.
	- Automatically included by some CMSs like WordPress but often removed for security reasons to obscure the platform version.

```
<meta http-equiv="Content-Language" content="en-US">
```

	- Specifies the natural language(s) of the document.
	- The use of <html lang="en-US"> is preferred for specifying the primary language.

```
<meta name="google" content="notranslate">
```

	- Indicates to Google not to offer translation for this page.
	- Useful for content that may be misinterpreted when automatically translated.

```
<meta property="fb:app_id" content="Your_App_ID">
```

	- Associates your website with a Facebook app ID.
	- Essential for using Facebook Insights to track user interaction and for a more enhanced sharing experience on Facebook.

```
<meta name="apple-mobile-web-app-capable" content="yes">
```

	- Instructs Safari on iOS to operate in full-screen mode when the website is saved to the home screen.
	- Enhances the mobile experience by hiding browser UI components.

```
<meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
```

	- Specifies the style of the status bar for web applications added to the home screen on iOS.
	- Options include default, black, and black-translucent.

```
<meta name="msapplication-TileColor" content="#000000">
```

	- Defines the color of the tile for Windows 8 and 10 when the user pins the site to their start menu.
	- Helps maintain brand consistency across user platforms.

```
<meta name="msapplication-config" content="/browserconfig.xml">
```

	- Specifies the location of the XML config file for Internet Explorer 11 when pinning websites to the Windows taskbar.
	- The XML file can define tile images, tile color, and other settings.

This list represents a snapshot of the diverse and evolving world of HTML meta tags, each serving specific roles from SEO optimization, security enhancements, social media integration, to providing a better user experience across various devices and platforms. Developers should consider these meta tags as tools in their toolkit, to be used thoughtfully to meet the goals of their web projects.

For the most current information and best practices, always refer to official documentation and guidelines from relevant platforms and organizations, as web standards and practices continue to evolve.
