# DOCUMENTATION (Web static)

## Meta Tag

---

### viewport
	Usage:
	
	```
	<meta name='viewport' content='width=device-width, initial-scale=1.0'>
	```
The `viewport` meta tag, as shown in the Usage above, is used to control the way a web page is displayed on a mobile device or in a responsive design.
Specifically, it defines how the web page's content should be scaled and sized in relation to the device's screen.

- viewport (attributes)

	* width=device-width:
		This attribute sets the `width` of the `viewport` to be equal to the width of the `device's screen`. In other words, it makes the web page content fit within the screen width, ensuring that the page is not scaled to be wider than the device's screen.

	* initial-scale=1.0:
		This attribute sets the initial zoom level when the page is first loaded. A value of 1.0 means that the page is displayed at its original size without any zooming.

By including the `viewport meta tag` with these attributes, you are essentially telling the browser to ensure that the web page is responsive and displays correctly on various devices, including mobile devices. It helps prevent issues like content being too small or too wide on smaller screens and provides a consistent user experience across different devices.

In modern web development, setting the `viewport meta tag` is considered a best practice for creating responsive and mobile-friendly websites. It's an important part of making sure that your web page looks and functions well on different screen sizes and orientations.

---
