# Simple way to use shadow contact with threejs.

I just copied the threejs example and make it working when i instanciate it.

You can tweak values from the gui and after modify it at the top of the ShadowContact.js
To make the place transparent set the plane opacity to 0.

```js
import ShadowContact from "./ShadowContact";

this.shadowContact = new ShadowContact(this.renderer, this.scene, this.gui); // GUI IS OPTIONIAL

// IN YOUR TICK/UPDATE FUNCTION
if (this.shadowContact) this.shadowContact.update();
```

You can also look at the implementation of it in the main.js file.
