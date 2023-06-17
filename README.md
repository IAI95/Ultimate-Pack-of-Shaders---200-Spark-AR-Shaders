Looking to enhance your Instagram filters and increase your client rates? This extensive Spark AR Shader pack contains all the necessary elements to elevate your filter prowess. Over the past three months, I dedicated my efforts to constructing and acquiring a wide range of shaders, enabling you to accelerate and expand your filter career like never before. 

This package contains of over 200 shaders that have been converted from shadertoy.com, sorted and ready to use in Meta Spark application. 

Shader categories:

2D Image x 11 \
Backgrounds x 38 \
Creepy x 2 \
Drawing x 10 \
Fire x 6 \
Funny x 10 \
Glitch x 8 \
Heart x 5 \
Old x 8 \
Other x 40 \
Pixalate x 8 \
TV x 11 \
Weather x 12 

https://github.com/IAI95/Ultimate-Pack-of-Shaders---200-Spark-AR-Shaders/assets/80382116/9de57b8a-eb7e-4ddd-9c4b-3ee2c8bb4eac

To use any of these shaders, just drag them into a new or existing project, then create a rectangle and add a flat material for that rectangle. finally drag the shader into the patch editor and connect it to a shader render pass and the material.

![Screenshot_1](https://github.com/IAI95/Ultimate-Pack-of-Shaders---200-Spark-AR-Shaders/assets/80382116/6db7284d-d6d1-44b3-9768-aeaee1888191)

if you've seen any shaders requare a "tex#" you need to open the Presets folder that i provided in the zip file and find the exact tex number picture and drag it in your assets panel and connect it with the shader. (Don't forget to put the U & V tiling mode to "Repeat")

![Screenshot_2](https://github.com/IAI95/Ultimate-Pack-of-Shaders---200-Spark-AR-Shaders/assets/80382116/0ebc287e-46e5-479c-901c-a4bbef728bb5)

There are few other shaders that are not single files but they are 2 or 3 or 4 buffers that work together. in this case you have an extra step to put them together. first there is BufferA that has to be connected to a shader render pass and then to a delay frame. you gonna have to do the same process for the rest of the Buffers. then right click on the delay frame patch of every buffer and make reciever for each. those recievers should be connected to anywhere that is needed. finally we have the "Image" shader wich comes last and must be connected to your material.

![Screenshot_3](https://github.com/IAI95/Ultimate-Pack-of-Shaders---200-Spark-AR-Shaders/assets/80382116/532640e4-e739-498e-a543-232bc2b1dbff)

