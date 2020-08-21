# Unity Package
Information about unity packages:

## Package 1: UI Transition Effect
This is a package that helps apply transition effect with a single channel texture.
Tutorial:
Step 1: Create a RawImage (GameObject> UI> RawImage)
Step 2: Drop the image into Raw Image> Texture in the Inspector tab
Step 3: Add unity package above to Assets in project (In Scene file in package there is example for image with transition effect)
Step 4: Add Component Animator for Raw Image and drag UIEffect_Demo_For Thumbnail.controller from the example Scenes file to the Animator Controller property for the newly created Raw Image object.
Step 5: Add Component, search the UITransitionEffect script and add that script for the newly created Raw Image
Step 6: Play project // You can change the way the transition occurs by changing the options of the EffectMode property of UITransitionEffect script in the Inspector tab.

## Package 2:
