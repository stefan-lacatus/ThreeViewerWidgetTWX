# Three Model Viewer

## Usage

The ThreeModelViewer widget is based on [three.js](http://threejs.org/) and is capable of displaying 3D models in various formats inside a Thingworx mashup. For a list of all the supported formats, please look at _CompatibleModels.ods_ file.

### How to get set up

* To build the importable zip extension run the `npm install`. Then you are able to use commands like `npm run build`, or `npm run upload` to build or upload the widget. For more details about he build process see [demoWebpackWidget](http://roicentersvn/placatus/DemoWebpackWidget).
* Use the *Three Model Viewer* widget in a mashup
* On the widgets, configure them according to the documentation

### Developing

You can easily change what happens when a model is loaded. By default, it is either added to the scene *this.addObjectCommand* or it is a scene so it's just rendered *this.setSceneCommand*. So you can pass a callback to the Loader.loadFile that specifies what is happened after the file is loaded.

#This Extension is provided as-is and without warranty or support. It is not part of the PTC product suite. This project is licensed under the terms of the MIT license

# Authors
Petrisor Lacatus - IOT Presales Engineer, Romania CoE Team


# Disclaimer
By downloading this software, the user acknowledges that it is unsupported, not reviewed for security purposes, and that the user assumes all risk for running it.

Users accept all risk whatsoever regarding the security of the code they download.

This software is not an official PTC product and is not officially supported by PTC.

PTC is not responsible for any maintenance for this software.

PTC will not accept technical support cases logged related to this Software.

This source code is offered freely and AS IS without any warranty.

The author of this code cannot be held accountable for the well-functioning of it.

The author shared the code that worked at a specific moment in time using specific versions of PTC products at that time, without the intention to make the code compliant with past, current or future versions of those PTC products.

The author has not committed to maintain this code and he may not be bound to maintain or fix it.


# License
I accept the MIT License (https://opensource.org/licenses/MIT) and agree that any software downloaded/utilized will be in compliance with that Agreement. However, despite anything to the contrary in the License Agreement, I agree as follows:

I acknowledge that I am not entitled to support assistance with respect to the software, and PTC will have no obligation to maintain the software or provide bug fixes or security patches or new releases.

The software is provided “As Is” and with no warranty, indemnitees or guarantees whatsoever, and PTC will have no liability whatsoever with respect to the software, including with respect to any intellectual property infringement claims or security incidents or data loss.
