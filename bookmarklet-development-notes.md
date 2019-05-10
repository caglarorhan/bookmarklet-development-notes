**Bookmarklets**

This will be a very short note. 
- Javascript can be run directly from browser itself.
- You can run a javascript code from address bar (like a command line interface). For example ``javascript: (function(){alert('Hello world!')})()``
- You can create a ``script`` element and append it to the ``DOM tree`` like ``document.head`` with javascript.
- You can put some javascript into the anchor tag href property value ``<a href="javascript: (function(){alert('Hello world!')})()"> Weird things about to happen </a>`` that triggered(runs) when the link clicked.
- When you create a connection between an element (anchor tag etc.) and a javascript file, you created a bookmarklet.
- Boorkmarklets can be move (press the mouse button and drag) and drop in to the bookmark area of browser. This area is right under the address bar in the Chrome browser.
- When you create a boorkmarklet, you create a trigger of the given javascript source. An whenever a user clicks this boorkmarklet, connected javascript runs and do what ever it codes do on the the page or etc.

**Samples**

All are draggable and to create bookmark!
- Just a simple anchor tag ``<a href="javascript:(function(){alert('Hello world!')})()"> Weird things about to happen </a>``
- To create script element and src to an external js file. 
``<a href="javascript: function(){let jss = document.createElement('script');jss.src="externalJsFile.js";document.appendChild(jss);})()"> Weird things about to happen </a>``




