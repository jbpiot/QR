## Custom Widget for [Wakanda](http://wakanda.org)
The __QR__ widget creates a QR code based on a value or a datasource attribute

### Properties
This widget has the following properties: 

* __content__: The data binding value of the widget

### Goals
The __QR__ is an example of how to create a QR code by giving a content value or by binding a datasource attribute.  



### widget.js

```
	Internal widget methods

    QR.prototype.repaint
    QR.prototype.getContent 
    QR.prototype.setContent 
   

```


### package.json

This widget uses 3rd party JS libraries that are listed in the package.json. 
The package.json was modified manually, so the widget had all the dependecies correctly addressed. 


### Wakanda Studio

1. Drag the widget to your Wakanda page. 
2. Select a datasource
3. Drop a datasource string attribute to the widget
4. Run the page, a QR code should be in the widget
5. When the datasource changes its value in the page, the widget should repaint the QR code with the new value


### CSS
The __QR__ CSS will define the background color of the widget.  
You can adjust its color by changing directly in the Studio OR by changing the /css/widget.css file.  


### More Information
For more information on how to install a custom widget, refer to [Installing a Custom Widget](http://doc.wakanda.org/WakandaStudio0/help/Title/en/page3869.html#1027761).

For more information about Custom Widgets, refer to [Custom Widgets](http://doc.wakanda.org/Wakanda0.v5/help/Title/en/page3863.html "Custom Widgets") in the [Architecture of Wakanda Applications](http://doc.wakanda.org/Wakanda0.v5/help/Title/en/page3844.html "Architecture of Wakanda Applications") manual.

