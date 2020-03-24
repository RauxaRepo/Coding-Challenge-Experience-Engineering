# Requirements

## Features

### The 3D Scene 
The 3D scene should contain:
-  One or more primitive object of your choice - Cube, Sphere or Torus Knot, etc.
-  One gLTF model. Load this in using the gLTF loader. Here's an [example](https://threejs.org/examples/?q=gltf#webgl_loader_gltf) from the ThreeJS team. Note: The model can be anything. The only requirement is that it's gLTF format.

### Scene Lighting 
Add some lighting to your scene.  The position and color of your lights are up to you. Have fun with it! 

Add the following lights: 
- 1 x Hemisphere light
- 2 x Spot lights
- 2 x Point Light

### Apply Color Buttons
- Add a 3 buttons of different colors. 
- Each button, when clicked, will update the color of your 3D object(s). 
- Button 1, should update your primitive. 
- Button 2 and 3 can update your gLTF model 
- The buttons should bind to a reuseable function that make the update happen. 

### Apply Image Texture Button
- Create a button that applies an image texture to your 3D model. 
- There are no requirements for how it is mapped over your 3D object - just that it is applied to the model. 
- The image used for the texture can be local to the application or hosted somewhere.  

## VueJS Requirements
- Use [single file ](https://vuejs.org/v2/guide/single-file-components.html) Vue components to encapsulate features.
- The EventBus should be leveraged to execute blocks of code at the correct times.  
- Mixins should be leveraged where applicable. 
- Leverage component properties and or computed properties where applicable. 

## Bonus Functionality
- **Random Color Buttons:** Add buttons that generate a random color and apply it to your model or objects when clicked.
- **Undo/Redo:** Demonstrate state management by adding **undo** and **redo** buttons to the random color button. Clicking "undo" and or "redo" would cycle through the history of colors applied to a 3D object. 
- **Image Texture Repeat Controls:** Add another button that toggles the repeat values of your texture up and down. 
- **Animate the Model:**  Animate your gLTF model. There are no specific requirements for this, just that the 3D model animates in some fashion on a repeating loop. 
- **Use AFRAME** - Integrate [AFRAME](https://aframe.io/) into your build.
