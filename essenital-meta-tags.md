<!-- bbauska/meta-tags/essential-meta-tags.md -->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>Essential HTML Meta Tags</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<pre>&lt;meta charset="UTF-8"&gt;</pre>
<ul>
	<li>Specifies the character encoding for the HTML document.</li>
	<li><a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/meta#attr-charset">MDN Web Docs</a></li>
</ul>
<pre>
&lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt;
</pre>
<ul>
  <li>Controls the viewport's size and scale, essential for responsive design.</li>
  <li><a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Viewport_meta_tag">MDN Web Docs</a></li>
</ul>
<pre>
&lt;meta http-equiv="X-UA-Compatible" content="IE=edge"&gt;
</pre>

<ul>
  <li>Advises Internet Explorer to use the latest rendering engine.</li>
  <li>No longer broadly relevant as IE reaches end-of-life.</li>
</ul>

<pre>
<meta name="description" content="Free Web tutorials">
</pre>

<ul>
  <li>Provides a brief description of the page. Important for SEO and when sharing 
    links on social platforms.</li>
  <li><a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/meta/name">
    MDN Web Docs</a></li>
</ul>

<pre>
<meta name="keywords" content="HTML, CSS, JavaScript">
</pre>

<ul>
  <li>Specifies keywords for search engines. Its importance for SEO has diminished over time due to overuse and spamming.</li>
</ul>

<pre>
<meta name="author" content="John Doe">
</pre>

<ul>
  <li>Defines the author of the webpage.</li>
</ul>

<pre>
<meta http-equiv="refresh" content="30">
</pre>

<ul>
  <li>Refreshes the page after a specified number of seconds.</li>
  <li><a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/meta/http-equiv#attr-refresh">MDN Web Docs</a></li>
</ul>

<pre>
<meta name="robots" content="noindex, nofollow">
</pre>

<ul>
  <li>Instructs search engines not to index or follow the links on the page.</li>
  <li><a href="https://developers.google.com/search/docs/advanced/robots/robots_meta_tag">Google Developers</a></li>
</ul>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>Security-Related Meta Tags</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->

<pre>
<meta http-equiv="Content-Security-Policy" content="default-src 'self'">
</pre>

<ul>
  <li>Controls resources the user agent is allowed to load, enhancing security.</li>
  <li><a href="https://developer.mozilla.org/en-US/docs/Web/HTTP/CSP">MDN Web Docs</a></li>
</ul>

<pre>
<meta http-equiv="X-Content-Type-Options" content="nosniff">
</pre>`

<ul>
  <li>Prevents the browser from MIME-sniffing a response away from the declared content-type.</li>
  <li><a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/meta/http-equiv#x-content-type-options">MDN Web Docs</a></li>
</ul>

<pre>
<meta name="referrer" content="no-referrer">
</pre>

<ul>
  <li>Controls the amount of referrer information sent along with requests.</li>
  <li><a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/meta/name">MDN Web Docs</a></li>
</ul>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>Social Media Integration Meta Tags</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h4>Open Graph (Facebook)</h4>

<ul>
  <li><pre>&lt;meta property="og:title" content="Title Here"&gt;</pre>: The title of your content.</li>
  <li><pre>&lt;meta property="og:description" content="Description Here"&gt;</pre>: A brief description.</li>
  <li><pre>&lt;meta property="og:image" content="https://example.com/image.jpg"&gt; : An image URL which should represent your content.</li>
  <li><a href="https://ogp.me/">Open Graph Protocol</a></li>
</ul>

<h4>Twitter Cards</h4>

<ul>
  <li><pre>&lt;meta name="twitter:card" content="summary_large_image"&gt;</pre>: Determines the card type.</li>
  <li><pre>&lt;meta name="twitter:title" content="Title Here"&gt;</pre></li>
  <li><pre>&lt;meta name="twitter:description" content="Description Here"&gt;</pre></li>
  <li><pre>&lt;meta name="twitter:image" content="https://example.com/image.jpg"&gt;</pre></li>
  <li><a href="https://developer.twitter.com/en/docs/twitter-for-websites/cards/overview/markup">Twitter Developer Docs</a></li>
</ul>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>Other Meta Tags</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<pre>
<meta name="format-detection" content="telephone=no">
</pre>

	- Instructs browsers not to detect and format telephone numbers automatically.
	- Useful for preventing unintended UI modifications, especially on mobile devices.

<pre>
<meta name="theme-color" content="#ffffff">
</pre>

	- Suggests a color that browsers should use to customize the display of the page or of the surrounding user interface.
	- <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/meta/name/theme-color">MDN Web Docs</a>

	- Particularly useful for mobile browsers to match the address bar color with the site’s theme color.

<pre>
<meta name="application-name" content="Application Name">
</pre>

	- Specifies the name of the web application.
	- Not widely used for SEO but can be useful in web app manifests and when the website is pinned to a screen, like on mobile devices or desktops.

<pre>
<meta name="generator" content="WordPress 5.8">
</pre>

	- Indicates the software or platform used to generate the page.
	- Automatically included by some CMSs like WordPress but often removed for security reasons to obscure the platform version.

<pre>
<meta http-equiv="Content-Language" content="en-US">
</pre>

	- Specifies the natural language(s) of the document.
	- The use of <html lang="en-US"> is preferred for specifying the primary language.

<pre>
<meta name="google" content="notranslate">
</pre>

	- Indicates to Google not to offer translation for this page.
	- Useful for content that may be misinterpreted when automatically translated.

<pre>
<meta property="fb:app_id" content="Your_App_ID">
</pre>

	- Associates your website with a Facebook app ID.
	- Essential for using Facebook Insights to track user interaction and for a more enhanced sharing experience on Facebook.

<pre>
<meta name="apple-mobile-web-app-capable" content="yes">
</pre>

	- Instructs Safari on iOS to operate in full-screen mode when the website is saved to the home screen.
	- Enhances the mobile experience by hiding browser UI components.

<pre>
<meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
</pre>

	- Specifies the style of the status bar for web applications added to the home screen on iOS.
	- Options include default, black, and black-translucent.

<pre>
<meta name="msapplication-TileColor" content="#000000">
</pre>

	- Defines the color of the tile for Windows 8 and 10 when the user pins the site to their start menu.
	- Helps maintain brand consistency across user platforms.

<pre>
<meta name="msapplication-config" content="/browserconfig.xml">
</pre>

	- Specifies the location of the XML config file for Internet Explorer 11 when pinning websites to the Windows taskbar.
	- The XML file can define tile images, tile color, and other settings.

This list represents a snapshot of the diverse and evolving world of HTML meta tags, each serving specific roles from SEO optimization, security enhancements, social media integration, to providing a better user experience across various devices and platforms. Developers should consider these meta tags as tools in their toolkit, to be used thoughtfully to meet the goals of their web projects.

For the most current information and best practices, always refer to official documentation and guidelines from relevant platforms and organizations, as web standards and practices continue to evolve.
